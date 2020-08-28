# How to use Jemdoc
The original link of jemdoc: http://jemdoc.jaboc.net/index.html

The following are simplified steps to generate website pages:
 
 1. Download Python 2: https://www.python.org/downloads/release/python-2718/
 2. Add the downloaded python.exe to the PATH. Then in terminal window, run "python --version" to check if it is correctly added.
 3. Start from creating index.jemdoc file (because github page requires "index.html" as the landing page), then run "python jemdoc.py index" to generate index.html.
 4. Add more *.jemdoc files as other pages.
 5. Add MENU file. And add "# jemdoc: menu{MENU}{*.html}" at the beginning of each *.jemdoc file and regenerate the html file.
 6. Update the GitHub, and forward to customized domain.
