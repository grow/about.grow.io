---
$title: "All I want to do is build a web site (and launch it)"
$published: 2013-10-11
published_by: Jeremy Weinstein
published_by_link: https://plus.google.com/113048734492945304167/posts
---
<img src="/public/images/blog/shuttle.jpg" class="banner">

## Let's say you want to build a web site

The premise is that you want to build a web site: any kind of site – a personal blog, a site about a local business, a site about your new small company, a large enterprise site, a product listing, a portfolio – you name it. There are many fantastic ways to do this now: we have lightweight static site generators written in the latest languages, hosted (or installable) blog systems that have been morphed into content management systems, monolithic database-backed CMSes that require high amounts of configuration and installation time – the list goes on and on.

<q class="right">Despite the choice, no one solution jumps out [...] solutions like these require configuration and installation.</q>
Let's go back to the premise though: *All I want to do is build a web site.* For kicks (more on this later), let's add another wrench into the mix: let's say I want to launch my site on the Google Cloud Platform. Despite the choice, no one solution jumps out. Sure, you can now install WordPress on the [just-released App Engine PHP runtime](https://developers.google.com/appengine/docs/php/), or you can use Google Compute Engine and install practically whatever you want on there.  But solutions like these require configuration and installation.

Remember, *all I want to do is build a web site*, not configure a bunch of stuff. (And, I'll have to configure it multiple times, if I'm building multiple web sites.) And if I configure and install something, I have to deal with upgrades. And if I have to deal with upgrades, I have to deal with releasing those upgrades without downtime or maintenance time.

You get the point: *all I want to do is build a web site*. And launch it.

<img src="/public/images/blog/mcc.jpg" class="banner">
<cite>Image credit: <a href="http://spaceflight.nasa.gov/gallery/images/shuttle/sts-114/html/jsc2005e09159.html">NASA</a></cite>

## These days, one person alone can't build a web site

The challenges that I've mentioned thusfar are challenges that developers face. But, as many developers know, the development of a web site itself is hardly the most difficult or time-consuming part. Years ago, one person may have done it all. Modern web site production needs to be rapid, collaborative, social – because there are often many people and many stakeholders involved throughout the process.

<q class="left">The development of a web site itself is hardly the most difficult or time-consuming part.</q>These days, the person doing the development is often different from the person doing the visual design, is different from the person structuring the content, is different from the person actually writing the content, is different from the person reviewing the launch, is different from the person writing the check to pay for the whole thing. This new level of complexity-in-teamwork isn't often reflected in existing tools – and if it has, those existing tools are largely complicated or proprietary – and not very social.

So, what if there was a better, more modern way to build a web site? It should not involve configuration, nor installation. It should allow developers to use all their favorite tools. It should solve the *actual* time-consuming parts of web site production: gathering and managing content, working with multiple teams between multiple organizations, managing launches, and collaborating amongst project members. And particularly, the system should be fast, nimble, and able to run everywhere to support the open web.

The distracting parts of the web site production process should be minimized. If I'm a developer, I want to focus on development and be able to use my favorite tools. If I'm a manager, I want to be able to closely follow the pulse and activity of my project. If I'm a designer, I want to be able to comment on and fine-tune my developer's work. If I'm a content author, I want to write without worrying about HTML. If I'm a translator, I want to see all the parts of my site that require translation.

Plus, launches are way too stressful. "When will my site go live?" "Do I need to be awake for our press release at 4 AM local time to deploy the site?" "How can I verify that everything will work before it's actually live?" "Please sign off on this page and I'll launch it." These scenarios occur before almost every single web site release. There must be a better way to control launches and to verify content before it goes live, and to schedule launches for precise times.

*All I want to do is build a web site.* And I want to launch without stressing out.

<img src="/public/images/blog/riding.jpg" class="banner">
<cite>Image credit: <a href="http://ingallsimages.com/">Bill Ingalls, NASA</a></cite>

## Enter Grow: the modern, rapid, social way to build, launch, and organize web sites

Grow is my answer to "all I want to do is built a web site," and to the challenges I've listed above. Grow is all of the following: a web application, a platform, a specification for how to define the structure of a web site, and, importantly, a way to manage all of the things (and people) involved in the web site production process.

Here are ten facts about Grow:

