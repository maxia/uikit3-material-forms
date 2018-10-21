# uikit3-material-forms

Pure CSS material design forms for use with [UIkit 3](http://twitter.com/#!/dominictarr).  
  
[Demo](https://maxia.github.io/uikit3-material-forms/test/index.html)

## Known issues
Validation states are not supported yet.


## Installation
Install package via npm

<pre>
npm install uikit3-material-forms
</pre>

Include files into your UIkit 3 theme (see: https://getuikit.com/docs/sass#how-to-structure-your-theme)

<pre>
// 1. Your custom variables and variable overwrites.
@import "~uikit3-material-forms/variables.scss";
 
// 2. Import default variables and available mixins.
@import "uikit/src/scss/variables-theme.scss";
@import "uikit/src/scss/mixins-theme.scss";
 
// 3. Your custom mixin overwrites.
@import "~uikit3-material-forms/mixins.scss";
 
// 4. Import UIkit.
@import "uikit/src/scss/uikit-theme.scss";
</pre>

## License

MIT license