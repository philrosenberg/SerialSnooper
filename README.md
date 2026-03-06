This is  a really basic command line application to pass through serial data on a windows machine.

I only provide build files for Visual Studio. Sorry. But it's easy to create your own as it only depends on system libraries.

It's really useful for debug science instruments as you can see data being transferred back and forth.

You will need to grab my header only scientific library, as I use my time functions from this code, you can get it from https://github.com/philrosenberg/sci, just put the headers somewhere they can be found.

Build it as usual and to run use a command like

SerialSnooper COM4 COM5 \"C:\\Data\\my file.txt
