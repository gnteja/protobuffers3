# protobuffers3 - Implementation of protobuffers in Java.

-protocol buffers is a serilization Implementation from google.

-In proto we define messages and these messages are exchanegd.

-Numbers: double, float, int32, int64, uint32, uint64, sint32, sint64, fixed32, fixed64, sfixed32, sfixed64.
-Boolean: bool
-String: string 
-Bytes: bytes (represented for sequence of byte array).

#Tags
cannot use 19000 through 19999 (Reserved by Google)
-frequently used tags should be numbered from 1 to 15 use 1 byte in space.
-Tags numbered from 16 to 2047 use 2 bytes of space.
- Reserved Tag ?

#Repeated Fields
the fields that take more then one add repeated field

#Default Values 
bool: false
number(Int32, etc..): 0
string: empty string
bytes: empty bytes
enum: first value
repeated: empty list

#Multiple Messages 
Defining multiple messages in the same file 

#Nested Types 
Defining a message inside another message. (to avoid repeation)

#Import Types 
Definig multiple messages and importing to another .proto file. (to re-use code in multiple files)

#Packages
important to define packages. to keep the file in the indicated package when the code is compiled.
(to prevent the name conflicts between messages myPackageName.messageName) 
used to compile correctly.


