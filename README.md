----------------------------------------------------------------------------
README:              Generic Makefile Template for C/C++
----------------------------------------------------------------------------

Author:

	Yonghyun Hwang		<freeaion@gmail.com>

Directory structure:

	example/	- example makefiles and hello world program
              explaining how to use the makefile templates

Introduction:

Generic makefile template is a build script that helps C/C++
developers to have their own build environment in a minute without
understanding the complexity of makefile and build process. The
template is highly flexible and ultra-easy to customize.

To use/customize the template, a developer can follow three simple
steps.

  1) put Makefile.macros and Makefile.rules in a project root
     directory

  2) copy the template, Makefile, into her/his directories w/ source
     code in them

  3) customize the templates by following the comments in the
     templates

Customizing the template sounds complicated or scary. However, it's
__not__. :) Sometimes, customizing is not necessary at all. To give an
example, let's assume that a developer implements a famous program,
'hello_world.cc' and wants to build it. In this case, simple one step
instead of the three steps. S/He copies Makefile* into the dir w/
'hello_world.cc' and run "make". That's it. The template is smart
enough to detect 'hello_world.cc' automatically and build it.

Even when a developer needs to specify compile/link options, have
directory hierarchies for a project, and build couple of shared
libraries, it is not a problem at all. The template is scalable enough
to accommodate all the needs. By specifying what's needed in the
template, jobs should get done as expected.

One of the best way to learn/appreciate something new quickly is to
take a look at examples. :) Hence, please take a look into "example"
directory for all gory? details.

For now, only *.cc, *.cpp, and *.c files are recognized by the
template. The template requires GNU make 3.81 or higher. If you need
any comments and/or feedback, please feel free to contact me at
<freeaion@gmail.com> Enjoy!

Yonghyun Hwang, Apr 2016.

----------------------------------------------------------------------------
