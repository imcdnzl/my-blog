---
title: "First post"
date: 2018-10-08
draft: false
---

Over the years I've had a number of blogs and published contents in different places - the most recent being at <http://blog.next-genit.co.uk/>. *So why create a new blog now?* Well hopefully this post will explain a bit more!

The main reason was because I started a new role (CTO in residence at [Microsoft for Startups](https://startups.microsoft.com/)), along with wanting to talk more about my autism, and I thought I'd better do a blog a bit more technical than just using something like Blogger or pre-packaged Wordpress. They are great, and would have been easier, but it's good for me to learn and play. Even though I've led large AWS and Azure projects, teams of software developers and done a few bits and pieces myself I'd lost a bit of the edge since my last lot of serious coding which was on the Linux kernel when I did my [PhD](https://researchcommons.waikato.ac.nz/handle/10289/8320).

So I went off and had a look at blogging platforms and asked people on Twitter what they thought also. I have a natural bias to trying to do things higher in the stack where possible as that's inherently less work to keep running, and far easier to keep secure. So the first decision was made - go for something with static HTML, and not a server. My choice was then between [GitHub pages](https://pages.github.com/) and [static website hosting on Azure storage](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website). I could have done with either, but went with GitHub due to the upcoming acquisition (still subject to final close).

So then how to write the content? I'm absolutely not going to write HTML / Javascript by hand - nobody should be doing that these days. I went and looked at the two leading opensource contenders in [Hugo](https://gohugo.io/) and [Jekyll](https://jekyllrb.com/). To be honest I could have gone with either, and Jekyll would have been the easier choice as it was already integrated with GitHub pages. In the end I went with Hugo - there's nothing wrong at all with Jekyll / Ruby, but like most tech people I'm attracted to new shiny things and Hugo is newer and written in Go. Don't worry - you don't need to install Go as I found out after installing it and getting it all working...

So then the fun began - I thought that I could get it all going in one night after work and I was wrong! Not because it's hard, but because I was too rusty and also I have a hard time staying focussed on tasks, along with a busy work schedule. I think the focus thing is quite related to my autism (I've seen a recent debate questiong whether all high funcioning autism people have ADHD). The other thing that slowed me down is that I want to try and understand **EVERYTHING** that I do. This might be because I started programming using machine code (not assembler - go check the difference) and have also done basic electronics and chip design along with coding drivers / firwmare / operating systems.

I did then try and write my own theme to do blog publishing, which I'm sure I could do if I had enough time but then realised I'd be better off using one already written. [This](https://github.com/nirocfz/arabica) is the one that I went with in the end.

One little side note about setting things up - when I was testing Hugo on Windows Subsytem for Linux (WSL) I was trying to work out what IP address I should put into the browser to view, like I need to do with virtual machines. It made sense afterward to realise of course that it is localhost as it's not a virtual machine. This wasn't well documented but now that Microsoft documents are open source I just made a pull request against [this page](https://docs.microsoft.com/en-us/windows/wsl/faq). I still love that I can do that!!

One of the joys on blogging on git and opensource is that you can follow along too - you can even see in advance what I'm writing if you really want at my [repo](https://github.com/imcdnzl/my-blog). I'm also dual publishing on Medium so you can check it out [here](https://medium.com/@imcdnzl), or if you're reading on Medium I'm posting firstly [over here](http://blog.imcdonald.com/). I do intend, at some time, on setting up your own blog using Hugo / GitHub as I didn't find the instructions around totally simple.

So you've got almost to the end - thanks for reading this far. I mentioned I'd also be talking about autism and I will but I'll save that for future posts. In short I have high functioning autism, which is also known as Aspergers. See you next time!!
