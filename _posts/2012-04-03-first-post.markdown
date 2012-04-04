---
title: First Post!
layout: post
---

Mostly meant for technically-minded users, this is a clean
and simple blogging template. It does have some pretty
sweet features:

* A great font selection powered by [Google Web Fonts](http://www.google.com/webfonts).
* Great syntax highlighting (powered by [Pygments](http://pygments.org/)).
* Commenting via the [Facebook Comments Box](http://developers.facebook.com/docs/reference/plugins/comments/).
* Totally, 100% hackable. Change anything you want to change.

#### Syntax Highlighting

You can wrap content in \` and `it will be treated as code`.

Code blocks should be formatted with the `highlight` Liquid tag, like this:

{% highlight text %}{% raw %}
{% highlight ruby %}
def fib(n)
  n < 2 ? n : fib(n-1) + fib(n-2)
end
{% endhighlight %}
{% endraw %}{% endhighlight %}

And you will get a nicely formatted code block:

{% highlight ruby %}
def fib(n)
  n < 2 ? n : fib(n-1) + fib(n-2)
end
{% endhighlight %}
