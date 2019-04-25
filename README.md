# stylelint settings

My lint settings for SCSS using stylelint with scss and order plugins


## Dependancies

Install via npm either globally or into specific projects, depending on your needs.

```sh
npm install stylelint stylelint-scss stylelint-order
```

## Usage

Add the stylelintrc.json file to the root of your project ( or a suitable folder if using globally).  
If you want visual feedback add as stylelint plugin to your editor.  


This will display errors in your console
```sh
stylelint "path/to/file"
```
To fix the errors use the fix flag
```sh
stylelint "path/to/file" --fix
```
This will auto fix what it can and also log to the conbsole any problems it cannot fix

