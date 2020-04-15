# Orca
A jekyll template for easy creation of course websites! Check out the template [here][website] 
<br><br>
![alt text](assets/orca.jpg)


### Why should I use it?

* Simple, elegant and responsive design, perfect for your course website.
* Easy to create and you get your website in no time, that too completely free!
* Highly flexible.
* No need to code the messy HTML pages. Just make a few changes in user-friendly syntax, and you'll be good to go.

If you want some inspiration, checkout [pipaf website][pipaf]

## 6 Quick steps :

 ### 1. Using the template 
 Click on the 'Use this template' button above & fill in the repository details. Once the repository is created, clone it & make the changes below to this cloned repository.  

 ### 2. Adding assets
 Add any data files(Lecture slides, notes, assignments ) in the respective subdirectories in `assets` directory. If images are needed, add them directly to assets directory. 
 Resources must be explicitly named with complete file extensions(.pdf, etc).
Note: Please avoid changing directory structure of the root.

 ### 3. Set up header & footer
 In the `_data` directory, go to the `includes` subdirectory's `header.yml` file and make the tabs you want (in existing format). Similarly customize the footer as per your wish.

 ### 4. Adding data in `.yml` files
 In the other `.yml` files of subdirectories of `_data` directory, fill out the required details. Avoid changing the keys/file names. If you have to change the keys, make the changes in all the files(.HTML files) where it is being used as a key.
 Use basic HTML tags such as `<p>`, `<br>`,`<a>`, etc. explicitly while writing HTML code in the `.yml` files for their corresponing roles in HTML files.<br>
**N.B.** :
* Avoid using double quotes(" ") in `.yml` files. Apostrophes & single inverted commas are fine. If you have to use double quotes, read the method of escape characters from [here][jekyll-qoutes]
* Ensure there is a 'space' character while writing in front of keys of `.yml` files and **indent** (note!) your code as per the format followed in the file.

 ### 5. Creating new pages
 You can create new pages to your website by simply creating `your_title.html` (in root directory itself) and simply adding the front-matter, as shown in `extra.html` file. Do not forget to write the front-matter as the webpage will not render properly without it.

 ### 6. Configure the `config.yml` file
 Fill in the details of `config.yml`. (If you are using github pages to host your website, baseurl is the name of your repository).
<hr>
<p>
And, its done! Your awesome course website is ready! 
</p>
P.S.
* To create anything new, carefully use the same format as used in the same file.
* While creating new headings/ sub-headings, all `id` attributes should have values same as heading itself, so as to automatically render it.
* If you want assistance in deploying, [click here][deploy].

## Contributions:
Any constructive feedback or contributions are welcome & highly appreciated.

[jekyll-qoutes]: https://talk.jekyllrb.com/t/how-to-use-single-quote-and-double-quote-as-part-of-title-without-escaping/2705
[website]: https://atharva-chandak.github.io/orca_web_template/

[pipaf]: https://p-paf.github.io/
[deploy]: https://jekyllrb.com/docs/deployment/third-party/