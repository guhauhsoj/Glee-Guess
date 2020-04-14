# Glee-Guess
A Glee Guess Who Game!


guhauhsoj here, this is a glee game [hertzmad](https://github.com/hertzmad) and I decided to make by randomizing a selection of 69 glee characters to make 
24 character guess who like pdf sheets. Besides hertzmad I'd like to thank github user [delimitry](https://github.com/delimitry) and [their code](https://github.com/delimitry/collage_maker) for a collage maker  is an essential part of this project, besides that the other python code is mine. 

A few basic rules the formatting of what we have right now

When running this make sure that your current WD has no file called "GleeImages" since the code in Glee.py will delete 
and then repopulate this with the resampled characters.

To use this 

Run "glee.py" to create the folder "GleeImages" these are your randomly sampled characters for your game of guess who.

Main characters as decided by hertzmad are weighed double as the rest of the recurring cast to ensure that you have on average 48/93 main cast characters.

After this you should run the code for "collage_maker.py"


with the command line arguments as follows 



collage_maker.py -f GleeImages -o GleeGuessWho.png -w 800 -i 250


This should output the collage into the working directory!

Have fun fellow gleeks!
