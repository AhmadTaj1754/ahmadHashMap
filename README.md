ahmadHashMap *
=========

ahmadHashMap is a cross-platform hashing/mapping Python module for human beings. Used to simulate a Python dictionary.


Install ahmadHashMap on your system using :

pip install ahmadHashMap

Import ahmadHashMap into your project using :

import hashMap

Example of creating and using instance of hashMap:

 import hashMap



 map = hashMap.HashMap(22)




 map.assign("City", "Cambridge, MA")



 
 map.retrieve("City")
    'Cambridge, MA'

*currently only working with python3 due to issues with the encode() method in python2
