enex-dump
=========

PHP script that accepts an Evernote export (ENEX) file and produces a folder of plain text documents.

Please see comment at top of script for configuration and usage instructions.

Note about non-breaking spaces
------------------------------

I've found out the hard way that ENEX exports often contain non-breaking space characters (0xA0) that you may not notice right away because they look like regular spaces.  This script does not remove them, so be aware that they might exist.
