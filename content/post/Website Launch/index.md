---
title: Launching my new website!
subtitle: ''
summary: Super excited to be launching my new website today. I learnt so much along
  the way!
authors:
- Sid
tags:
- website launch
categories:
- Article
- Blog
date: 2020-09-16T12:48:58+00:00
lastmod: 2020-09-16T12:48:58+00:00
featured: false
image:
  caption: ''
  focal_point: ''
  preview_only: false
projects: []

---
**September 22, 2020**

I originally set up my website almost a year ago using a free template I obtained from [HTML5 Up](https://html5up.net "HTML5 Up") and I tweaked it quite substantially to suit my needs. It was also my first time buying a new domain and hosting it .

When I started with building my own website in 2019, as a Junior in the [Electrical Engineering](http://engineering.buffalo.edu/ee.html) at the [University at Buffalo](http://engineering.buffalo.edu/) then, my original goals were simple:

* Have a modern online presence
* A personal (cloud hosted) mail domain to use professionally
* Other than the yearly cost to renew the domain and to use a third-party mail service, running costs should be $0.

In the beginning, it was really challenging to devise a plan or even find where to begin. While researching, I set-up micro goals defined steps that would help me establish each goal. 

The simplest answer then was to use [GitHub Pages](https://pages.github.com) and host a free personal page there. The only problem with that was that visitors would still see myname.github.io. I wanted a personal domain so I continued researching. 

I found [Netlify](https://www.netlify.com). They had a free plan for personal websites that fit exactly what I was looking for. Instead of building a deploying a static website through [Netlify](https://www.netlify.com), I decided to host my code in a private repository on [Github](https://github.com) and host my website on Netlify. 

I then decided to use [Cloudflare](https://cloudflare.com) (using their very generous free plan for individuals) to secure and serve the [Netlify](https://www.netlify.com) hosted website on my personal domain. Using [Cloudflare](https://cloudflare.com) gave me free DDos protection, using complex page rules, and an HTTPS certificate, as well as using their network of CDNs to serve my website all over the globe. 

Then, the only issue remained designing my website. I could use [Wordpress](https://wordpress.com), but it wouldn't be free. That's when I leveraged the templates on [HTML5 Up](https://html5up.net "HTML5 Up"). 

I had basic HTML from previous experiences, but I took this moment to brush them up. Using the [Astral](https://html5up.net/astral) template from [HTML5 Up](https://html5up.net "HTML5 Up"), I set myself a starting point. I tweaked the template substantially to include discussions about my work experience.

Another challenge (I enjoyed solving all the little things to deliver a complete and a perfect experience) was to set up a contact form that visitors could use to contact me. Again, the biggest hurdle was to avoid being charged since each form collector charged fees. Using [Netlify](https://www.netlify.com) helped again, since I could leverage their [Netlify Forms](https://www.netlify.com/products/forms/) product. It took me a while to figure out but I finally had a working form submission page on my website.

With everything setup, I published my website that was stored on [Github](https://github.com), deployed on [Netlify](https://www.netlify.com), served through [Cloudflare](https://cloudflare.com) and it cost me $0 other than the fees to renew my domain each year. 

The only thing that remained was setting up a cloud-hosted mail provider. I looked at a few options, including: [GSuite](https://gsuite.google.com/pricing.html) ($8/user/month or $96/year), [Microsoft 365](https://www.microsoft.com/en-ca/microsoft-365/business/compare-all-microsoft-365-business-products-b?&ef_id=EAIaIQobChMIxujN687u6wIVCZ2zCh0biAo2EAAYASAAEgLBqPD_BwE:G:s&OCID=AID2100139_SEM_EAIaIQobChMIxujN687u6wIVCZ2zCh0biAo2EAAYASAAEgLBqPD_BwE:G:s&lnkd=Google_O365SMB_Brand&gclid=EAIaIQobChMIxujN687u6wIVCZ2zCh0biAo2EAAYASAAEgLBqPD_BwE) ($7/user/month or $84/year) and a few others. I decided to use [Zoho](https://www.zoho.com) to host my mail server. Their basic plan is $1/month per user or just $12/year. 

Looking back at the Statement of Purpose that I started with (using the PM principles I learnt before): Mission Accomplished. I covered everything that I was looking for.

Over time, I set up another personal domain that I use to access my HomeLab and deliver my personal media server over the internet but this I provided my own HTTPS certificates using [NGINX](https://www.nginx.com) (and then [Caddy](https://caddyserver.com)) in my [Docker](https://www.docker.com) setup. I also set-up another static website using everything I learnt for advertising a commercial product.

By summer of 2020 (almost a year later), I knew it was time for an upgrade. While this solution was great, it was hard to upgrade and manage. I took down my original website and replaced with a Coming Soon page (this time using [Eventually](https://html5up.net/eventually) by [HTML5 Up](https://html5up.net/)).

With that up, I continued researching, this time with an expanded focus on Content Management System (CMS). I discovered [Hugo](https://gohugo.io) and I knew that that was it. Although it didn't have a direct CMS, I could write my content in [Markdown]() instead of in HTML, and that was a lot easier. It integrated with Netlify extremely well and Netlify could build my website using the _blueprint_ I provided_._

With a similar arrangement as before, I now transitioned to using [Hugo]() paired with Netlify to build my website. Similar to before, I used [Github](https://github.com) (this time as a public repository) to store my content, [Hugo](https://gohugo.io) as a framework to build the website,  [Netlify](https://www.netlify.com) to run the builds, and [Cloudflare](https://cloudflare.com) to serve it. While I was at it, I also discovered [Forestry](https://forestry.io) – it basically delivers a CMS front to [Hugo](https://gohugo.io) websites. Upgrade complete.

Going the [Hugo](https://gohugo.io) route had a steep learning curve (again), specially to getting started at the beginning and then to get all the customizations in. I am so happy because I enjoyed it and I learnt so much along the way. 

> # It's the not the Destination, It's the journey.
>
> \- **Ralph Waldo Emerson**

This quote is 100\% on point to how I feel. It wasn't just satisfying to completing my goals, but rather what I learnt throughout.

Thanks for getting this far and reading about my experience. Next stop: building an iOS app using Swift. 