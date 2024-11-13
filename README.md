# Plex Theme

A light theme with minimal amount of highlighting for [Visual Studio Code](http://code.visualstudio.com).

Plex uses minimal highlighting 

## Syntax Palette

<table style="width:100%">
  <tr>
    <th>Scope</th>
    <th>Color</th>
    <th>Scope</th>
    <th>Color</th>
  </tr>
  <tr>
    <td>Background</td>
    <td><img src="https://via.placeholder.com/35/f4f4f4/?text=+"></td>
    <td>Foreground</td>
    <td><img src="https://via.placeholder.com/35/000000/?text=+"></td>
  </tr>
  <tr>
    <td>Comment</td>
    <td><img src="https://via.placeholder.com/35/b3b1ad/?text=+"></td>
    <td>Primitives/Keywords</td>
    <td><img src="https://via.placeholder.com/35/b83453/?text=+"></td>
  </tr>
  <tr>
    <td>Strings</td>
    <td><img src="https://via.placeholder.com/35/198038/?text=+"></td>
    <td>Entities</td>
    <td><img src="https://via.placeholder.com/35/0043ce/?text=+"></td>
  </tr>
  <tr>
    <td>Constants</td>
    <td><img src="https://via.placeholder.com/35/6929c4/?text=+"></td>
    <td>Punctuation</td>
    <td><img src="https://via.placeholder.com/35/8d8d8d/?text=+"></td>
  </tr>
</table>

## Preview
<p align="center">
<img  src="https://raw.githubusercontent.com/d1ego77/vscode-theme-plex/refs/heads/master/screenshot.png"  
title="Plex theme" />
</p>
Tested languages: Rust, Go, Python, Ruby, Java, Javascript, C#, C, C++, Typescript, PHP, Elixir, Groovy, Lua, Clojure, HTML

## Additionally

Consider using these settings to reduce visual noize:

```js
{
  "editor.inlayHints.enabled": "off",
  "editor.minimap.enabled": false,
  "editor.smoothScrolling": true,
  "editor.scrollbar.vertical": "hidden",
  "explorer.decorations.colors": false,
  "window.autoDetectColorScheme": true,
  "workbench.editor.showIcons": false,
  "workbench.editor.tabSizing": "shrink",
  "workbench.tree.indent": 10,
  "editor.stickyScroll.enabled": true,
  "editor.guides.indentation": false,
  "editor.occurrencesHighlight": "off",
  "editor.selectionHighlight": false,
  "editor.rulers": [
    120,
  ],
  "workbench.editor.tabActionLocation": "left",
  "editor.bracketPairColorization.enabled": false,
  "symbols.hidesExplorerArrows": false,
  "breadcrumbs.enabled": false,
}
