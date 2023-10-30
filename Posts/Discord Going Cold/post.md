Title: Discord Going Cold
Date: 2023-10-27 12:30 EDT
Tags:

# Discord Going Cold

Coming later this year, Discord will be killing hot links. Well, not killing killing. You’ll still be able to send a link to things hosted on Discord (images, files, etc). However, those links will only be good for 24 hours. 

Hot linking, in short. Is is adding a resource to a site, that is not hosted by that site. <br>
Take this for example [^1] <-- click the footnote. This picture of Walt, is not hosted on my site. Its hosted on Imgur. Whereas this picture [^2], is hosted on my site.

Here's an example of how images are embedded on my site in Markdown.

```markdown
An image hosted on my site

![](_pics/fig1.jpeg)

An image hot linked

![](https://i.imgur.com/CNjSZWH.jpg)

```

Come some time this year. Discord will be adding a restriction to image links[^3]. They'll only be good, for 24h. After 24h, that link will expire, and you'll have to grab a new one. Discord cites one main reason they're doing this. Cost.

Amateur web-devs can be cheep, and lazy. They might not want to pay for storage, or for a web host that comes with storage. So, a number of them will just spin up a private Discord server (which is free), and host all their assets in there. This uses up Discords bandwidth, something they have to pay for. Now instead of Discord just having to serve that image to server members, they also have to serve it to any one who goes to that site hot linking it. By add this 24h restriction, they effectively fix this problem. While still allowing images to be shared (temporarily) to non-discord users.

Overall, this is a small change, that will have a large impact. And I'm down for it. Having a website doesn't have to be expensive. This site only costs me $4/month. So stop being lazy amateur web-devs. You'll make a better site that way.

[Reply to this post via email](mailto:reply.13a8f@nthp.me?subject=Re: Discord Going Cold)

[^1]: ![](https://i.imgur.com/CNjSZWH.jpg)

[^2]: ![](_pics/fig1.jpeg)

[^3]: Well, all file links