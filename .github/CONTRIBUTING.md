# Forumoji Contributing Guide
| This is for contributing to maintaining(and adding new features to) the Project Forumoji website, and or suggestions for upkeep of the GitHub Repository, if you'd like to contribute a Forumoji, please see the [Forumoji Style-Guide](../styleguide.md). | 
--

## Identifying a Problem

The first step to contributing to Project Forumoji is to find a problem, issue, or bug. You can find some of these reported by other contributors, collaborators, and users on the GitHub repository's [Issues Tab](https://github.com/lopste/forumoji/issues).

## Code Style-Guide
| This is not the style guid for new forumojis, please see the [Forumoji Style-Guide](../styleguide.md) if that is your intention. |
-
In order to keep everything uniform and easy to read, make sure to follow these rules for styling your code.

| Element | Value |
|-|-|
| Indentation Level | `2`, in spaces |
| Casing | for HTML+CSS: Kebab Case(`kebab-case`); for JS: Camel Case(`camelCase`) |
| Strings | JavaScript strings should use apostrophes(`'`), and backticks(`` ` ``) when a string needs to be formatted |
| Inline-Functions | Prefer inline-functions(`function() {}`) over arrow functions(`() => {}`). Inline-functions can be named, allowing for more self-explanatory statements, such as `function unlinkEmoji()` is more descriptive than `() =>`. |
| Comments | In general, it is recommend to avoid comments, and instead choose to allow code to explain itself. However, if a method that isn't self-explanatory is used for performance reasons, it is acceptable to provide comments to explain what the segment does. TODOs are also allowed. |
| Variable Naming | (For casing information, see _Casing_ -- 2nd row) when naming a variable, make sure to take into account what its value should be. For example, instead of using `e` use `emoji`. The only time a single letter variable-name is acceptable is when it is unused, in which example it should be named `_`(add additional `_`s if needed) |
| Line-Endings | Make sure every line of JavaScript ends with a semicolon(`;`) |