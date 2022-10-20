# how to create a block plugin on moodle
To define a "block" in Moodle, in the most basic case we need to provide just four PHP files. Remember, in this example we are creating a block called 'simplehtml', replace 'simplehtml' with the name of your custom block. The four files should be located in blocks/simplehtml and are:

```picture
blocks/simplehtml/
 |-- db
 |   `-- access.php
 |-- lang
 |   `-- en
 |       `-- block_simplehtml.php
 |
 |-- block_simplehtml.php
 |
 |-- version.php

```
