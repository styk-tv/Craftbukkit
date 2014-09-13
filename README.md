This project has been stripped of all references to the Bukkit
API project as it can be found on https://github.com/Bukkit/Bukkit

All org.bukkit.CLASSNAME_HERE references in the code of this
program references to the wolf in a Bukkit code found on 
https://github.com/Wolf-in-a-bukkit/wolf-in-a-bukkit

This package is present to aid in the reverse enginering of API
functionality so craft bukkit can function WITHOUT the bukkit api
and WITH the wolf in a bukkit api whilst maintaing compatiblity!

This project as it stands in this repository is fully LGPLv3
compliant!

WARNING WARNING WARNING WARNING WARNING WARNING WARNING WARNING 
*****************************************************************
THIS CRAFT BUKKIT MAY NOT BE DISTRIBUTED UNDER ANY CIRCUMSTANCES
TOGETHER WITH A COPY OF THE BUKKIT API WETHER IT BE COMPILED OR
SOURCE CODE!
*****************************************************************
WARNING WARNING WARNINGWARNING WARNING WARNING WARNING WARNING 
=================================================================
LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL *****************************************************************
=================================================================
The following terms are applicable in this document:

Wolf in a Bukkit: a NEW API X11/MIT licensed implementation to
work with craftbukkit, reverse enginered from craftbukkit functionality and bug report found at 
https://github.com/Wolf-in-a-bukkit/wolf-in-a-bukkit

Bukkit API: The GPLv3 of Bukkit found at 
https://github.com/Bukkit/Bukkit

Craftbukkit: The LGPL implementation that used the Bukkit API in
the past and will now be modified to use the wolf in a bukkit api.

GPLv3: The GNU Public License version 3

LGPLv3 : The Lesser GNU Public License version 3

X11/MIT : The X11 license, commenly referred to as MIT

This is the source code craftbukkit minecraft server jar. This
source code of the server jar, or compiled version of it 
may not be distributed with any GPLv3 Software becasue it is
fully incompatbile!
It is incompatible through its own license(lgplv3) and through
the proprietary software fully owned by Mojang AB.

The minecraft server code is used in this software package is
used without official permission of Mojang AB but Mojang AB has a
history of not enforcing their rights concerning modding via
craftbukkit, even encouraging modding(see the EULA). 
The moment they start enforcing their rights this project will be
deleted.

You cannot and may not use any intermediate libraries to link
this to the Bukkit API and then distrubute the package.
This is because the intermediate will become GPLv3 as well by the
action of linking against the GPLv3 library. 
In short, GPL sucks. Thanks grum for choosing that 4 years ago.

This craftbukkit will hold all its references to org.bukkit in
the code but will not compile in this package as it stands now.

The wolf in a bukkit code is being reverse enginered from
craftbukkit code, plugin code and bug reports. The wolf in a
bukkit API will gain a spot in the org.bukkit package with links
to the original hooks deduced from afore mentioned methods to
maintain compatibility with plugins that were created with
the bukkit api since those will look for a package org.bukkit.*
files.

These files however will be unrelated to the original bukkit api
and will be reverse enginered and the reverse enginering
documented in the code by means of comments. This sucks but is
the only legal way to accomplish this. Prepare for source code
with HEAPS of comments where we deduced functionality from.

in short:

THIS CRAFTBUKKIT IS NOT INTENDED FOR USE WITH THE GPLv3 BUKKIT API!

THIS CRAFTBUKKIT IS INTENDED FOR USE WITH THE X11/MIT LICENSED WOLF IN A BUKKIT API!

LOOPHOLE!

GPLv3 provides a loophole to private end users and companies. Please pay close attention: You may, in the privacy of your own
household or company modify the software as much as you want,
even in ways that would violate the GPLv3 License. BUT, YOU ARE
NOT ALLOWED TO DISTRIBUTE THAT SOFTWARE, unless
you can do this under full GPLv3 means. Which would entail you
getting permission from mojang to distribute their source code
under GPLv3. Good luck with that

Be WARNED though that compatibility with a Bukkit API software
package cannot be guaranteed since this craftbukkit is intended
for use with the wolf in a bukkit API.

Steps you would have to take to make this happen:

Download craftbukkit. Download bukkit.
Place the files from bukkit in the src/main/java/org/bukkit
directory in the corresponding directory of craftbukkit.
Use maven to compile with the command: mvn clean install

You will then have your own personal copy of craftbukkit with the
bukkit api. AGAIN: YOU ARE NOT ALLOWED TO DISTRUBTE THAT COPY!
The file will be in the directory called target.

==================================================================
******************************************************************
LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL 


CraftBukkit
===========

A Wolf in a Bukkit (Minecraft Server API) implementation

Bugs/Suggestions/helping out: http://reddit.com/wolf_in_a_bukkit

his craftbukkit is stripped of what is known as the bukkit api.
It will not compile since it misses the bukkit api.

The wolf in a bukkit api will be built to make this package
compile again https://github.com/Wolf-in-a-bukkit/wolf-in-a-bukkit
Feel free to help out reverse engineer craftbukkit :D we could
use the help!


Compilation
-----------

We use maven to do the magic and get dependencies from the bukkit project - sans bukkit api :(

* Install [Maven 3](http://maven.apache.org/download.html)

* Check out this repo and: `mvn clean package`
