# Pycraft mod for Minetest
<img src="https://alessandronorfo.files.wordpress.com/2017/09/pycraft_minetest.png" alt="pycraft_minetest icon" height="360">

This is a fork of the https://github.com/arpruss/raspberryjammod-minetest created to support the [Pycraft for Minetest](https://github.com/sprintingkiwi/pycraft_lib) Python library: https://github.com/sprintingkiwi/pycraft_lib

Thanks to Arpruss for his amazing work :)

Alessandro Norfo (ale.norfo@gmail.com) & Giuseppe Menegoz (gmenegoz@gmail.com)

# Getting started
## WINDOWS
Go to the release page and download the last version of the Pycraft_Minetest.exe installer: https://github.com/sprintingkiwi/pycraft_mod/releases.

## LINUX
* Install Minetest from your distribution's repository
* Install Lua (preferably 5.1)
* Install Luarocks for your version of Lua
* In a terminal execute this command as superuser: luarocks install luasocket
* Follow this tutorial on how to install a mod in Minetest: http://dev.minetest.net/Installing_Mods. We suggest to clone this repository inside the "mods" folder of Minetest.
* Add "collections.Iterable = collections.abc.Iterable" just after the line "import collections" in pycraft_mod/mcpipy/mcpi/util.py
* In .minetest/minetest.conf add "secure.enable_security = false" or add "secure.trusted_mods = pycraft_mod"
* Create a world (it's better to enable creative mode)
* Click on "configure" and enable "pycraft_mod"
* Play the game, press "escape"
* In a terminal : python ~/.minetest/mods/pycraft_mod/mcpipy/helloworld.py
* You should have a message in the chat, and a diamond block under your feet !
* Write a new python script in ~/.minetest/mods/pycraft_mod/mcpipy/ and enjoy !


## MAC OSX
Work in progress...
