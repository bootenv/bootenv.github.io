---
title: Get Started 
bg: black
color: white
fa-icon: cogs
---

## It's simple

<a href="https://app.bootenv.com" class="button"><i class="fa fa-check-square-o"/> Create an account</a> <a href="https://github.com/bootenv/bootenv-docs/wiki" class="button"><i class="fa fa-book"/> Read the docs</a>
{: style="text-align: center"}

You can get the values in your environment, for example:

{% highlight console %}
$ curl api.bootenv.com/env/YOUR_SECRET_TOKEN.env | while read line; do export "$line"; done
$ echo $MY_VAR
some value
{% endhighlight %}

Also soon checkout the integrations for Gradle, IntelliJ, Java, Node.js/io.js, Python, Ruby...

