
#main xmpl repository
## Installation
XMPL repository is structured in a way that allows searching through examples based on packet's name 
and the content of examples.
Inside the starting folder "/commands" there are folders named after available packets.
Inside each packet, there is a descriptive file named "packet's_name.desc", which contains
description of the packet's purpose.
Finally, there are .xmpl files named after the examples. Content of .xmpl files is an example of command which executes in a way described. Name of example  and words to search and fetch examples are in the comments.
Comments, by default, don't print during fetching of an example. If the example requires input of a relative variable, it
is defined inside the .xmpl file, structured as {:variable name:}.
