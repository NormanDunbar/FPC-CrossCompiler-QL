# A *Free Pascal* Cross Compiler for the Sinclair QL
This repository is for a PDF document describing how anyone can set up and build the Free Pascal Compiler for the Sinclair QL. The document will be updated as and when required, the latest version will always be found at:

https://github.com/NormanDunbar/FPC-CrossCompiler-QL/releases/latest/.

Just for fun, in November 2020 some people out there, who should have known better, decided that as part of *QLvember*, they would get a version of the Free Pascal Compiler running on and for a Sinclair QL. Ok, running on is possibly a bit far fethced, but a cross compiler was indeed created.

I decided that I would stick my oar in and attempt to remember how to code in Pascal, and also, to see if I could help get the required units and so on working. As I tend to forget stuff, and always have, I figured I better document everything I was doing in case I had to wipe it out and start again.

This document describes how I:

* Installed FPC for Linux x86-64 which is required in order to create the cross compiler;
* Downloaded the source code for FPC which is again required to build the cross compiler;
* Built the cross compiler;
* Amended, compiled and installed the QL's Run Time Library;
* Amended, compiled and installed the QL's units;

All of this took place on an old Dell Vostro 17" laptop fitted with an AMD dual core processor, 8 GB RAM and took place in a Virtual Machine specifically built for the experiment. Experiments go bad sometimes, and in a VM it's easy to wipe and start again.

The instructions obviously cover Linux, I'm hoping someone will help translate them into Windows for those unfortunates who are still having to use that particular OS. 😉
