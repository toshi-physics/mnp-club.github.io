# Maths And Physics Club

The Maths and Physics Club is a community to celebrate the sciences we revere in their purest of forms, undiluted and in all their grandeur. We cater to stimulate your brains with the best intellectual events, quizzes, symposiums, lectures & to keep the streak of curiosity level with knowledge by introducing you to labs in and off the campus with exquisite research work and setting you off to build your own experimental setups, funded by us.

## Contributing
We at MnP believe in building a community, and an integral part of an interactive community is contributing. If you have an interesting topic that you would like to share to the world, through our page, or if you come across something exciting and new, we would love to host your post. Follow the steps to get your post up!

  * Make sure you have git on your system, and a Github account; if not, you can create one for free now!    
  * It is recommended that you have *jekyll* on your system, to see how your post would look, if published. Follow this [simple guide fr Ubuntu](http://sharadchhetri.com/2014/06/30/install-jekyll-on-ubuntu-14-04-lts/), or the [official docs](https://jekyllrb.com/docs/installation/) if you don't have it yet._(You can continue in the absence of Jekyll as well!)_  
  * You can use any text editor to create your post, but a sophisticated editor like [Atom](https://atom.io/), which supports markdown rendering, for convenience.  

Once you have the above packages, you can now create your own post! Just a few more steps!

  1. Fork this repository, and clone it to your system using `git clone`. If you are new to git, you may refer to this [site](http://gitref.org/), or Google your way out!

  2. Our page supports various author profiles, and you can create your own avatar which accompanies your post! Isn't that cool? You must create your own before you proceed.
    * Navigate to the _images/_ folder in the directory and add your avatar (1x1 resolution preferably), as <username>.jpg
    * Navigate to *_data/* and edit the file *authors.yml*. Follow the other formats and add your username, Name and Image filename, among other things.

  3. You are almost ready now! Navigate to *_posts/blog/*.
    * If you have [octopress](http://octopress.org/) installed, type `octopress new post <post-name>`
    * In case you don't have it, or are unable to use the above method, create a file in the same format as existing files in the folder: `yyyy-mm-dd-post-title.md`.

  4. If you used _octopress_, then your file will have a header file containing simple details and some blanks. If not, the file would be a blank file as of now. Further, open any other file in the folder, and copy the header file in the same way, and update the details. The author would be your username that you used when creating avatar. You can further add relevant tags to your post.

  5. After the **---** line, you can write your post (note that you do not need to add a title here). The blog supports markdown, and hence you can format your post using standard `html` tags, or use `markdown`. If you are new to markdown, you can refer to [this concise guide](https://daringfireball.net/projects/markdown/syntax). You can add plain text, formatting, hyperlinks and images with markdown too!
    * If you want to use LaTeX in the Math Mode, you can do so by enclosing the code in $ ... $ for inline LaTeX, and $$ ... $$$ for the standard new line centred format.
    * If you wish to embed YouTube videos, instead of links, you can follow these simple steps!
      - Open the video on YouTube.
      - Scroll down to find the _Share_ option, and navigate to the _Embed_ tab.
      - Copy the link suggested there, and paste it in the blog file.
    It would look something like this when added. A great way to refer videos, right?
    <iframe width="560" height="315" src="https://www.youtube.com/embed/yZzcLc-XxM4" frameborder="0" allowfullscreen></iframe>

  6. Commit your local changes and push to your fork of the website repo. _([Git commands](http://gitref.org/))_ If you have Jekyll, you can _build_ and _serve_ the page locally to see how the page would look once published.

  7. Once this is done, visit [Github](https://github.com/) and open your version of the club site. Create a _Pull Request_, and allow us to verify the post. It should be up on the site in no time!

We look forward to receiving some amazing posts from you soon!
