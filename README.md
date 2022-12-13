# hammerstone-config-api

This is a temporary, experimental repository which documents a potential data-driven API for Sapiens Modding. The `configs` folder contains various example configurations. The goal is that we can eventually empower Hammerstone to read and consume these config files. 

Here is an example of the proposed flow:
 - User creates `pumpkin_cobbler.json`
 - User uses lua to access something like `hammerstone/objectManager::addObject('my_mod/objects/pumpkin_cobbler.json')
 - Hammerstone 'processes' this file into a format Sapiens can understand, by shadowing a lot of files, and inserting into a lot of type-maps.

The end result is that various modding tasks can be extrapolated to a *config file* and a *graphical element* (models, materials).