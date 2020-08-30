# How to use Jemdoc
The original link of jemdoc: http://jemdoc.jaboc.net/index.html

The following are simplified steps to generate website pages:
 
 1. Download Python 2: https://www.python.org/downloads/release/python-2718/
 2. Download Visual Studio Code: https://code.visualstudio.com/download
 3. Download Git: https://git-scm.com/downloads, and GitHub Desktop: https://desktop.github.com/
 4. Add the downloaded python.exe to the PATH environment variable(by default, add "C:\Python27" to environment variable). Then open a terminal window, run "python --version" to check if it is correctly added. If Python3 is already installed, to avoid conflicts, change the file name "python.exe" to "python2.exe" in the folder "C:\Python27". When we want to run python2 files, just use "python2 *.py".
 5. After setting up the environment variable, we can edit our pages, which end with ".jemdoc", in Visual Studio Code.
 6. start from creating index.jemdoc file (because github page requires "index.html" as the landing page), then run "python2 jemdoc.py index" to generate index.html.
 7. Add more *.jemdoc files as other pages.
 8. Add MENU file. And add "# jemdoc: menu{MENU}{*.html}" at the beginning of each *.jemdoc file and regenerate the html file.
 9. Update the GitHub, and forward to customized domain.
