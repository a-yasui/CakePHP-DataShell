Introduction
===============

    $ git submodule add git://github.com/a-yasui/CakePHP-DataShell.git app/Plugin/CakePHP-DataShell

And add for bootstrap.php

    CakePlugin::load(array("CakePHPDataShell"));


Usage
===============

Export
---------------
	cake CakePHP-DataShell.data export {Model name|Table name}

Import
---------------
	cake CakePHP-DataShell.data import {Model name|Table name}

Memo
======

  This keep to CakePHP 2.2.4. But not test yet.

