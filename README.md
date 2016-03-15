# globalcss
Global CSS

## Table of contents

* [Margins](#margins)
* [Paddings](#paddings)
* [Fonts](#fonts)
* [Colors](#colors)
* [Documentation](#documentation)



# [Jorge Brunetto](http://jorgebrunetto.com.br)

Global CSS foi desenvolvido pensando em varias necessidades do dia a dia, desenvolvido em LESS e Stylus, um framework completo com recursos para agilizar o dia-a-dia.

Atende as seguintes necessidades.

## Margins / Paddings
Em breve
Coming Soon

```
Margins ALL, TOP, BOTTOM, RIGHT, LEFT
├───m-*
│   └── margin: 0..150px;
├───m-t-*
│   └── margin-top: 0..150px;
├───m-b-*
│   └── margin-bottom: 0..150px;
├───m-r-*
│   └── margin-right: 0..150px;
└───m-l-*
    └── margin-left: 0..150px;

Margins (Negative) ALL, TOP, BOTTOM, RIGHT, LEFT
├───m-n-*   
│   └── margin: -1..-150px;
├───m-t-n-*
│   └── margin-top: -1..-150px;
├───m-b-n-*
│   └── margin-bottom: -1..-150px;
├───m-r-n-*
│   └── margin-right: -1..-150px;
└───m-l-n-*
    └── margin-left: -1..-150px;

Margins Height and Widht / Negatives
├───m-w-*   
│   ├── margin-left: 0..150px;
│   └── margin-right: 0..150px;
├───m-w-n-*   
│   ├── margin-left: -1..-150px;
│   └── margin-right: -1..-150px;
├───m-h-*   
│   ├── margin-top: 0..150px;
│   └── margin-bottom: 0..150px;
└───m-h-n-*   
    ├── margin-top: -1..-150px;
    └── margin-bottom: -1..-150px;


Paddings ALL, TOP, BOTTOM, RIGHT, LEFT
├───p-*
│   └── padding: 0..150px;
├───p-t-*
│   └── padding-top: 0..150px;
├───p-b-*
│   └── padding-bottom: 0..150px;
├───p-r-*
│   └── padding-right: 0..150px;
└───p-l-*
    └── padding-left: 0..150px;

Paddings (Negative) ALL, TOP, BOTTOM, RIGHT, LEFT
├───p-n-*   
│   └── padding: -1..-150px;
├───p-t-n-*
│   └── padding-top: -1..-150px;
├───p-b-n-*
│   └── padding-bottom: -1..-150px;
├───p-r-n-*
│   └── padding-right: -1..-150px;
└───p-l-n-*
    └── padding-left: -1..-150px;

Paddings Height and Widht / Negatives
├───p-w-*   
│   ├── padding-left: 0..150px;
│   └── padding-right: 0..150px;
├───p-w-n-*   
│   ├── padding-left: -1..-150px;
│   └── padding-right: -1..-150px;
├───p-h-*   
│   ├── padding-top: 0..150px;
│   └── padding-bottom: 0..150px;
└───p-h-n-*   
    ├── padding-top: -1..-150px;
    └── padding-bottom: -1..-150px;
```

## Documentation

//Colors - Globais
@import '_colors.styl'
//Variables
@import '_variables.styl'
//Backgrounds - Colors
@import '_bg-color.styl'
//Font - Colors
@import '_ft-color.styl'
//Font - Sizes
@import '_ft-size.styl'
//Font - Weight
@import '_ft-weight.styl'
//Font - Line Height
@import '_l-h-height.styl'
//Font - Letter Spacing
@import '_l-s-spacing.styl'
//Margins
@import '_margin.styl'
//Paddings
@import '_padding.styl'
//Border - Radius
@import '_border-radius.styl'
//Border - Colors
@import '_border-color.styl'
//Border - Stylus
@import '_border-stylus.styl'
//Border - Size
@import '_border-size.styl'
//Centers - Divs
@import '_others.styl'


## Contributing

BREVE


## Community

Get updates on Bootstrap's development and chat with the project maintainers and community members.

* Follow [@getbootstrap on Twitter](https://twitter.com/getbootstrap).
* Read and subscribe to [The Official Bootstrap Blog](http://blog.getbootstrap.com).
* Join [the official Slack room](https://bootstrap-slack.herokuapp.com).
* Chat with fellow Bootstrappers in IRC. On the `irc.freenode.net` server, in the `##bootstrap` channel.
* Implementation help may be found at Stack Overflow (tagged [`twitter-bootstrap-3`](https://stackoverflow.com/questions/tagged/twitter-bootstrap-3)).
* Developers should use the keyword `bootstrap` on packages which modify or add to the functionality of Bootstrap when distributing through [npm](https://www.npmjs.com/browse/keyword/bootstrap) or similar delivery mechanisms for maximum discoverability.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [the Semantic Versioning guidelines](http://semver.org/). Sometimes we screw up, but we'll adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/twbs/bootstrap/releases) for changelogs for each release version of Bootstrap. Release announcement posts on [the official Bootstrap blog](http://blog.getbootstrap.com) contain summaries of the most noteworthy changes made in each release.


## Creators

**Mark Otto**

* <https://twitter.com/mdo>
* <https://github.com/mdo>

**Jacob Thornton**

* <https://twitter.com/fat>
* <https://github.com/fat>


## Margins

Code and documentation copyright 2011-2016 Twitter, Inc. Code released under [the MIT license](https://github.com/twbs/bootstrap/blob/master/LICENSE). Docs released under [Creative Commons](https://github.com/twbs/bootstrap/blob/master/docs/LICENSE).
