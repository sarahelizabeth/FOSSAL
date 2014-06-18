### {less}

Operating system: Cross-platform
Target audience: Web developers and designers
Website: lesscss.org
Github url: https://github.com/less/less.js 
Overview/flowchart of how LESS works: http://www.gliffy.com/go/publish/4784259 

LESS extends CSS with dynamic behavior such as variables, mixins, operations and functions. LESS can run on the client-side and server-side or can be compiled into plain CSS. LESS is a CSS preprocessor, which allows writing clean CSS in a programming construct instead of static rules.

LESS is inspired by Sass. Sass was designed to both simplify and extend CSS, so things like curly braces were removed from the syntax. LESS was designed to be as close to CSS as possible, so the syntax is identical to existing CSS code. As a result, existing CSS can be used as valid LESS code.

LESS allows variables to be defined. LESS variables are defined with an at sign(@). Variable assignment is done with a colon (:).
During translation, the values of the variables are inserted into the output CSS document.

    @color: #4D926F;
    #header {
      color: @color;
    }
    h2 {
      color: @color;
    }

The code above in LESS would compile to the following CSS code.

    #header {
      color: #4D926F;
    }
    h2 {
      color: #4D926F;
    }

CSS supports logical nesting, but the code blocks themselves are not nested like they are in HTML. LESS allows you to nest related selectors inside other selectors. This makes inheritance clear and style sheets shorter. You can make your CSS look like your HTML.

LESS allows operations and functions. Operations allow addition, subtraction, division and multiplication of property values and colors, which can be used to create complex relationships between properties. Because functions relate to JavaScript methods, it is much easier to manipulate jQuery using only CSS. This improves page load time drastically on JavaScript-heavy pages.

LESS inspires a lot of developer interest. The project is well-maintained and has many opportunities for developers to both solve issues and add features to the project. The issues are labeled appropriately in Github and well written so that people can easily understand what problems need to be solved. 

What I was most impressed with was the overview flowchart the developers created outlining how exactly the preprocessor works. It makes it very easy to see which programs/algorithms handle which steps in the process so that people don't get confused by the rather large code bank.

When I first used LESS, I thought that the documentation could use some work. It took me several hours to entirely figure out the system for using it, and I didn’t fully understand the benefits of it over regular CSS. With their most recent updates, the instructions have improved dramatically. It much more clearly explains the benefits of using LESS over other CSS preprocessors.

### Tarbell

Operating system: Linux/Unix and Mac OSX
Target audience: Journalists, web developers and designers, bloggers
Website: http://tarbell.tribapps.com/
Github url: http://github.com/newsapps/flask-tarbell
Project docs: http://build-with-tarbell.readthedocs.org/en/latest/index.html# 
Technical presentation: http://tarbell.tribapps.com/build-with-tarbell/#/front 

Tarbell was created by the Chicago Tribune News Applications team. The project was led in large part by my mentor, David Eads. Tarbell is named for Ida Tarbell, a famous female journalist.

Tarbell is a lightweight web publishing platform. It utilizes Twitter Bootstrap, Google spreadsheets, and Python Flask to produce web content that can be easily stored in Amazon S3 and Github.

This resource was designed in a newsroom with the newsroom in mind. Allowing easy and simple Google spreadsheet integration makes it easy for many people to contribute to the site (anyone with a Google account is able to access the spreadsheets) and collaborate easily on the product.

Because it is so new (the first version was available for download by the public only last summer), it is so far only used by the Tribune staff and other data journalists who have seen David talk about it at conferences. I personally have used it to make several personal portfolio sites for people and two blogs, and I really enjoy using it. It has also received positive reviews on Github and by users at conferences. It takes the first tedious steps out of building a dynamic website and allows the developer to focus on the design and functionality of the website.

A critique I have as far as the maintainability and readability of the code, I feel that the issues section of Tarbell’s Github could be better organized. However, Tarbell’s docs are very informative and well-organized. I always consult Tarbell’s model when writing my own instructions for a presentation or training session. David has two separate, equally visually appealing presentations that provide people who have never coded before the tools they need to make their own website using the Mac’s Terminal and text editing software.

A major drawback of Tarbell is its lack of a graphical user interface. However, many people prefer to use command line tools to a GUI. This limits Tarbell to fewer potential users, but users who do like using command line tools, such as myself, really like being able to use commands instead of buttons. In my Human Computer Interaction course this Spring, we learned that if a certain product appeals to a select group of users, it is better to invest time into those aspects and features which appeal to the core group instead of trying to do too many things and ending up with a mediocre product with lots of features instead of an excellent product with few well-rounded features. This is why I think Tarbell does not need a graphical interface.

Many Tribune staff have created beautiful projects with no prior coding experience using Tarbell. They get valuable experience writing very basic code to create basic websites, but more experiences developers can really mould Tarbell to their own tastes and use its flexible base template to do great things.

### AdBlock Pro

Browser compatibility: Google Chrome, Safari, and Firefox
Target audience: People who use the internet
Source code: https://adblockplus.org/en/source
Overview/flowchart of AdBlock: https://adblockplus.org/en/images/how-adblock-plus-works.png

Adblock Plus blocks annoying ads on the web. It can block other things, like tracking, as well. With more than 50 million users, it is the world's most popular browser extension. Adblock Plus is an open source project created by Wladimir Palant in 2006.

Faster loading, more readable content, and less risk of things being shoved aside by incorrectly-sized images are all benefits of this useful tool, not to mention reducing the problem of otherwise safe sites which contains ads from dubious or hacked sources that attempt drive-by downloads and exploits.

Adblock Plus doesn’t block all ads; website owners rely on advertising dollars to make money. The creators of AdBlock established strict criteria to identify Acceptable Ads: unobtrusive, family-friendly ones that don't need to be blocked. Websites that are willing to comply with these criteria can have their ads added to the exception list, which will unblock them for most users. Even then, users will always be able to opt out of this.

In terms of popularity, most people I know use some form of AdBlock. Although many people claim ads don’t bother them, I really am distracted by them. When I use someone else’s computer who doesn’t have AdBlock, I am really distracted by the amount of ads on their internet.

AdBlock’s issues page is rather daunting and confusing. The issues are user-submitted, and they are often difficult to understand, or have duplicates. For instance, one such issue simply says: “Can’t do anything”. However, because this project has such high user interest, there are many developers who want to contribute. This allows AdBlock’s controlling interest group to refrain from taking so much money as to corrupt the essence of the project.

The roadmap of where AdBlock has been, where it currently is, and where it is headed is rather convoluted. Clearly AdBlock’s target developers are well-versed in their subject matter because it was rather difficult for a beginner such as myself to understand how the code is maintained and edited. I did see that they intend to modify it for Android next, but no definite plans yet. Their code would be improved by using a mainstream repository such as Github or BitBucket.

Buttons to share content on social media platforms such as Facebook, Twitter, Google Plus and many others are placed on almost every website you visit. Even if you are not clicking them, every website containing these buttons is sending a request to the servers of the social network which can use that information to create a profile based on your browsing habits. You can use Adblock Plus to remove all social media buttons from every website, making sure that social networks can’t create a profile about you based on the websites you visit.
