# Exercise 2

Learn the basics of git workflow, including adding new files.

1. **Fork** the repo onto your own github account  
(maybe you already did it).

2. clone it to your laptop  
`git clone ...`

3. Download an image from the web and place it into the repo folder
   into _exercise-2_ subfolder.
   
> assume you call this image "cute-dolphin.jpg" and it is placed in
> the same folder as this readme file.
   
4. Add this file to _git_.  See [Adding
   Files](file:///home/otoomet/tyyq/teaching/info201/book/localbook/build/git-basics.html#adding-files). 
   
```bash
git add cute-dolphin.jpg
```

5. Add the image to this file using markdown syntax.

> You need to add a line along the line
> ![alt text](cute-dolphin.jpg)
> * ! means to show the image in rendered page (on github), without it
> it will just show a link there (try this!)
> * _alt text_ is the alternative text, shown in case when the browser
> cannot show the image (e.g. you put a wrong file name there), try it!
> * file name should be the relative path to the file.
   
5. Write a paragraph of text where you explaine what the picture is
   about.  Feel free to add more.
   
> You can write about the content of the image, and also provide link
> to the source.  Links can be supplied in markdown with [link text](url). 

4. commit your changes:  
`git commit -am "<explain what did you do>"`

5. send your edits back to GitHub
`git push`

6. check the repo on your github account.  Did it work?

> The image should be there.  It may look way too big (or small) on GitHub,
> markdown does not have standard ways to scale image.
