# Formulas, and samples for the Ultrafractal program   
   
## Intention, notes:   
**This repository is mainly intended as a playground for formulas etc, and related samples for the program `Ultrafractal (UF)` which are not intended to move them to the official formula database.**   
   
Originally these `ABC-formulas` repositories were mainly intended to publish my own formulas, and related samples for the several fractal programs I use.   
This was mainly since I found that I need a central place for my formulas rather to have them scattered across the fractal forums, deviantart etc.   
Also I made the experience in earlier days in Ultrafractal that versioning 'by hand' is really a nightmare - I know, that should be self-eveident for any 'real' developer, but I don't see me as true developer, and hence I felt into that trap...   
   
However, while thinking about the way to build such a central repository I came to the conlusion that I would like to follow more the common open source approach, and to publish the formulas in a way that everyone can contribute.   
   
Of course there is already an official formula database (see below link).   
However, many of the formulas published here are less sophisticated than many of the formulas in the official database.   
So this repository is thought as a playground for formulas that are written with less ambition, but which may also be interesting enough to share them.   
   
Please feel free to contribute, ask for changes / corrections / improvements, to add your comments, and questions etc.   
   
Please find the necessary program Ultrafractal at https://ultrafractal.com   
The official formula database can be downloaded through the program, or via http://formulas.ultrafractal.com/   
   
## Usage:   
You will need the program Ultrafractal to use the formulas.   
Due to the architecture of UF I would think that the formulas can be used wherever UF is able to run.   
Most of the formulas have been created in earlier UF versions (in case of .frm files even back to Fractint), but as far as I know they should also work in the most current version.   
They use a proprietary language that cannot run directly anywhere else.   
   
As these formulas are not part of the official database you need to place them manually in the folder you have configured for formulas, colorings etc.   
   
## Folders:   
- The folder [/formulas-ufm](/formulas-ufm) contains UF formula (i.e. \*.ufm) files independent from any publishing elsewhere.   
  Any possible development will happen here.   
      
- The folder [/formulas-frm](/formulas-frm) will contain old formula files of Fractint style independent from any publishing elsewhere.   
  There is of course no "development" anymore, but for quick testing I still like those .frm files, especially if it comes to rough mutations of pure formulas without any further logic.   
  And I may commit changes as I have to consolidate many different versions ( Yeah, I did not use git before ;-) )   
    
- The folder [/colorings](/colorings) contains UF coloring algorithms (i.e. \*.ucl)    

- I may also publish other types of formulas (like transdorms), and params - the naming of the folders will be self-explaining.   
   
- The folder [/published-samples](/published-samples) contains any type of formulas, and other related data published elsewhere (currently at fractalforums.org only).    
  The files will not be changed (beyond any possible improvements of non-functional parts like documentation etc).   
  Even corrections would result in new files for compatibility with the existing threads.   
   
## Disclaimer:   
The formulas need Ultrafractal to run. They use UF's own proprietary language, and cannot run independently.   
Please however do not hesitate to re-use the ideas behind as appropriate (with the according credit).   
   
The formulas have been developed over the years on several of my Windows boxes, and on several Ultrafractal versions - and often nowhere else.   
All published formulas have been tested to a certain extend in UF version 5 \- I will share an according information if there should be any other dependencies.   
There is however one exception regarding testing:     
Not all of the (originally some 1000 of) entries in the several .frm files have been tested in UF, especially if they have been copied over from Fractint.   
   
As of now I assume that the formulas can be used whereever Ultrafractal does run.   
But I neither have the capacity, nor the intention to test the formulas somewhere else than on my normal boxes.   
   
Hence I cannot provide any warranty for this code.   
Please however do not hesitate to share your experiences, or to add code that helps to run it on other UF version, hardware, or OS.   
As of now I'm publishing all of my formulas under the LGPL license (see the according license file if you really should like that stuff)...   
   
Of course Ultrafractal is using own (closed-source) license.   
But neither in the program, nor in the web page I see a hint that would restrict the license of the formulas - But please tell if you should have contrary informations.   
   
Hence please check the according information at ultrafractal.com as needed.
