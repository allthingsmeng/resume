# Michelle Meng Nguyen's Resume
this is a jekyll project

## Some things to know
### What things do
- ```_includes``` usually the main html page **head** and any other site elements to be broken out of individual pages like a **footer** or **header** refer here if you see code that resembles this ```{% include head.html %}```
- ```_layouts``` this where the page **templates/layouts** live these give the content of your files their skeleton refer here when you see something like this ```layout: default``` in the head of your page between the set of ```---```
- ```assets``` to your site like images, javascripts, etc
- ```css``` yup... usually compiled sass/scss
- ```CNAME``` how your url knows to call here
- ```_config.yml``` this file gives **Jekyll** core directions like your site name or even where your css lives its the settings file. *Please note: you must restart Jekyll if anything is changed here and you want to see the affect*
- ```index.md/index.html``` the first page of your site

### Jekyll
- ```jekyll serve --watch``` to start jekyll to build your site locally 
- ``` ctrl + c``` will stop the jekyll server
