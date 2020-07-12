
**Showdown** is a markdown parser and html converter with an attempt to stay [as close as possible](https://github.com/showdownjs/showdown/wiki/divergences) to the [original](http://web.archive.org/web/20110111145019/http://attacklab.net/showdown/), while providing extensibility through a simple yet efficient [plugin](https://github.com/showdownjs/showdown/wiki/extensions) facility. Tables, GitHub flavoured, and what not.

## Get It

```
npm install showdown
# or
bower install showdown
```

## Use It

```
var Showdown = require('showdown');
var converter = new showdown.Converter();

converter.makeHtml('#hello markdown!');

// <h1 id="hellomarkdown">hello markdown!</h1>
```

## Need Help?

+ [Change Log](https://github.com/showdownjs/showdown/blob/master/CHANGELOG.md)
+ [Wiki](https://github.com/showdownjs/showdown/wiki)
+ [Google Group](https://groups.google.com/forum/#!forum/showdownjs)
+ [Issues](https://github.com/showdownjs/showdown/issues)
+ [stackoverflow](http://stackoverflow.com/questions/tagged/showdown)

## Credits

+ [Showdown Copyright (c) 2007 John Fraser](http://web.archive.org/web/20110111145019/http://attacklab.net/showdown/)
+ [Original Markdown Copyright (c) 2004-2005 John Gruber](http://daringfireball.net/projects/markdown/)