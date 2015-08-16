# BULatexTemplate
I am a recent Bournemouth University graduate and used LaTeX for my dissertation, initially I spent some time getting the template right for the style that BU require, as they didn't provide a LaTeX template, I made my own. Now am sharing it with you in the hopes time is saved and more people use LaTex as its far better than MS Word!  

This template also includes the BU Harvard referencing style, if you are using the template it is included and will work straight away, this style was created with a tool freely available online, it did take an afternoon to get right.

##What does it look like?
Check out main.pdf and see for yourself! I neglected the front page as it is supplied to you by the University in a very fetching blue colour.  

#Usage 
I used this template with Sublime Text and the LaTeX tools plugin, found [here](https://github.com/SublimeText/LaTeXTools), this doesn't have to be used but I did find it to be the best for my ways of working. 

If you use other tools then you may have to take out the first line in each of the files as that lets LaTeX Tools know where the primary file is to start the build process.

##Referencing 
Use `citep{}` this gives the references the parenthesis that BU require.

#Just the referencing style?
Download the buHarvard.bst file and ensure your preamble has `\bibpunct{(}{)}{,}{a}{}{ }` and `\bibliographystyle{buHarvard}`, sorted!


#Changes
If there are changes to the template that need to be done, then please just put in a merge request and reasoning for the change, I will check them over and add them in, hopefully we can create a sustainable template for those who want to use LaTeX in their dissertations.

#Lastly 
Good luck with your dissertations, or any other project if you're just using the referencing style!