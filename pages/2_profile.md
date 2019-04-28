---
layout: page
title: About Me
comments: true
permalink: /about_me/
---


<body>
    <div style="float:left">
        <img src="/images/profile.jpg" >
    </div>
    <div style="float:right;">
        <h2>Shuai Guo</h2>
          <p>Dalian University of Technology</p>
          <p>
            <a href="mailto:{{ site.email }}">
                <span class="icon">
                <svg viewBox="0 0 1024 1024">
                <path fill="#000000" d="M927.604364 798.440727l-250.600728-302.359272 250.88-269.591273c1.768727 5.585455 3.025455 11.403636 3.025455 17.501091v536.017454c0 6.469818-1.349818 12.567273-3.304727 18.432z m-332.567273-304.779636L512 561.152l-82.850909-67.351273-42.030546-34.164363-252.369454-270.801455c5.213091-1.536 10.612364-2.653091 16.290909-2.653091h722.013091c5.678545 0 11.031273 1.117091 16.290909 2.653091l-252.276364 270.615273-41.984 34.210909zM96.395636 798.440727A56.32 56.32 0 0 1 93.090909 780.008727V243.991273c0-6.097455 1.256727-11.962182 3.025455-17.501091l251.019636 269.730909-250.740364 302.219636zM512 630.178909l123.019636-99.933091 253.672728 305.105455a56.226909 56.226909 0 0 1-15.639273 2.466909H150.993455c-5.445818 0-10.612364-1.024-15.592728-2.420364l253.765818-305.012363L512 630.225455z"/>
                </svg>
                </span> 
            </a>
            <a href="https://github.com/{{ site.github_username }}">
                <span class="icon">
                <svg viewBox="0 0 16 16">
                <path fill="#aaa" d="M7.999,0.431c-4.285,0-7.76,3.474-7.76,7.761 c0,3.428,2.223,6.337,5.307,7.363c0.388,0.071,0.53-0.168,0.53-0.374c0-0.184-0.007-0.672-0.01-1.32 c-2.159,0.469-2.614-1.04-2.614-1.04c-0.353-0.896-0.862-1.135-0.862-1.135c-0.705-0.481,0.053-0.472,0.053-0.472 c0.779,0.055,1.189,0.8,1.189,0.8c0.692,1.186,1.816,0.843,2.258,0.645c0.071-0.502,0.271-0.843,0.493-1.037 C4.86,11.425,3.049,10.76,3.049,7.786c0-0.847,0.302-1.54,0.799-2.082C3.768,5.507,3.501,4.718,3.924,3.65 c0,0,0.652-0.209,2.134,0.796C6.677,4.273,7.34,4.187,8,4.184c0.659,0.003,1.323,0.089,1.943,0.261 c1.482-1.004,2.132-0.796,2.132-0.796c0.423,1.068,0.157,1.857,0.077,2.054c0.497,0.542,0.798,1.235,0.798,2.082 c0,2.981-1.814,3.637-3.543,3.829c0.279,0.24,0.527,0.713,0.527,1.437c0,1.037-0.01,1.874-0.01,2.129 c0,0.208,0.14,0.449,0.534,0.373c3.081-1.028,5.302-3.935,5.302-7.362C15.76,3.906,12.285,0.431,7.999,0.431z"/>
                </svg>
                </span>
                <!-- <span>{{ site.github_username }}</span> -->
            </a>
            <a href="https://blog.csdn.net/qq_30565883">
                <span class="icon">
                <svg viewBox="0 0 1024 1024">
                <path fill="#CE000D" d="
                M512 0c282.784 0 512 229.216 512 512s-229.216 512-512 512S0 794.784 0 512 229.216 0 512 0z m189.952 752l11.2-108.224c-31.904 9.536-100.928 16.128-147.712 16.128-134.464 0-205.728-47.296-195.328-146.304 11.584-110.688 113.152-145.696 232.64-145.696 54.784 0 122.432 8.8 151.296 18.336L768 272.704C724.544 262.24 678.272 256 599.584 256c-203.2 0-388.704 94.88-406.4 263.488C178.336 660.96 303.584 768 535.616 768c80.672 0 138.464-6.432 166.336-16z"/>
                </svg>
                </span>
            </a>
          </p>
    </div>
</body>

* content
{:toc}

## About the site
This is a personal website of LiXizhi, created with github and jekyll. 
Create your own website is as easy as clone or fork a [template](https://github.com/LiXizhi/lixizhi.github.io) on github, and [commit](http://jekyllrb.com/docs/posts/) to `_posts` folder. 

### Admin tools
* site [configuration file](https://github.com/LiXizhi/lixizhi.github.io/blob/master/_config.yml)
* Jekyll + [lixizhi.duoshuo.com](http://lixizhi.duoshuo.com/admin/)
* Jekyll + [lixizhi.disqus.com](http://lixizhi.disqus.com/admin/)
* Jekyll theme templates: [jekyllthemes.org](http://jekyllthemes.org)
   * Theme used: [cool-concise](http://jekyllthemes.org/themes/cool-concise-high-end/)
* Jekyll official site: [jekyllrb.com](http://jekyllrb.com)
* YAML for human readable markdown: [yaml.org](http://www.yaml.org/)
* markdown reference: [kramdown](http://kramdown.gettalong.org/quickref.html)

### About comments
Add a variable called `comments` to the [YAML front matter](http://jekyllrb.com/docs/frontmatter/) and set its value to true. A sample might look like:

    ---
    layout: post
    comments: true
    # other options
    ---

### Sample markdowns
Click view source at the bottom of the page

* Embedding code
{% highlight lua %}
local function main()
	print("hello world everyone")
end
{% endhighlight %}


## About me

My primary research interest is in artificial intelligence, programming and education. See my project page for details.


### 2005 Old Website 
Here is my old personal website when I was in University. It was mostly on my projects and thoughts before 2005.

* [Xizhi's old website before 2005](/oldsite2005/index.htm). 

