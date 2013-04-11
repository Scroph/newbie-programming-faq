Newbie Programming FAQ
======================

Are you new to programming? Has something spurred your mind into `I want to make cool things!` mode?  
Well look no further, this should answer some of the common questions that we get in the programming sections of various sites.

## Note:
### What's this `HF` you keep mentioning?
That's not important; in short, it's a community of sorts where users are under the strange disillusion that they're _hackers_ (in the non-conventional media sense of the word) and that making another stupid clone of the same scripts will make them respected users.  
You can also pay the owner of the website lots of money to get various ranks, which in turn gets users more respect (for reasons unknown to myself), and the power to abuse the reputation point system.

### How do you know what questions are commonly asked?
Good question; it's because I frequent many of the programming sections (`Coding and Programming`, `PHP` and `Python` mostly, with stops into `.NET languages`, `Java` and `Batch, Bash & CLI`) on HF.  
This is compiled from the many questions that I come across daily.  
__Every day__ these threads are popping up in the various sections, and they're just a nuisance.

### What if someone posts these questions anyway?!
That's a good point. Often, these users don't seem to understand that the internet is widely and easily searchable, and it's almost guaranteed someone has asked their exact question before.  
What should we do when that happens? You can do a variety of things, here's a few:

* Link them to the __search__ feature of whatever forum/site you're using.
    * If the site doesn't have a search feature, send them to Google, and explain the `site:xyz.com` filter!
* Provide links to various threads or topics where this question has been asked and answered before.
    * Mention that searching will often times turn up answers, and they should consult that first.
* Send them a link to this document!
    * Nothing wrong with a bit of self promotion, right?

### They're just ignoring me!
Don't worry, newbies often take a bit of nudging to get them pointed in the right direction!  
If you just follow the steps above, and they're continuously provided with the same steps time and time again, it's bound to sink in!

### What should I do if I've got ideas or questions that you don't cover?
Open up an issue on the GitHub repository, or send in a pull request.  
I published this on a git repo specifically so that the community can join in and help make this guide complete and informative.

With that in mind, let's get straight to it!
**********
_For now, I've split this into sections for general FAQs and language specific ones._

# General FAQs

## I'm new, which language is best?
There isn't particularly a _best_ language in any sense. Some are more suited to a particular task than another.  
Think of programming as a being a carpenter, and the languages are your tools. Sure, you can hammer in a nail with a spanner, but why would you when you've got a perfectly good hammer right there?

What I'm saying is, there isn't a _best_, there's just _preferred_ languages. Some people are biased because of their love for certain languages (like my love for Python), but in general, you pick the language which works best for your current project or requirements.

Some languages which people suggest frequently for new programmers are:

* [Python](https://python.org)
    * A beautifully written all round language, which excels in scripting
    * __Interpreted__, so definitely not the fastest language out
    * Usable for for just about anything:
        * Web projects (with `Flask`, `Django` or others)
        * Servers (with `Twisted`, `gevent` or others)
        * Web crawlers (with `requests` and `urllib(2)`)
    * A __gigantic__ amount of modules available online, easily installable via [PyPI](https://pypi.python.org)
    * Has an __amazing__ community available
* [Ruby](https://ruby-lang.org)
    * Designed to be human readable, which it definitely achieves
    * Easy to read, easy to write, easy to distribute and just a nice language to work in
    * __Interpreted__,  so definitely not the fastest language out
    * Usable for just about anything, with similar libraries available as Python
    * Has an __amazing__ community available
* [PHP](https://php.org)
    * Designed by a man who self-describes as a man who ["hates programming, but loves solving problems"](http://en.wikiquote.org/wiki/Rasmus_Lerdorf)
    * Wide support, since it's got interpreters out the wazoo for most web servers
    * Has lots of gotchas and caveats, as documented in [PHP: A fractal of bad design](http://me.veekun.com/blog/2012/04/09/php-a-fractal-of-bad-design/) by [@eevee](https://github.com/eevee)
    * __Interpreted__, so it's slow as all heck
    * Probably a poor choice for a first language
    * Interfaces with HTTP quite well, since it's basically designed for web applications
    * Not really usable for anything but websites
    * The community is somewhat lacking, but StackOverflow is a good place for PHP stuff
* [VB.net](http://msdn.microsoft.com/en-us/vstudio/hh388573.aspx)
    * Designed by Microsoft, specifically targeting the Windows operating system
    * Usable on other operating systems __sometimes__ via workarounds such as compat. layers like Wine or Mono.
    * __Compiled__, so it's fairly fast
    * In my opinion, a poor choice for a first language
    * The community (in my opinion) is alright. Not as amazing as Python, not quite lackluster like PHP; somewhere in-between
* [Java](http://docs.oracle.com/javase/tutorial/java/)
    * Object oriented to boot.
    * Comes with an amazing amount of getters and setters (whether you enjoy this is personal preference)
    * __Interpreted__ by the JVM (Java Virtual Machine). It's not quite as slow as an interpreted language, but not quite as fast as a compiled language.
    * Used in many enterprise level projects, so an understanding of it can't really hurt anyone.
    * The community around Java is fairly nice, and as per PHP, StackOverflow is a great place for Java things
