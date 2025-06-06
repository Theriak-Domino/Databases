# Databases
Thermodynamic databases for use with the Theriak-Domino suite of programs.

## Usage
Please review each file before using it to ensure all the models and pure phase components that you do or do not want to use are activated/deactivated appropriately. The convention used for this is to change the spelling of one of the keywords GAS, MINERAL, SOLUTION, or MARGULES so the program skips all following lines until it finds a correctly spelled keyword. Keywords are recognized by at least three * at the beginning of a line.

## Changes/Updates

### 2025-06-06: td-ds62-mb50-v07.txt / td-ds62-mb50-v08.txt
A block of database species was inadvertently left active towards the bottom of the database.
With that large block active, the program would predict a pure ilm species coexisting with solid-solution
ILM00 for some bulk compositions. This large block of database species has been deactivated to avoid this,
and the file renamed to td-ds62-mb50-v08.txt. In addition, the included buffers have been rewritten in terms
of equilibrium minus species so they can be used in iron and/or nickel absent systems.
### 2025-06-04: td-ds636-ig51G25-v01.txt
Database file td-ds636-ig50G25-v01.txt was added. See the comments in the file for details.
### 2023-11-23: td-ds62-ef21-v03.txt
There was an error in the site mixing for one of the phase components of the CHL model. This has been corrected and td-ds62-ef21-v02.txt was replaced by td-ds62-ef21-v03.txt.
