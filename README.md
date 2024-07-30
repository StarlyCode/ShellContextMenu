# ShellContextMenu

A context menu for use with WinForms. 
Copied from http://afjohansson.spaces.live.com


## Original Description
"Stand-alone" shell context menu

It isn't really debugged but is mostly working.
Create an instance and call ShowContextMenu with a list of FileInfo for the files.
Limitation is that it only handles files in the same directory but it can be fixed
by changing the way files are translated into PIDLs.

Based on FileBrowser in C# from CodeProject
http://www.codeproject.com/useritems/FileBrowser.asp

Hooking class taken from MSDN Magazine Cutting Edge column
http://msdn.microsoft.com/msdnmag/issues/02/10/CuttingEdge/

Andreas Johansson
afjohansson@hotmail.com
http://afjohansson.spaces.live.com