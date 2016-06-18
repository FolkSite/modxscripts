Description:
============

Quick-start scripts for MODX command-line tools. 


## Install teleport script:

* Get teleport.phar from http://modx.s3.amazonaws.com/releases/teleport/teleport.phar
* Change teleport script to point to the phar file

## Using modx script:

* Requires teleport script
* Only works in the directory containing the core directory (current directory must have a child named "core")
* First, profile the site:
   cd /modx/base/path/
   modx profile
* To inject the package into a profiled site:
   cd /modx/base/path/
   modx inject <package>.trasport.zip
* View source for more examples   

## Install gitify script:

* Install gitify as instructed in: https://github.com/modmore/Gitify/
* Edit gitify script to have the correct path

