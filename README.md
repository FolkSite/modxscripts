Description:
============

Quick-start scripts for MODX command-line tools. 


## Install teleport script:

* Get teleport.phar from http://modx.s3.amazonaws.com/releases/teleport/teleport.phar
* Change teleport script to point to the phar file
* Teleport Documentation: http://modxcms.github.io/teleport/

## Install gitify script:

* Install gitify as instructed in: https://github.com/modmore/Gitify/
* Edit gitify script to have the correct path
* Gitify Documentation: https://github.com/modmore/Gitify/wiki

## Using modx script:

* This is an example wrapper script - some commands use teleport, others use gitify
* Only works in the directory containing the core directory (current directory must have a child named "core")
* First, profile the site:

    ```bash
    cd /modx/base/path/
    modx profile
    ```

* To inject the package into a profiled site:

    ```bash
    cd /modx/base/path/
    modx inject <package>.transport.zip
    ```

* View source for more examples   


