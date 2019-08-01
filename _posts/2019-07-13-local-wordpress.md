---
layout: post
title: How to setup local WordPress environment
categories: [Web,Coding]
tags: [technical,web,cloud,coding]
header: You will learn to setup WordPress environment locally
excerpt_separator: <!--more-->
---

{% capture image_mgt %}local_wp{% endcapture %}

<!-- ![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image_name.png) -->

<img src="{{ site.baseurl }}/images/{{image_mgt}}/header.png" title="" style="width: 80%;"/>

Why pay for a web hosting just to setup a WordPress site when you are only learning or developing a new site and not planning to deploy it yet? In this blog, you will learn to setup a complete WordPress development environment with phpMyAdmin on your local machine for free.

<!--more-->

## How to setup local WordPress environment



**Step 1:**

Download Docker that suits your system.

[For Mac](https://docs.docker.com/docker-for-mac/install/)

[For Windows](https://docs.docker.com/docker-for-windows/install/)

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image3.png)

You will be asked to login first. If you do not have an account, please create a new account. It’s free.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image5.png)



**Step 2:**

Install Docker (the following installation uses Mac as an example, but the installation on Windows would be similar.)

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image4.png)



**Step 3:**

Run Docker

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image7.png)



**Step 4:**

Download the docker-compose.yaml file

<a href="{{ site.baseurl }}/docker-compose)">Download link</a>



**Step 5:**

Open Terminal. And change directory into the folder that contains the docker-compose.yaml file (in my case, it is in the Download folder)

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image6.png)



**Step 6:**

Run the following command:

`docker-compose up`

When the container has finished loading, you should be able to access the WordPress site at [http://localhost:8000/](http://localhost:8000/)



**Step 7:**

Setup your WordPress site as usual.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image2.png)



**Step 8:**

To end the session, press Ctrl + C at the terminal.

![_config.yml]({{ site.baseurl }}/images/{{image_mgt}}/image1.png)

You can restart the WordPress site using the same command:

`docker-compose up`

And when you are done with your site, you may remove it complete using the command:

`docker-compose down -v`