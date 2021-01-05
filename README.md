# brouter
 Beautifule Router. A router with elegance.

 ## Directory

* ./src -- Source files.
  * ./src/config.h -- Header file.
  * ./src/Framer.h/cpp -- Framer class to handle ethernet frame.
  * ./src/Router.h/cpp -- Router class to execute routing procedure.
  * ./src/Interactor.h/cpp -- Interactor class to interact with user input.
  * ./src/main.cpp -- Main function file.

## Usage

The repository doesnot contain any project directory because one Visual Studio's project directory is too large. 

To run the output file, your computer must have installed VC++ run time and WinPcap, both of which are easy to acquire online. 

To Compile this code, your platform must be windows. It will be better if you are using Visual Studio 2019. You must first include the WpdPack directory (Provided by WInPcap) in your working project. To ignore possible warnings generated by MSVC compiler, you're advised to add defines `WPCAP;HAVE_REMOTE;_WINSOCK_DEPRECATED_NO_WARNINGS;_CRT_SECURE_NO_WARNINGS` in preprocesser settings. And then, if lucky, you can compile this code now. 