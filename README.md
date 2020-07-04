# App_Offline Template
A simple app_offline.htm template for whatever application you would need to put it.

# What is this?
This is a pleasant static page saying _"Hey, my application is offline. Go grab a coffee/tea/whatever you'd like to drink and get back here"_ (not literally).

Works for any .NET web application if you put it in the website root directory

Tested on
- ✅ .Net Core 3.1 
- ✅ ASP.NET MVC 5 

Anyway, it will work wherever it would accept a static page with a specific name in order to put the application down.

# How to use?
You can either fork it or download this for your personal/commercial use. 

Once you put your hands in the code, just replace every `%WEBSITE%` with the company or the website name. and `%WEBSITE_IMG%` with a Base64 encoded image (or external resource) and you're good to go.

> Do not use internal resources. Because since _app_offline.htm_ will make your webserver reject every request, your images will also be rejected, thus, making your images `404`.

Please, feel free to change the text too.

# Why?
Sometimes, the very last thing you would put in your website is an app_offline file to make your maintenances. And it happened to me ~~twice~~ way too often. So I put this page together to make things easier whenever I need to have a good-looking ~~that's debatable~~ responsive page in no time.

# Highlights

The background was done thanks to [SVG Backgrounds](https://www.svgbackgrounds.com/), which is an awesome resource to do backgrounds with just vectors. They got stylish vector backgrounds, and fits so well for this mission!

The image was from lineicon.com, but they seem to be down.

# Final words
I hope I don't have to waste time doing app_offline files in a while. I know, it's a basic page, but on tight schedules, the more time you can have in your hands, the better.

Perhaps I could put more templates here. 