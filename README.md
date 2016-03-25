# CodeIgniter Logs Extension

Installation
------------

Replace the Log.php from the repo to your CodeIgniter Folder.
Path to copy/replace : system/core/Log.php


Config Setup
------------

* 0 = Disables logging, Error logging TURNED OFF
* 1 = Error Messages (including PHP errors)
* 2 = Debug Messages
* 3 = Informational Messages
* 4 = Warn Messages
* 5 = Success Messages
* 6 = All Messages


Usage
-------

```php
log_message('success', 'Success Message.');
log_message('warn'   , 'Warning Message.');
log_message('info'   , 'Info    Message.');
log_message('error'  , 'Error   Message.');
log_message('debug'  , 'Debug   Message.');
```
