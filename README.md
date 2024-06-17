# HTMLBrowse [Pre Alpha]
Lightweight browser written in HTML 
![image](https://github.com/scoilcax/HTMLBrowse/assets/102550814/2a2f528b-5397-4f8e-9b79-82954f5e5e55)
[Web Demo](https://scoilcax.github.io/HTMLBrowse/) (Websites will not load)

## Feature that need to be added
- Tabs
- Saved tabs
- Saved logins (may be difficult due to the nature of this project)
- Fix keyboard shortcuts
- Create an icon

## Known Issues
- Some login pages will not work natively so to bypass this hold shift when clicking a login link to open a new electron window

## [Windows Executable (Recommended)](https://github.com/scoilcax/HTMLBrowse/releases)

  
## Build to run on Mac/Linux/Windows
1. [NodeJS](https://nodejs.org/en/download/package-manager) and [Git](https://git-scm.com/downloads)
1. Run in terminal
```
npm install electron-builder
``` 

3. Open your prefered terminal in the install location and run
```
git clone https://github.com/scoilcax/HTMLBrowse.git
```
4.<br>
Mac:
```
npx electron-builder build -m
```
Windows
```
npx electron-builder build -w
```
Linux
```
npx electron-builder build -l
```




