# Installing plugins for Sublime's jsfmt (esformatter)

https://github.com/ionutvmi/sublime-jsfmt

## spaced-comment
https://github.com/briandipalma/esformatter-spaced-lined-comment

If you want to use a plugin that is not installed by default you will need to follow the next steps:

1. Go to the packages folder in terminal (find by Preferences -> Browse Packages)
1. cd into the jsfmt folder.
1. Install the plugins you need. `npm i esformatter-quotes && npm i esformatter-semicolons && npm i esformatter-braces && npm i esformatter-dot-notation && npm i esformatter-spaced-lined-comment && npm i esformatter-jsx-ignore && npm i esformatter-var-each`
1. Go to your jsfmt settings file and add the name of the plugin in the plugins array.
