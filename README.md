# web2py modular blog engine

An example of web2py app using modules to define data models instead of traditional model files.

## why?

web2py loads scripts under /models folders in alphabetical order, and it is loaded in every request, with this approach you can have a more "Pythonic" way to define your data models using pure Python Modules and an ORM like structure to define your tables.

### features

This app comes with: 

- a simple blog engine
- urls-slugs
- multi author
- author picture grabbed from gravatar.com
- WYSIWYG editor with CKeditor supporting image uploads inside the editor
- multi theme support

Author: Bruno Cezar Rocha / 2011


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/pythonhub/web2py-modular-blog-engine/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

