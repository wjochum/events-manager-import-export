# Events Manager Import Export (Network Support Fork)

## Changelog

### 0.0.12, 2016-10-17

* fix bug with update event in network mode
* fix bug with post_id set to uid creates duplicates of imported event in tables  
* fix bug multiple locations created when importing multiple events with the same new location


### 0.0.11, 2016-02-09

* fix bug with geolocation overwriting location object for new locations
* refactor .xcs location creation to work like .csv location creation

### 0.0.10, 2016-01-31

* attempt to set location coordinates on import

### 0.0.9, 2016-01-30

* the plugin can receive update notifications and auto-update from within WordPress

### 0.0.8, 2016-01-30

* fix category imports for current Events Manager
* fix WordPress 4.4 import error for missing post_excerpt
