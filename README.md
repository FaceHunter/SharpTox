SharpTox
========

This project aims to provide a simple library that wraps all of the functions found in the [Tox library](https://github.com/irungentoo/ProjectTox-Core "ProjectTox GitHub repo").
Tox is a free (as in freedom) Skype replacement.

Note: SharpTox is far from finished/perfect. Feel free to contribute!

### Things you'll need

* The libtoxcore library, you should compile that yourself from the [ProjectTox GitHub repo](https://github.com/irungentoo/ProjectTox-Core "Tox Github repo").

* Depending on your operating system, Tox's core library could have more dependencies apart from libsodium (which you should already have compiled while following the compilation guidelines on the ProjectTox repo page). For Windows, this dependency is libgcc_s_dw2-1.dll.

Please note that at this time, this project hasn't been tested on any operating system other than Windows. You are of course, free to give it a try on the operating system of your choice. (some changes to the ToxFunctions class are needed for that though)

### Toxy
Toxy is basically just a WinForms client used as an example to show how SharpTox can be used.
If you're considering using SharpTox for your project, you should definitely have a look at that. It should have most of the functionality of Tox implemented.

Toxy will be available [here](https://github.com/Impyy/Toxy) soon.
