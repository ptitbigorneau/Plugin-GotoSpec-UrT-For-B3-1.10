# gotospec plugin

# Plugin for B3 (www.bigbrotherbot.net)

# www.ptitbigorneau.fr

gotospec plugin (v1.2) for B3

Requirements
------------

* BigBortherBot(3) >= version 1.10

Installation
------------

1. Copy the 'gotospec' folder into 'b3/extplugins' and 'gotospec.ini' file into '/b3/extplugins/conf'.

2. Open your B3.ini or b3.xml file (default in b3/conf) and add the next line in the [plugins] section of the file:
    for b3.xml
        <plugin name="gotospec" config="@b3/extplugins/conf/gotospec.ini"/>
    for b3.ini
        gotospec: @b3/extplugins/conf/gotospec.ini

 
3. create the gotospec table in your database importing the gotospec.sql file.



