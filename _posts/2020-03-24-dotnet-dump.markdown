---
layout: post
title:  "Welcome to Jekyll!"
date:   2020-03-24 14:32:06 -0500
categories: [blog, travel]
excerpt: "EEEEEE"
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight powershell %}
dotnet tool install -g dotnet-dump
{% endhighlight %}

{% highlight powershell %}
dotnet new console --name DumpPlayground
{% endhighlight %}



{% highlight csharp %}
using System.Threading.Tasks;

namespace DumpPlayground
{
    class Program
    {
        static async System.Threading.Tasks.Task Main(string[] args)
        {
            await Task.Delay(20000);
        }
    }
}
{% endhighlight %}

{% highlight powershell %}
dotnet-dump ps
{% endhighlight %}

{% highlight powershell %}
C:\dev\dumps> dotnet-dump ps
  11032 dotnet     C:\Program Files\dotnet\dotnet.exe
  11352 dotnet     C:\Program Files\dotnet\dotnet.exe
  7892 DumpPlayground C:\dev\DumpPlayground\bin\Debug\netcoreapp3.1\DumpPlayground.exe
{% endhighlight %}

{% highlight powershell %}
C:\dev\dumps> dotnet-dump collect -p 7776
Writing minidump with heap to C:\dev\dumps\dump_20200326_065155.dmp
Complete
{% endhighlight %}
{% highlight powershell %}
dotnet-dump analyze .\dump_20200326_065155.dmp
{% endhighlight %}


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
