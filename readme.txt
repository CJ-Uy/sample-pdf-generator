Yooo so this is the pdf generator basically

This is the way I implemented it but if you want you can also explore other options like:
    - pdf-lib
    - pdfkit
    - reactpdf
    - react to pdf
and so on. Idk what's best "now" but back then this was the solution that was fastest and worked for me


To start you need to be in the root directory of this project and run "npm install"
This will install "puppeteer js"

The idea basically is the same thing when you "ctrl + p" a website and save as pdf. Although it does require
a lot of trial and error to get all the formatting perfect

now to try the generator you can run the commands in the terminal
    cd creating
    node makePDF.js (or if you have code runner extension "ctrl + alt + n" while active on the makePDF.js file)

If you make changes to the makePDF.js you can run "node makePDF.js" and it will overwrite the current file. 
If the pdf is opened on ur browser just refresh and you will get the new file

Reminders tho:
    - The "creating" folder is just for making the form like a test site. To actually add it with other
        functionality on your site you can refer to some of the scripts in the "original_utils" with how
        I actually implemented it
    - Puppeteerjs does have its quirks tho. For example it does not work when the app is hosted in Vercel or at least
        it did not the last time I tried. However, it does work locally so it should be fine in a server.
    - If you want to see how this is connected to the frontend backend and database "follow the functions" 
        by cloning https://github.com/CJ-Uy/RAILS and using the global search tool in VSCode. (./utils/forms)
    - If ever you have a question or need me to rewrite it to make it simpler feel free to just message me.   