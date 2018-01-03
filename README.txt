                        Mscore
			======

What is Mscore?
-------------------

Mscore is a shell script for calculating medical scores in the command line. The
score informations are stored in a plain text file and can be easily added /
modified / removed depending on the user's preferences.

Mscore is written in bash script.

Downloading
-----------

Latest release of Mscore can be downloaded from http://code.agnibho.com/mscore/

Installation
------------

1. Download the script and place it in your path. Alternatively you can place it
anywhere and create an alias instead.

2. Download the data folder which also contains some working examples of medical
score files.

3. Edit the main script and update the DIR variable to contain the path to your
downloaded data folder.

Usage
-----

Mscore can be used from bash command line.

Run mscore without any arguments to see a list of available scores.

You can run mscore with the name of an score file as argument to calculate it.

After selecting the score mscore will run the score file and ask for your input
for different variables required in the calculation. After entering the values
mscore will run the calculation and print the result in the screen.

The score files are placed in the data folder. Empty lines are ignored. The
lines starting with # are treated as comments.

Some examples are available within the downloaded data folder. 

Licensing
---------

Copyright (c) 2017 Agnibho Mondal
All rights reserved

This file is part of Mscore.

Mscore is free software: you can redistribute it and/or modify it under the
terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

Mscore is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
Mscore.  If not, see <http://www.gnu.org/licenses/>.

Contacts
--------

Agnibho Mondal
contact@agnibho.com
www.agnibho.com
