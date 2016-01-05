This project is a TinyOS SDK implementation written in C# ([tinyos-main/support/sdk/](https://github.com/tinyos/tinyos-main/tree/master/support/sdk/csharp)). The solution includes the following projects:

<b>tinyos-sdk</b>

A class Library project which compiles into a single `.dll` file that can be referenced from any C# project.

<b>sfsharp</b>

A Serial Forwarder built on top of the sdk which combines in the same command shell features from both the Java SF and the C++ SF. Features:

*	`start`,`stop`,`info` and `list` commands. Mote interface for the SF-Servers can be Serial and TCP, hence SF-Servers are chainable and doesn't need to run on the machine to which the motes are physically connected

*	`send` and `listen` commands integrated in the program shell

*	Local and control client

*	Command history and inline command editing with enhanced visualization through text color (see Wiki)

<b>ExampleTelosB </b>(Usage example)

Simple application that reads, converts and displays sensor values from telosB nodes.

<b>TestSerial</b> (Usage example)

An implementation of the TestSerial application


#####TODO

- Build a simple [mig](http://www.tinyos.net/tinyos-1.x/doc/nesc/mig.html) program for the sdk
- Code documentation

#####CREDITS

www.advanticsys.com
