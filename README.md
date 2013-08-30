tinyos-csharp-sdk
=================

This is a TinyOS SDK implementation written in C#, similar in functionallity to those found under `tinyos-main/support/sdk` directory. The solution includes the following projects:

<b>tinyos-sdk

A class Library project which compiles into a single `.dll` file that can be referenced from any C# project.

<b>sfsharp

A Serial Forwarder built on top of the sdk which combines in the same command shell features from both the Java SF and the C++ SF. Features:

*	`start`,`stop`,`info` and `list` commands. Mote interface for the SF-Servers can be Serial and TCP, hence SF-Servers are chainable and doesn't need to run on the machine to which the motes are physically connected

*	`send` and `listen` commands integrated in the program shell

*	Local and control client

*	Command history and inline command editing with enhanced visualization through text color

<b>ExampleTelosB </b>(Usage example)

Simple application that reads, converts and displays sensor values from telosB nodes.

<b>TestSerial</b> (Usage example)

An implementation of the TestSerial application

TODO
----
- Port to Mono
- Build a simple mig program for the sdk
- Code documentation

CREDITS
-------
www.advanticsys.com
