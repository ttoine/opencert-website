---
title: Eclipse APP4MC
type: index
---

 **Eclipse "#projectname"** is a not so empty template to create website very quickly for new projects and working groups joigning the Eclipse Foundation. It is made with static html website generator [Hugo](https://gohugo.io)

 Below is an example of an image.

<img src="images/eclipse.jpg" class="img-responsive">

When you open the index.md file you will see that embeded pictures have a related link. Please don't start URL of files with a "/". Please put all pictures in the "static" folder, and eventually use or create dedicated sub-folders for each page if you will use a lot of picture, e.g screenshots for a tutorial.


### A video from Youtube

<div class="embed-responsive embed-responsive-16by9">
<iframe class="embed-responsive-item" src="https://www.youtube.com/embed/dPDuy2lXJHc" frameborder="0" allowfullscreen></iframe>
</div>

### Update the website logo:
First step is to create a picture with the good size. For example, the template logo is 210x76px. FYI, on this theme, the logo picture is set to a max-width of 210px in the CSS.

There are two ways to change the picture:

 - you create a logo.png file, and to replace the file "static/images/logo.png", or
 - you create any file like "foo.jpg" in "static.images/" and then you update the "logo" path in the [params] section of config.toml.

### Aim

The aim is that end users have all the resource they need to use the project. But, also, information if they want to get involved.

### This is a h3 title

You can find information about the Markdown Syntax here:

 - [Basics](https://daringfireball.net/projects/markdown/basics)
 - [All syntax](https://daringfireball.net/projects/markdown/syntax)

 ---

### Let's add some Lorem Ipsum

Lorem Ipsum is very convenient to fill some pages with dummy content that looks like actual content. You can learn its history on Wikipedia and generate some paragraphs via websites like [Lipsum.com](http://www.lipsum.com/).

### Lorem ipsum dolor sit amet

In nec fermentum urna. Ut consectetur diam nec tempor suscipit. Praesent fringilla diam dui, id molestie dolor tempor eu. Sed viverra risus in consequat tristique. Aliquam non pulvinar felis. Ut molestie nisl nulla, ut aliquam risus eleifend in.

> Suspendisse purus massa, malesuada quis est at, feugiat ullamcorper ipsum. Quisque tempus nunc vehicula odio condimentum, at feugiat lacus posuere. Phasellus purus nibh, gravida sed luctus malesuada, iaculis sed quam. Nullam dapibus felis enim, id auctor elit suscipit ut. Nam dapibus orci eget elit interdum, sed tincidunt nisl consequat. Vestibulum sed sagittis mi. Vivamus at mollis felis, quis pharetra enim.

Praesent volutpat convallis massa, et maximus dolor tincidunt at. In sed fringilla diam, sit amet consectetur risus. Aliquam elementum nunc consectetur diam mattis maximus. Nam mattis, lectus quis efficitur porttitor, erat orci molestie eros, ac consectetur nisi metus a justo. In vehicula ullamcorper felis. Nullam aliquet, dolor pharetra condimentum pharetra, ligula ante facilisis est, sit amet fermentum elit nunc ut tortor. Ut convallis vehicula laoreet. Vestibulum placerat nulla vitae imperdiet hendrerit. Aliquam et ullamcorper dui. Fusce rutrum tortor id leo lobortis blandit.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin imperdiet quis turpis a mollis. Aliquam elementum tortor vitae imperdiet porttitor. In nec quam turpis. Praesent interdum quam a tellus auctor, ut auctor turpis ullamcorper. Pellentesque mollis eget urna et eleifend. Vestibulum dapibus tortor bibendum leo ultricies, nec ultricies metus porta. Mauris sagittis posuere sapien, a pulvinar orci accumsan vel.
