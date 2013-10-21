#RapidWeaver Bootstrap Snippets
##Introduction
[Twitter Bootstrap](http://http://getbootstrap.com/) has grown quickly in recent years to become a powerful front end framework for the construction and deployment of modern, responsive websites. [ThemeFlood](http://themeflood.com) was the first addon company to pioneer the use of Bootstrap in RapidWeaver themes. 

To make things easier for people new to the idea of Bootstrap code in RapidWeaver, a selection of installable code snippets were developed. These are provided for free and allow users to drag and drop particular Bootstrap components into a page. 

Compared with Stack elements, these Bootstrap code snippets can be used in any RapidWeaver page style, within either styled text or HTML code regions of a page. Code and content within the snippets is fully accessible, and this aids the setup and customisation of the Bootstrap elements.

##System requirements
These code snippets require a RapidWeaver theme which is advertised as having support for **Bootstrap 3**. The snippets will fail to work in themes either running an older version of Bootstrap or not having support for Bootstrap at all.

Tip: with some care, it is feasible to add support for Bootstrap 3 to a RapidWeaver theme by calling Bootstrap CSS and Javascript files from the [Net DNA](https://www.netdna.com/) content delivery network:

	<!-- Latest compiled and minified CSS -->
	<link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css">

	<!-- Latest compiled and minified JavaScript -->
	<script src="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/js/bootstrap.min.js"></script>
	
Typically this code can go in your **Custom Header** box in the **RapidWeaver Page Inspector** or you could edit your theme **index.html** file to hard-code the Bootstrap calls into the *head* section of every page using the theme.

##Installation and usage
The snippets can be downloaded by navigating to the official repository on Github:
[https://github.com/willwood/RapidWeaver-Bootstrap-Snippets](https://github.com/willwood/RapidWeaver-Bootstrap-Snippets)

On that page, you should see a link or button with an option to download the complete repository. The repository consists of this *readme* file and all of the latest RapidWeaver Bootstrap code snippets.

Alternatively, the code snippets are available using the download links provided on the [ThemeFlood](http://themeflood.com) website.

Once downloaded, you will typically have a folder containing a **readme.md** file (the same one you are reading right now) and a bunch of several dozen code snippets. Double-clicking on these snippets will install them into the RapidWeaver **Library** folder, in the **Snippets** sub directory.

After installation, you will find that the snippets are all available for use in the **RapidWeaver Snippets** window. Click on one of the listed code snippets and drag it into your page (when RapidWeaver is in edit mode).

All of the Bootstrap code snippets are prefixed *bootstrap-* so they should be sorted into a single group and won't disorganise other snippets you already have installed. Of course you have complete freedom to edit any of the snippets or delete ones you are not using.

##Support
The official [Twitter Bootstrap](http://getbootstrap.com/) website has working examples of many of the snippets and long descriptions of what they do, plus lists of customisable variables which might be available to you.

RapidWeaver Bootstrap snippets tend to include a title and brief comments relating to setup and usage in the top of the snippets. These comments will include any important information.

The [ThemeFlood theme user guide](http://www.themeflood.com/support/userguide/) has a whole chapter dedicated to use of Bootstrap in ThemeFlood RapidWeaver themes. If you need help with using a ThemeFlood theme, then you can also get in contact via [the website](http://themeflood.com/).

##Contribute
The [RapidWeaver Bootstrap Snippets](https://github.com/willwood/RapidWeaver-Bootstrap-Snippets) project is very much a community-led project and actively encourages input from any interested individuals or companies. 

If you have identified bugs or have requests for new or modified RapidWeaver Bootstrap Snippets, please use the **Issues** button on the repository page to make a comment:
[https://github.com/willwood/RapidWeaver-Bootstrap-Snippets](https://github.com/willwood/RapidWeaver-Bootstrap-Snippets)

If you have created new RapidWeaver Bootstrap snippets that you feel would appeal to other users and you want them distributed via this repository, please forward them to me via email or commit them to the repository via Git.

##Getting updates
The easiest option is to clone this repository in software like SourceTree or Gitbox via the following link:

	https://github.com/willwood/RapidWeaver-Bootstrap-Snippets.git
	
When new commits are made, you will get notification of these and details about what has changed. 

The other option is to just periodically download the snippets and overwrite the ones you already have installed with the latest ones in the package.

##Extra snippets
Alongside Bootstrap code snippets, the repository also includes code snippets for [ExtraContent](https://github.com/seyDoggy/ExtraContent), FreeStyle banner containers and [Font Awesome Icons](http://fortawesome.github.io/Font-Awesome/). These three code snippets are commonly used in conjunction with Bootstrap, so are included for added convenience.

##License
The RapidWeaver Bootstrap Snippets are dual licensed under [MIT](http://opensource.org/licenses/MIT) and [GPL-v3](http://www.gnu.org/copyleft/gpl.html). This grants you almost complete freedom to download, modify and redistribute any of the snippets, plus the ability to bundle them as part of other projects or to resell them.

##Footnotes
RapidWeaver is a trademark of Realmac Software LTD, Brighton, UK.

The RapidWeaver Bootstrap Snippets repository maintained by [Will Woodgate](http://about.me/willwoodgate).