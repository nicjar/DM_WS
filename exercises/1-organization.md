---
layout: default
title:  '1. File organization'
---

# <a name="begin"></a> Preparations

If you haven't done so already, make sure that you do all preparatory steps described in [Preparations]({{site.url}}/preparations.html)
<br />

# File organization
:computer:Create a folder for your project in some suitable location on your computer
<br />

:computer:Create relevant subfolders according to some best-practice outline.
<details>
<summary>:key: Click to see a suggest folder structure</summary>
{% highlight bash %}
my_project
|─ bin
|- doc
|- data
|  |- raw
|  |- clean
|     |- 2016-11-16
|- results
|- src
{% endhighlight %}
</details>  
<br />

:computer:Create a README.txt (or README.md) file in each directory that describes the purpose of the directory.
<details>
<summary>:key: Click to see an example</summary>
<br />A README.md for a **results** directory:
{% highlight markdown %}
# results
Results directory for tracking computational experiments peformed on data. Keep results from different runs in date-stamped directories.
{% endhighlight %}
</details>  
<br />
