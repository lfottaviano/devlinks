# Software Development links 
Mainly .NET, but scope can change.

## Index
- [js](#js)
  - [libs](#libs)
    - [Knockout](#knockout)
    - [AngularJS](#angularjs)
  - [Misc](#misc)
- [LINQ](#linq)
- [NoSQL](#nosql)
  - [DocumentDB](#documentdb)
  - [MongoDB](#mongodb)
- [WCF](#wcf)
- [WebApi](#webapi)
- [Web servers](#web-servers)
  - [IIS](#iis)
- [Performance](#performance)
  - [Web](#web)
  - [SQL](#sql)
- [Diagnostics and Debugging](#diagnostics-and-debugging)
- [Security](#security)
  - [DDoS](#ddos)
  - [SQL Injection](#sql-injection)
  - [XSS](#xss)
  - [Bug bounty](#bug-bounty)
  - [SSL](#ssl)
  - [Blogs](#blogs)
- [Learning and resources](#learning-and-resources)
  - [Magazines](#magazines)
  - [Books](#books)
  - [Agile Books](#agile-books)

# Content

## js
* [MDN Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Mozilla Developer Network Javascript
* [MDN Javascript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference) - Javascript reference itself
* [MDN Javascript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) - guide

* [A re-introduction to Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) - "Because JavaScript is notorious for being the world's most misunderstood programming language."
* [Eloquent Javascript](http://eloquentjavascript.net/) - free ebook
* [Javascript enlightenment](http://www.javascriptenlightenment.com/) - free ebook
* [Javascript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/) - design patterns
* [Javascript tutorial](http://javascript.info/) - tutorial

### libs

#### Knockout
* [Knockout documentation](http://knockoutjs.com/documentation/introduction.html) - Simplify dynamic JavaScript UIs with the Model-View-View Model (MVVM)

#### AngularJS

* [AngularJS API ref](https://docs.angularjs.org/api) - Api Reference. 
* [AngularJS Cheatsheet](http://www.cheatography.com/proloser/cheat-sheets/angularjs/) - with links to api reference.
* [AngularJS Cheatsheet](https://dncmagazine.blob.core.windows.net/downloads/AngularCheatSheet-DNCMagazine.pdf) - by dncmagazine
* [AngularJS Expressions](http://teropa.info/images/angular_expressions_cheatsheet.pdf) - Cheatsheet for Expressions
* [Angular Style Guide](https://github.com/johnpapa/angular-styleguide) - style guide
* [Angular Style Guide](https://github.com/mgechev/angularjs-style-guide) - another style guide
* [Angular pinboard](https://pinboard.in/u:bitchwhocodes/t:angular/) - by thebitchwhocodes

### Misc
* [DNS js.org](http://dns.js.org/) - domains for github pages
* [Stats js.org](http://stats.js.org/) - 10k most popular JavaScript projects on GitHub

## LINQ
* [linqpad](https://www.linqpad.net/) - Test any C#/F#/VB snippet or program, query databases in LINQ 

## NoSQL
### DocumentDB
* [DocumentDB](https://azure.microsoft.com/en-us/documentation/learning-paths/documentdb/) - ms learning path
* [DocumentDB SQL cheatsheet](https://azure.microsoft.com/en-us/documentation/articles/documentdb-sql-query-cheat-sheet/) - sql query cheatsheet

### MongoDB
* [MongoDB cheatsheet](https://blog.codecentric.de/files/2012/12/MongoDB-CheatSheet-v1_0.pdf)
* [Robomongo](https://robomongo.org/) - Mongo querying & management tool
* [MongoDB C# cheatsheet](http://www.layerworks.com/blog/2014/11/11/mongodb-shell-csharp-driver-comparison-cheat-cheet)
* [Linqpad + MongoDB C# driver](http://www.rkconsulting.com/blog/mongodb-with-linqpad)

## WCF
* [WCF .NET 3.5 MS](https://msdn.microsoft.com/en-us/library/ms735119.aspx) -

## WebApi
* [Learn About ASP.NET Web API](http://www.asp.net/web-api) - official site

## Web servers
### IIS
* [HTTP status code](https://support.microsoft.com/en-us/kb/943891) -  in IIS 7.0, IIS 7.5, and IIS 8.0
* [IIS.net Learn](http://www.iis.net/learn) - Learn IIS.net
* [IIS Config Reference](http://www.iis.net/configreference) - Get IIS 7 & IIS 7.5  Reference Guides
* [Introduction to IIS Architecture](http://www.iis.net/learn/get-started/introduction-to-iis/introduction-to-iis-architecture) - IIS arch introduction
* [IIS 8.5 Idle worker process page-out](http://www.iis.net/learn/get-started/whats-new-in-iis-85/idle-worker-process-page-out-in-iis85) - Process worker: Idle time-out action , terminate or suspend. Suspend makes it faster. 
* [Getting Started with AppCmd.exe](http://www.iis.net/learn/get-started/getting-started-with-iis/getting-started-with-appcmdexe) - Single command line tool for managing IIS 7 and above

## Performance
### Web
* [Yahoo Best practices](https://developer.yahoo.com/performance/rules.html) - Best Practices for Speeding Up Your Web Site
* [Tips for fast loading html pages](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Tips_for_authoring_fast-loading_HTML_pages) - mozilla developer network

### SQL
* [SQL performance](http://sqlperformance.com/) - Improving SQL Server performance

## Diagnostics and Debugging
* [Glimpse](http://getglimpse.com/) -  diagnostics platform, very useful lets you see sql queries on EF, Identity Claims, all from the brownser.
* [Fiddler](http://www.telerik.com/fiddler) - free web debugging proxy, let us examine/compose http requests & responses.
* [Postman](http://www.getpostman.com/) - chrome extension for testing http requests (WebAPI / REST)
* [StopWatch class](https://msdn.microsoft.com/en-us/library/system.diagnostics.stopwatch(v=vs.110).aspx) - msdn documentation, provides a set of methods and properties that you can use to accurately measure elapsed time.
* [.NET System.Diagnostics](https://msdn.microsoft.com/en-us/library/system.diagnostics(v=vs.110).aspx) - Namespace

## Security
* [awesome-pentest repo](https://github.com/enaqx/awesome-pentest) - Big collection of pen test resources 
* [.NET Security Cheatsheet](https://www.owasp.org/index.php/.NET_Security_Cheat_Sheet) - By OWASP

### DDoS
* [Javascript based DDoS](https://blog.cloudflare.com/an-introduction-to-javascript-based-ddos/) - Cloudfare introduction.

### SQL Injection
* [sqlmap](http://sqlmap.org/) - sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers.

### XSS
* [xssposed](https://www.xssposed.org/) - List of sites vulnerable to XSS (Open bug bounty program)
* [XSS Filter evasion cheatsheet](https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet) - 
* [xssed](http://xssed.com/) - News and lists of vulnerabilities 
* [XSS Prevension Cheatsheet](https://www.owasp.org/index.php/XSS_(Cross_Site_Scripting)_Prevention_Cheat_Sheet) - OWASP
* [DOM based XSS Prevention Cheat Sheet](https://www.owasp.org/index.php/DOM_based_XSS_Prevention_Cheat_Sheet) - OWASP

### Bug bounty
* [hackerone](https://hackerone.com/python) - Bug bunty platform

### SSL
* [Let's encrypt](https://letsencrypt.org/) - is a free, automated, and open certificate authority (CA), run for the public’s benefit. 

### Blogs
* [sucuri](https://blog.sucuri.net/) 

## Learning and resources
* [Microsoft Virtual Academy](http://www.microsoftvirtualacademy.com/) - Learn different technologies
* [CodeAcademy](https://www.codecademy.com/) - Learn to code
* [Learn X in Y minutes](http://learnxinyminutes.com) - Learn X in Y minutes 
* [Technical Development Guide](https://www.google.com/about/careers/students/guide-to-technical-development.html) - google careers, provides tips and resources to help you develop your technical skills 
* [bitboot.camp](http://bitboot.camp/resources.html) - General resources, CS, Java, git, Linux, Sql, Python and more.
* [Awesome Courses](https://github.com/prakhar1989/awesome-courses/blob/master/README.md) - List of CS courses
* [hackr.io](http://hackr.io/) - Share and discover the best programming tutorials and courses online.
* [Software Architecture Resources](https://msdn.microsoft.com/architects-overview-msdn) - From Microsoft
* [Software Architecture Resources](https://msdn.microsoft.com/en-us/library/ms978007.aspx) - From Microsoft
* [Bizpark](https://www.microsoft.com/bizspark) - Support for your startup
* [Dreamspark](https://www.dreamspark.com/) - for students
* [Microsoft API and reference catalog](https://msdn.microsoft.com/en-us/library/default.aspx) - Library reference
* [Technet](https://technet.microsoft.com/en-us/default.aspx) -
* [Channel9 MSDN](https://channel9.msdn.com/) - 
* [Continuous Integration](http://martinfowler.com/articles/continuousIntegration.html) - Martin Fowler
* [DI - Ninject](http://www.ninject.org/) - Open source dependency injector for .NET 
* [blackwasp tutorials](http://www.blackwasp.co.uk/Tutorials.aspx) -
* [C# corner](http://www.c-sharpcorner.com/) -
* [C# station](http://www.csharp-station.com/) -
* [Techotopia](http://www.techotopia.com/) -
* [JustDecompile](http://www.telerik.com/products/decompiler.aspx) - Telerik decompilation engine
* [CS & Engineering](https://github.com/open-source-society/computer-science-and-engineering) - Open Source Society University

### Magazines
* [dotnetcurry](http://www.dotnetcurry.com/ShowCategories.aspx) - .NET tutorials & magazine
* [VisualStudio Magazine](https://visualstudiomagazine.com/Home.aspx) - .NET, C#, ASP.NET, etc
* [MSDN Magazine](https://msdn.microsoft.com/en-us/magazine/default.aspx) 


### Books
* [Free ebooks](http://blogs.msdn.com/b/mssmallbiz/archive/2015/07/07/i-m-giving-away-millions-of-free-microsoft-ebooks-again-including-windows-10-windows-8-1-windows-8-windows-7-office-2013-office-365-sharepoint-2013-dynamics-crm-powershell-exchange-server-lync-2013-system-center-azure-clo.aspx)

### Agile Books
* Scrum: A Pocket Guide by Gunther Verheyen
* Software in 30 days by Ken Schwaber
* Scrum Insights for Practitioners: The Scrum Guide Companion by Hiren Doshi
* Extreme Ownership: How U.S. Navy SEALs Lead and Win by Jocko Willink
* Adapt by Tim Harford
* Team of Teams by Stanley McChrystal
* Servant Leadership by Robert K. Greenleaf
* Scrum Mastery by Geoff Watts
* Coaching Agile Teams by Lyssa Adkins
* The Surprising Power of Liberating Structures by Henri Lipmanowizc and Keith McCandless
* The Professional Product Owner by Don McGreal and Ralph Jocham
* The Product Samurai by Chris Lukassen
* Product Mastery by Geoff Watts
* Lean Change Management by Jason Little
* Reinventing Organizations by Frederic Laloux
* The Nexus Framework for Scaling Scrum by Kurt Bittner, Patricia Kong and Dave West
* Creating Great Teams by Sandy Mamoli and David Mole
* The Serving Leader: Five Powerful Actions to Transform Your Team, Business, and Community by Ken Jennings and John Stahl-Wert
* Turn the Ship Around!: A True Story of Turning Followers into Leaders by L. David Marquet

lfottaviano
