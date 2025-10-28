# Changelog

## Added
### PATCH 2025.01.17
- New endpoints for news and tools, along with language updates and fixes to `rpavirtual` (`9827cec1`).
- CRUD endpoints for robots and databases (`59c5b7ce`).
- New version now compatible with Linux (`5eed3054`).
- Configuration option to close modal on backdrop click (`6ddb9d34`).

### PATCH 2025.02.28
- New default arguments and options in rpaweb to open chrome browser without automation detection (`c31bd56c`)

### PATCH 2025.03.20
- Add max executions of Rocketbot in license section (`93fa706e`)

### PATCH 2025.xx.xx
- Implemented HTTP response headers to all endpoints to prevent caching (``)
- Added message warning control to avoid unnecesary warnings in Rocketbot console (``)
- Improved browser automation handling to minimize detection (``)
- Enhanced file extraction process with error handling when downloading modules from marketplace (``)


## Changed
### PATCH 2025.01.17
- Improved directory filtering to exclude unwanted module directories (`58e40e3d`).
- Enhanced error handling in `a_mods` for reading `package.json`, preventing crashes and returning `None` on failure (`58e40e3d`).
- Added `projects` to the `setConfig` endpoint and checks for `close_modal` in the request body (`07050424`).
- Fixed language api endpoints to ensure proper flow functionality (`9827cec1`).

### PATCH 2025.02.28
- Import of `undetected_chromedriver` now works only for Windows systems (`4711022e`).

### PATCH 2025.03.20
- If a module fails to update, an error message will be displayed (`5b47ad1`)


## Fixed
### PATCH 2025.01.17
- Resolved an issue allowing multiple tabs in Autocreator Addon without adding extra code (`85926b9e`).
- Fixed validation results for `if` commands (`481ffd29`).
- Evaluated numeric values correctly in `setcell` of Excel command (`874fe798`).
- Forced string conversion for `wait_time` in `rpaweb` to prevent errors (`bd4e391a`).
- Updated `rpavirtual` in order to prevent crashes (`228db194`).
- Removed leading characters from custom log paths starting with `os.path` (`bc9ddca2`).
- Compatibility updates for `driverupdater` with Linux, along with fixes to prevent crashes (`746370de`).
- Fixed visual icons in treeview addon (`6ddb9d34`).
- Fixed logs viewer addon to display logs correctly (`6ddb9d34`).
- Fixed Double clicking a variable category name while editing won´t change it to its previous value, instead it will select all text. (`1r35d2d3`).
- Minor UI fixes on homepage. (`1r35d2d3`).

### PATCH 2025.02.28
- Fixed `rpavirtual` internal methods to improve image quality and prevent crashes (`588e8c61`).

### PATCH 2025.03.20
- Widened the code console on Javascript and Phyton commands (`5b47ad1`)
- Fixed a resolution error on small screens causing the right sidebar not to collapse (`5b47ad1`)
- Fixed a problem that caused cloned child commands to retain the same hidden id (`5b47ad1`)

## Removed
### PATCH 2025.01.17
- Several outdated modules deleted (`8834ce91`).
- Unused files removed (`3c7b42bb`).
- Modules and drivers updated, removing deprecated content (`851fd433`).