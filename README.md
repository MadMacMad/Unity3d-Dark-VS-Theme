# Dark Unity3d Theme for VS Code


## Recommended Settings

```js
{
    "editor.fontSize": 20,
    "editor.fontFamily": "Holle Sans Mono, Operator Mono, Menlo, Monaco, 'Courier New', monospace",
    "csharp.format.enable": false,
    "workbench.activityBar.visible": true,
    "sublimeTextKeymap.promptV3Features": true,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.snippetSuggestions": "top",
    "editor.formatOnPaste": true,
    "editor.lineHeight": 25,
    "editor.letterSpacing": 0.5,
    "files.trimTrailingWhitespace": true,
    "editor.fontWeight": "400",
    "prettier.eslintIntegration": true,
    "editor.cursorStyle": "line",
    "editor.cursorBlinking": "smooth",
    "editor.renderWhitespace": "all",

    "files.exclude": {
        "**/.git": true,
        "**/.DS_Store": true,
        "**/*.meta": true,
        "**/*.*.meta": true,
        "**/*.unity": true,
        "**/*.unityproj": true,
        "**/*.mat": true,
        "**/*.fbx": true,
        "**/*.FBX": true,
        "**/*.tga": true,
        "**/*.cubemap": true,
        "**/*.prefab": true,
        "**/Library": true,
        "**/ProjectSettings": true,
        "**/Temp": true
    },


    "window.zoomLevel": 0,
    "workbench.colorTheme": "Unity3dDark",
    "workbench.iconTheme": "vscode-great-icons",


    // this isn't really underline-thin but we hack it to be a thicker cursor

    // Very important: Install this plugin: https://github.com/be5invis/vscode-custom-css
    // you'll need to change this to an absolute path on your computer

    "vscode_custom_css.imports": [
        "/Users/holle/.vscode/extensions/holle.theme-unitydark-1.0.0/vs-custom-hacks.css"
    ],



}
```

## Important: CSS Hacks For Extra Sweet Editor
Some things in VS code can't be controlled by settings, but you can install [this plugin](https://github.com/be5invis/vscode-custom-css), then make a file on your computer that will hold your custom CSS, I like to make one in my root called `~/.vscodestyles.css` and then put this everything in [cobalt2-custom-hacks.css](https://github.com/wesbos/cobalt2-vscode/blob/master/./cobalt2-custom-hacks.css) into your file.

Once done, open your command palette and select enable **custom CSS and JS**

![Custom CSS/JS Hack](https://d3vv6lp55qjaqc.cloudfront.net/items/0B37352D3s2A2e33353c/Screen%20Shot%202017-09-15%20at%2011.02.49%20AM.png?X-CloudApp-Visitor-Id=26998&v=7ff79bcc)

Finally reload your editor and the Custom CSS should be taking. You can test this by typing into file - the dirty circle should be yellow not white.

