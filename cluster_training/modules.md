
# Module system

- The Environment Modules package provides for the dynamic modification of 
  a user's environment via module files.
- Each module file contains the information needed to configure the shell
  for an application. Once the Modules package is initialized, the 
  environment can be modified on a per-module basis using the module command 
  which interprets module files. Typically module files instruct the module 
  command to alter or set shell environment variables such as PATH, MANPATH, 
  etc. module files may be shared by many users on a system and users may 
  have their own collection to supplement or replace the shared module files.
- Modules are useful in managing different versions of applications. 
  Modules can also be bundled into meta-modules that will load an entire 
  suite of different applications, or ensure dependencies are loaded.

# Module basics

module avail, show, load, list, unload

   $ module avail # shows the currently available module to the system # format is application/version

   $ module show beast/1.8.3 # shows information, such as what-is, other modules loaded and path information

   $ module load beast/1.8.3 # load the module beast version 1.8.3 $ module list # show currently loaded modules
   $ module unload beast # unload the module beast

# Module advantages

- Modules are great for keeping track of what software and specifically 
  what version of the software is being used in an analysis.

- If you load specific versions of modules, the software you are using will
  not change, even if a newer version is installed.
