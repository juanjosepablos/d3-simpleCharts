=== Plugin Name ===
Contributors: Jouni Santara, TERE-tech ltd
Donate link: http://www.tere-tech.eu/
Tags: d3, visualization, chart, graph, CSS, CSS3, SVG, vector graphics, DOM
Requires at least: 3.3.2
Tested up to: 3.5.1
Stable tag: 1.2.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

d3-simpleCharts offers you direct access to a few d3 basic charts and let you add them into your WordPress posts fast.

== Description ==

d3-simpleCharts is here: you can start to show the next generation W3C's sharp charts and graphs (eq SVG formats via d3.js library) from your any WordPress blogs easily.

This WP plug-in contains just 4 simple example graph types that you can call and draw by one shortcode: 

  'simpleChart'

The available chart types now are here: 'Columns', 'Bars', 'Pie', 'Area'

Pretty *simple* and obvious there, yes!!?

You can define *data input values* on the standard and uniform way from *wordpress shortcode's arguments* directly or from *external data files*. 

Shortcode's input is preferred way always as the primary source of data values & their labels (if both are given).

Three external file type formats are currently supported for input:

1. CSV
1. JSON
1. TSV (eq tab separated data values)

Note: XML should be easy to add soon, a bare skeleton JS code is there existing already but parsing of document is missing at this very 1st version of plugin package.

simpleCharts lets you start with very simple basic calls when you start to use it as a novice and then let you progress gradually to the quite advanced levels of SVG's *real professional properties* when you need them and are willing to budget enough time for deeper learning curve. 

Software is also automatically choosing default settings for more complex features that you vote not to use them yet.

Here is the most *simple example of shortcode's call* that works very well:

[simpleChart mtitle='Pets', labels='(Cats, Dogs, Birds)', values='(2,1,5)']

Pretty *simple* & obvious (to create default 'Columns' chart) is it, huh?

