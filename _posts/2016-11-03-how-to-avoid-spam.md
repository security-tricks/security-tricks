---
title: How To Avoid Spam Mail
layout: post
---

So, you are setting up a new email account for yourself, your mom, brother, sister, friend, etc... What is the best advice you can give them? *DON'T GIVE IT OUT*.

Everybody knows what its like and everybody hates it: spam. How can you avoid it?

1. Never, ever, give your email out to someone you do not absolutely trust. If the company is not reputable, then just don't cough it up. It's that simple.

2. Encode your email address on your website/s. Do not use the traditional:

{% highlight ruby %}
<a href="mailto:myemailaddress@me.com">Email Me</a>
{% endhighlight %}

Instead, use a decimal converter <a href="https://www.branah.com/ascii-converter">(here)</a> to translate your regular email address into the following:

{% highlight ruby %}
<a href="10997105108116111581091211011099710510897100100114101115115641091014699111109">Email Me</a>
{% endhighlight %}

You need to encode the html which is written for your website if you are putting your email on a website. Why is this a big deal? It's a big deal because "bots" are computer programs that run automated tasks. There are millions of "bots" that comb the interenet for - you guessed it - *email addresses*. So, don't put yours out there - that includes putting your email address on your Facebook profile.

This is a good example of how internet security is a combination of human discipline - don't give your email out to just anyone - and good software - encoding email addresses on websites.
