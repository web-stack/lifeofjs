[Life of JS](http://www.lifeofjs.com)
========

### What is Life of JS ###

"Life of JS" is the source for all types of awesome resources available for JavaScript. 
This includes books, presentations, videos, feeds, sites, libraries, frameworks and tools.
Very basic but identifying information about each resources is provided.
The collection does not contain all the resources but only useful/awesome/innovative/interesting of them.

The resources are categorized into 'json' files based on type. So there are 8 json files in total.

Template of each json collection:

    {
        source: <repository path>,
        name: <name of the file>,
        type: <type of resource belonging to this collection>,
        collection: [{...}, {...}, ...]	
    }
	
 
  1. Why is there `source` and `name` attribute?  
  Whoever has this file will be able to track down the origin to check for updates and other info.  
  
  2. Why is there `type` attribute?  
  So that machines can understand what type of collection is this.  


In short, 
"Life of JS" is - A collection of not all but awesome resources about JavaScript in a programmatically manageable JSON format


Implementation: [http://lifeofjs.com](http://www.lifeofjs.com)

### Why the repository ###

JavaScript language is evolving at large in recent time.
There are countless number of libraries for specific aspects in web programming to handle very specific needs.
People write great articles about existing and also upcoming features in JavaScript. 
And also write books give detailed and very acute knowledge.
There are tools to give the lightening speed to development

This repository is started with the intention to link all these awesome things about JavaScript at one place. 
So that next time anybody want to find a book/article or want to get tool for development or build on top of framework/library, 
this repository can be the first point of reference.

### Contribute ###

Contribution is very much required in this kind of repository or otherwise this would become my personal set of choices.
This is a live document and to make this awesome in true fashion, efforts to improving the collection are always welcome.

`Quick way`: 
You know any good resource about JavaScript and want to be included in collection here?  ==> Raise an issue with the details 

`Long way`: 
Want to combine a large collection with the one here? ==> Raise a pull request  

  

##API##

Every resource can have properties as listed below.

#### Books: `js-books.json` ####

* name: full title of the book
* author: author(s) of the book
* isbn: 13 digit ISBN number of the book
* url: official site of the book OR page where information about the book can be obtained
* tags: tags to categorize the Book.


#### Presentations: `js-presentations.json` ####

* name: full title of the presentation.
* author: author(s) of the presentation
* url: url of the presentation
* tags: tags to categorize the presentation.


#### Videos: `js-videos.json` ####

* name: title of the video
* speaker: speaker(s) of the video (commas separated list)
* url: url of the video
* tags: tags to categorize the video.


#### Sites: `js-sites.json` ####

A site with a good knowledge-base or articles around JavaScript and related content would fall under this category.

* name: title of the web site
* url: url of the web site
* tags: tags to categorize the site.


#### Feeds: `js-feeds.json` ####

Feeds are the blogs, twitter profiles or similar social sources which people can follow or subscribe to.

* name: title of the web site
* url: url of the blog or social feed.
* feed: link to RSS or ATOM feed
* twitterId: screen name of the twitter profile
* tags: tags to categorize the feed.


#### Frameworks: `js-frameworks.json` ####

A collection of frameworks that give a substantial stage to build js apps on.

* name: name of the framework
* url: official web site which gives information about the framework
* source: path to the source code of the framework
* desc: a short description of the framework
* tags: tags to categorize the framework.


#### Libraries: `js-libraries.json` ####

* name: name of the library or plug-in
* url: official web site which gives information about the library or plug-in
* source: path to the source code of the library or plug-in
* desc: a short description of library
* tags: tags to categorize the library or plug-in.


#### Tools: `js-tools.json` ####

A collection of tools/applications/browser-addons/IDEs to make the JavaScript development better.

* name: name of the tool
* url: web site which provides the tool
* source: path to the source code of the tool
* desc: short description of the tool
* tags: tags to categorize the tool.