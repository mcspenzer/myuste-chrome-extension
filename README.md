# MyUSTe Chrome Extension

This is an Unofficial Chrome Extension for UST MyUSTe Student Portal. Inspired from the GWA Calculator App.

## Features
* Change MyUSTe default ID Picture to a URL Image.
* Calculate GWA for each Semester.
* Pressure Filter - only see `PASSED`, `FAILED`, or `NO GRADE`
* Calming message everytime you login to MyUSTe.
* Display in popup - `SYNCED SUBJECTS`, `CURRENT GWA VIEW` , or `OVERALL GWA`

### Installation
1. Clone Repository with `git clone https://github.com/medinajuanantonio95/myuste-chrome-extension.git`.
2. Open Chrome Browser and type in the address bar `chrome://extensions`.
3. Toggle on the Developer Mode.
4. Click the `Load Unpacked` button and import the project folder.

### Instructions
1. For Installation, follow the Installion Process above.
2. On your first use, you are required to sync your data first to MyUSTe.
3. After logging in, you would see your info when you click the popup on the top right position of your browser.
4. To change your Icon virtually, enter in the `textbox` the URL of the Image. 
5. To calculate your GWA, sync your grades by opening each semester one by one. Your syncing status can be viewed in the popup. (Overall GWA calculates only Finals Period grades)
6. To switch on Pressure-filter, toggle `ON` the switch. 

### Bugs
1. After toggling on Pressure Filter, it doesn't turn off. (Fixed)
2. Myuste_grades doesn't automatically on pressure filter. (Fixed)
3. After syncing grades, everything is undefined. (Fixed)