1. It is neither "cloud" nor "local," and neither "managed" nor "decentralized".
1. It is something you can learn in under an hour.
1. It allows collaborators to start working on a web site in under 30 seconds.
1. It defines a language-agnostic structure to encapsulate, generate, and serve a web site. (My reference implementation will be written in Python.)
1. It is fast, portable, file-based, backed by Git, works with your favorite tools, and embraces popular technologies like Markdown, YAML, SASS, and Jinja2 templates.
1. It provides zero-configuration deployment to places like the Google Cloud Platform, Amazon Web Services, and GitHub Pages. But, it also works wherever else you need it to.
1. It allows you to build fully îñtérñåtîøñål web sites using built-in translation and localization features.
1. It provides a beautiful, distraction-free web interface for collaboratively modeling and writing content. You can see content as you write it and collaboratively review everything. It's perfect for anyone who is more comfortable writing in a browser than in a text editor.
1. It provides a place for you to list, organize, arrange, and control access to all of your web projects. Think Pinterest plus GitHub plus WordPress.
1. It allows your web sites to accept "launch requests". Think pull requests for non-technical folks.

That's Grow. A modern rapid, social way to build, launch, and organize web sites. It can be either "static" or "dynamic," depending on your needs. It provides one place to go not only for all your web sites, but also for your whole team. It will work splendidly for all kinds of sites: from blogs, to content-heavy informational sites, to portfolios, to creative marketing campaigns, to landing pages.

## Grow in the Google Cloud Developer Challenge (#GCDC)

<q class="right">Grow is a demonstration of how a powerful application can be written to leverage key features of the platform while still remaining portable.</q>If you haven't heard, Google is [putting on a contest](http://www.google.com/events/gcdc2013/) to see what developers can do with the Google Cloud Platform (GCP). When I first heard of this contest last week, I thought Grow would be a perfect entry for a few reasons.

Firstly, everyone entering the contest is a potential user of Grow. Grow and the Google Cloud Platform will interoperate perfectly – so all the users that *just want to build and launch a web site (on the Google Cloud Platform)* will be able to use Grow to do just that. Usage of Grow will enhance the Google Cloud Platform – and vice versa. It's no secret that GCP has a smaller community than its alternatives, and Grow can help platform growth.

Secondly, lock-in on the Google Cloud Platform is a hot topic. So much so, that Peter Magnusson, the Engineering Director for Google Cloud Platform, has written and supported [numerous posts](https://plus.google.com/110401818717224273095/posts/Uoj3pmhbCkH) and [articles](http://googlecloudplatform.blogspot.com/2013/09/appscale-brings-choice-to-google-app-engine-developers.html) on the matter.

Grow is a demonstration of how a powerful application can be written to leverage key features of the platform (such as [Cloud Endpoints](https://developers.google.com/appengine/docs/python/endpoints/) and [Cloud Storage](https://cloud.google.com/products/cloud-storage)) while still remaining portable and avoiding lock-in. Like I've mentioned, Grow is neither "cloud" nor "local" – when Grow runs locally, files are stored on your hard disk. When Grow runs on Google's cloud, files are stored in Cloud Storage.

Thirdly, the timing is perfect! What better way to get initial feedback than to participate in a contest full of people with similar goals? Grow in GCDC will feature a prototype of GrowEdit (the content-authoring space) and the ability to generate and download sites using a version of Grow running on App Engine.

<img src="/public/images/blog/launch.jpg" class="banner">
<cite>Image credit: <a href="http://www.nasa.gov/multimedia/imagegallery/image_feature_887.html">NASA</a></cite>

## Next steps

The initial work to get a prototype version of Grow up and running has already been completed. Grow was used to author this post and to generate this web site! (For demonistrational purposes, it is hosted by Google Cloud Storage.) My goal over the next two months (aside from getting married next week) will be to get the various pieces of Grow into your hands so you can try them out and provide feedback.

<q class="left">What do you want to see in a modern, fast, portable CMS?</q>There's a lot of work to do, and throughout the process it's important for me to gather feedback and suggestions. Grow is the kind of site-production and organization system that I see teams embracing now, and for years into the future.

What do you want to see in a modern, fast, portable content management system? What problems do you face building and launching web sites? What does your ideal management and collaboration space look like for web site production? Do you believe this is an already-solved problem and that I am crazy for building yet another system? Let me know what you think using Google+ comments below. 

<form class="form-inline" role="form" action="http://grow.us7.list-manage1.com/subscribe/post?u=ccff056826183226b4176c736&amp;id=75e0004099" method="post">
  <div class="form-group">
    <input type="email" class="form-control" placeholder="Email address" name="EMAIL" size="40">
  </div>
  <button type="submit" class="btn btn-default">Sign up for updates</button>
</form>
 
Sign up for updates on Grow (and to get on the beta release list) using the form above. If you're interested in using Grow for your small business or startup and are in San Francisco, <a href="mailto:jeremydw@grow.io">shoot me an email</a>. Most importantly, stay tuned for more information on Grow!
