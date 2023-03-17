# punkContentWithAside

[![NuGet release](https://img.shields.io/nuget/v/punkContentWithAside.svg)](https://www.nuget.org/packages/punkContentWithAside/)

A package that allows you to view a Block List in two columns.

## Credits  

This plugin was taken from Søren Kottal's article (https://24days.in/umbraco-cms/2020/grid-nouveau-block-list/) and tweaked slightly. 
I've moved this into to a nuget package for keeping it up to date on projects

## Usage 

Using the block list editor, select the component you want to use, ensuring the component has multiple block list properties for "content" and "aside". 

Set the custom view of the component to be '~/app_plugins/punkContentWithAside/punkcontentwithaside.html'

Also set the "force hide content editor" in the advanced settings of the component. 

## Nuget

`Install-Package punkContentWithAside`

https://www.nuget.org/packages/punkContentWithAside/

## Compatibility

- Umbraco 10+ with Block List Editor.

## Screenshots
 
### Property Editor
![Screenshot](https://raw.github.com/garpunkal/punkContentWithAside/main/blocklisteditor.png)

### Component Edit in the Block List Editor datatype
![DataType setup](https://raw.github.com/garpunkal/punkContentWithAside/main/component_edit_1.png)

### Ensure you force hide content editor 
![DataType setup](https://raw.github.com/garpunkal/punkContentWithAside/main/component_edit_2.png)

