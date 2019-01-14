# Pass Fail scoreboard

| Fixed bug | Issue checked | Result Win | Result iOS | Notes |
| --------| --------------| ------ | ---------------| ---|
| 5.0  | HTML source files| pass | pass | 
| 5.0  | Square brackets near MD link | pass | pass |
| 5.0  | cp and vp markers | pass | ? |
| 5.0  | About text PNG and MD issues | partial | ? | PNG and JPG no longer causing issues. Now `[link]()`, `[link](C01/MAT)` and `[email](email:someone@somewhere.org)` cause app crash on entry to About page.
|   | Russian Short names for Jhn | Fail | ? |
| 5.0  | fp in footnotes | pass | pass |
| 5.0  | Double quotes beside Search word | pass | ? |
|   | Thumbnail repeating work-around exists | fail | ? | Need to add `background-repeat: no-repeat; background-position: center;` to handle images not in 16:9 proportions.
| 5.0  | MD internal and cross collection links | partial | ? | Gets correct text but jumps to book in current collection not in remote collection.
