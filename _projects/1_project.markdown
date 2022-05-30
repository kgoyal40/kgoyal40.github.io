[comment]: <> (---)

[comment]: <> (layout: page)

[comment]: <> (title: Project 1)

[comment]: <> (description: a project with a background image)

[comment]: <> (img: /assets/img/12.jpg)

[comment]: <> (---)

[comment]: <> (Every project has a beautiful feature shocase page. It's easy to include images, in a flexible 3-column grid format. Make your photos 1/3, 2/3, or full width.)

[comment]: <> (To give your project a background in the portfolio page, just add the img tag to the front matter like so:)

[comment]: <> (    ---)

[comment]: <> (    layout: page)

[comment]: <> (    title: Project)

[comment]: <> (    description: a project with a background image)

[comment]: <> (    img: /assets/img/12.jpg)

[comment]: <> (    ---)


[comment]: <> (<div class="img_row">)

[comment]: <> (    <img class="col one left" src="{{ site.baseurl }}/assets/img/1.jpg" alt="" title="example image"/>)

[comment]: <> (    <img class="col one left" src="{{ site.baseurl }}/assets/img/2.jpg" alt="" title="example image"/>)

[comment]: <> (    <img class="col one left" src="{{ site.baseurl }}/assets/img/3.jpg" alt="" title="example image"/>)

[comment]: <> (</div>)

[comment]: <> (<div class="col three caption">)

[comment]: <> (    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.)

[comment]: <> (</div>)

[comment]: <> (<div class="img_row">)

[comment]: <> (    <img class="col three left" src="{{ site.baseurl }}/assets/img/5.jpg" alt="" title="example image"/>)

[comment]: <> (</div>)

[comment]: <> (<div class="col three caption">)

[comment]: <> (    This image can also have a caption. It's like magic.)

[comment]: <> (</div>)

[comment]: <> (You can also put regular text between your rows of images. Say you wanted to write a little bit about your project before you posted the rest of the images. You describe how you toiled, sweated, *bled* for your project, and then.... you reveal it's glory in the next row of images.)


[comment]: <> (<div class="img_row">)

[comment]: <> (    <img class="col two left" src="{{ site.baseurl }}/assets/img/6.jpg" alt="" title="example image"/>)

[comment]: <> (    <img class="col one left" src="{{ site.baseurl }}/assets/img/11.jpg" alt="" title="example image"/>)

[comment]: <> (</div>)

[comment]: <> (<div class="col three caption">)

[comment]: <> (    You can also have artistically styled 2/3 + 1/3 images, like these.)

[comment]: <> (</div>)


[comment]: <> (<br/><br/>)


[comment]: <> (The code is simple. Just add a col class to your image, and another class specifying the width: one, two, or three columns wide. Here's the code for the last row of images above:)

[comment]: <> (<div class="img_row">)

[comment]: <> (    <img class="col two left" src="/img/6.jpg"/>)

[comment]: <> (    <img class="col one left" src="/img/11.jpg"/>)

[comment]: <> (</div>)
