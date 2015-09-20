# Installation

 * TODO

# Plugins
## Adding a plugin
Plugins are loaded thanks to pathogen.
To add a plugin use the following command:

~/.vim> git submodule add git://URL/OF/PLUGIN bundle/PLUGIN_NAME

Do not forget to commit it !

# Cheat sheet

Keys: http://www.viemu.com/vi-vim-cheat-sheet.gif

## Using buffers

## Search and Replace
### Current file
 * Search: /Things
 * Search and replace on selection: :s/Things/replace/g
 * Search and replace on whole file: :%s/Things/replace/g
 * Search and replace with confirm option: :%s/Things/replace/gc 
 * Search and replace selected word: ,r

### On several file
 * Search: ,g
 * Display result per file: ,cc 
 * Next result: ,n
 * Previous result: ,N

## Markdown
### Navigation
| Command | Effect                                       |
|---------|----------------------------------------------|
| ]c      | go to current title                          |
| ]u      | go to parrent heander                        |
| ]]      | go to next header                            |
| [[      | go to previous header                        |
| ][      | go to next sibling header (if any)           |
| []      | go to previous sibling header (if any)       |
| :Toc    | Display outline. Do not update automatically |

### Edition
 * :TableFormat
  Used tabular to format a table correctly

