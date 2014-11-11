iWo
===

iWoEditor is a WYSIWYG editor like MediumEditor,the editor core is simple and extensible.

You can very easy to write plugin for iWoEditor,we also provide many basic plugins for it.

It supported IE6-11 and Chrome,Firefox,Safari latest version.

![editor](public/editor.png)

## Usage

```html
<script src="iwo.core.min.js"></script>
<div id="editor"></div>
```

```javascript
var editorDiv = document.getElementById('editor');
var configs = {
  themePath:'path/to/themePath',
  theme:'default',
  pluginPath:'path/to/plugins',
  plugins:iwo.base
  //plugins:'bold,italic,underline,justify,color,link,toolbar,image,video,music,http://my.domain/path/to/someplugin.js'
};
var iwoEditor = new iwo(editorDiv,configs);
```

## Api

[Methods](docs/methods.md),[Attribute](docs/attribues.md),[Events](docs/events.md)

## Contributors

```
project  : iWo
 repo age : 5 days
 active   : 2 days
 commits  : 12
 files    : 12
 authors  : 
    11  xiaojue                 91.7%
     1  LIU LUYING              8.3%
```

## License

[WTFPL](LICENSE)
