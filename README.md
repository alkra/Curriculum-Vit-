Pour voir ce fichier en français, allez sur
[LISEZMOI.md](LISEZMOI.md).  
Um diese Datei auf Deutsch zu lesen, bitte gehen Sie auf
[LIESMICH.md](LIESMICH.md).


This is my CV
=============

My name is Alban Kraus, and I am a last-year student at the [French
School for Geomatics](http://www.ensg.eu), near Paris, France.  I am
specialized in information systems; at school, I have explored a panel
of new technologies.

You are on my [GitHub](https://github.com/alkra), and here you can see
some of my school projects; do not forget to have a look at my
contributed repositories.

This repository is my *curriculum vitæ*.  It is written in LaTeX, but
I plan to provide also a Markdown and an HTML+CSS version.



The latest PDF
==============

* [In English]()
* [In French]()
* [In German]()



Compiling from source
=====================

Download
--------

### Requirements

A *git* client.  Get it from the *Download* section of
[git-scm.com](https://git-scm.com/).

### Process

From a command prompt, issue the following commands:

    git clone https://github.com/alkra/Curriculum-Vitae.git
    cd Curriculum-Vitae

Alternatively, you can press the *Download ZIP* button, extract it,
and then open a command prompt in the folder.

Then, download all branch's head:

    git fetch

According to which language you want, you have to checkout the
corresponding branch. For example, if you want to compile a PDF in
English, issue the command below:

    git checkout origin/master-en



As PDF
-----

### Requirements

* A working LaTeX distribution. See files [`cv.tex`](cv.tex) and
  [`cv.sty`](cv.sty) for the required packages.

### Process

From a command prompt, fire the following command:

    pdflatex cv.tex

### Result

The resulting PDF will be named `cv.pdf` .




Licensing
=========

You can freely download and distribute the above PDF files. They are
brought to you under the [Creative Commons – Attribution –
Non-commercial – No
derivatives](http://creativecommons.org/licenses/by-nc-nd/3.0/)
licence.

The stylesheet is `cv.sty`. You are free to download, modify, compile,
and distribute this file, under the conditions of the
[GNU Lesser General Public Licence](lgpl-3.0.txt) version 3.0 or
above.

The content of this work (the Content) is made of all `.tex` files of
this repository, as well as the images located in the `imgs`
subfolder.  It is protected under the French law.  Permission is
granted to:

* download and read the Content; you may make minor modifications in
  order to make the files readable;

* generate a compiled document from the unmodified Content;

* modify all or part of the Content, thus creating a derivative work;
  in that case, you must remove all content that refer to me, such as
  my name, photograph, and other personal data.  This permission does
  not apply to the photographs in `imgs` folder; thus, you must remove
  them from your derivative work.

You may distribute unmodified copies of the Content.  You may
distribute a compiled document if it respects the semantics and
disposition of the output of `pdflatex` running on the unmodified
Content.  In any case, you are not allowed to make commercial benefits
from the distribution.  If you distribute any of the preceding, you
must not apply terms that restrict or extend the permissions you have
been granted.

Alternatively, you can reuse the Content under the terms of the
[Creative Commons – Attribution – Non-commercial – No derivatives](http://creativecommons.org/licenses/by-nc-nd/3.0/)
licence.
