# Testing square brackets in verse before a Markdown hyperlink.

SAB can read Markdown hyperlinks in text. This test has a note in square bracktes 
before a MD hyperlink and also verse with two hyperlinks.

Verse one should show one Hyperlink wheil verse two should show two hyperlinks.
All Hyperlinks should go to Chapter 2 verse 1.

## SAB 5.0

### Windows build

- \v 1 Includes all text in hyperlink from first [ to last ]
- Touching Hyperlink does bring up popup **but no linked verse text**.

### Mac Build Android

- \v 1 has correct part hyperlinked
- \v 1 Touching Hyperlink does bring up popup with linked verse.

##$ Mac build iOS

- not tested yet.