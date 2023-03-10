# Test of indexing Zbrush controls in customized UI

- Assigning controls to customized UI is by their loading order


## How controls in plugins are indexed:

1. Plugins are loaded by order of .zsc files
1. Controls are ordered as they are in file


## Order of palettes & subpalettes

1. Palettes are ordered by alphabet
1. Subpalettes are ordered by loading order of .zsc files

- Display order of them has no effect to index of controls in customized UI


### Notes:

- Adding controls to plugin should not break custom ui

- When plugin or button is removed, then customized controls are replaced by next controls in index

- Only missing controls should be replaced by Zbrush itself

- The smallest width of button is 2px