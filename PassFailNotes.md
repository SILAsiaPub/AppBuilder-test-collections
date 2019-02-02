# Pass Fail scoreboard

| Fixed bug | Issue checked | Result Win | Result iOS | Notes |
| --------| --------------| ------ | ---------------| ---|
| 5.0  | HTML source files| pass | pass | 
| 5.0  | Square brackets near MD link | pass | pass |
| 5.0  | cp and vp markers | pass | ? |
| 5.1  | Russian Short names like  Jh and 1 Jn | pass | ? |
| 5.0  | fp in footnotes | pass | pass |
| 5.0  | Double quotes beside Search word | pass | ? |
| 5.1  | Thumbnail repeating when pic wrong proportion | pass | ? |
| 5.1  | Cross ref with 2 periods like: apo. Ka. 1:2 | pass | ? |
| 5.0  | Single verse footnote showing | pass | ? |
|   | MD internal and [cross collection links](MDx internal and cross collection links.md) | partial | ? | Gets correct text but jumps to book in current collection not in remote collection.
|   | Cross Ref to [whole chapter](Cwc-CrossRef to whole Chapter.md) | partial | ? | Worked in the past. Does not work 4.6.1, 4.7, 5.0, 5.1

## About text tests for version 5.1

| Test | WinDroid | iOSdroid | Note | 
| ---  | ---      | ---      | ---  |
| html &lt;b&gt; | pass |  |  |  
| html &lt;i&gt; | pass |  |  | 
| html &lt;u&gt; | pass |  |  |
| html &lt;img width="80%" src="fig1.png"/&gt; | pass |  |  |
| html &lt;div align="center"&gt; | pass |  |  |
| html &lt;div align="left"&gt; | pass |  |  |
| html &lt;div align="right"&gt; | pass |  |  |
| html &lt;img width="75%" src="fig1.png"/&gt; | pass |  |  |
| html &lt;div class="q2"&gt; | pass |  |  |
| html &lt;span style="font-family:font1;"&gt; | pass |  |  |
| html &lt;span style="font-family:font2;"&gt; | pass |  |  |
| html &lt;&gt; | pass |  |  |
| MD [http link]&#40;http://xxx.xx&#41;  | pass |  |
| MD [https link]&#40;https://xxx.xx&#41;  | pass |  |
| MD [Ph: 912341234]&#40;tel:912341234&#41; | pass |  |
| MD [email link]]&#40;mailto:someone@somewhere.org&#41;  | pass |  |
| MD [empty link]&#40;&#41; | pass |  | Used to cause crash
| MD [72348706]&#40;72348706&#41; telephone number in link | fail |  | No crash, tries to link to none existent web page
| MD [link]&#40;C01/MAT.2&#41; | fail |  | Cross collection link causes crash on selecting About from drawer menu
| variable %app-name% | pass |  |
| variable %version-name% | pass |  |
| variable %copyright-text:C08% | pass |  |
| variable %copyright-audio:C08% | pass |  |
| variable %copyright-images:C08% | pass |  |
| variable %license-text:C08% | fail |  | Nothing displayed
| variable %license-audio:C08% | fail |  | Nothing displayed
| variable %license-images:C08% | fail |  | Nothing displayed
| text match file ext PNG | pass |  | Used to treat a MD and remove it |
| text match file ext JPG | pass |  | Used to treat a MD and remove it |
| text match file ext GIF | pass |  | |



