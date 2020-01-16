# JSON snippets for Visual Studio Code
Makes writing JSON fluent, with a simple set of snippets.

## Applications:

* Write JSON in configuration files.
* Write JSON code embed in different programming languages (eg. jQuery ajax).
* Write any key/value pair style code in different programming languages.

Working with JSON config files:

![JSON snippet example](https://raw.githubusercontent.com/wilsonmontalvo/vsc-jsonsnippets/master/images/json-snippet-demo.gif)

Defining json-data in several programming languages (JavaScript, TypeScript, etc):

![JSON snippet example](https://raw.githubusercontent.com/wilsonmontalvo/vsc-jsonsnippets/master/images/json-snippet-js.gif)

## Snippets:

| Snippets | Content |
| -------: | --------|
| obj | Create a JSON object |
| objc | Create a JSON object ending with comma |
| arr | Create a JSON array |
| arrc | Create a JSON array ending with comma |
| pair | Create JSON key/value pair |
| pairc | Create JSON key/value pair ending with comma |
| paircln | Create JSON key/value pair ending with comma and jumping to next line. Not recommended for complex "value" |

## Productivity shortcuts:

| Snippets | Content |
| -------: | --------|
| pair*2 | Create 02 pairs |
| pair*3 | Create 03 pairs |
| obj>1 | Create JSON object with 01 pair. |
| obj>2 | Create JSON object with 02 pairs. |
| obj>3 | Create JSON object with 03 pairs. |
| arr>1 | Create JSON array with 01 item. |
| arr>2 | Create JSON array with 02 items. |
| arr>3 | Create JSON array with 03 items. |

## Supported languages:

* JSON
* JavaScript
* TypeScript
* Other(s) to come...

## Extended functionality:
Other languages with key/value pair style code:

* C# : Anonymous types, Object initializer and Implicitly-typed Arrays in Object Initializers.
* Other(s) to come...

Visual Studio Marketplace: 
https://marketplace.visualstudio.com/items?itemName=wmontalvo.vsc-jsonsnippets