#What is LaTeX?

LaTeX is a document preparation system.  A document is prepared in a "markup language" and is then rendered into a completed document, most commonly as a pdf.  

#Installing/Using LaTeX

To use LaTeX, you need both an editor and a compiler.  The editor can be any standard code editor although you may prefer using one that has LaTeX support (shortcuts, autocomplete, etc...).  I've used [Texmaker](http://www.xm1math.net/texmaker/download.html) in the past and think it's pretty good.  

The compiler is a package that you install on your machine (unless you use one of the online options).  Instructions are available on the sites listed below to install the LaTeX compiler for your OS.

##Online

Use an online editor and compiler.  Both [ShareLatex](http://sharelatex.com) and [WriteLatex](http://writelatex.com) are free and work well.  The only caveat is that you'll have to upload your figures to the sites in order to insert them into your documents.  

##Install locally

###Windows
I recommend using MiKTeX on Windows.  The download page is [here](http://www.miktex.org/2.9/setup).  If you are using a machine in a lab, you probably don't have administrator rights, but you can still install and use the MiKTeX Portable version available on the download page.  

###Mac
Download and install the [MacTex Package](http://mirror.ctan.org/systems/mac/mactex/MacTeX.mpkg.zip).  This may require admin rights. 

###Linux
Your distribution almost certainly has a LaTeX package available.  Use your package manager to download and install it.  

#Getting started

Now that you have an editor and compiler installed, let's get started.  

First, download these [starter files](https://github.com/gforsyth/learnlatex/archive/master.zip) and put them in their own directory.  

##Hello World
First, a quick test to make sure everything on your end is working.  
Open the LaTeX editor you've chosen and load in the file HelloWorld.tex

Try to compile it.  There should be a button for this labeled something like "Generate", "Run" or "Compile".  
Either a pdf of the simple document should open automatically, or you can click View PDF in your editor.  

That's the general workflow.  A document is edited and typed in this markup format and then the compiler renders it into the completed document. 

Assuming the HelloWorld document compiled without issue, we can get started on something a bit more substantial.  
Download [learnlatex.tex](https://github.com/gforsyth/learnlatex/blob/master/learnlatex.tex).  This tex file will look for an image when it compiles to add it in to the final document, so also download the [mewbacca.jpg](https://github.com/gforsyth/learnlatex/blob/master/mewbacca.jpg) and stick it in the same directory as the tex file.  

Ok, now open learnlatex.tex in your editor.  There's a lot going on here, but it will (hopefully!) be pretty straightforward.  Try to compile learnlatex.tex.  If all goes well, you should have a pdf the corresponds to the code.  

Place the pdf and the editor side by side and go through the code and the resulting document line by line and you'll be able to see how a document is put together.  You can try changing or adding elements as you go, if you like.  If it doesn't compile, you can always undo your changes or just re-download the original and have another go.  

Feedback is welcomed, I'd like this to be useful and not a chore.  
