# Maths And Physics Club

How to add posts
1. Default command for creating a new post.

{% highlight bash %}
$ octopress new post "Post Title"
{% endhighlight %}

Default works great if you want all your posts in one directory, but if you're like me and want to group them into subfolders like `/posts`, `/portfolio`, etc. Then this is the command for you. By specifying the DIR it will create a new post in that folder and populate the `categories:` YAML with the same value.

{% highlight bash %}
$ octopress new post "New Article Title" --dir articles
{% endhighlight %}

2. How to add one as an author 

Go to _data -> authors.yml. Add your name as shown there and your name code. In your post in the front matter add

author : name code 


