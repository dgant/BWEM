# BWEM (Brood War Easy Map)
### A Github-hosted fork of the library by Igor Dimitrijevic

## About
BWEM (Brood War Easy Map) is a library written by Igor Dimitrijevic for developers using BWAPI (Brood War API) to develop AI players for Starcraft: Brood War

I am, notably, *not* the author Igor Dimitrijevic. I put this repository together because I am working on a JNI (Java Native Interface) port of BWEM and needed to build BWEM as a standalone DLL.

So this repository includes a Visual Studio 2013 solution which builds BWEM as a DLL against a local copy of the BWAPI library source code.

## Version
This is BWEM version 1.3.1, published by Igor in September 2016

## Links
Official BWEM website: http://bwem.sourceforge.net/index.html
Official BWEM download: http://sourceforge.net/projects/BWEM

##Setup (Using BWEM in your Starcraft AI)
Just follow Igor's instructions at http://bwem.sourceforge.net/start.html

##Setup (Producing a standalone DLL in Windows)
1. Install Visual Studio 2013: https://www.visualstudio.com/en-us/news/releasenotes/vs2013-community-vs
2. Clone BWAPI: https://github.com/bwapi/bwapi
3. Build BWAPI. The goal is to create the BWAPI.lib and BWAPId.lib files used by BWEM
4. Create an environment variable called BWEM_BWAPI, and set it to your BWAPI source code directly (directly underneath /include and /lib)
5. Open the BWEM.sln in Visual Studio 2013. You should be able to just build it!

##License
Igor has licensed BWEM under the MIT/X11 license.

