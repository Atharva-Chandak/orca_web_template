# Orca
A jekyll template for easy creation of course websites! Check out the template [here][website] 
![alt text](assets/orca.jpg)

6 Quick steps :

1. Fork this repository. 

2. Add any data files(Lecture slides, notes, assignments ) in the respective directories in 'assets' directory. If images are needed, add them directly to assets directory. 
Resources must be explicitly named with complete file extensions(.pdf, etc).
Note: Please do not change directory structure of the root.

3. Set up header & footer: In the '_data' folder, go to the 'includes' subfolder's 'header.yml' file and make the tabs you want in the existing format. Similarly customize your footer as per your wish.

4. Now, write the required contents in all of the files of '_data' directory. Do not change the keys/file names. If you have to change the keys, make changes in all the files/locations(.html files) where it is being used/mentioned directly as a key.
Use basic html tags such as 'p', 'br','a', etc explicitly to the .yml files for their corresponing roles.<br>
*N.B.*:
"Do  not use double quotes(" ") in .YML files". Apostrophes & single inverted commas are fine. If you have to use double quotes, read the method of escape characters from [here][jekyll-qoutes]
Ensure there is a 'space' character before writing in-front of keys of .yml files

5. You can create new pages to your website by simply creating 'title.html' files and adding the front-matter as shown in example of "extra.html" file. Do not forget to write the front-matter as the webpage will not render properly without it.

6. In the config.yml file, write the course tite(which also appears on homepage). Fill in the url as your website's url. If you are using github to host your website, then baseurl is the name of your repository. Else, it is the subpath(if any) of your website.

Its Done! Your website is now live at the link: {url}/{baseurl}/ 

P.S.
To create anything new, carefully use the same format as used above in the same document.
While creating new headings/ sub-headings, all 'id' attributes should have values same as heading itself, so as to automatically render it.

[jekyll-qoutes]: https://talk.jekyllrb.com/t/how-to-use-single-quote-and-double-quote-as-part-of-title-without-escaping/2705
[website]: https://atharva-chandak.github.io/orca_web_template/