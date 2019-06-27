MK.Dependent-walker is a tool use for check dependent and generate script copy dll to running dir. file copy to running dir is a link file. if the original file changed, it will be changed to, to keep this file, you must copy it to other folder.

usage: type mk.dependent-wakler

to add search dll path:
modify search_dll_path.cfg to those folder, 
Note: each line is a folder (not end with / or \)
examples:
 - correct: 
	.
	..
	c:\system32
 - incorect:
	..\
	c:\system32\