* [More basic things on Wiki](https://github.com/mrBigJS/d3-simpleCharts/wiki/Getting-started)

Now - to get a whole picture of all rich features available here - you can expand your knowledge and finally master something like this for each new post/page on WP:

[simpleChart chart='Pie' mtitle='All Animals' values='(1,2,4,8,16)' labels='(Cats,Dogs,Birds,Frogs,Bears)' xtitle="Animal race" ytitle="Pcs on wild farm" datafile="animals.json" css='{ ".bar" : {"fill" : "navy", "stroke" : "blue"} , ".axis path, .axis line" : {"stroke" : "orange", "fill" : "gray"} , " " : { "font" : "12px sans-serif"}, ".chart":{"stroke":"gray"}, ".axis .xtpos":{"x":"200"} }'  width="800" height="600" format="+0.02%" title="These animals are living free around." minrange="1.0" url="http://en.wikipedia.org/wiki/Wild_animals"]

* Very advanced & powerfull shortcode's call* above to draw just the way you want your professional embedded super fast vector graphics.
* [Advanced in detail on Wiki](https://github.com/mrBigJS/d3-simpleCharts/wiki/Advanced-examples)

You can customize almost every main aspect of new created chart by feeding in legal CSS and SVG attributes to the graphs. These attributes are listed & documented openly on *W3C's* sites, like: 

*www.w3schools.com*
.

**Key Features**

1. Chart type switcher buttons to compare data different ways.
1. New chart's vertical position control based on CSS.
1. New chart's total look & feel control based on CSS.
1. Smooth gradient coloring of each bar of chart available by request.
1. Many embedded charts on the same page, no problem.
1. Supporting W3C's globally recognized web standards: DOM, SVG, and CSS.
.

**Data input and output**

* Data importing from shortcode / external files (CSV/TSV/JSON) on server.
* Exporting: Excel and JSON formats (eq big data).
* Optional smart parsing of 2x2 matrix data points files row by row.
.

**Software Upgrades & Further Development**

* Distributed collaborative development via GitHub too (= welcome to fork and improve core's code for "d3-simpleCharts", note BIG 'C' in name).
* Supporting D3 (eq data driven documents) developers society for powerfull JavaScript graphics (d3.js on GitHub).

All software is written also in a style that should be easy to expand & understand for any normal web developer of WordPress, DOM, JS & PHP languages. 

Also, there is left on purpose a plenty of 'console.info(foo)' debugging calls for those essential variables of JS that you can activate in order to see what is really going on when SVG drawing takes its place (= consoles of FireBug & Chrome). 

d3 lib is abit tricky to grasp at first - take your time & fill your coffee machine :-)

**Full open source + reference guide**

* [d3-simpleCharts on GitHub](https://github.com/mrBigJS/d3-simpleCharts "Join in and fork this code even better to anyone.")


**HAPPY Charting on WordPress !**


== Installation ==

Two WP standard ways to install the package.

1. Go to wordpress 'Dashboard' front page.
1. Select PlugIns / Add New for searching new plugin from internet.
1. Write 'd3' to the search box + Search PlugIns.
1. Select 'Install Now' under the result of 'd3-simpleCharts'.
1. Activate the PlugIn on WordPress after its download.
1. Start to use & enjoy shortnotes '[simpleChart]' inside your posts & pages.

Or you may want to do it 'old traditional way'.

1. Upload `d3-simpleCharts.php` & `d3-simpleCharts.js` to the `/wp-content/plugins/` directory from wordpress.com site.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Start to use shortnotes '[simpleChart]' inside your posts & pages.

This software is provided as it is and we can not guarantee very fast support & help for it, unfortunately.

Also, we do not have time to test this software against different WP versions but we gladly hear your feedback and update that version support numbers based on your (hopefully positive) comments.

We warmly welcome some professional WP developer to build around this core all those fancy 'Bells & Whistles' that could nicely integrate this shortnote available to the graphical user interface of publishing new posts and pages for everyone, naturally.

Let me know if you are producting suggested improvement and take this work to the next level !


== Frequently Asked Questions ==

= Is it possible to have multiple charts on the same WP post or page? =

Good point!

YES indeed, the software is written so that it hides all the (= ugly) complexity of accounting of many separate charts + styles on the same page of WP.

So, you may have many pretty charts on the same page with their own original CSS styles attached to each one, independently. Everything is perfectly under your control transparently.

= Is it possible to embed a single chart to some exact position of post / page? =

Not yet: generating the container for a graph dynamically is not so easy task for PHP & WordPress environment (without binding this to other external frameworks, like JQuery, etc).

Sorry - give us a good suggestion to solve it and we do this at the next version.

Now, since all shortcode processing happens at first of WP post (/page) the graphs are also printing out at the top of post, too.

This could change in future's versions - stay tuned in !

= How can I develope my fancy XYZ or ABC around this code and get it included inside this package, too? =

We encourage open collaborative development for programmers (by GitHub) over here:

[d3-simpleCharts on GitHub](https://github.com/mrBigJS/d3-simpleCharts "Join in and fork this code even better to anyone.")

= So, there is no user manual at all for this WordPress plugin, huh? =

User online manual & reference is building up gradually on GitHub's Wiki over here:

[d3-simpleCharts - user's manual & reference of all functions](https://github.com/mrBigJS/d3-simpleCharts/wiki/Introduction)

Also, we recommend on windows to use [TortoisesSVN](http://tortoisesvn.tigris.org/) client together with GitHub. It really takes the pain away from learning Git. Here is [a nice tutorial](http://techlunatic.com/2011/09/how-to-submit-your-first-plugin-to-wordpress-ultimate-guide/) about its use.


*Very Good Further Links*

* [D3, All Galleries](https://github.com/mbostock/d3/wiki/Gallery
            "Fancy, impressive & professional charts that should inspire you to jump in.")
* [Chart's SVG standard](http://www.w3schools.com/svg/svg_reference.asp
            "Usefull for personalizing your own visual outlook of chart contents, use together with Firebug's/Chrome's 'Inspect element' on browser's window command.")
* [Chart's CSS styles & layout control](http://www.w3schools.com/tags/tag_table.asp
            "Usefull for contolling chart's background look and its overall position.")
* [D3, Tutorial](https://github.com/mbostock/d3/wiki/Tutorials
            "Now, let's get your fingers dirty and start programming more charts!")
* [D3, API's reference](https://github.com/mbostock/d3/wiki/API-Reference
            "All you finally need when get up to PRO level with D3 & its cool programming universe.")

			
== Screenshots ==

1. Shows how 'Columns' looks out together with home's pets example.
2. Shows how 'Area' looks out together with home's pets example.
3. More complex 'Pie' chart: its segments are colored smoothly from 'navy' to 'gold' + more custom titles present.

== Changelog ==

= 1.2.6 =
Version 1.2.6 - Adding basic icon buttons for the chart and a folder for their pics (eq style of open office).

= 1.2.5 =
Version 1.2.5 - Chart on new window link, adding support of css style file for svg, fixing bug of chart's width at start (on Chrome).

= 1.2.4 =
Version 1.2.4 - Cleaning the code.

= 1.2.3 =
Version 1.2.3 - Centering chart's title and introducing positioning of logo option.

= 1.2.1 =
Version 1.2.1 - Adding chart's branding logo and a flag to add jQuery lib.

= 1.2.0 =
Version 1.2.0 - New options to remove chart's buttons to appear.

= 1.1.5 =
Version 1.1.5 - Finally tagging right subversion public on wordpress svn system.

= 1.1.3 =
Version 1.1.3 - Adding some pointers to GitHub's full documentation.

= 1.1.1 =
Version 1.1.1 - A few screenshots added.

= 1.1.0 =
Version 1.1.0 - Charts fixed and optional menu to other data sets added.

= 1.0.0 =
Version 1.0.0 - This is very first release of the d3-simpleCharts plugin.

== Upgrade Notice ==


            
