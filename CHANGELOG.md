## 0.3.0 - 2020-10-06
- New method for storing the OCR text, now stores it in `title` attr of the img html tag
- Handle old versions of Anki not having different progressbar.update()

## 0.2.5 - 2020-10-06

- Add alternate import method for Collection due to API changes in Anki

## 0.2.4 - 2020-10-05

- Changed order of operations so that OCR is attempted before notes are modified to elimainate risk of database errors
- Updated path to tesseract executable for mac and linux

## 0.2.3 - 2020-10-05

- HOTFIX for tesseract cmd path on Mac

## 0.2.2 - 2020-10-05

- Removed the install file for Tesseract-OCR for windows, now that the binaries themselves are included. 
- Updated the inital message the user sees to notify re: the database change message Anki will show.

## 0.2.1 - 2020-10-05

- HOTFIX for Fixing tesseract executable detection

## 0.2.0 - 2020-10-05

- Now packaged with windows binaries for Tesseract-OCR, no install neccesary!
- Added flag in config.json to indicate valid tesseract exec
- Updates to README to reflect above changes

## 0.1.0 - 2020-10-05

- Initial release
