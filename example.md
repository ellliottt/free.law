Title:
Author: mlissner, brianwc, etc.
Date: 1982-06-09
Modified: (Optional)
Tags:
Summary:
Status: Draft


An image:

![Alt Text]({filename}/images/han.jpg)

Floated left:

<div class="left-image">
    <a href="http://recapthelaw.org">
        <img src="{filename}/images/recap_r-150x150.png"
             alt="RECAP Logo"/>
    </a>
</div>


Centered:

<div class="text-center">
    <img src="{filename}/images/recap_r-150x150.png"
             alt="RECAP Logo"/>
    </a>
</div>

Or right:

<div class="right-image">
    <a href="http://recapthelaw.org">
        <img src="{filename}/images/recap_r-150x150.png"
             alt="RECAP Logo"/>
    </a>
</div>

You can make a big button with:

<a href="blah" class="btn btn-primary btn-lg">Foo</a>

With a caption below:

![Alt Text]({filename}/images/han.jpg)

*My caption*

An embedded thing:

<div class="embed-responsive embed-responsive-4by3">
    <iframe class="embed-responsive-item" src="" frameborder="0" allowfullscreen></iframe>
</div>

A warning:

<p class="bg-danger alert">Oh no!!!!</p>

Some links:
[a link relative to content root]({filename}/article1.md)
[a link relative to current file]({filename}../article1.md)
