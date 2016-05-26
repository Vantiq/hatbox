# Hatbox
Git clone of hatbox svn repository.

This is a fork of jdeolive/hatbox, which is a copy of the hatbox project (see https://sourceforge.net/projects/hatbox/ and http://hatbox.sourceforge.net/)

Here is a description of the project from Hatbox's website: 

Hatbox is a user-space add-on for Apache Derby and H2 databases. 'user-space add-on' what does that mean? It means that HatBox employs user visible tables, procedures, functions and triggers to implement spatial functionality on top of standard Derby/JavaDB and H2. The upside is that when you use HatBox you are not tied to a special version of Derby or H2, you can upgrade Derby and H2 independently of HatBox. The down side is that feature geometry must be created and manipulated outside the database and the tables, procedures, functions and triggers that make up HatBox may be corrupted by inadvertent user action.

We've forked this project to add support for indexing multiple geometry columns in the same table.
