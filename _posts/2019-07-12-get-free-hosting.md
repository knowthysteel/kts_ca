---
layout: post
title: How to get free web hosting
categories: [Web,Coding]
tags: [technical,web,cloud,coding]
header: You will learn to obtain free web hosting
excerpt_separator: <!--more-->
---

{% capture image_mgt %}free_hosting{% endcapture %}

<!-- ![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image_name.png) -->

<img src="{{ site.baseurl }}/images/{{image_mgt}}/header.png" title="" style="width: 80%;"/>

There are so many web hosting companies to choose from, and the cost to host a website is not cheap. But there is a trick to host any static website for free forever. Read this post to learn more.

<!--more-->

## How to get free web hosting for your static website

You will need to have your own web domain. If you do not have one yet, follow <a href="{{ site.baseurl }}/get-free-domain">this post</a> to get one for free.


You should find a web hosting. There are so many to choose from and they come in all shapes and sizes. Let’s take a look at some examples below ([Siteground](https://www.siteground.com/index.htm?afcode=802ebba08eb2a092771d0db73bce82b0 "SiteGround homepage")):

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image1.png)


It’s not too bad you may think. It’s only $3.95/mo if I choose the cheapest plan. It’s even cheaper than a hamburger. But you should always read the smaller words. The regular price is $11.95/mo. That means after the “initial period” you will have to pay the “regular” price when you renew. And it can get expensive very quickly.

I personally like [Siteground](https://www.siteground.com/index.htm?afcode=802ebba08eb2a092771d0db73bce82b0 "sign-up with SiteGround!"), they are amazing. But that ain’t cheap!! And today I am going to walk you through the process of hosting your own website without paying a single dime.

~~Of course if you really like to sign up for a reliable web hosting and save the trouble, I strongly recommend you to use the affiliate link below to sign up. That would really help me out a lot!! Thank you very much!~~



**Step 1:**

Go to [GitHub](https://github.com "GitHub homepage") and login to your account (or create a new one).
![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image3.png)



**Step 2:**

Then login and add a new repository

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image2.png)



**Step 3:**

Name it whatever you want but make sure to give it a meaningful name (it should be a public repository and do not initialize with a readme). Click “Create repository”.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image5.png)



**Step 4:**

After the repository is created, you should be able to see the page below:

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image4.png)



**Step 5:**

Open Terminal

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image7.png)

It may get a little scary from now but if you follow carefully you should be fine.



**Step 6:**

Change directory to Desktop so that it is easier to work with.

`cd Desktop`

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image6.png)



**Step 7:**

Clone the repository to your local machine.

Type > `git clone [url of your github repository]`

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image8.png)


Forgot the url of your GitHub repository? Don’t worry, you can find it on the quick setup guide. Make sure you are using HTTPS

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image4.png)



**Step 8:**

Notice that the github repository is copied to your local machine. And you can add your webpage to it.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image11.png)



**Step 9:**

Let’s build some simple web pages. I prefer to use [Atom](https://atom.io/ "Atom text-editor"). But really any text editor would work. Even notepad would work.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image9.png)



Add an index.html page to your site. Type something to your heart’s content and then save.


**Step 10:**

Now let’s send the files back to GitHub. First change directory to the folder.

`cd mydomain`

Then add the changes.

`git add .`

Then commit the changes.

`git commit -m "first commit"`

Finally push the changes.

`git push`

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image10.png)


You may be asked to input your GitHub login name and password to proceed. The password is hidden so just continue typing and believe in yourself.



**Step 11:**

You should be able to see the changes on GitHub. Go to settings.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image12.png)



**Step 12:**

Scroll down to “GitHub Pages” and select “master branch” as the source.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image13.png)



**Step 13:**

Add your domain name to the “Custom domain” and save.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image14.png)



**Step 14:**

Wait for the changes to take effect and check your domain.

It works!!

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image14.png)