# Snippets are an incredibly powerful way to quickly generate commonly needed code syntax from a shortcut.

• https://github.com/Shrugs/react-native-snippets

# Auto completed syntax <Tag> components React Native

• https://atom.io/packages/react-native-components

#Following JSX tag closure

• https://atom.io/packages/language-babel

# Detect JSX syntax errors (6 steps)

• https://atom.io/packages/linter

• Install two packages in Atom: <code>linter-eslint</code> & <code>linter</code> 

<b>noted:</b>

<i> never add sub package if show the suggestions without Atom panel</i>

<i> if show errors is not defined, you must add flow command in the top file:</i>

<code>/*global
alert, confirm, console, Debug, opera, prompt, WSH
*/</code>

• Open <code>gitbash</code> in root project

• Run <code>npm install --save-dev eslint-config-rallycoding</code>

• Add new file in root project <code>.eslintrc</code>

• Edit file with contain <code>{ "extends": "rallycoding" }</code>

• Re-Open project in Atom

