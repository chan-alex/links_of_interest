
Python pants   
-------------  

Pants makes the manipulation and distribution of hermetically sealed Python environments painless.  
You can organize your code in the Pants way with targets for binaries, libraries, and tests.  
Pants builds Python code into PEXes.  
A PEX is, roughly, an archive file containing a runnable Python environment.



A pex file is a self-bootstrapping python environment. You can consider it as an isolated virtual environment packed in a file.  
This makes for an environment super easy to distribute.  
It can be built once and used everywhere with a few caveats, mostly due to platform dependencies.
Most likely, you should be able to build platform specific "pex" distribution file. 

Example:
You can use it to create a file that acts like a python interpreter with all the dependencies added already.
You can use pex to create a sphinx documentation tool executable - "sphinx.pex".  
Executing the tool, you will find that it acts like "sphinx-build" script. You can read more about it in pex documentation.  
  
Pants is a build system designed for codebases that:  

  Are large and/or growing rapidly.  
  Consist of many subprojects that share a significant amount of code.  
  Have complex dependencies on third-party libraries.  
  Use a variety of languages, code generators and frameworks.  

Pants supports Java, Scala, Python, C/C++, Go, Javascript/Node, Thrift, Protobuf and Android cod

- built and used by Twitter, Foursquare, Square, Medium and other companies.


References:
http://www.pantsbuild.org/first_tutorial.html
http://pyfunc.blogspot.sg/2014/09/building-and-packaging-python.html

