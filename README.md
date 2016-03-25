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

#####################
The MIT License (MIT)
#####################

Copyright (c) 2016, Aditya Karnam, ITechnospot.com

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
