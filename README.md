This is a copy of telnetlib for python3.13+
It was deprecated and is being removed in python3.13 but many people would still like their old code to work.

Just install it with pip/poetry/etc for python3.13+ and your old telnetlib code should keep working.

Currently it is an exact copy(except for removing the derpracation warning),  
but I will accept patches for compatibility for future python versions.  
No extra options or feature or formatting fixes are likely.

The pep suggested telnetlib3 which has a differnt api and isn't a drop in replacemnet or Exscript which has an old copy of telnetlib  
https://github.com/knipknap/exscript/blob/master/Exscript/protocols/telnetlib.py  
which you can import with `import Exscript.protocols.telnetlib as telnetlib`  
but also a bunch of other stuff.
Also it requires you to modify your imports, this package doesn't.