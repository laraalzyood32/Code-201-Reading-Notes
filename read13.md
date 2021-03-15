# ersistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, 
# the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state
# they have three potentially dealbreaking downsides:

1.Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
2.Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3.Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful What we really want is
a lot of storage space on the client that persists beyond a page refresh and isn’t transmitted to the server
Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.
# INTRODUCING HTML5 STORAGE :
way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site,
close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually
# USING HTML5 STORAGE
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string.
The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. 
If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
# TRACKING CHANGES TO THE HTML5 STORAGE AREA
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(),
removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys,
the storage event will not fire, because nothing actually changed in the storage area.
# HTML5 STORAGE IN ACTION 
# There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally,
within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage,
the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made, the position of each of the pieces on the board,
and even whether a particular piece is selected.
# BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS
While the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer, that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,” and the future of persistent local storage is… how shall I put it… well, there are competing visions.
One vision is an acronym that you probably know already: SQL. In 2007, Google launched Gears, an open source cross-browser plugin which included an embedded database based on SQLite. This early prototype later influenced the creation of the Web SQL Database specification. Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database, allowing you to do things like this from JavaScript:
WEB SQL DATABASE SUPPORT
IE : .
FIREFOX : .
SAFARI : 4.0+
CHROME : 4.0+
OPERA : 10.5+
IPHONE : 3.0+
ANDROID : 2.0+

