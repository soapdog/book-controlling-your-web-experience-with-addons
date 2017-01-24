# Introduction

## Loosing control
The Web is as mainstream as possible these days yet, most of its users have a very passive approach to their online experience as they approach web technology as if it was a black box best not tampered with. The average web user believes that there are only two possible actions on the Web[^1]:

* To browse someones site.
* To create your own site.

And since most people spend more time browsing other peoples site then they do creating their own, the overall experience of web users is a quite uninvolved one much like cable TV or video games. By uninvolved I don't mean that it is not interactive, I mean that you don't have a say or a way to influence the interactivity of that experience at first glance. If people restrict themselves to whatever experience they are given by the content producer, they will never become content producers themselves.

The last decade of the Web has been marked by one upward trend in siloed experiences. Our online experience becomes more centralized and controlled each day. [Many people actually believe that facebook is all there is on the web](http://qz.com/333313/milliions-of-facebook-users-have-no-idea-theyre-using-the-internet/).

> A small-scale survey in five countries showed that many Facebook users either don't know the app is on the Internet, or have no idea there is an Internet beyond Facebook. Without Web literacy, we cannot expect people to understand what the Internet can do for them, or why they should care. &mdash; from [Mozilla Internet Health Report v0.1 - Web Literacy](https://internethealthreport.org/v01/web-literacy/).

Not long ago, the Web was thriving on a decentralized blogosphere where each author was in control of their own content. Portals such as [Geocities](https://en.wikipedia.org/wiki/Yahoo!_GeoCities) made having a Web Page and experimenting with HTML/CSS very easy. Today, online citizens live inside social networks that promote siloed experiences and are hostile to the concept of a [decentralized Web](https://internethealthreport.org/v01/decentralization/).

In summary, we lost control of our online experiences to entities that potentially do not share the same vision and values [we want for the Web](https://webwewant.mozilla.org/). I believe it is time for a change.  

[^1]: Not really, I just made this up to suit the text, it is called storytelling and ad companies and newspapers are doing it too. Felt cheated? I do too, every time I watch the news...  


## Rebellion and Agency
There is a third possible Web action besides browsing and creating Web sites, one that is much less explored but is immensely powerful: **Interfering with other peoples site**. Lets be pragmatic for a second, unless you are a very influential person, there is almost zero chance that a large company such as Facebook or Twitter will actually change their products because *you'd like it to work a bit different*.

A simple example is that most web apps are developed from the point of view of right handed people, if you're left handed such as I am then lots of buttons are suddenly out of reach. Asking for a *Left Handed* mode might be a sound suggestion but it is also be completely ignored because it is not seen as a priority. What can you do when you'd like to take back the control of your Web experience but whoever developed the Web site you're using is not prone to listening to you? **You write an Addon to change that site only for you!**

Addons are small, self-contained packages, that alter your browser experience. They can add functionality to your favorite browser and even change how a given site works for you. They are very popular with Firefox and Chrome and now with the new WebExtension API, both browsers can use the same Addons with minimal tweaking. Some popular examples are: ad blockers, download accelerators and password managers.

Even though most Web Developers use a bunch of Addons in their daily lives, very few actually wrote their own. It is as if we're all behaving like chefs that cook in other restaurants but never at home. Throughout this book we are going to put those web development skills to a rebellious use. We're going to write Addons to change the browser and some popular sites, we're going to take back control over our personal online experience.

> **AGENCY:** the capacity, condition, or state of acting or of exerting power. &mdash; [from Merriam Webster dictionary](https://www.merriam-webster.com/dictionary/agency).

The browser is called a *user agent*, we're going to put it to work on behalf of us eschewing the passive Web experience that is forced onto us. Together we're going unlock more agency on the Web by building and sharing our own Addons. 

## Look at me! I am the captain now!
Instead of simply exposing the [WebExtension API and workflow](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) as if this was a reference book, we're going to take a more practical approach and build four Addons to alter our online experience. These Addons will tackle common wants from users and demonstrate that we don't need to accept whatever online experience is forced onto us quietly.

So this book is a case study of the development of four tiny Addons and how they improve my personal experience. I hope they also inspire you to develop your own.

* **9wantz:** This Addons alters a popular meme sharing site to change the layout by removing some clickbait links while also changing the sharing features to be something I think is better.
* **NoBullshit:** This one removes feed items from Facebook based on terms you define. Sometimes, you just want to hide all that hate speech.

**TODO: Define the next two WebExtensions**