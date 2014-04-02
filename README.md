#What is LaTeX?

LaTeX is a document preparation system.  A document is prepared in a "markup language" and is then rendered into a completed document, most commonly as a pdf.  

#Installing/Using LaTeX

To use LaTeX, you need both an editor and a compiler.  The editor can be any standard code editor although you may prefer using one that has LaTeX support (shortcuts, autocomplete, etc...).  

The compiler is a package that you install on your machine (unless you use one of the online options).  Instructions are available on the sites listed below to install the LaTeX compiler for your OS.

##Online

Use an online editor and compiler.  Both [ShareLatex](http://sharelatex.com) and [WriteLatex](http://writelatex.com) are free and work well.  The only caveat is that you'll have to upload your figures to the sites in order to insert them into your documents.  

##Install locally

##Windows

###Compiler
I recommend using MiKTeX on Windows.  The download page is [here](http://www.miktex.org/2.9/setup).  If you are using a machine in a lab, you probably don't have administrator rights, but you can still install and use the MiKTeX Portable version available on the download page.  
From the MiKTeX website:

The portable edition allows you to run MiKTeX from a portable storage device:
*  you carry MiKTeX on a portable storage device for use on any Windows computer
*  configuration settings are stored on the portable storage device and not in the Windows Registry of the host computer
*  by using MiKTeX Portable, you leave no traces on the host computer
*  you do not need administrator privileges on the host computer

###Editor
[Texmaker](http://www.xm1math.net/texmaker/download.html) is a nice cross-platform editor with autocomplete and other useful features. 

##Mac

###Compiler
Download and install the [MacTex Package](http://mirror.ctan.org/systems/mac/mactex/MacTeX.mpkg.zip).  This may require admin rights. 

###Editor
The MacTex package includes the TeXworks editor, which is reportedly nice to use.

##Linux

###Compiler
Your distribution almost certainly has a LaTeX package available.  Use your package manager to download and install it.  You should be able to find a wiki page for your distribution with instructions.

###Editor 
Again, [Texmaker](http://www.xm1math.net/texmaker/download.html) is a nice cross-platform editor with autocomplete and other useful features. 
There's also a nice vim plugin called [TeX 9](http://www.vim.org/scripts/script.php?script_id=3508) if you believe in the one true editor.

#Getting started

Now that you have an editor and compiler installed, let's get started.  

First, download these [starter files](https://github.com/gforsyth/learnlatex/archive/master.zip) and put them in their own directory.  

##Hello World
First, a quick test to make sure everything on your end is working.  

1. Open the LaTeX editor you've chosen and load in the file HelloWorld.tex
2. Try to compile it.  There should be a button for this labeled something like "Generate", "Run" or "Compile".  
3. Click View PDF in your editor.  (Or your editor may automatically open the document)

That's the general workflow.  A document is edited and typed in this markup format and then the compiler renders it into the completed document. 

Assuming the HelloWorld document compiled without issue, we can get started on something a bit more substantial.  

##Learn LaTeX

1. Open learnlatex.tex in your editor.  There's a lot going on here, but it will (hopefully!) be pretty straightforward. 
2. Try to compile learnlatex.tex.  If all goes well, you should have a pdf that corresponds to the code.  
3. Place the pdf and the editor side by side and go through the code and the resulting document line by line and you'll be able to see how a document is put together. 

You can try changing or adding elements as you go, if you like.  If it doesn't compile, you can always undo your changes or just re-download the original and have another go.  

##Cheat Sheet
You can also grab the wonderful LaTeX cheat sheet [(pdf)](http://www.stdout.org/~winston/latex/latexsheet.pdf) put together by Winston Chang which is a nice reference to have, especially when you're starting out.

Feedback is welcomed, I'd like this to be useful and not a chore.  
