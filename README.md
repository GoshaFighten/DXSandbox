# DXSandbox
```
git clone https://github.com/GoshaFighten/DXSandbox myFolder
cd myFolder
rd .git /S/Q
del .gitignore README.md src\.gitignore
npm install
npm start
```
`npm start` is configured to run [lite-server](https://github.com/johnpapa/lite-server) with the `src` folder as the base folder and tracking changes in this folder. Add a HTML page to the `src` folder, save it (`Ctrl+S`) and press `Ctrl+Shift+B`. A VS Code task is configured to open the current page in Chrome by a `Ctrl+Shift+B` press. Further changes in the HTML page will be tracked by `browser sync` and the browser will refresh the page automatically.<br >
See how it works:<br >
[<img src="https://camo.githubusercontent.com/c629b7202fce18320af02c90fa040d39e1314e1a/687474703a2f2f636f6e74656e742e73637265656e636173742e636f6d2f75736572732f476f7368615f4669676874656e2f666f6c646572732f4a696e672f6d656469612f39363339363266332d373863622d343131382d393863312d3334633035326562353031642f323031362d30382d30375f303130302e706e67" alt="How it works" data-canonical-src="http://content.screencast.com/users/Gosha_Fighten/folders/Jing/media/963962f3-78cb-4118-98c1-34c052eb501d/2016-08-07_0100.png" width="250">](http://screencast.com/t/prvEdnujH9)

You can get a script to download and setup DXSandbox from my [DXTools repository](https://github.com/GoshaFighten/DXTools/blob/master/GetDXSandbox.bat)
