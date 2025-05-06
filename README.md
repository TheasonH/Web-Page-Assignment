<h1>A perfect summer's day</h1>
<p>It was a lovely day for a walk in the park. The birds were
singing and the kids were all back at school.</p>
.footer {
background-color: #CCC;
border-top: 1px solid #333;
}
border-top: 1px solid #333;
.footer {
background-color: #CCC;
border-top: 1px solid #333;
padding: 5px;
}
.footer {
⋮
margin: 5px;
}
Some lines of code are intended to be entered on one line, but we’ve had to wrap
them because of page constraints. A ➥ indicates a line break that exists for formatting
purposes only, and should be ignored:
URL.open("http://www.sitepoint.com/blogs/2007/05/28/user-style-she
➥ets-come-of-age/");
Menus
When you need to select an option from a menu, it’ll be written as File > Save; this
means “select the Save option from the File menu.”
Tips, Notes, and Warnings
Hey, You!
Tips will give you helpful little pointers.
Ahem, Excuse Me ...
Notes are useful asides that are related—but not critical—to the topic at hand.
Think of them as extra tidbits of information.
Order the print version of this book to get all 400+ pages!
xxxiv
Make Sure You Always ...
... pay attention to these important points.
Watch Out!
Warnings will highlight any gotchas that are likely to trip you up along the way.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Chapter
1
Setting Up Shop
Before you dive in and start to build your web site, we need to take a little time to
get your computer set up and ready for the work that lies ahead. That’s what this
chapter is all about: ensuring that you have all the tools you need installed and are
ready to go.
If you were to look at the hundreds of computing books for sale in your local
bookstore, you could be forgiven for thinking that you’d need to invest in a lot of
different programs to build a web site. However, the reality is that most of the tools
you need are probably sitting there on your computer, tucked away somewhere you
wouldn’t think to look for them. And if ever you don’t have the tool for the job,
there’s almost certain to be one or more free programs available that can handle the
task.
We’ve made the assumption that you already have an Internet connection, most
likely broadband (or similar). Don’t worry if you have a slower connection: it won’t
affect any of the tasks we’ll undertake in this book. It will, however, mean that some
of the suggested downloads or uploads may take longer to complete, but you probably
knew that already.
2 Build Your Own Web Site The Right Way Using HTML & CSS
Planning, Schmanning
At this point, it might be tempting to look at your motives for building a web site.
Do you have a project plan? What objectives do you have for the site?
While you probably have some objectives, and some idea of how long you want
to spend creating your site, we’re going to gloss over the nitty-gritty of project
planning to some extent. This is not to say that project planning isn’t an important
aspect to consider, but we’re going to assume that because you’ve picked up a
book entitled Build Your Own Web Site The Right Way, you probably want to just
get right into the building part.
As this is your first web site and it will be a fairly simple one, we can overlook
some of the more detailed aspects of site planning. Later, once you’ve learned—and
moved beyond—the basics of building a site, you may feel ready to tackle a larger,
more technically challenging site. When that time comes, proper planning will
be a far more important aspect of the job. But now, let’s gear up to build our first,
simple site.
The Basic Tools You Need
As I mentioned earlier, many of the tools you’ll need to build your first web site are
already on your computer. So, what tools do you need?
■ The primary—and most basic—tool that you’ll need is a text editor; a program
that allows you to edit plain text files. You’ll use this to write your web pages.
■ Once you’ve written a web page, you can see how it looks in a web
browser—that’s the application you use to view web sites.
■ Finally, when you’re happy with your new web page, you can put it on the
Internet using an FTP client—a utility that allows you to transfer files across the
Internet using the File Transfer Protocol. Using FTP may seem a little complicated
at first, but thankfully you won’t need to do it too often. We’ll discuss FTP clients
in detail in Chapter 8.
You’ve already got most of these programs on your computer, so let’s go and find
them.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
3Setting Up Shop
Windows Basic Tools
In the following section—and indeed the rest of this book—where we refer to the
Windows operating system, that’s really a shorthand way of saying Windows Vista
(in all its confusing varieties). Any instructions and screen shots will be with Vista
in mind. However, we are not going to shut out all you Windows XP users—and
there are many people out there who use XP in preference to Vista, much to Micro
soft’s displeasure—so where instructions provided for Vista are not the same for
XP, we’ll cover the differences for you.
Your Text Editor: Notepad
The first tool we’ll consider is the text editor. Windows comes with a very simple
text editor called Notepad. Many professional web designers who use complicated
software packages first started out many years ago using Notepad; indeed, many
professionals who have expensive pieces of software that should be time-savers
still resort to using Notepad for many tasks. Why? Well, because it’s so simple, little
can go wrong. It also loads much more quickly than fully-featured web development
programs. Bells and whistles are definitely not featured.
You can find Notepad in the Start menu: go to Start > All Programs > Accessories.
Shortcut to Notepad
To save yourself navigating to this location each time you want to open Notepad,
create a shortcut on your desktop. With the Start menu open to display Notepad’s
location, hold down the Ctrl key, click and hold down the mouse button, then
drag the Notepad icon to your desktop. When you release the mouse button, a
shortcut to the application will appear on your desktop, as in Figure 1.1.
Figure 1.1. Creating a shortcut to Notepad
Notepad is the most basic of applications, as you can see from Figure 1.2.
Order the print version of this book to get all 400+ pages!
4 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 1.2. Notepad: a contender for the world’s plainest program?
Your Web Browser: Internet Explorer
Once you’ve created a web page using Notepad, you’ll need a way to view the results
of your handiwork. You’ll remember that in the preface to this book, we mentioned
Internet Explorer (IE). Well, that’s your viewer. As Figure 1.3 shows, Internet Explorer
sits right there in the Start menu, also in the Programs folder (accessed via All Programs
from the Start menu), in the Quick Launch area (bottom left of the Start menu, near
the Windows logo), and a shortcut may also lurk on your desktop.
Figure 1.3. Internet Explorer: there’s no hiding this browser!
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
5Setting Up Shop
Mac OS X Basic Tools
Like Windows, the Mac operating system (specifically OS X; we won’t be looking
at previous versions of the Mac OS) has a number of tools that you can use straight
out of the box. These tools are virtually equivalent to the Windows programs men
tioned above.
Your Text Editor: TextEdit
While Windows has Notepad, the Mac has TextEdit, which can be found in the
Applications folder, as Figure 1.4 illustrates.
Figure 1.4. TextEdit comes as part of Mac OS X’s default installation
Unlike Notepad, TextEdit works as a rich text editor by default, which means we
can work with fonts, make text bold and italic, and so on. However, we want to
work with TextEdit as a plain text editor, so you’ll need to adjust some of TextEdit’s
preferences. Start TextEdit, then select TextEdit > Preferences from the menu to bring
up the Preferences screen. Select Plain text within New Document Attributes, then
close the Preferences screen. The next time you create a new file in TextEdit, it will
be a plain text document.
Your Web Browser: Safari
The default browser for Mac users is Safari. You can usually find Safari in the dock
(the dock is the bar of icons at the bottom of your screen), but you can also access
it through the Applications folder, as Figure 1.5 illustrates.
Order the print version of this book to get all 400+ pages!
6 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 1.5. Safari is available via Mac’s Applications folder
Stick It in the Dock
Just as you can drag shortcuts to programs onto the Windows desktop, you can
add programs to the dock in Mac OS X. To add a program to the dock, just drag
its icon from the Applications folder onto the dock, and presto! The application
is now easily accessible whenever you need it.
If you are using a slightly older Mac, you may also have a copy of Internet Explorer
installed. Our advice for Internet Explorer for Mac? Send it to Trash. The Mac version
of IE was abandoned by Microsoft many years ago, so it’s considerably outdated
and is rarely supported or used in the wider world; no new Macs come with this
application preinstalled. It also bears no real resemblance to its Windows counter
part, for those more comfortable using IE.
Beyond the Basic Tools
You can certainly make a good start using the tools mentioned above. However,
once you’re dealing with a handful of web pages and other resources, you may want
to go beyond these basic tools. We’ll show you how to use some slightly more ad
vanced applications later in the book.
Countless other text editors and web browsers are available for download, and many
of them are free. Obviously, we don’t have time to describe each and every one of
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
7Setting Up Shop
them, so I’ve settled on a few options that have worked for me in the past, and which
you might like to download and have at your disposal. And remember, they’re all
free!
Windows Tools
NoteTab
NoteTab’s tabbed interface lets you have many different files open simultaneously
without cluttering up your screen, as Figure 1.6 illustrates. Files that you’ve opened
are remembered even after you close the program and open it again later, which is
very useful when you’re working on a batch of files over many days. You can
download the free NoteTab, or its Light version, from http://www.notetab.com/.
Figure 1.6. NoteTab Light’s tabbed interface
Firefox
As mentioned in the Preface, Firefox is a very popular alternative to Internet Explorer
and, as we proceed through this book, it will be our browser of choice for a number
of reasons. As with NoteTab, Firefox offers a tabbed interface that helps keep your
computer free from window clutter. You can download Firefox from
http://www.mozilla.com/firefox/; the browser is depicted in Figure 1.7.
Order the print version of this book to get all 400+ pages!
8 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 1.7. Firefox—this creature is worth hunting down
Mac OS X Tools
It is true that there are fewer free programs available for the Mac operating system
than there are for Windows. However, there are a few programs that you might like
to consider as you move beyond the basics.
TextWrangler
TextWrangler is a free, simple text editor made by BareBones Software. As with
NoteTab for Windows, TextWrangler can tidy up your workspace by allowing sev
eral text files to be open for editing at the same time (the documents are listed in a
pull-out drawer to one side of the interface, rather than in tabs). You can download
TextWrangler, shown in Figure 1.8, from the BareBones Software web site.1
1 http://www.barebones.com/products/textwrangler/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
9Setting Up Shop
Figure 1.8. TextWrangler, a free text editor from BareBones Software
Firefox
Firefox is popular not just among Windows users, but also with Mac users, many
of whom prefer to use it instead of Safari (often because of the extra features—known
as add-ons—that can be bolted on to the browser). A web page viewed in Firefox
should display the same regardless of whether the browser is installed on a PC
running Windows XP or Vista, on a Mac running OS X, or on Linux, a free, open
source operating system (generally favored by highly technical people who like to
tinker with their computers a lot). The predictability of Firefox is a welcome change
from the bad old days of endless browser competition, and is one very good reason
why we will mainly use Firefox in the examples included in this book.
Not Just Text, Text, Text
You can build an entire web site using just the tools mentioned above, but it won’t
be the sexiest site on the Web. The missing element here is images: so far, the pro
grams we’ve mentioned are used to manipulate plain text or view web pages. If your
web site is going to be visually appealing, you’ll need to be able to create and ma
nipulate images, either from scratch using photos you’ve taken, or using images
that you have the legal right to use on your web site.
Unfortunately, when it comes to image editing software, that old saying, “You get
what you pay for,” applies. A professional image editing program, like Photoshop
or Fireworks, costs hundreds of dollars. While these programs offer some excellent
capabilities, we can’t really recommend that you go out and pay for them unless
you’re sure that they’re right for you. If you already have a copy of one of these, or
a similar image editing program, by all means use it and experiment with it. Programs
Order the print version of this book to get all 400+ pages!
10 Build Your Own Web Site The Right Way Using HTML & CSS
like Paint Shop Pro or Photoshop Elements (a cut-down version of Photoshop) are
more reasonably priced. However, for the purposes of this book, we’ll look only at
tools that are free to download and offer enough functionality to give you an idea
of what’s possible.
Keep an eye open for free image editors that are included on disks attached to the
covers of Internet, computing, and design magazines. Software vendors often give
away older versions of their software in the hope that users might be tempted to
upgrade to a new version at a later date. Look out for Paint Shop Pro, or any image
editor that supports layers—a way to construct an image by stacking 2 or more
layers, one on top of the other. While we’ll keep our image editing fairly simple
throughout this book, it’s certainly worth keeping an eye open for free (and full-
featured) image editing software, as these offers will not always be available.
Taking the Big Boys for a Spin
The most commonly used image editing packages are available for trial download.
They are large downloads (hundreds of megabytes) and may need to be left to
download overnight, even on a broadband connection.
These trial versions are typically available for 30 days’ use; after that time you
can decide whether you want to pay for the full software or stop using the program.
However, those 30 days might just be enough time for you to use the software
while you work through this book.
Adobe Photoshop A trial of the latest version of Photoshop is available for
download.2 If you’d rather try the lighter Photoshop Ele
ments, trial versions are available for Windows3 and Mac.4
Adobe Fireworks You can download a trial version of Fireworks from the
Adobe web site.5
Paint Shop Pro Paint Shop Pro is available for Windows only. To download
a trial version, visit the Paint Shop Pro site,6 and click the
Free Trial link.
2 http://www.adobe.com/products/photoshop/
3 http://www.adobe.com/products/photoshopelwin/
4 http://www.adobe.com/products/photoshopelmac/
5 http://www.adobe.com/products/fireworks/
6 http://www.corel.com/paintshoppro/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Setting Up Shop 11
Windows Tools
A standard Windows install has not always been blessed with image editing software.
Certainly this was the case with Windows XP (although if you bought the computer
as a bundle with PC, scanner, or digital camera all together, you might be lucky and
find some image editing software included in the deal; scout around in your Start
> All Programs menu to see what you can uncover).
In Windows Vista, the Photo Gallery application has seen some big improvements
over its previous XP incarnation and now includes some basic, but still useful, image
manipulation tools, including cropping, color, and contrast adjustment. The Photo
Gallery application can be found directly in the Start menu.
Figure 1.9. Vista’s Photo Gallery application
Picasa
If you’re using Vista, the tools offered in Photo Gallery may do everything that you
need; if you’re using XP, you’ll almost certainly need to use an extra application.
With that in mind, you might like to try out an excellent image management tool
that Google offers for free download. The program is called Picasa, and it’s extremely
Order the print version of this book to get all 400+ pages!
12 Build Your Own Web Site The Right Way Using HTML & CSS
well equipped to handle most of the tasks that you’re likely to encounter as you
manage imagery for your web site. Download a copy from the Picasa web site,7 and
soon enough you’ll be using this program to crop, rotate, add special effects to, and
catalog the images stored on your computer. Figure 1.10 gives you an idea of the
program’s interface.
Figure 1.10. Picasa: Google’s free, fully-featured photo and image editing and management tool
Mac OS X Tools
The Mac has a reputation for being favored by designers and creative types, and the
platform makes many tools available to the budding artist. However, they usually
come at a price, and often that price is higher than those of the Windows equivalents.
So, what free software can we use on the Mac, assuming that we want something
more permanent than a 30-day trial version of Photoshop or Fireworks?
GraphicConverter
GraphicConverter has much greater capabilities than its name suggests. It’s been
bundled with new Macs at times, and is also available for download8 (you’ll be
7 http://picasa.google.com/download/
8 http://www.graphicconverter.net/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Setting Up Shop 13
encouraged to pay a modest registration fee for the software, but you can try it out
for free). Although this is primarily a tool for converting graphic files, it can also
be used for simple editing tasks. Using GraphicConverter, which is illustrated in
Figure 1.11, you’ll be able to crop, resize, rotate, and add text to any image.
Figure 1.11. GraphicConverter does a lot more than simply convert graphics
iPhoto
Also included with Mac OS X is a program that probably needs no introduction to
the experienced Mac user: iPhoto. This excellent program is not intended to be a
fully featured image editor; it’s really designed for managing and viewing large
numbers of photos stored on a computer. It’s great for organizing photo albums, but
iPhoto also has some very useful editing facilities that take it beyond a mere cata
loging tool.
iPhoto, seen in Figure 1.12, can be found in the Applications folder or in the dock.
Order the print version of this book to get all 400+ pages!
14 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 1.12. Using the image adjustment tools in iPhoto 6
Creating a Spot for Your Web Site
So far, we’ve looked at some of the tools that you’ll need to create your web site.
We’ve looked at programs that are readily available, and where you can find them
on your computer. And for cases in which the free tools that came with your com
puter are not up to the job, we’ve suggested other programs that you can download
and use. The next task we must tick off our to-do list before we go any further is to
create a space for your web site on the hard drive.
Windows
The easiest and most logical place to keep your web site files is in a dedicated folder
within the Documents folder (or the My Documents folder in Windows XP). The
Documents folder can be found inside your user folder. “But what’s this user folder?”
I hear you cry. And a fair point too, because it won’t be labeled User but rather it
will be labeled according to the user name that you provided when you first set up
Windows. In Windows Vista you’ll find the user folders of all local computer account
holders under C:\Users (in Windows XP it’s under C:\Documents and Settings) and
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Setting Up Shop 15
will have a folder name matching your user name. More conveniently though, you’ll
find it on your computer’s desktop as shown in Figure 1.13.
Figure 1.13. The user folder—in this case the user is “Administrator”—contains the Documents folder (highlighted)
Don’t worry if your user folder is not on the desktop: it’s easy to get it to appear
there (see the tip below for details on how to add this for Vista and XP). Double-
click to open your user folder, then double-click on Documents, then finally create
a new folder called Web by selecting File > New > Folder.
Displaying the Users Folder in Vista and the My Documents Folder
in Windows XP
Can’t find your user folder on your Vista desktop? Missing your My Documents
folder in XP? In an effort to clean up your desktop, you may have removed the
icon by accident—it’s easily done. This is how you can return the folder to your
desktop:
■ From the Start Menu, select Control Panel.
■ Select Appearance and Personalization (or Appearance and Themes in XP).
■ Vista users: choose Personalization and listed in the top left, under the title Tasks
is the option to Change Desktop Icons. A new dialogue box will appear: check
the option entitled User’s Files in the section Desktop Icons, then press OK. You
may now also close the Appearance and Personalization window.
Order the print version of this book to get all 400+ pages!
16 Build Your Own Web Site The Right Way Using HTML & CSS
■ XP users: select Change the desktop background from the list of options, then
click the Customize Desktop... button at the bottom. Check the My Documents
option in the dialogue box that appears, then click OK. Close the Appearance
and Themes window also by pressing OK.
■ Your user folder/My Documents folder should now be back on the desktop, as
shown in Figure 1.14.
Figure 1.14. Administrator’s user folder and My Documents folder displayed on the desktop in Windows Vista and
Windows XP, respectively
Mac OS X
In Mac OS X, there’s already a handy place for you to store your web site files: the
Sites folder shown in Figure 1.15. Open your home directory (from Finder, select
Go > Home), and there it is.
It’s easy to add the Sites folder to your sidebar (seen in Figure 1.16) for quick access:
just drag the folder to the sidebar in the same way you add items to the dock.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Setting Up Shop 17
Figure 1.15. The Sites folder displayed in the Mac OS X home directory
Figure 1.16. The Sites folder placed in the sidebar
Getting Help
Books may be a wonderful way to learn: you’re sitting there with a computer running,
perhaps a cup of coffee keeping your mind ticking over, and a bookmark signifying
your progress to date. Great. But what if you don’t understand something in the
Order the print version of this book to get all 400+ pages!
18 Build Your Own Web Site The Right Way Using HTML & CSS
book? What do you do next? Shouting at the book won’t help, though there may be
some therapeutic value to it!
Hopefully, you won’t find yourself with too many questions as you work through
this book, but if you’re the curious type—or a quick learner—you might want to go
beyond what we’re going to teach you here.
Whether you’re getting stuck or want to learn more, your first stop should be the
SitePoint Forums.9 It will only take a few moments to register, and once you’ve
done so you can log in and ask questions in a range of different forums. Whether
you have questions about writing content for your web site, you need marketing
tips, or you’re facing a few tricky graphic design issues, the hundreds of experts
who contribute to and moderate these pages every day will be happy to help out.
Register at SitePoint’s forums today; then, when we recommend further reading or
research, you’ll be good to go. Oh, and did we mention that all this friendly, helpful
advice is free of charge? We thought that might encourage you!
Summary
Believe it or not, we’ve now got everything we need to build our own web site—and
all without spending a cent! Not only do we have the basic tools—our text editor
(Notepad or TextEdit) and our web browser (Internet Explorer or Safari)—but we’ve
also looked at some alternatives to these.
We’ve reviewed some simple and freely available image editing programs that can
help us spruce up our sites: Picasa for Windows, and GraphicConverter and iPhoto
for Mac. Finally, we mentioned some more capable—and more expensive—options,
such as Photoshop and Paint Shop Pro.
Now we’ve got the tools, let’s learn how to use them!
9 http://www.sitepoint.com/forums/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Chapter
2
Your First Web Pages
A wise man once said that a journey of a thousand miles begins with a single step.
In this chapter, you’ll take that first metaphorical step on your journey towards web
site enlightenment: you’ll create your first web page. By the end of the chapter,
you’ll have duplicated that first page to form the beginnings of a multi-page web
site.
Nice to Meet You, XHTML
In the preface to this book, we touched briefly on what XHTML is. In this chapter,
we’ll learn the basics of XHTML, periodically previewing our progress in a browser,
and steadily building up our knowledge of various XHTML elements (elements are
the basic building blocks of XHTML). Elements tell the web browser what a partic
ular item in the page is: a paragraph, a heading, a quotation, and so on. These ele
ments contain all the information that the browser requires, as we’ll soon see.
Anatomy of a Web Page
In the preface, we said that learning XHTML was like taking a driving lesson. To
take that analogy a step further, imagine a web page as being the car in which you’re
20 Build Your Own Web Site The Right Way Using HTML & CSS
learning to drive. There are some things that are essential to the process of driving;
others are mere fashion items.
To drive the car you need to have wheels (including the steering wheel), and a place
to sit. The car must also have some kind of chassis to which the bodywork can be
bolted. An engine is required to power the car, as is bodywork to which your
(nonessential, but spiffy) trim can be attached. Anything less, and all you have is a
collection of attractive—but useless!—spare parts.
Like the car, your web page also needs to have a chassis: a basic structure upon
which everything else can be built. But what does this hypothetical chassis look
like? The best way to find out is to roll up our sleeves, figuratively speaking, then
take a closer look at what’s going on underneath the cosmetic features.
Viewing the Source
One of the great things about learning to build web pages is that we all have the
ability to view the source code of other people’s web pages. You can learn a lot by
simply taking a peek at how someone else’s web page was built ... but how do you
do that?
Although every browser uses slightly different terminology, the variations in the
ways different browsers let us view web page code are so small that the process
doesn’t need to be spelled out for every browser. Here’s the technique you’d use to
view a web page’s source in IE:
■ Bring up a page in your browser, for example the Web Standards Project’s
homepage.1 The Web Standards Project (WaSP) is a group that promotes the
benefits of building your web site correctly, so you can be pretty confident that
they’ve got it right.
■ Position your cursor somewhere on the page (other than over an image), and
right-click (Ctrl-click on a Mac). You should be presented with a context menu
similar to those shown in Figure 2.1.
1 http://webstandards.org/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 21
Figure 2.1. Selecting the View Source command after right-clicking on a web page (as seen in Internet Explorer
and Firefox, respectively)
■ Select View Source, (or View Page Source for Firefox) and a new window will ap
pear, displaying all of the page’s underlying markup.
At this point, we’re not going to analyze the markup that you’re looking at, but this
is one of those tricks that’s really useful to know from the beginning.
Careful Who You Trust!
Most web pages don’t use best-practice techniques, so avoid looking at a page’s
source unless the web site in question is mentioned in this book as being a good
example.
Order the print version of this book to get all 400+ pages!
22 Build Your Own Web Site The Right Way Using HTML & CSS
Basic Requirements of a Web Page
As we’ve already discussed, in any web page there are some basic must-have items.
You would have seen all of these if you scanned through the markup that appeared
when you tried to view source a moment ago:
■ a doctype
■ an <html> tag
■ a <head> tag
■ a <title> tag
■ a <body> tag
These requirements make up the basic skeleton of a web page. It’s the chassis of
your car with some unpainted bodywork, but no wheels or seats. A car enthusiast
would call it a project—a solid foundation that needs a little extra work to turn it
in to something usable. The same goes for a web page. Here’s what these requirements
look like when they’re combined in a basic web page:
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Untitled Document</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
</body>
</html>
Those of you with eagle eyes may have also spotted the <meta> tag in the markup
above. I know I haven’t mentioned this yet; we’ll get to it soon enough. For now be
content with the knowledge that, although the <meta> tag is not part of the skeletal
requirements of a web page, it serves many useful purposes, especially the provision
of supporting information about the web page.
The markup above is the most basic web page you’ll see here. It contains practically
no content of any value (at least, as far as someone who looks at it in a browser is
concerned), but it’s crucial that you understand what this markup means. Let’s
delve a little deeper.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 23
The Doctype
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
This is known as the doctype2 (short for Document Type Definition). It must be the
first item on a web page, appearing even before any spacing or carriage returns.
Have you ever taken a document you wrote in Microsoft Word 2007 on one computer,
and tried to open it on another computer that only had Word 2000 on it? Frustrat
ingly, without some preemptive massaging when the file is saved in the first place,
this doesn’t work quite as expected. It fails because Word 2007 includes features
that Bill Gates and his team hadn’t even dreamed of in 2000, and so Microsoft
needed to create a new version of its file format to cater for these new features. Just
as Microsoft has many different versions of Word, so too are there different versions
of HTML, most recently XHTML and HTML 5. Mercifully, the different versions of
HTML have been designed so that it doesn’t suffer the same incompatibility gremlins
as Word, but it’s still important to identify the version of HTML that you’re using.
This is where the doctype comes in. The doctype’s job is to specify which version
of HTML the browser should expect to see. The browser uses this information to
decide how it should render items on the screen.
The doctype above states that we’re using XHTML 1.0 Strict, and includes a URL
to which the browser can refer: this URL points to the W3C’s specification for
XHTML 1.0 Strict. Got all that? Okay, let’s take a jargon break! There are way too
many abbreviations for this paragraph.
HTML5—The New Kid on the Block
Note that at the time of writing, the HTML5 specification is not yet finalized and
browser support for it is also incomplete (understandable, given the moving
goalposts). For this reason, we’ll not be covering HTML5 in this book. You should,
however, be aware of its existence at the very least.
2 http://reference.sitepoint.com/html/doctypes/
Order the print version of this book to get all 400+ pages!
24 Build Your Own Web Site The Right Way Using HTML & CSS
Jargon Busting
URL
URL stands for Uniform Resource Locator. It’s what some (admittedly more
geeky) people refer to when they talk about a web site’s address. URL is def
initely a useful term to know, though, because it’s becoming more and more
common.
W3C
W3C is an abbreviation of the name World Wide Web Consortium, a group
of smart people spread across the globe who, collectively, come up with
proposals for the ways in which computing and markup languages used on
the Web should be written. The W3C defines the rules, suggests usage, then
publishes the agreed documentation for reference by interested parties, be
they web site creators like yourself (once you’re done with this book, that is),
or software developers who are building the programs that need to understand
these languages (such as browsers or authoring software).
The W3C documents are the starting point, and indeed everything in this
book is based on the original documents. But you won’t want to look at any
W3C documents for a long time yet. They’re just plain scary for us mere
mortals without Computer Science degrees. Just stick with this book for the
time being and I’ll guide you through.
The html Element
So, the doctype has told the browser to expect a certain version of HTML. What
comes next? Some HTML!
An XHTML document is built using elements. Remember, elements are the bricks
that create the structures that hold a web page together. But what exactly is an ele
ment? What does an element look like, and what is its purpose?
■ An XHTML element starts and ends with tags—the opening tag and the closing
tag.3
3 Like any good rule, there are exceptions to this: empty elements, such as meta, use special empty
tags. We’ll take a look at empty tags soon.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 25
■ A tag consists of an opening angled bracket (<), some text, and a closing bracket
(>).
■ Inside a tag, there is a tag name; there may also be one or more attributes.
Let’s take a look at the first element in the page: the html4 element. Figure 2.2 shows
what we have.
Figure 2.2. Components of a typical XHTML element
Figure 2.2 depicts the opening tag, which marks the start of the element:
<html xmlns="http://www.w3.org/1999/xhtml">
Below this we see the closing tag, which marks its end (and occurs right at the end
of the document):
</html>
Here’s that line again, with the tag name in bold:
<html xmlns="http://www.w3.org/1999/xhtml">
And there is one attribute in the opening tag:
<html xmlns="http://www.w3.org/1999/xhtml">
4 http://reference.sitepoint.com/html/html/
Order the print version of this book to get all 400+ pages!
26 Build Your Own Web Site The Right Way Using HTML & CSS
What’s an Attribute?
HTML elements can have a range of different attributes; the available attributes
vary depending on which element you’re dealing with. Each attribute is made up
of a name and a value, and these are always written as name="value". Some at
tributes are optional while others are compulsory, but together they give the
browser important information that the element wouldn’t offer otherwise. For
example, the image element (which we’ll learn about soon) has a compulsory
“image source” attribute, the value of which gives the filename of the image. At
tributes appear only in the opening tag of any given element. We’ll see more attri
butes crop up as we work our way through this project, and, at least initially, I’ll
be making sure to point them out so that you’re familiar with them.
Back to the purpose of the html element. This is the outermost “container” of our
web page; everything else (apart from the doctype) is kept within that outer contain
er. Let’s peel off that outer layer and take a peek at the contents inside.
There are two major sections inside the html element: the head and the body. It’s
not going to be difficult to remember the order in which those items should appear,
unless you happen to enjoy doing headstands.
The head Element
The head5 element contains information about the page, but no information that
will be displayed on the page itself. For example, it contains the title6 element,
which tells the browser what to display in its title bar (the title bar is the very top
part of the browser window—the part with minimize, maximize and close buttons):
⋮
<head>
<title>Untitled Document</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
⋮
5 http://reference.sitepoint.com/html/head/
6 http://reference.sitepoint.com/html/title/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 27
The title Element
The opening <title> and closing </title> tags are wrapped around the words
“Untitled Document” in the markup above. Note that the <title> signifies the start,
while the closing </title> signifies the end of the title. That’s how closing tags
work: they have forward slashes just after the first < angle bracket.
The Untitled Document title is typical of what HTML authoring software provides
as a starting point when you choose to create a new web page; it’s up to you to
change those words. As Figure 2.3 shows, it really pays to put something meaningful
as a title, and not just for the sake of those people who visit our web page.
Figure 2.3. “Untitled Document”—not a very helpful title
The content of the title element is also used for a number of other purposes:
■ It’s the name that appears in the Windows Taskbar—that strip along the bottom
of your Windows desktop that show all the currently open windows—for any
open document, as shown in Figure 2.4. It also appears in the dock on a Mac,
as Figure 2.5 illustrates. When you have a few windows open, you’ll appreciate
those people who have made an effort to enter a descriptive title!
Figure 2.4. The title appearing in the Windows Taskbar
Order the print version of this book to get all 400+ pages!
28 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 2.5. The title displaying in the Mac dock
■ If users decide to add the page to their bookmarks (or favorites), the title will
be used to name the bookmark, as Figure 2.6 illustrates.
Figure 2.6. An untitled document saved to IE’s favorites
■ Your title element is used heavily by search engines to ascertain what your
page contains, and what information about it should be displayed in the search
results. Just for fun, and to see how many people forget to type in a useful title,
try searching for the phrase Untitled Document in the search engine of your
choice.
meta Elements
Inside the head element in our simple example, we can see a meta element, which
is shown in bold below:
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 29
⋮
<head>
<title>Untitled Document</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
⋮
meta elements can be used in a web page for many different reasons. Some are used
to provide additional information that’s not displayed on screen to the browser or
to search engines; for instance, the name of the page’s author or a copyright notice
might be included in meta elements. In the example above, the meta tag tells the
browser which character set to use (specifically, UTF-8, which includes the char
acters needed for web pages in just about any written language).
There are many different uses for meta elements, but most of them will make no
discernible difference to the way your page looks, and as such, won’t be of much
interest to you (at least at this stage).
Self-closing Elements
The meta element is an example of a self-closing element (or an empty element).
Unlike title, the meta element needn’t contain anything, so we could write it
as follows:
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"></meta>
XHTML contains a number of empty elements, and the boffins who put together
XHTML decided that writing all those closing tags would get annoying pretty
quickly, so they decided to use self-closing tags: tags that end with />. So our
meta example becomes:
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
Order the print version of this book to get all 400+ pages!
30 Build Your Own Web Site The Right Way Using HTML & CSS
The Memory Game: Remembering Difficult Markup
If you’re thinking that the doctype and meta elements are difficult to remember,
and you’re wondering how on earth people commit them to memory, don’t worry,
most people don’t. Even the most hardened and world-weary coders would have
difficulty remembering these elements exactly, so most do the same thing—they
copy from a source they know to be correct (most likely from their last project or
piece of work). You’ll probably do the same as you work with project files for this
book.
Fully-fledged web development programs, such as Dreamweaver, will normally
take care of these difficult parts of coding. But if you are using a humble text ed
itor and need some help, you need only remember that there is a completely
searchable HTML reference,7 accessible at any time at SitePoint.com.
Other head Elements
Other items, such as CSS markup and JavaScript code, can appear in the head ele
ment, but we’ll discuss these as we need them.
The body Element
Finally, we get to the place where it all happens. The body8 element of the page
contains almost everything that you see on the screen: headings, paragraphs, images,
any navigation that’s required, and footers that sit at the bottom of the web page:
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Untitled Document</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
</body>
</html>
7 http://reference.sitepoint.com/html/
8 http://reference.sitepoint.com/html/body/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 31
The Most Basic Web Page in the World
Actually, that heading’s a bit of a misnomer: we’ve already shown you the most
basic page—the one without any content. However, to start to appreciate how
everything fits together, you really need to see a simple page with some actual
content on it. Let’s have a go at it, shall we?
Open your text editor and type the following into a new, empty document (or grab
the file from the code archive if you don’t feel like typing it out):
basic.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>The Most Basic Web Page in the World</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<h1>The Most Basic Web Page in the World</h1>
<p>This is a very simple web page to get you started.
Hopefully you will get to see how the markup that drives
the page relates to the end result that you can see on
screen.</p>
<p>This is another paragraph, by the way. Just to show how it
works.</p>
</body>
</html>
Once you’ve typed it out, save it as basic.html.
If you’re using Notepad:
1. Select File > Save As... from the menu and find the Web folder you created inside
your Documents folder.
2. Enter the filename as basic.html.
3. Select UTF-8 from the Encoding drop-down list.
4. Click Save.
Order the print version of this book to get all 400+ pages!
32 Build Your Own Web Site The Right Way Using HTML & CSS
If you’re using TextEdit on a Mac, first make sure that you’re in plain text mode,
then:
1. Select File > Save As... from the menu.
2. Find the Sites folder, enter the filename as basic.html.
3. Select Unicode (UTF-8) from the Plain Text Encoding drop-down list.
4. Click Save.
5. TextEdit will warn you that you’re saving a plain text file with an extension
other than .txt, and offer to append .txt to the end of your filename. We want
to save this file with an .html extension, so click the Don’t Append button, and
your file will be saved.
The Importance of UTF-8
If you neglect to select UTF-8 when saving your files, it’s likely that you won’t
notice much of a difference. However, when someone else tries to view your web
site (say, a Korean friend of yours), they’ll probably end up with a screen of
gobbledygook. Why? Because their computer is set up to read Korean text, and
yours is set up to create English text. UTF-8 can handle just about any language
there is (including some quite obscure ones) and most computers can read it, so
UTF-8 is always a safe bet.
Next, using Windows Explorer or Finder, locate the file that you just saved, and
double-click to open it in your browser. Figure 2.7 shows how the page displays.
Figure 2.7. Displaying a basic page
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 33
Analyzing the Web Page
We’ve introduced two new elements to our simple page: a heading element, and a
couple of paragraph elements, denoted by the <h1>9 tag and <p>10 tags, respectively.
Do you see how the markup you’ve typed out relates to what you can see in the
browser? Figure 2.8 shows a direct comparison of the document displays.
Figure 2.8. Comparing the source markup with the view presented in the browser
The opening <h1> and closing </h1> tags are wrapped around the words “The Most
Basic Web Page in the World,” making that the main heading for the page. In the
same way, the p elements contain the text in the two paragraphs.
A Case of Keeping Low
The tags are all lowercase. All of our attribute names will be in lowercase, too.
Many older HTML documents include tags and attributes in uppercase, but this
isn’t allowed in XHTML.
Headings and Document Hierarchy
In the example above, we use an h1 element to show a major heading. If we wanted
to include a subheading beneath this heading, we would use the h2 element. A
subheading under an h2 would use an h3 element, and so on, until we get to h6.
9 http://reference.sitepoint.com/html/h1/
10 http://reference.sitepoint.com/html/p/
Order the print version of this book to get all 400+ pages!
34 Build Your Own Web Site The Right Way Using HTML & CSS
The lower the heading level, the lesser its importance and the smaller the font size
(unless you have re-styled the headings with CSS, but more of that in Chapter 3).
With headings, an important and commonsense practice is to ensure that they do
not jump out of sequence. In other words, you should start from level one, and work
your way down through the levels in numerical order. You can jump back up from
a lower-level heading to a higher one, provided that the content under the higher-
level heading to which you’ve jumped does not refer to concepts that are addressed
under the lower-level heading. It may be useful to visualize your headings as a list:
■ First Major Heading
■ First Subheading
■ Second Subheading
■ A Sub-subheading
■ Another Major Heading
■ Another Subheading
Here’s the XHTML view of the example shown above:
<h1>First Major Heading</h1>
<h2>First Subheading</h2>
<h2>Second Subheading</h2>
<h3>A Sub-subheading</h3>
<h1>Another Major Heading</h1>
<h2>Another Subheading</h2>
Paragraphs
Of course, no one wants to read a document that contains only headings—you need
to put some text in there. The element we use to deal with blocks of text is the p
element. It’s not difficult to remember, as p is for paragraph. That’s just as well,
because you’ll almost certainly find yourself using this element more than any
other. And that’s the beauty of XHTML: most elements that you use frequently are
either very obvious, or easy to remember once you’re introduced to them.
For People Who Love Lists
Let’s imagine that you want a list on your web page. To include an ordered list (the
HTML term for a numbered list) of items, we use the ol element. An unordered
list—known as bullet points to the average person—makes use of the ul element.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 35
In both types of list, individual points or list items are specified using the li element.
So we use ol for an ordered list, ul for an unordered list, and li for a list item.
Simple.
To see this markup in action, type the following into a new text document, save it
as lists.html, and view it in the browser by double-clicking on the saved file’s icon:
lists.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Lists - an introduction</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<h1>Lists - an introduction </h1>
<p>Here's a paragraph. A lovely, concise little paragraph.</p>
<p>Here comes another one, followed by a subheading.</p>
<h2>A subheading here</h2>
<p>And now for a list or two:</p>
<ul>
<li>This is a bulleted list</li>
<li>No order applied</li>
<li>Just a bunch of points we want to make</li>
</ul>
<p>And here's an ordered list:</p>
<ol>
<li>This is the first item</li>
<li>Followed by this one</li>
<li>And one more for luck</li>
</ol>
</body>
</html>
How does it look to you? Did you type it all out? Remember, if it seems like a hassle
to type out the examples, you can find all the markup in the code archive, as I ex
plained in the preface. However, bear in mind that simply copying and pasting
markup, then saving and running it, doesn’t really give you a feel for creating your
own web site—it really will pay to learn by doing. Even if you make mistakes, it’s
still a better way to learn (you’ll be pleased when you can spot and fix your own
Order the print version of this book to get all 400+ pages!
36 Build Your Own Web Site The Right Way Using HTML & CSS
errors yourself). When displayed in a browser, the above markup should look like
the page shown in Figure 2.9.
There are many, many different elements that you can use on your web page, and
we’ll learn more of them as our web site development progresses. As well as the
more obvious elements that you’ll come across, there are others that are not imme
diately clear-cut: for example, what would you use div, span, or a elements for?
Any guesses? All will be revealed in good time.
Figure 2.9. Using unordered and ordered lists to organize information
Commenting Your HTML
Back in the garage, you’re doing a little work on your project car and, as you prepare
to replace the existing tires with a new set, you notice that your hubcaps aren’t
bolted on: you’d stuck them to the car with nothing more than super glue. There
must have been a good reason for doing that, but you can’t remember what it was.
The trouble is, if you had a reason to attach the hubcaps that way before, surely you
should do it the same way again. Wouldn’t it be great if you’d left yourself a note
when you first did it, explaining why you used super glue instead of bolts? Then
again, your car wouldn’t look very nice with notes stuck all over it. What a quandary.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 37
When you’re creating a web site, you may find yourself in a similar situation. You
might build a site then not touch it again for six months. Then when you revisit the
work, you might find yourself going through the all-too-familiar head-scratching
routine. Fortunately, there is a solution.
XHTML—like most programming and markup languages—allows you to use com
ments.11 Comments are perfect for making notes about something you’ve done and,
though they’re included within your code, comments do not affect the on-screen
display. Here’s an example of a comment:
comments.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Comment example</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<p>I really, <em>really</em> like this XHTML stuff.</p>
<!-- Added emphasis using the em element. Handy one, that. -->
</body>
</html>
Figure 2.10 shows the page viewed on-screen.
Figure 2.10. The comment remains hidden in the on-screen display
Comments must start with <!--, after which you’re free to type whatever you like
as a “note to self.” Well, you’re free to type almost anything: you cannot type double
11 http://reference.sitepoint.com/html/html-xhtml-syntax#html-xhtml-syntax__sect-comments
Order the print version of this book to get all 400+ pages!
38 Build Your Own Web Site The Right Way Using HTML & CSS
dashes. Why not? Because that’s a signal that the comment is about to end—the -->
part.
Oh, and did you spot how we snuck another new element in there? The emphasis
element, denoted with the <em> and </em> tags, is used wherever ... well, do I really
need to tell you? Actually, that last question was there to illustrate this point: did
you notice that the word “really” appeared in italics? Read that part to yourself
now, and listen to the way it sounds in your head. Now you know when to use the
em element.
Using Comments to Hide Markup from Browsers Temporarily
There is no limit to the amount of information you can put into a comment, and
this is why comments are often used to hide a section of a web page temporarily.
Commenting may be preferable to deleting content, particularly if you want to put
that information back into the web page at a later date (if it’s in a comment, you
won’t have to re-type it). This is often called “commenting out” markup. Here’s an
example:
commentout.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Commenting out XHTML</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<h1>Current Stock</h1>
<p>The following items are available for order:</p>
<ul>
<li>Dark Smoke Window Tinting</li>
<li>Bronze Window Tinting</li>
<!-- <li>Spray mount</li>
<li>Craft knife (pack of 5)</li> -->
</ul>
</body>
</html>
Figure 2.11 shows how the page displays in Firefox.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 39
Figure 2.11. The final, commented list items are not displayed
Remember, you write a comment like this: <!--Your comment here followed by
the comment closer, two dashes and a right-angled bracket-->.
Symbols
Occasionally, you may need to include the greater-than (>) or less-than (<) symbols
in the text of your web pages. The problem is that these symbols are also used to
denote tags in XHTML. So, what can we do? Thankfully, we can use special little
codes called entities in our text instead of these symbols. The entity for the greater-
than symbol is &gt;—we can substitute it for the greater-than symbol in our text,
as shown in the following simple example. The result of this markup is shown in
Figure 2.12.
entity.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Stock Note</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<p>Our current stock of craft knives &gt;
OUT OF STOCK (more due in 3 days)</p>
</body>
</html>
Order the print version of this book to get all 400+ pages!
40 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 2.12. The &gt; entity is displayed as > in the browser
Many different entities are available for a wide range of symbols, most of which
don’t appear on your keyboard. They all start with an ampersand (&) and end with
a semicolon. Some of the most common are shown in Table 2.1.
Table 2.1. Some common entities
Symbol (displayed on screen)Entity (used in markup)
>&gt;
<&lt;
&&amp;
£&pound;
©&copy;
™&trade;
Diving into Our Web Site
So far, we’ve looked at some very basic web pages as a way to ease you into the
process of writing your own XHTML markup. Perhaps you’ve typed them up and
tried them out, or maybe you’ve pulled the pages from the code archive and run
them in your browser. Perhaps you’ve even tried experimenting for yourself—it’s
good to have a play around. None of the examples shown so far are worth keeping,
though. You won’t need to use any of these pages, but you will be using the ideas
that we’ve introduced in them as you start to develop the fictitious project we’ll
complete in the course of this book: a web site for a local diving club.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 41
The diving club comprises a group of local enthusiasts, and the web site will provide
a way for club members to:
■ share photos from previous dive trips
■ stay informed about upcoming dive trips
■ provide information about ad-hoc meet-ups
■ read other members’ dive reports and write-ups
■ announce club news
The site also has the following goals:
■ to help attract new members
■ to provide links to other diving-related web sites
■ to provide a convenient way to search for general diving-related information
The site’s audience may not be enormous, but the regular visitors and club members
are very keen to be involved. It’s a fun site that people will want to come back to
again and again, and it’s a good project to work on. But it doesn’t exist yet. You’re
going to start building it right now. Let’s start with our first page: the site’s home
page.
The Homepage: the Starting Point for All Web Sites
At the very beginning of this chapter, we looked at a basic web page with nothing
on it (the car chassis with no bodywork or interior). You saved the file as basic.html.
Open that file in your text editor now, and strip out the following:
■ the text contained within the opening <title> and closing </title> tags
■ all the content between the opening <body> and closing </body> tags
Save the file as index.html.
Order the print version of this book to get all 400+ pages!
42 Build Your Own Web Site The Right Way Using HTML & CSS
Here’s the markup you should have in front of you now:
index.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title></title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
</body>
</html>
Let’s start building this web site, shall we?
Setting a Title
Remembering what we’ve learned so far, let’s make a few changes to this document.
Have a go at the following:
■ Change the title of the page to read “Bubble Under—The diving club for the
south-west UK.”
■ Add a heading to the page—a level one heading—that reads “BubbleUnder.com.”
■ Immediately after the heading, add a paragraph that reads, “Diving club for the
south-west UK—let’s make a splash!” (This is your basic, marketing-type tag
line, folks.)
Once you make these changes, your markup should look something like this (the
changes are shown in bold):
index.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Bubble Under—The diving club for the south-west
UK</title>
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 43
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<h1>BubbleUnder.com</h1>
<p>Diving club for the south-west UK—let's make a
splash!</p>
</body>
</html>
Save the page, then double-click on the file to open it in your chosen browser. Fig
ure 2.13 shows what it should look like.
Figure 2.13. Displaying our work on the homepage
Welcoming New Visitors
Now, let’s expand upon our tag line a little. We’ll add a welcoming subheading—a
second level heading—to the page, along with an introductory paragraph:
index.html (excerpt)
<body>
<h1>BubbleUnder.com</h1>
<p>Diving club for the south-west UK - let's make a splash!</p>
<h2>Welcome to our super-dooper Scuba site</h2>
<p>Glad you could drop in and share some air with us! You've
passed your underwater navigation skills and successfully
found your way to the start point - or in this case, our
home page.</p>
</body>
Apologies for the diving terminology puns, they’re truly cringe-worthy!
Order the print version of this book to get all 400+ pages!
44 Build Your Own Web Site The Right Way Using HTML & CSS
Hey! Where’d It All Go?
You’ll notice that we didn’t repeat the markup for the entire page in the above
example. Why? Because paper costs money, trees are beautiful, and you didn’t
buy this book for weight-training purposes. In short, we won’t repeat all the markup
all the time; instead, we’ll focus on the parts that have changed or have been added
to. And remember: if you think you’ve missed something, don’t worry. You can
find all of the examples in the book’s code archive.
Once you’ve added the subheading and the paragraph that follows it, save your
page once more, then take another look at it in your browser (either hit the refresh/re
load button in your browser, or double-click on the file icon in the location at which
you saved it). You should be looking at something like the display shown below in
Figure 2.14.
Figure 2.14. The homepage taking shape
So, the homepage reads a lot like many other homepages at this stage: it has some
basic introductory text to welcome visitors, but not much more. But what exactly
is the site about? Or, to be more precise, what will it be about once it’s built?
What’s It All About?
Notice that, despite our inclusion of a couple of headings and a couple of paragraphs,
there is little to suggest what this site is about. All visitors know so far is that the
site’s about diving. Let’s add some more explanatory text to the page, along with
some contact information:
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 45
■ Beneath the content you already have on the page, add another heading: this
time, make it a level three heading that reads, “About Us” (remember to include
both the opening and closing tags for the heading element).
■ Next, add the following text. Note that there is more than one paragraph.
Bubble Under is a group of diving enthusiasts based in the south
west UK who meet up for diving trips in the summer months
when the weather is good and the bacon rolls are flowing. We
arrange weekends away as small groups to cut the costs of accom
modation and travel, and to ensure that everyone gets a trust
worthy dive buddy.
Although we’re based in the south-west, we don’t stay on our
own turf: past diving weekends have included trips up to Scapa
Flow in Scotland and to Malta’s numerous wreck sites.
When we’re not diving, we often meet up in a local pub to talk
about our recent adventures (any excuse, eh?).
Save Yourself Some Trouble
If you don’t feel like typing out all this content, you can paraphrase, or copy
it from the code archive. I’ve deliberately chosen to put a realistic amount of
content on the page, so that you can see the effect of several paragraphs on
our display.
■ Next, add a Contact Us section, again, signified by a level three heading.
■ Finally, add some simple contact details as follows:
To find out more, contact Club Secretary Bob Dobalina on 01793
641207 or email bob@bubbleunder.com.
Order the print version of this book to get all 400+ pages!
46 Build Your Own Web Site The Right Way Using HTML & CSS
So, just to recap, we suggested using different heading levels to signify the import
ance of the different sections and paragraphs within the document. With that in
mind, you should have something much like the following markup in the body of
your document:
index.html (excerpt)
<h1>BubbleUnder.com</h1>
<p>Diving club for the south-west UK - let's make a splash!</p>
<h2>Welcome to our super-dooper Scuba site</h2>
<p>Glad you could drop in and share some air with us! You've
passed your underwater navigation skills and successfully
found your way to the start point - or in this case, our home
page.</p>
<h3>About Us</h3>
<p>Bubble Under is a group of diving enthusiasts based in the
south-west UK who meet up for diving trips in the summer
months when the weather is good and the bacon rolls are
flowing. We arrange weekends away as small groups to cut the
costs of accommodation and travel and to ensure that everyone
gets a trustworthy dive buddy.</p>
<p>Although we're based in the south-west, we don't stay on our
own turf: past diving weekends away have included trips up to
Scapa Flow in Scotland and to Malta's numerous wreck
sites.</p>
<p>When we're not diving, we often meet up in a local pub
to talk about our recent adventures (any excuse, eh?).</p>
<h3>Contact Us</h3>
<p>To find out more, contact Club Secretary Bob Dobalina on
01793 641207 or email bob@bubbleunder.com.</p>
You can see how our home page is shaping up in Figure 2.15.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 47
Figure 2.15. Viewing index.html
It’s still not very exciting, is it? Trust me, we’ll get there. The important thing to
focus on at this stage is what the content of your site should comprise, and how it
might be structured. We haven’t gone into great detail about document structure
yet, other than to discuss the use of different levels of headings, but we’ll be looking
at this in more detail later in this chapter. In the next chapter, we’ll see how you
can begin to style your document—that is, change the font, color, letter spacing and
more—but for now, let’s concentrate on the content and structure.
Order the print version of this book to get all 400+ pages!
48 Build Your Own Web Site The Right Way Using HTML & CSS
Clickable Email Links
It’s all well and good to put an email address on the page, but it’s hardly perfect.
To use this address, a site visitor would need to copy and paste the address into
an email message. Surely there’s a simpler way? There certainly is:
<p>To find out more, contact Club Secretary Bob Dobalina
on 01793 641207 or <a
href="mailto:bob@bubbleunder.com">email
bob@bubbleunder.com</a>.</p>
This clickable email link uses the a element, which is used to create links on web
pages (this will be explained later in this chapter). The mailto: prefix tells the
browser that the link needs to be treated as an email address (that is, the email
program should be opened for this link). The content that follows the mailto:
section should be a valid email address in the format username@domain.
Add this to the web page now, save it, then refresh the view in your browser. Try
clicking on the underlined text: it should open your email program automatically,
and display an email form in which the To: address is already completed.
The page so far seems a little boring, doesn’t it? Let’s sharpen it up a little. We can
only keep looking at a page of black and white for so long—let’s insert an image
into the document. Here’s how the img element is applied within the context of the
page’s markup:
index.html (excerpt)
<h2>Welcome to our super-dooper Scuba site</h2>
<p><img src="divers-circle.jpg" width="200" height="162"
alt="A circle of divers practice their skills"/></p>
<p>Glad you could drop in and share some air with us! You've
passed your underwater navigation skills and successfully
found your way to the start point - or in this case, our home
page.</p>
The img element is used to insert an image into our web page, and the attributes
src, alt, width, and height describe the image that we’re inserting. src is just the
name of the image file. In this case, it’s divers-circle.jpg, which you can grab from
the code archive. alt is some alternative text that can be displayed in place of the
image if, for some reason, it can’t be displayed. This is useful for blind visitors to
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 49
your site, search engines, and users of slow Internet connections. width and height
should be pretty obvious: they give the width and height of the image, measured in
pixels. We’ll cover pixels when we look into images in more detail a bit later.
Go and grab divers-circle.jpg from the code archive, and put it into your web site's
folder. The image is shown in Figure 2.16.
Figure 2.16. Divers pausing in a circle
Open index.html in your text editor and add the following markup just after the level
two heading (h2):
index.html (excerpt)
<p><img src="divers-circle.jpg" width="200" height="162"
alt="A circle of divers practice their skills"/></p>
Save the changes, then view the homepage in your browser. It should look like the
display shown in Figure 2.17.
Order the print version of this book to get all 400+ pages!
50 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 2.17. Displaying an image on the homepage
Adding Structure
Paragraphs? No problem. Headings? You’ve got them under your belt. In fact, you’re
now familiar with the basic structure of a web page. The small selection of tags that
we’ve discussed so far are fairly easy to remember, as their purposes are obvious
(remember: p = paragraph). But what on earth is a div?
A div is used to divide up a web page and, in doing so, to provide a definite structure
that can be used to great effect when combined with CSS.
When you place content inside a div, it has no effect on the styling of the text it
contains, except for the fact that it adds a break before and after the contained text.
Unlike a p element, the div does not add any margins or padding. Compare the
following:
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 51
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
<p>This is yet another paragraph.</p>
<p>And just one more paragraph.</p>
<div>This is a div.</div>
<div>The content of each div appears on a new line.</div>
<div>But unlike paragraphs, there is no additional padding.</div>
<div>A div is a generic block-level container.</div>
The difference can be seen in Figure 2.18.
Figure 2.18. Paragraphs have additional spacing above and below, unlike div elements
The purpose of a div is to divide (hence the abbreviation ‘div’) up a web page into
distinct sections—a basic structural framework with no styling—whereas p should
be used to create a paragraph of text.
Use Elements as Intended
Never use an XHTML element for a purpose for which it was not intended. This
really is a golden rule.
Order the print version of this book to get all 400+ pages!
52 Build Your Own Web Site The Right Way Using HTML & CSS
Rather than leaving the paragraph tags as they are, you might decide to have some
thing like this:
<div>
<p>This is a paragraph inside a div.</p>
<p>So is this.</p>
</div>
You can have as many paragraphs as you like inside that div element, but note that
you cannot place div elements inside paragraphs. Think of a div as a container
that’s used to group related items together, and you can’t go wrong.
If we look at our homepage in the browser, it’s possible to identify areas that have
certain purposes. These are listed below, and depicted in Figure 2.19. We have:
■ a header area that contains:
■ the site name
■ a tag line
■ an area of body content
Figure 2.19 shows how the different segments of content can be carved up into
distinct areas based on the purposes of those segments.
Take the homepage we’ve been working on (index.html) and, in your text editor of
choice, add <div> and </div> tags around the sections suggested in Figure 2.19.
While you’re adding those divs, add an id attribute to each, appropriately allocating
the names header, sitebranding, tagline, and bodycontent. Remember that attrib
ute names should be written in lowercase, and their values should be contained
within quotation marks.
No Sharing ids
id attributes are used in XHTML to uniquely identify elements, so no two elements
should share the same id value. You can use these ids later, when you’re dealing
with elements via CSS or JavaScript.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 53
Figure 2.19. Noting distinct sections in the basic web page
h1, header, and head
An id attribute set to header should not be confused with headings on the page
(h1, h2, and so on); nor is it the same as the head of your HTML page. The id=
attribute could just as easily have been named topstuff or pageheader. It
doesn’t matter, so long as the attribute name describes the purpose of that page
section to a fellow human being (or to yourself 12 months after you devised it,
and have forgotten what you were thinking at the time!).
To get you started, I’ve done a little work on the first part of the page. In the snippet
below, that section has been changed to a div with an id attribute:
index.html (excerpt)
<div id="header">
<h1>BubbleUnder.com</h1>
<p>Diving club for the south-west UK - let's make a splash!</p>
</div> <!-- end of header div -->
Now, try doing the same: apply divs to the parts of the content that we’ve identified
as “site branding” and “tag line.”
Order the print version of this book to get all 400+ pages!
54 Build Your Own Web Site The Right Way Using HTML & CSS
Nesting Explained
We already know that divs can contain paragraphs, but a div can also contain a
number of other divs. This is called nesting. It’s not tricky, it’s just a matter of putting
one div inside the other, and making sure you get your closing tags right. Nesting
elements can help to logically group sections of a web page together, just as you
might do in the real world by placing a selection of small boxes containing similar
items inside a larger box.
<div id="outer">
<div id="nested1">
<p>A paragraph inside the first nested div.</p>
</div>
<div id="nested2">
<p>A paragraph inside the second nested div.</p>
</div>
</div>
As Figure 2.19 shows, some nesting is taking place: the “site branding” and “tag
line” divs are nested inside the “header” div.
The Sectioned Page: All Divided Up
All things being well, your XHTML should now look like this:
index.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Bubble Under - The diving club for the south-west
UK</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
<h1>BubbleUnder.com</h1>
</div>
<div id="tagline">
<p>Diving club for the south-west UK - let's make
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)54 Build Your Own Web Site The Right Way Using HTML & CSS
Nesting Explained
We already know that divs can contain paragraphs, but a div can also contain a
number of other divs. This is called nesting. It’s not tricky, it’s just a matter of putting
one div inside the other, and making sure you get your closing tags right. Nesting
elements can help to logically group sections of a web page together, just as you
might do in the real world by placing a selection of small boxes containing similar
items inside a larger box.
<div id="outer">
<div id="nested1">
<p>A paragraph inside the first nested div.</p>
</div>
<div id="nested2">
<p>A paragraph inside the second nested div.</p>
</div>
</div>
As Figure 2.19 shows, some nesting is taking place: the “site branding” and “tag
line” divs are nested inside the “header” div.
The Sectioned Page: All Divided Up
All things being well, your XHTML should now look like this:
index.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Bubble Under - The diving club for the south-west
UK</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
<h1>BubbleUnder.com</h1>
</div>
<div id="tagline">
<p>Diving club for the south-west UK - let's make
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 55
a splash!</p>
</div>
</div> <!-- end of header div -->
<div id="bodycontent">
<h2>Welcome to our super-dooper Scuba site</h2>
<p><img src="divers-circle.jpg" width="200" height="162"
alt="A circle of divers practice their skills"/></p>
<p>Glad you could drop in and share some air with us! You've
passed your underwater navigation skills and
successfully found your way to the start point - or in
this case, our home page.</p>
<h3>About Us</h3>
<p>Bubble Under is a group of diving enthusiasts based in
the south-west UK who meet up for diving trips in the
summer months when the weather is good and the bacon
rolls are flowing. We arrange weekends away as small
groups to cut the costs of accommodation and travel and
to ensure that everyone gets a trustworthy dive
buddy.</p>
<p>Although we're based in the south-west, we don't stay on
our own turf: past diving weekends away have included
trips up to Scapa Flow in Scotland and to Malta's
numerous wreck sites.</p>
<p>When we're not diving, we often meet up in a local pub
to talk about our recent adventures (any excuse,
eh?).</p>
<h3>Contact Us</h3>
<p>To find out more, contact Club Secretary Bob Dobalina on
01793 641207 or
<a href="mailto:bob@bubbleunder.com">email
bob@bubbleunder.com</a>.</p>
</div> <!-- end of bodycontent div -->
</body>
</html>
Order the print version of this book to get all 400+ pages!
56 Build Your Own Web Site The Right Way Using HTML & CSS
Indenting Your Markup
It’s a good idea to indent your markup when nesting elements on a web page, as
is demonstrated with the items inside the div section above. Indenting your code
can help resolve problems later, as you can more clearly see which items sit inside
other items. Note that indenting is only really useful for the person—perhaps just
you—who’s looking at the source markup. It does not affect how the browser in
terprets or displays the web page.12
Notice that, in the markup above, comments appear after some of the closing div
tags. These comments are optional, but again, commenting is a good habit to get
into as it helps you fix problems later. Often, it’s not possible to view your opening
and closing <div> tags in the same window at the same time, as they’re wrapped
around large blocks of XHTML. If you have several nested <div> tags, you might
see something like this at the end of your markup:
</div>
</div>
</div>
In such cases, you might find it difficult to work out which div is being closed off
at each point. It may not yet be apparent why this is important or useful, but once
we start using CSS to style our pages, errors in the XHTML can have an impact.
Adding some comments here and there can really help you debug later.
</div> <!-- end of inner div -->
</div> <!-- end of nested div -->
</div> <!-- end of outer div -->
How does the web page look? Well, we’re not going to include a screen shot this
time, because adding those div elements should make no visual difference at all.
The changes we just made are structural ones that we’ll build on later.
12 The one exception to this is the pre element. Pre is short for pre-formatted, and any text marked
up with this element appears on the screen exactly as it appears in the source; in other words, carriage
returns, spaces, and any tabs that you’ve included will be evident. The pre element is usually used
to show code examples.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 57
Show a Little Restraint
Don’t go overboard adding divs. Some people can get carried away as they section
off the page, with <div> tags appearing all over the place. Overly enthusiastic
use of the div can result in a condition that has become known as “div-itis.” Be
careful not to litter your markup with superfluous <div> tags just because you
can.
Splitting Up the Page
We’ve been making good progress on our fictitious site ... but is a web site really a
web site when it contains only one page? Just as the question, “Can you have a
sentence with just one word?” can be answered with a one-word sentence (“Yes”),
so too can the question about our one-page web site. But you didn’t buy this book
to learn how to create a one-page web site, did you?
Let’s take a look at how we can split the page we’ve been working on into separate
entities, and how these pages relate to each other.
First, let’s just ensure that your page is in good shape before we go forward. The
page should reflect the markup shown in the last large block presented in the pre
vious section (after we added the <div> tags). If not, go to the code archive and grab
the version that contains the divs (/chapter2/website_files/06_adding_struc
ture_with_divs/index.html). Save it as index.html in your web site’s folder (if you see
a prompt that asks whether you want to overwrite the existing file, click Yes).
Got that file ready? Let’s break it into three pages. First, make two copies of the file:
■ Click on the index.html icon in Windows Explorer or Finder.
■ To copy the file, select Edit > Copy.
■ To paste a copy in the same location, select Edit > Paste.
■ Repeat the process once more.
You should now have three HTML files in the folder that holds your web site files.
The index.html file should stay as it is for the time being, but take a moment to rename
the other two in lowercase only. Select each file in turn, choosing File > Rename, if
you’re using Windows; Mac users, simply select the file by clicking on it, then hit
Return to edit the filename.
Order the print version of this book to get all 400+ pages!
58 Build Your Own Web Site The Right Way Using HTML & CSS
■ Rename one file as contact.html.
■ Rename the other one as about.html.
Where’s My File Extension?
If your filename appears as just index in Windows Explorer, your system is cur
rently set up to hide extensions for files that Windows recognizes. To make the
extensions visible, follow these simple steps:
1. Launch Windows Explorer.
2. Vista users, select Organize > Folder and Search Options...; Windows XP users,
select Tools > Folder Options...
3. Select the View tab.
4. In the Advanced Settings group, make sure that Hide extensions for known file types
does not have a tick next to it.
We have three identical copies of our XHTML page. Now, we need to edit the content
of these pages so that each page includes only the content that’s relevant to that
page.
To open an existing file in Notepad, select File > Open..., and in the window that
appears, change Files of type to All Files. Now, when you go to your Web folder, you’ll
see that all the files in that folder are available for opening.
Opening a file in TextEdit is a similar process. Select File > Open... to open a file,
but make sure that Ignore rich text commands is checked.
In your text editor, open each page in turn and edit them as follows (remembering
to save your changes to each before you open the next file):
index.html Delete the “About Us” and “Contact Us” sections (both the head
ings and the paragraphs that follow them), ensuring that the rest
of the markup remains untouched. Be careful not to delete the
<div> and </div> tags that enclose the body content.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 59
about.html Delete the introductory spiel (the level two heading and associated
paragraphs, including the image) and remove the “Contact Us”
section (including the heading and paragraphs).
contact.html You should be getting the hang of this now. This time, we’re re
moving the introductory spiel and the “About Us” section. (If
you’re not sure you’ve got it right, keep reading: we’ll show the
altered markup in a moment.)
Now, each of the three files contains the content that suits its respective filename,
but a further change is required for the two newly created files. Open about.html in
your text editor and make the following amendments:
■ Change the contents of the title element to read “About BubbleUnder.com:
who we are; what this site is for.”
■ Change the level three heading <h3>About Us</h3> to a level two heading. In
the process of editing our original homepage, we’ve lost one of our heading
levels. Previously, the “About Us” and “Contact Us” headings were marked up
as level three headings that sat under the level two “Welcome” heading. It’s not
good practice to skip heading levels—an h2 following h1 is preferable to an h3
following an h1.
Next, open contact.html in your text editor and make the following changes:
■ Amend the contents of the title element to read, “Contact Us at Bubble Under.”
■ Change the level three heading to a level two heading, as you did for about.html.
If everything has gone to plan, you should have three files named index.html,
about.html, and contact.html.
Order the print version of this book to get all 400+ pages!Your First Web Pages 59
about.html Delete the introductory spiel (the level two heading and associated
paragraphs, including the image) and remove the “Contact Us”
section (including the heading and paragraphs).
contact.html You should be getting the hang of this now. This time, we’re re
moving the introductory spiel and the “About Us” section. (If
you’re not sure you’ve got it right, keep reading: we’ll show the
altered markup in a moment.)
Now, each of the three files contains the content that suits its respective filename,
but a further change is required for the two newly created files. Open about.html in
your text editor and make the following amendments:
■ Change the contents of the title element to read “About BubbleUnder.com:
who we are; what this site is for.”
■ Change the level three heading <h3>About Us</h3> to a level two heading. In
the process of editing our original homepage, we’ve lost one of our heading
levels. Previously, the “About Us” and “Contact Us” headings were marked up
as level three headings that sat under the level two “Welcome” heading. It’s not
good practice to skip heading levels—an h2 following h1 is preferable to an h3
following an h1.
Next, open contact.html in your text editor and make the following changes:
■ Amend the contents of the title element to read, “Contact Us at Bubble Under.”
■ Change the level three heading to a level two heading, as you did for about.html.
If everything has gone to plan, you should have three files named index.html,
about.html, and contact.html.
Order the print version of this book to get all 400+ pages!
60 Build Your Own Web Site The Right Way Using HTML & CSS
The markup for each should be as follows:
index.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Bubble Under - The diving club for the south-west
UK</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
<h1>BubbleUnder.com</h1>
</div>
<div id="tagline">
<p>Diving club for the south-west UK - let's make a
splash!</p>
</div>
</div> <!-- end of header div -->
<div id="bodycontent">
<h2>Welcome to our super-dooper Scuba site</h2>
<p><img src="divers-circle.jpg"
alt="A circle of divers practice their skills"
width="200" height="162"/></p>
<p>Glad you could drop in and share some air with us! You've
passed your underwater navigation skills and
successfully found your way to the start point - or in
this case, our home page.</p>
</div> <!-- end of bodycontent div -->
</body>
</html>
about.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>About Bubble Under: who we are, what this site is
for</title>
<meta http-equiv="Content-Type"
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 61
content="text/html; charset=utf-8"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
<h1>BubbleUnder.com</h1>
</div>
<div id="tagline">
<p>Diving club for the south-west UK - let's make a
splash!</p>
</div>
</div> <!-- end of header div -->
<div id="bodycontent">
<h2>About Us</h2>
<p>Bubble Under is a group of diving enthusiasts based in
the south-west UK who meet up for diving trips in the
summer months when the weather is good and the bacon
rolls are flowing. We arrange weekends away as small
groups to cut the costs of accommodation and travel and
to ensure that everyone gets a trustworthy dive
buddy.</p>
<p>Although we're based in the south-west, we don't stay on
our own turf: past diving weekends away have included
trips up to Scapa Flow in Scotland and to Malta's
numerous wreck sites.</p>
<p>When we're not diving, we often meet up in a local pub
to talk about our recent adventures (any excuse,
eh?).</p>
</div> <!-- end of bodycontent div -->
</body>
</html>
contact.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Contact Us at Bubble Under</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
Order the print version of this book to get all 400+ pages!Your First Web Pages 61
content="text/html; charset=utf-8"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
<h1>BubbleUnder.com</h1>
</div>
<div id="tagline">
<p>Diving club for the south-west UK - let's make a
splash!</p>
</div>
</div> <!-- end of header div -->
<div id="bodycontent">
<h2>About Us</h2>
<p>Bubble Under is a group of diving enthusiasts based in
the south-west UK who meet up for diving trips in the
summer months when the weather is good and the bacon
rolls are flowing. We arrange weekends away as small
groups to cut the costs of accommodation and travel and
to ensure that everyone gets a trustworthy dive
buddy.</p>
<p>Although we're based in the south-west, we don't stay on
our own turf: past diving weekends away have included
trips up to Scapa Flow in Scotland and to Malta's
numerous wreck sites.</p>
<p>When we're not diving, we often meet up in a local pub
to talk about our recent adventures (any excuse,
eh?).</p>
</div> <!-- end of bodycontent div -->
</body>
</html>
contact.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Contact Us at Bubble Under</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
Order the print version of this book to get all 400+ pages!
62 Build Your Own Web Site The Right Way Using HTML & CSS
<h1>BubbleUnder.com</h1>
</div>
<div id="tagline">
<p>Diving club for the south-west UK - let's make a
splash!</p>
</div>
</div> <!-- end of header div -->
<div id="bodycontent">
<h2>Contact Us</h2>
<p>To find out more, contact Club Secretary Bob Dobalina on
01793 641207 or <a
href="mailto:bob@bubbleunder.com">email
bob@bubbleunder.com</a>.</p>
</div> <!-- end of bodycontent div -->
</body>
</html>
Linking Between Our New Pages
We’ve successfully created a three-page web site, but there’s a small problem: there
are no links between the pages. Try for yourself: open index.html in a web browser
and take a look at the display. How will you get from one page to another?
To enable site visitors to move around, we need to add navigation. Navigation relies
on anchors, which are more commonly referred to as links. The XHTML for an an
chor, or link, is as follows:
<a href="filename.html">Link text here</a>
The a element might not be intuitive (it stands for “anchor”), but you’ll get to know
this one very quickly: it’s what the Web is built on.
■ The a element contains the link text that will be clicked (which, by default, ap
pears on the screen as blue, underlined text).
■ The href attribute refers to the URL to which you’re linking (be that a file stored
locally on your computer, or a page on a live web site). Unfortunately, again,
href is not immediately memorable (it stands for “hypertext reference”), but
you’ll use it so often that you’ll soon remember it.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 63
Don’t Click Here!
The link text—the words inside the anchor element, which appear underlined on
the screen—should be a neat summary of that link’s purpose (for example, email
bob@bubbleunder.com). All too often, you’ll see people asking you to “Click here
to submit an image,” or “Click here to notify us of your change of address” when
"Submit an image,” or “Notify us of your change of address” more than suffices.
Never use “Click here” links—it really is bad linking practice and is discouraged
for usability and accessibility reasons.13
Let’s create a simple navigation menu that you can drop into your pages. Our nav
igation is just a list of three links. Here’s the markup:
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="about.html">About Us</a></li>
<li><a href="contact.html">Contact Us</a></li>
</ul>
We’ll place all of this inside a div, so we can quickly and easily see what this block
of XHTML represents.
<div id="navigation">
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="about.html">About Us</a></li>
<li><a href="contact.html">Contact Us</a></li>
</ul>
</div> <!-- end of navigation div -->
Now, we just need to paste this markup into an appropriate place on each of our
pages. A good position would be just after the header has finished, before the main
body content starts.
13 Why ‘Click here’ is bad linking practice [http://www.cs.tut.fi/~jkorpela/www/click.html], Jukka
Korpela.
Order the print version of this book to get all 400+ pages!
64 Build Your Own Web Site The Right Way Using HTML & CSS
In the code below, the navigation block appears in position on the homepage:
index.html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Bubble Under - The diving club for the south-west
UK</title>
<meta http-equiv="Content-Type" content="text/html;
charset=utf-8"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
<h1>BubbleUnder.com</h1>
</div>
<div id="tagline">
<p>Diving club for the south-west UK - let's make a
splash!</p>
</div>
</div> <!-- end of header div -->
<div id="navigation">
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="about.html">About Us</a></li>
<li><a href="contact.html">Contact Us</a></li>
</ul>
</div> <!-- end of navigation div -->
<div id="bodycontent">
<h2>Welcome to our super-dooper Scuba site</h2>
<p><img src="divers-circle.jpg" width="200" height="162"
alt="A circle of divers practice their skills"/></p>
<p>Glad you could drop in and share some air with us!
You've passed your underwater navigation skills and
successfully found your way to the start point - or in
this case, our home page.</p>
</div> <!-- end of bodycontent div -->
</body>
</html>
You should now be looking at a page like the one shown in Figure 2.20.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 65
Figure 2.20. Displaying simple navigation on the page
Add the block of links to contact.html and about.html, then try clicking on the links
that you’ve just added. It should be possible to flick between all three pages, as
shown in Figure 2.21.
This is a landmark: you’re now the creator of a working, navigable web site. Let's
now discuss a few more XHTML elements that you can add to your pages.
Order the print version of this book to get all 400+ pages!
66 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 2.21. Navigating the web site
The blockquote (Who Said That?)
We’re going to add a sound bite—well, a written quote, to be precise—to the About
Us page. Here are the lines:
“Happiness is a dip in the ocean followed by a pint or two of Old
Speckled Hen. You can quote me on that!”
We’ll add the quote after the final paragraph in about.html using a blockquote14
element; here’s the markup you’ll need:
about.html (excerpt)
<blockquote>
<p>"Happiness is a dip in the ocean followed by a pint or two of
Old Speckled Hen. You can quote me on that!"</p>
</blockquote>
14 http://reference.sitepoint.com/html/blockquote/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 67
Or is it? Who’s doing the talking? Well, it’s our dear (fictional) Club Secretary, Bob
Dobalina:
about.html (excerpt)
<p>Or as our man Bob Dobalina would put it:</p>
<blockquote>
<p>"Happiness is a dip in the ocean followed by a pint or two of
Old Speckled Hen. You can quote me on that!"</p>
</blockquote>
The quotation can contain as many paragraphs as you like, as long as each one starts
and ends correctly, and the opening <blockquote> tag is closed off properly.
Figure 2.22 shows how the blockquote above will appear on the page.
Figure 2.22. Displaying a quotation on the page
Order the print version of this book to get all 400+ pages!
68 Build Your Own Web Site The Right Way Using HTML & CSS
Displaying blockquotes
In most browsers, your use of blockquote will see the quoted text indented in
the page display. This effect can be overridden if it’s not to your taste, but that’s
something we’ll cover in a later chapter. On the flip side, you should never use
the blockquote element for the purposes of indenting text. This is very poor
form. Only use blockquote for its intended purpose: to present a quotation.
There are other, better ways to create visual indentations, namely CSS.
The cite Element
If the quote to which you’ve referred is written elsewhere—in a magazine, for in
stance, or a book, or even your own web site—you can add some information to
communicate the quote’s source. One way is to use the cite element. A citation,
by default, will style the text in italics. Here’s how the markup would look for a
citation:
<p>I remember reading <cite>Salem's Lot</cite> by Stephen King as
a child, and being very scared of the dark for days after.</p>
So what do we do if something is both a quotation and a citation? The blockquote
element has a cite attribute for this very purpose:
<blockquote cite="http://www.petermoore.net/sftb/chapter1.htm">
<p>It didn't take long for a daily routine to form: when they
left for work in the morning I'd still be in bed. And when
they came home they'd find me sitting on the sofa, drinking
beer and watching TV soaps.</p>
</blockquote>
We’re not using the cite element (or the cite attribute) in the diving web site, but
you may find them useful in your own web site projects.
strong and em
We mentioned the em element earlier in this chapter. It’s a fairly straightforward
element to remember. If you can imagine yourself adding some kind of inflection
as you say a word, then emphasis is probably what you need. If you’re looking to
strike a slightly more forceful tone, then you should consider “going in strong”.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Your First Web Pages 69
By default, adding em will style text in italics, while using strong makes the text
bold. You can combine the two if you want, but usually, one or the other will suffice.
The examples below should help you understand what these elements are used for.
Figure 2.23 shows how they appear in the browser.
<p>Although Jimmy was told to <strong>never</strong> put his hands
on the exhaust pipe, he <em>still</em> couldn't help
himself.</p>
Figure 2.23. Displaying different emphasis styles in the browser
Taking a Break
The chapter’s almost at an end, so why take a break? Well, this is just an excuse for
a headline pun. We have one more element to look at: the break element.
The break element (br)15 basically replicates what happens when you hit the carriage
return on an old typewriter. To create a paragraph on an old typewriter, you’d hit
Enter twice to give the necessary spacing. In XHTML, the fact that you’re marking
up a paragraph with <p> and </p> tags means the spacing is worked out for you
automatically. However, if you just want to signify the start of a new line, rather
than a new paragraph, the element you need is br, as demonstrated in this limerick:16
<p>The limerick packs laughs anatomical,<br/>
Into space that is quite economical.<br/>
But the good ones I've seen,<br/>
So seldom are clean,<br/>
And the clean ones so seldom are comical.</p>
15 http://reference.sitepoint.com/html/br/
16 http://en.wikipedia.org/wiki/Limerick_(poetry)
Order the print version of this book to get all 400+ pages!
70 Build Your Own Web Site The Right Way Using HTML & CSS
Avoid Multiple Breaks
It’s all too easy to resort to using multiple breaks in a web page to achieve a visual
effect. If you find yourself doing this, something’s wrong: you almost certainly
need to look for a more suitable technique (we’ll look at how this visual effect
should be achieved later). Be careful in your use of br.
Note that br is an empty element, just like meta and img, so in XHTML it’s written
as <br/>.
Summary
Wow—what a great start we’ve made. In this chapter, you’ve built a single web page
gradually into three linked pages. You’ve become familiar with the most commonly
used XHTML tags, as well as some of the less common ones that you can apply to
your web pages. But, somehow, despite all your efforts, the web pages are still
looking a little on the bland side. We’re going to fix that very soon: in the next
chapter, we’ll start to add some splashes of color, and make the site look a little
more like a fun diving site and less like a boring old Word document.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Chapter
3
Adding Some Style
In Chapter 1 and Chapter 2, we stepped through the process of setting up your
computer so that we could develop web sites, and pulled together the beginnings
of a web site with which you could impress your friends and family. The trouble
is, when you came to show off your fledgling site to your nearest and dearest, they
weren’t that impressed. What have you done wrong?
The answer is: nothing. It’s true that the web site may look a little bland at present,
but the underlying structure on which it’s built is rock-solid. To return to our
automotive analogy, you now have a perfect chassis and some decent bodywork,
and, while your car’s not making people turn their heads just yet, it’s only a matter
of time. Just let them see what you can do with this rolling shell!
In this chapter, we’ll begin the process of adding that lick of paint to your site. The
tool for the job is Cascading Style Sheets—CSS to those in the know (or with limited
typing abilities). Let’s take a look at what CSS can do for you.
72 Build Your Own Web Site The Right Way Using HTML & CSS
What is CSS?
As this chapter revolves almost exclusively around CSS, it’s probably a good idea
to begin with a basic discussion of what CSS is, and why you should use it. As
we’ve already mentioned, CSS stands for Cascading Style Sheets, but that’s too
much of a mouthful for most people—we’ll stick with the abbreviation.
CSS is a language that allows you to change the appearance of elements on the page:
the size, style, and color of text, background colors, border styles and colors—even
the position of elements on the page. Let’s take a look at some CSS in action; we’ll
start by learning about inline styles.
Inline Styles
If you’re familiar with Microsoft Word (or a similar word processing package), you
may well have created your fair share of flyers, advertisements, or personal news
letters (as well as the more mundane letters to the local authorities and so on). In
doing so, you’ve probably used text formatting options to color certain parts of your
text. It’s as simple as highlighting the words you want to change, then clicking on
a color in a drop-down palette. The same effect can be achieved in XHTML using
a little bit of inline CSS. This is what it looks like:
<p style="color: red;">The quick brown fox jumps over
the lazy dog.</p>
In the example above, we use a style attribute inside the opening <p> tag. Applying
a style to a specific XHTML element in this way is known as using an “inline style.”
But Wait a Minute: Inline Styles?
If you have dabbled with CSS before you may be thinking at this stage, “But this
isn’t the right way to do it," to which I say “Just wait a short while—all will be
explained soon." We just need to run through these basics first before approaching
the best way of doing this.
The style attribute can contain one or more declarations between its quotation
marks. A declaration is made up of two parts: a property, and a value for that
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 73
property. In the example above, the declaration is color: red (color being the
property and red being its value).
If you wanted to, you could add another declaration to the example above. For in
stance, as well as having the text display in red, you might want it to appear in a
bold typeface. The property that controls this effect is font-weight; it can have a
range of different values, but mostly you’ll use normal or bold. As you might expect,
you’d use the following markup to make the paragraph red and bold:
<p style="color: red; font-weight: bold;">The quick brown fox
jumps over the lazy dog.</p>
Notice that a semicolon separates the two declarations. You could carry on adding
styles in this way, but beware, this approach can be messy. There are cleverer ways
to apply styling, as we’ll see very soon.
Adding Inline Styles
Open about.html in your text editor, and add an inline style. We want to make the
text in the first paragraph after the “About Us” heading bold and blue. Refer to the
previous example as you create the style.
Does the markup for your paragraph look like this?
<p style="color: blue; font-weight: bold;">Bubble Under is a group
of diving enthusiasts based in the south-west UK who meet up
for diving trips in the summer months when the weather is good
and the bacon rolls are flowing. We arrange weekends away as
small groups to cut the costs of accommodation and travel and
to ensure that everyone gets a trustworthy dive buddy.</p>
If your markup looks like that shown here, save about.html and take a look at it in
your browser. It should appear like the page shown in Figure 3.1.
Order the print version of this book to get all 400+ pages!
74 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 3.1. Content displayed using blue and bold styles
The span Element
You can easily color a whole paragraph like this, but more often than not, you’ll
want to pick out just specific words to highlight within a paragraph. You can do
this using a span element, which can be wrapped around any content you like.
Unlike p, which means paragraph, or blockquote, which signifies a quotation, span
has no meaning. A span is little more than a tool for highlighting the start and end
of a section to which you want to apply a style.1 Instead of making that whole
paragraph blue, we might want just the first two words, “Bubble Under,” to be blue
and bold. Here’s how we can use the span element to achieve this:
<p><span style="color: blue; font-weight: bold;">Bubble
Under</span> is a group of diving enthusiasts based in the
south-west UK who meet up for diving trips in the summer
months when the weather is good and the bacon rolls are
flowing. We arrange weekends away as small groups to cut the
costs of accommodation and travel and to ensure that everyone
gets a trustworthy dive buddy.</p>
1 Applying a span also gives you the ability to do some other clever things to your web page using
JavaScript, but for our purposes, its scope is limited to what it allows you to do using CSS.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 75
When we view that markup in a browser, we see the display shown in Figure 3.2.
Figure 3.2. Using the span element to pick out specific words for styling
Let’s take a quick look at other ways that we can apply inline styles (don’t worry,
this isn’t part of our project site; feel free to experiment).
<p style="font-style: italic">The quick brown fox jumps over the
lazy dog.</p>
Not surprisingly, that CSS declaration will italicize all the text in the paragraph.
Here’s another example, in which span is used to highlight specific words:
<p>The quick brown fox <span style="font-style: italic;
font-weight: bold">jumps</span> over the lazy dog.</p>
Order the print version of this book to get all 400+ pages!
76 Build Your Own Web Site The Right Way Using HTML & CSS
Embedded Styles
Inline styles are a simple, quick way to apply some CSS effects to specific sections
of a document, but this is not the best method of styling a page. Wouldn’t it be better
if you could set styles in just one place, rather than having to type them out every
time you wanted to use them?
Embedded style sheets are a logical step up. An embedded style sheet is a section
you add to the start of a web page that sets out all the styles that will be used on
that page. To do this, you need to use the style2 element inside the head:
<head>
<title>Bubble Under - The diving club for the south-west
UK</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
<style type="text/css">
p {
font-weight: bold;
}
</style>
</head>
In the markup shown above, we’ve moved the inline style into an embedded style
sheet. The embedded style sheet starts with a <style type="text/css"> tag and,
predictably, ends with a </style> tag. The actual style declarations are enclosed
in a set of curly braces: { and }. The p that appears before the first curly brace tells
the browser what elements the style rules are for; in this case, we’re making the text
inside every p element bold. The p is called the selector, and it’s a great tool for
quickly and easily changing the appearance of lots of elements on your page. The
selector instructs the browser to apply all the declarations between the curly braces
to certain elements. The selector, curly braces, and declarations combine to form
what’s called a rule.
In this case, our style sheet contains one rule: “Please style all the paragraphs on
this page so that the text appears in a bold font.”
2 http://reference.sitepoint.com/html/style/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 77
If we wanted to, we could add more declarations to our rule. For instance, if we
wanted to make the text bold and blue, we’d add the declaration color: blue to
our rule:
<style type="text/css">
p {
font-weight: bold;
color: blue;
}
</style>
Jargon Break
Okay, okay. There’s been an awful lot of jargon so far. Let’s recap: Figure 3.3 brings
the theory into focus.
Figure 3.3. The anatomy of a rule
Why Embedded Styles Are Better than Inline Styles
In the example provided in Figure 3.3, text in all paragraphs will display in bold,
blue type. This is useful because it saves you having to type <p
style="font-weight: bold; color: blue"> every time you start a new para
graph—a clear benefit over inline styles.
Order the print version of this book to get all 400+ pages!
78 Build Your Own Web Site The Right Way Using HTML & CSS
If you wanted to change the color of all paragraphs text to red, you need only to
change it in the style sheet at the top of the page:
<style type="text/css">
p {
font-weight: bold;
color: red;
}
</style>
That’s efficiency for you. For this reason, an embedded style sheet is a marked im
provement over inline styles. But what if you have a web site that comprises many
pages? If you want to make your changes across the whole site, using embedded
style sheets in the way I demonstrated above is still not quite the perfect solution.
Why not? Because, to make a site-wide change, you’d have to edit the embedded
style sheet on every single page of that site. The best solution is to use an external
style sheet.
External Style Sheets
Why External Style Sheets Are Better than Embedded
Styles
An external style sheet provides a location in which you can place styles that can
be applied on all of your web pages. This is where the true power of CSS lies, and
it’s for this reason that we haven’t spent too much time applying inline styles or
embedded styles to our diving club project site.
The Bad Old Days
In the past, or The Bad Old Days as we’ll call them, people would create web sites
on a page-by-page basis, and style them on a page-by-page basis using all manner
of nasty elements of which I dare not even speak! Sometimes, these sites grew
beyond the webmaster’s wildest imagination. “Fantastic,” thought Mr or Mrs Web
master. “My web site now has over 200 pages! Soon I’ll be bigger than Microsoft.”
A few months later, the webmaster decided to redesign the web site and realized,
with considerable horror, that he or she would have to alter each and every single
web page in order to redesign the site in a consistent manner. Every page needed
20 or more different tweaks, and each tweak had to be applied consistently to every
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 79
page of the site. Inevitably, some pages were missed and eventually the redesign
plan was unceremoniously dropped. In short, the ugly web site remained ugly for
a whole lot longer before dying a nasty death through sheer negligence (indeed,
there are many such legacy documents littered around the Web today). This need
not be the case though.
CSS gives you the power to set styling rules in one place. When you want to make
changes to your web site, you make changes in that one place, and your whole web
site changes automatically to reflect those new styles.
Happy Days! CSS Support Is Here
The good news is that the large majority of web browsers in use today offer excellent
support for CSS (though this has not always been the case, which is why some
people were slow to adopt CSS-based design in the past). Some browsers can choke
on a few of the more advanced CSS techniques, but, by and large, you can style
your web pages using CSS and be confident that what you see on your screen is the
same view that 99.5% of your intended audience will see.
Creating an External CSS File
If you are to make use of all the benefits that an external style sheet can provide,
you’ll first need to create a CSS file that can be shared among all the pages of your
web site. Open your text editor and enter the following:
style1.css
/*
CSS for Bubble Under site
*/
p {
font-weight: bold;
color: blue;
}
Save the file in the same folder as your HTML files, naming it style1.css; you can
save a CSS file in the same way you saved your HTML files.
Note that the first few lines we typed into our CSS file will not actually do anything.
Like HTML, CSS allows you to add comments. It’s a shame that the tags for HTML
Order the print version of this book to get all 400+ pages!
80 Build Your Own Web Site The Right Way Using HTML & CSS
comments are different from those for CSS comments, but they perform exactly the
same function: they allow you to make notes about your work without affecting the
on-screen display. In CSS, a comment starts with a /* and ends with a */; the
browser ignores anything in between. Above, we used the comment simply to make
a note about the purpose of the file, namely that it is the CSS for the Bubble Under
site. We’ve also added a rule to turn the type in all our paragraphs bold and blue.
Linking CSS to a Web Page
Before your CSS can have any effect, you need to link it to the web page, or pages,
to which you want the styles to apply. To do this, you need to add a link3 element
to the head of each and every web page that will be styled using CSS. Our site con
tains just three pages at the moment, so this will be nice and easy. The link element
simply links a file to the page on which the element appears; in this case, the linked
file is a style sheet.
Below, the new line appears in the context of the homepage:
index.html (excerpt)
<head>
<title>Bubble Under - The diving club for the south-west
UK</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
<link href="style1.css" rel="stylesheet" type="text/css"/>
</head>
Let’s take a look at what the markup means.
The href attribute tells the web browser where the style sheet file (style1.css) can
be found, in the same way that the href attribute is used in an anchor to point to
the destination file (e.g. <a href="home.htm">Home</a>).
The rel="stylesheet" and type="text/css" parts of the link tag tell the browser
what kind of file is being linked to, and how the browser should handle the content.
You should always include these important attributes when linking to a .css file.
3 http://reference.sitepoint.com/html/link/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 81
Empty Element Alert!
The link element is another of those special empty elements we discussed in
Chapter 2: it does not have separate start and end tags. link is a complete element
in its own right, and ends using the space and forward slash required by XHTML.
Now that we know how to link our pages to our CSS file, let’s try it out on our
project site:
■ Open each of your web pages—index.html, about.html, and contact.html—in your
text editor. Add the following line just before the closing </head> tag in each of
those files:
<link href="style1.css" rel="stylesheet" type="text/css"/>
■ Be sure to save each page. Then, try opening each one in your web browser.
All of your paragraphs should now display in bold, blue text. If so, congratula
tions—you’ve now linked one style sheet to three separate pages. If you change the
color specified in your .css file from blue to red, you should see that change reflected
across your pages the next time you open them. Go ahead, give it a try.
Now, using blue, bold text might be a good way to make sure your style sheets are
correctly linked, but it’s not necessarily the design effect we want to use. Remove
the p rule from your style sheet, but leave the comment, and let’s start building our
style sheet for real.
Starting to Build Our Style Sheet
The style sheet is ready to be used: it’s saved in the right location, and all of your
web pages (all three—count ’em) are linked to it correctly. All we need to do is set
some styles.
One of the first changes that people often make to a web site’s default styling is to
alter the font (or typeface) that’s used. On Windows, most browsers use Times New
Roman as the default—it’s the font that has been used in all the screen shots we’ve
seen so far. For many people, though, it’s a little bit dull, probably because this font
Order the print version of this book to get all 400+ pages!
82 Build Your Own Web Site The Right Way Using HTML & CSS
is used more than any other. It’s very easy to change fonts using CSS’s font-family
property.
The best place to use this is within the body element, as shown below:
style1.css
/*
CSS for Bubble Under site
*/
body {
font-family: Verdana;
}
Here, I’ve chosen to use the Verdana font. It’s applied to the body element because
body contains every element that you will see on the web page. The nature of the
way in which CSS is applied means that every element contained in the body element
will take on the same font (unless another font is specified for a given element or
elements within body—but more on that a little later).
Great: Verdana it is! But ... what if some people who view your site don’t have
Verdana installed on their computers? Hmm, that’s a tricky one. The short answer
is that the browser will make its best guess about which font it should use instead,
but we don’t have to make the browser do all the guesswork. The font-family
property allows us to enter multiple fonts in the order in which we’d prefer them
to be used. So, we could type the following:
body {
font-family: Verdana, Helvetica, Arial, sans-serif;
}
This translates as: “Please style everything in the body of my web page so that the
text appears as Verdana. Failing that, please try using Helvetica and, failing that,
Arial. If none of the above are installed, just use whatever sans-serif font is available.”
We’ll use this selection of fonts in our diving site, so let’s open the style sheet file
and play around with some CSS.
■ Type the above CSS into style1.css.
■ Save the file, then open the homepage (index.html) in your browser.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 83
If everything went to plan, your web page (all three of them, actually) should display
slightly differently than they did before. Figure 3.4 shows the appearance of our
newly-styled homepage.
Figure 3.4. A font change in the style sheet affects the body of our web pages
Sans-serif Fonts: Better for On-screen Viewing
A serif font is one that has all those little flourishes at the ends of each letter.
These flourishes, which are shown in Figure 3.5, are known as serifs. They’re
great for reading printed material, as they give a little shape to the words, making
them easier to read.
However, on the screen, serif fonts can become a little messy, especially when
they’re used for smaller type—there simply aren’t enough pixels on the screen to
do these little flourishes justice. For this reason, you’ll notice that many web sites
use sans-serif fonts (from French, translating as “without serif”) when the font
size is set quite small.
Note that when you refer to a sans-serif font in CSS, you must hyphenate the two
words, i.e. sans-serif.
Order the print version of this book to get all 400+ pages!
84 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 3.5. Highlighting the serifs of a serif font (Georgia)
Stylish Headings
The first element that we’ll style is our level 1 headings, denoted by the h1 element.
Let’s add some rules to our CSS file to see what’s possible when it comes to those
headings. In your text editor, add the following to style1.css:
h1 {
font-family: "Trebuchet MS", Arial, Helvetica, sans-serif;
}
Save the CSS file and refresh your view of the homepage in your browser. Can you
see what’s changed? All the first-level headings now display in the Trebuchet MS
font, while everything else displays in Verdana.
The font we’ve chosen is another sans-serif font, but it’s different enough to provide
plenty of contrast with the paragraphs, as Figure 3.6 illustrates.
Some Font Names Deserve Quotes
In the code example above, “Trebuchet MS” appeared in quotation marks. You
don’t need to bother wrapping quote marks around font names, unless the font
comprises several words, such as “Courier New” or “Times New Roman.” A single-
word font name, such as Arial or Verdana, does not need to be wrapped inside
quotes.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 85
Figure 3.6. h1 headings displayed in one sans-serif font (Trebuchet MS) while paragraph text displayed in another
(Verdana)
Have a quick look around all three pages of the web site and you’ll see that your
new styles have been applied to all your web pages. Let’s go a step (or two) further.
What’s Going on? Nothing’s Changed!
If you try refreshing your browser’s view of a page and nothing appears to change,
first check that you saved the changes you made to the CSS file. If you have saved
the altered file, check that you typed the CSS exactly as described. If you did, you
may be experiencing a caching problem with your browser.
Web browsers “cache” some content. Caching is when your browser accesses files
previously saved to the hard drive when you visit a given web page, rather than
downloading new files each time. For example, you enter the URL, and the browser
pulls the page stored in its cache. This speeds up the process of displaying a web
page that has been loaded before. Unfortunately, your cache can soon become out
of-date, and when that happens, the page you visit might not display the most
recent data.
Order the print version of this book to get all 400+ pages!
86 Build Your Own Web Site The Right Way Using HTML & CSS
This happens most frequently with images, but it can also occur using CSS files.
The good news is that you have control over your browser’s cache settings.
Therefore, the amount of space the cache takes up on your hard disk before cached
content is replaced with newer data can be adjusted. You can poke around your
browser’s settings for terms like “Cache” or “Temporary Internet Files” to change
these settings; however, most users opt to leave their caches to the default settings.
If you’re positive that you’ve made the necessary changes to your CSS file (and
saved them) correctly, you may need to force-reload the CSS file in your browser.
To stop the caching problem and force the browser to retrieve the most up-to-date
version of your CSS file, simply hold down the Shift key and click on the Refresh
(or Reload) icon on your browser’s toolbar.
A Mixture of New Styles
Let’s change the look of the site a little more—we’ll add more styles to the body,
and change the look of the navigation. Copy the CSS below into your style1.css file
(or copy it from the book’s code archive):
style1.css
/*
CSS for Bubble Under site
*/
body {
font-family: Verdana, Helvetica, Arial, sans-serif;
background-color: #e2edff;
line-height: 125%;
padding: 15px;
}
h1 {
font-family: "Trebuchet MS", Helvetica, Arial, sans-serif;
font-size: x-large;
}
li {
font-size: small;
}
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 87
h2 {
color: blue;
font-size: medium;
font-weight: normal;
}
p {
font-size: small;
color: navy;
}
Save the CSS file, then click Reload (or Refresh) in your browser. Hopefully, you’ll
be looking at a page like the one shown in Figure 3.7.
Figure 3.7. Applying subtle changes to the CSS that affects the display of the font
Order the print version of this book to get all 400+ pages!
88 Build Your Own Web Site The Right Way Using HTML & CSS
A New Look in a Flash!
We’ve introduced quite a few new style declarations here. Let’s examine a few of
them in the order in which they appear in the CSS file:
style1.css (excerpt)
body {
font-family: Verdana, Helvetica, Arial, sans-serif;
background-color: #e2edff;
line-height: 125%;
padding: 15px;
}
The background-color property can be applied to most elements on a web page,
and there are many different ways in which you can specify the color itself. One is
to use recognized color names4 such as navy, blue, red, yellow, and so on. These
are easy to remember and spell, but you can be limited by the range. Another way
of referencing colors is to use a hexadecimal color specification. Yes, you’re right:
that does sound a little scary. I mean, just look at the code for it:
background-color: #e2edff;
It’s hardly intuitive, is it? This obscure-looking reference (#e2edff) translates to a
light shade of blue. You could not, as a beginner, begin to guess that this would be
a light blue. Thankfully there are numerous tools on the Web that let you choose a
color from a chart (often called a color picker), then give you the code to match.
Take a look at some of these tools,5 and you’ll soon be able to find the hexadecimal
numbers you need to create your ideal color schemes.
What the Heck’s Hex?
Colors in HTML are often written as a hexadecimal color specification. You might
remember the hexadecimal counting system from your high school math class.
Or maybe you were asleep up the back of the room. Never mind. Hexadecimal is
that weird counting system that goes up to 16 instead of 10; the one you thought
you’d never have any practical use for. Well, you do now!
4 http://reference.sitepoint.com/html/color-names
5 A good selection of links to color scheme tools is available at http://www.clagnut.com/blog/260/.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 89
That’s right: when you count in hexadecimal, there are not ten, but 16 digits. The
hexadecimal sequence looks like this:
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F, 10, 11, 12...
Eh? What’s happening here? Well, as you can see, after we reach 9, instead of going
straight to 10 (as we do when counting in decimal) we go through A, B, C, D, E,
and F before we finally hit 10. That gives us six extra digits to use when we count.
Sound confusing? Well, as it so happens, computers can count in hexadecimal
far better than humans can!
The key here is that all of those numbers that we know and love in the decimal
system, like 2,748, 15,000,000, and 42, can be represented in hexadecimal. And
Table 3.1 proves it!
Table 3.1. Decimal to Hexadecimal Conversion
HexadecimalDecimal
77
F15
ABC2,748
E4E1C015,000,000
2A42
When a color is expressed as a hexadecimal number, such as ff0000, that number
actually comprises three values that are joined together. The values represent the
proportions of red (the ff part), green (the first two zeros), and blue (the second
two zeros) that are mixed to create the specified color. Those three primary colors
can be combined to display any color on the screen, similar to the way a television
set uses different amounts of red, green, and blue to create a single dot on its
screen.6 In this example, ff is the value for red, while the green and blue values
are zero. It may not surprise you, then, to learn that #ff0000 will give you the
color red.
The line-height property is an interesting one. By increasing that value (we used
125% in our example), you can increase the space between lines of text—which
6 If you thought the primary colors were red, blue, and yellow you’re not wrong! Head over to
http://en.wikipedia.org/wiki/Primary_color to learn all about the additive and subtractive methods
of color mixing.
Order the print version of this book to get all 400+ pages!
90 Build Your Own Web Site The Right Way Using HTML & CSS
can greatly increase legibility. Try tweaking this value, save your CSS file, and see
how the new value affects the text on your web page.
The padding property is used to provide space between the outside edge of the
element in question and the content that sits inside it. Because we’re referring to
the body element, you can think of the outside edge as being the top, bottom, and
sides of the browser’s viewport (that being the part of the browser where the web
page is viewable, not including any of the browser’s tool bars, menus, or scroll bars).
We’ll take a look at padding in more detail in Chapter 4.
The value we’ve given to this property specifies how much space must exist between
the edge of the viewport and the content. In this case, we’ve specified 15px, or 15
pixels. We mentioned pixels before, when we specified the size of an image, but
what is a pixel? Basically, one pixel is one of the tiny dots that make up what you
see on the computer screen. The screen itself is made up of hundreds of thousands
of these pixels, so a 15-pixel border won’t take up too much space on your screen!
Now, to the paragraph styles:
style1.css (excerpt)
p {
font-size: small;
color: navy;
}
We’ve already shown that it’s possible to change the color of text in a paragraph;
now, we’re going to settle on the appropriate color of navy.
Let’s see what’s changed with the list item style:
style1.css (excerpt)
li {
font-size: small;
}
The size of the list items has changed ever so slightly through our application of
the font-size property. Here, we’ve decided to set the font size using the small
keyword, but we could just as easily have used the percentage or pixel methods.
As we’ve already seen—there are many ways to skin a cat using CSS! Font-size
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 91
keywords range from xx-small to xx-large and offer a quick way to style text.
Unfortunately, different browsers implement font-size keywords slightly differently,
and unfortunately you can’t be guaranteed that an xx-large font will render at the
same size in all browsers. However, unless you’re extremely worried about precise
sizing, these keywords make a good starting point.7
We’ve also introduced a new rule for the h1 element (the main heading on our web
pages, which displays the site name) and, once again, used a font-size property
to specify the size of the text (extra large!).
style1.css (excerpt)
h1 {
font-family: "Trebuchet MS", Helvetica, Arial, sans-serif;
font-size: x-large;
}
The h2 element also receives a minor makeover:
style1.css (excerpt)
h2 {
color: blue;
font-size: medium;
font-weight: normal;
}
Browsers usually display headings in bold type, but we can have them display in
standard type by giving the font-weight property a value of normal.
A Beginner’s Palette of Styling Options
We’ve looked at some examples of styles that can be applied to your web pages
through CSS, but the examples we’ve seen have been a mixed bag (and deliberately
so). There are so many more from which you can pick and choose—too many pos
sibilities, in fact, for us to be able to list them all here. However, this section lists
7 For more reasons than we have space to discuss, text sizing in CSS is a topic that causes heated debate
in some circles. As you become familiar with CSS, you may want to learn more about the other text-
sizing techniques that it offers. A good place to start would be SitePoint’s CSS discussion forum at
http://www.sitepoint.com/launch/cssforum/.
Order the print version of this book to get all 400+ pages!
92 Build Your Own Web Site The Right Way Using HTML & CSS
some of the basic properties and values with which you might like to experiment.
Feel free to try any of these in your CSS file. Note that we’ll be adding to this list
in subsequent chapters; it’s by no means exhaustive!
color As we’ve seen, both of these properties can take color
background-color keywords (e.g. red, blue, or green) or hexadecimal color
specifications such as #ff0000.
font-family This property takes a list of font names, containing any fonts
you choose in order of preference. Be sure to provide options
that users are likely to have on their computers (e.g. Arial,
Verdana, etc.). This list should end using one of the “generic”
CSS fonts such as serif or sans-serif, which any browser
that supports CSS will recognize.
font-size This property can be any one of the following:
font size keywords
■ xx-small
■ x-small
■ small
■ medium
■ large
■ x-large
■ xx-large
relative font sizes
■ a percentage (e.g. 140%)
■ em units (e.g. 1.2em; 1em is equal to the height of the
M font character)
fixed font sizes
■ pixels (e.g. 20px)
■ points (e.g. 12pt, as you may be used to using in Mi
crosoft Word)
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 93
Fixed font sizes are not always a great idea, as they
cannot easily be scaled up or down to suit the reader’s
needs. Relative font sizes are definitely the preferred
option.
font-weight bold or normal
font-style normal or italic
text-decoration none, underline, overline, or line-through
Backing It Up!
Before you experiment using the CSS properties above, it might be an idea to make
a backup of your CSS file, just in case you run into difficulties. Remember that
you can download all the examples used in this chapter from the code archive if
you accidentally mangle your CSS file. If this happens, don’t worry! It’s all part
of the learning process, and you can be sure that no animals will be harmed in
the process.
Recap: the Style Story so Far
Let’s allow ourselves a moment to reflect. Our site now boasts a CSS file using a
selection of attractive styles. We’re in the enviable position of being able to change
the site at a whim by altering just that one CSS file. Let’s try styling some more of
the elements on our web pages.
Changing the Emphasis
■ Open about.html in your text editor.
■ Find the paragraph about meeting up in a local pub and add an emphasis element
as shown here:
about.html (excerpt)
<p>And when we're not diving, we often meet up in a local pub
to talk about our recent adventures (<em>any</em> excuse,
eh?).</p>
Order the print version of this book to get all 400+ pages!
94 Build Your Own Web Site The Right Way Using HTML & CSS
■ Save the page, then view it in your web browser; it should appear as shown in
Figure 3.8. As you can see, emphasis elements appear in italics by default. We’re
going to use CSS to change that default style.
Figure 3.8. Using emphasis to set type to italics by default
■ Open style1.css (if you haven’t already opened it for editing) and add the following
rule below the others:
style1.css (excerpt)
em {
font-style: normal;
text-transform: uppercase;
}
■ Save the CSS file, then refresh your browser’s view of the About Us page. Does
your page look like Figure 3.9?
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 95
Figure 3.9. Changing the emphasis to capitalized text from italics
Now, whenever you add an em element to any web page of your site (assuming that
page is linked to style1.css), the emphasized text will appear in capital letters, not
italics. But this raises an interesting point: when should you override a browser’s
default style for one of your own choosing? Presumably, the default styles that
browsers use were selected carefully; how can you be sure that redefining the styles
is a good idea? Aren’t italics a suitable style for emphasis? They probably are. As
they say in the Spider-Man film, “With great power comes great responsibility,” so
be sure to exercise caution. Just because you can change a default style doesn’t al
ways mean you should.
Order the print version of this book to get all 400+ pages!
96 Build Your Own Web Site The Right Way Using HTML & CSS
Perhaps a compromise is in order. Let’s change the emphasis so that it’s still italic,
but also appears in uppercase letters. All we need to do is remove the font-style
declaration; the em element will then revert to its default italicized appearance, as
depicted in Figure 3.10:
style1.css (excerpt)
em {
text-transform: uppercase;
}
Figure 3.10. Emphasis displayed as uppercase italics
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 97
Emphasis or Italics?
You might well be asking yourself, “If I want an italic font, can’t I use an italic
element?” In fact, HTML provides an i element for just this purpose, but its use
isn’t recommended. Why not? Well, marking text as i says nothing about its
meaning; i only communicates how it should be presented on the screen. Such
elements are referred to as presentational HTML elements, and they should be
avoided. Likewise, the b element (for bold), another old HTML element, should
not be used. The preferred option is to use strong or, if you just want to display
headings in bold, use CSS.
Why is this important? It might not seem a big deal as you look at the italicized
text in your web browser. But imagine if you were blind, and you used software
that read web pages aloud to you, instead of displaying them on the screen. This
program (called a screen reader) might read text marked up with an em element
using slight emphasis, and text marked up with strong in a more powerful voice
(though this, of course, depends on the screen reader being used). But what would
it do with text marked up with i or b? Well, these elements say nothing about the
meaning of the text, so it would not treat them in any special way—thus potentially
losing the meaning that you were trying to convey. A search engine (e.g. Google,
Yahoo) may also place more importance on a user’s search terms that appear
within a strong element than a b element (although the search engine companies
never give anything solid away about how their search algorithms work!).
One other presentational tag that you might see others use, but should never copy,
is the u element. Wrap this around some text and needless underlining occurs
that only serves to confuse users. This is because in web pages, underlined text
normally signifies a link—which the u element most definitely isn’t!
Looking at Elements in Context
Here’s a riddle for you: which of these items is bigger? A pen or a sheep? Well, the
answer is either, depending on the context. If you were a farmer, you’d swear that
the pen is bigger. After all, you spend many hours a week rounding up herds of
sheep into a big, solid pen. If, however, you’re an office worker, you’d opt for the
sheep being the larger of the two—after all, you’d find it a lot easier to pick up a
pen and flip it around your fingers.
Context can change a situation quite drastically, and we can use context to our ad
vantage in CSS. We can style an element in a number of different ways, depending
Order the print version of this book to get all 400+ pages!
98 Build Your Own Web Site The Right Way Using HTML & CSS
on its position. Let’s head back to our example site for another lesson. Don’t be
sheepish, now!
Currently, we have styled paragraphs so that they appear in a navy blue, sans-serif
font (Verdana, specifically), as does almost everything else on the page:
style1.css (excerpt)
body {
font-family: Verdana, Helvetica, Arial, sans-serif;
}
p {
font-size: small;
color: navy;
}
This is all well and good, but there’s one paragraph on our site that’s a little different
than the others in terms of its purpose. Can you spot which one it is? It’s our first
paragraph, the one in the tag line. Here’s the XHTML for that section:
index.html (excerpt)
<div id="tagline">
<p>Diving club for the south-west UK - let's make a splash!</p>
</div>
It’s different because it’s not really part of the document content and, as such, it
might benefit from some different styling. The fact that this particular paragraph is
contained within a specific div element—which has an id attribute of tagline—can
be useful. Because it’s contained within its own div, we can set a rule for this
paragraph and this paragraph only.
■ Open the CSS file for editing, and add the following after the first paragraph
rule:
style1.css (excerpt)
#tagline p {
font-style: italic;
font-family: Georgia, Times, serif;
}
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 99
■ Save the file, then refresh the About Us page (or any of the three, for that matter)
in your browser. Your page should now look similar to the one shown in Fig
ure 3.11.
Figure 3.11. Putting the tag line in italics
What’s happening here? Perhaps a CSS-to-English translation is required. This CSS
rule means, “For any paragraph element that occurs inside an element that has an
id of tagline, set the text to italics and the font to Georgia, Times, or some other
serif font if you don’t have either of those.”
Getting a Positive ID
The # notation in the CSS refers to an element with a specific id attribute—in
this case, tagline. We’ll learn more about selecting ids and manipulating them
in subsequent chapters.
Order the print version of this book to get all 400+ pages!
100 Build Your Own Web Site The Right Way Using HTML & CSS
Contextual Selectors
#tagline p is known as a contextual selector. Here are some other examples (with
their English translations):
■ #navigation a {
text-decoration: none;
}
Translation: for any link found inside the navigation area (an element with an
id of navigation), remove any decoration on that text; in other words, remove
the underline (any other links on the page will remain underlined).
■ #footer p {
line-height: 150%;
}
Translation: set the vertical height between lines of text contained in paragraphs
inside the footer area (e.g. a div element with an id of footer) to 150%. This
would override the browser default of 100%, or other line-height values that
might be set, for example, for the body text.
■ h1 strong {
color: red;
}
Translation: for any text inside a level one heading that’s marked up as strong,
set the color to red (any other instance of strong on the page will not be set to
red).
■ h2 a {
text-decoration: none;
}
Translation: don’t underline the text of any link inside a level two heading (the
default setting underlines all links, so any other links on the page will remain
underlined).
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 101
Grouping Styles
If you want to apply the same style to different elements on a web page, you don’t
have to repeat yourself. For example, let’s say that you want to set heading levels
one through three in yellow text with a black background. Perhaps you’d do this:
h1 {
color: yellow;
background-color: black;
}
h2 {
color: yellow;
background-color: black;
}
h3 {
color: yellow;
background-color: black;
}
That’s very messy and repetitive. Plus, once you have a lot of styles on the page, it
is even more difficult to maintain. Wouldn’t it be great if you could reduce some
of that work? You can! Here’s how:
h1, h2, h3 {
color: yellow;
background-color: black;
}
Translation: if the element is a level one heading, a level two heading, or a level
three heading, set the text to yellow and the background to black.
Comma = “Or”
You can think of the commas in CSS selectors (like the one above) as the word
“or.”
Let’s try grouping some styles in our project site. We don’t have any h3 headings
yet, but we will soon.
Order the print version of this book to get all 400+ pages!
102 Build Your Own Web Site The Right Way Using HTML & CSS
■ Edit your CSS file (style1.css) by adding the following to the bottom of it:
style1.css (excerpt)
h1, h2, h3 {
font-family: "Trebuchet MS", Helvetica, Arial, sans-serif;
background-color: navy;
color: white;
}
■ Save the file, then refresh the About Us page in your browser. You should be
looking at a page like the one shown in Figure 3.12.
Figure 3.12. Displaying the changed heading styles
That CSS really does kill several birds with one stone (figuratively speaking, of
course; I did say no animals would be harmed!). Not only do you have the conveni
ence of being able to style many pages from one central location (your CSS file), but
you have the added convenience of being able to style many elements in one go.
Your CSS file becomes easier to manage and—a nice little side-benefit—smaller,
and therefore quicker to download.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 103
Filenames for Your Style Sheets
Although we’ve been working with style1.css for some time, you may be wondering
why we named the file this way. The name is deliberate. You might want to add
another style to your web site at a later date, and numbering is a basic way to keep
track of the styles you can apply to a site.
You might be thinking, “Why not name it something like marine.css because it
uses marine colors, references to sea animals, and so on?” That’s a fair question,
but it’s important to remember with CSS is that you can always change the styles
later, and your naming convention might, at a later date, bear no relevance to the
styles a file contains. For example, you can edit marine.css such that all the colors
in your web site are changed to ochres, browns, and sandy yellows. This ability
to change the web site’s design in one action is the whole point of CSS! With the
new design, your web site might have an earthy/desert feel to it, yet you could
still have 200 or more pages referring to a style sheet by the filename of marine.css.
It’s not quite right, is it? This is why I’ve chosen an abstract name for the CSS file,
and I recommend that you do the same for the web sites you develop.
But something interesting is happening in our CSS file: it appears that we may have
a conflict in our rules. Or have we?
Which Rule Wins?
When we added the grouped declaration for the headings, we changed some styles
that we’d set previously. A look at the source shows that the level two heading, h2,
has been set to be blue and white in different places in our style sheet:
style1.css (excerpt)
h2 {
color: blue;
font-size: medium;
font-weight: normal;
}
⋮
h1, h2, h3 {
font-family: "Trebuchet MS", Helvetica, Arial, sans-serif;
background-color: navy;
color: white;
}
Order the print version of this book to get all 400+ pages!Adding Some Style 103
Filenames for Your Style Sheets
Although we’ve been working with style1.css for some time, you may be wondering
why we named the file this way. The name is deliberate. You might want to add
another style to your web site at a later date, and numbering is a basic way to keep
track of the styles you can apply to a site.
You might be thinking, “Why not name it something like marine.css because it
uses marine colors, references to sea animals, and so on?” That’s a fair question,
but it’s important to remember with CSS is that you can always change the styles
later, and your naming convention might, at a later date, bear no relevance to the
styles a file contains. For example, you can edit marine.css such that all the colors
in your web site are changed to ochres, browns, and sandy yellows. This ability
to change the web site’s design in one action is the whole point of CSS! With the
new design, your web site might have an earthy/desert feel to it, yet you could
still have 200 or more pages referring to a style sheet by the filename of marine.css.
It’s not quite right, is it? This is why I’ve chosen an abstract name for the CSS file,
and I recommend that you do the same for the web sites you develop.
But something interesting is happening in our CSS file: it appears that we may have
a conflict in our rules. Or have we?
Which Rule Wins?
When we added the grouped declaration for the headings, we changed some styles
that we’d set previously. A look at the source shows that the level two heading, h2,
has been set to be blue and white in different places in our style sheet:
style1.css (excerpt)
h2 {
color: blue;
font-size: medium;
font-weight: normal;
}
⋮
h1, h2, h3 {
font-family: "Trebuchet MS", Helvetica, Arial, sans-serif;
background-color: navy;
color: white;
}
Order the print version of this book to get all 400+ pages!
104 Build Your Own Web Site The Right Way Using HTML & CSS
Because the declaration specifying that the h2 should be white comes later, it has
overridden the earlier one. It doesn’t matter if you’ve defined an h2 to be blue 100
times through your style sheet; if the last definition says it should be white, then
white it will be!
Recapping Our Progress
Time for another breather. What have we learned? Well, we’ve learned some more
styles that you can apply in CSS, we’ve seen how you can style certain elements
depending on their context, and more recently, we’ve discussed how you can group
elements that need to be styled in the same way. There’s one thing that we’ve touched
on only briefly, yet it demands more attention because it’s so fundamental to the
way the Web functions. That topic is links.
Styling Links
Links are everywhere on the Web: they truly are the basis of everything you see
online. Nowadays, we’re used to seeing highly decorative web pages adorned by a
wealth of different images and features. Take a step back in time, though, and you’ll
find that the World Wide Web was little more than a collection of linked documents.
Go back to the earliest browsers and you’ll see that those links were underlined,
which remains the case today. By default, a browser uses the following color scheme
for links:
blue an unvisited link
purple a link to a web page that you’ve previously visited
red an active link (one you’re clicking on; you may have noticed links flash
red momentarily when you initially click on them)
This color scheme isn’t to everyone’s taste, but it’s what we’re stuck with for now.
At least, it’s what we would be stuck with if we couldn’t use CSS to redefine those
colors.
At its most basic, a CSS style for links might look like this:
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 105
a {
font-weight: bold;
color: black;
}
Now, instead of being blue and having a normal font weight, your links appear in
bold, black type. Try adding that to your style1.css file, then save it and see how it
affects your web pages—Figure 3.13 illustrates this.
Figure 3.13. Styling all the links in our navigation to bold and black
Link States
As I mentioned previously, there are different types of links (unvisited, visited,
active) that you’ll come across on a web page. There’s one other state that I haven’t
mentioned, but it’s one with which you’re probably familiar: the hover state (which
occurs when you pass your cursor over the link). In CSS, you can change the styling
of all these link states using pseudo-classes, which sounds complicated but really
is fairly straightforward. You can think of a pseudo-class as being like an internal
class the browser automatically applies to the link while it’s in a certain state. Here
is some CSS that shows the color/style scheme for the different link states:
Order the print version of this book to get all 400+ pages!
106 Build Your Own Web Site The Right Way Using HTML & CSS
a {
font-weight: bold;
}
a:link {
color: black;
}
a:visited {
color: gray;
}
a:hover {
text-decoration: none;
color: white;
background-color: navy;
}
a:active {
color: aqua;
background-color: navy;
}
The different states are addressed within the CSS through the use of the a element
selector, and by adding a colon (:) and the pseudo-classes link, visited, hover,
and active. Adding pseudo-classes to your style sheet means the browser applies
the rule when the element is in the state specified by the pseudo-class.
Getting Your Link States in Order
Browsers usually aren’t fussy about the order in which you specify rules in your
CSS file, but links should always be specified in the order shown above: link,
visited, hover, and active. Try to remember the letters LVHA. The more
cynical users might find it easier to remember this mnemonic with the phrase,
“Love? Ha!” We can thank Jeffrey Zeldman for that little gem.8
8 Designing With Web Standards, Jeffrey Zeldman, New Riders.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)106 Build Your Own Web Site The Right Way Using HTML & CSS
a {
font-weight: bold;
}
a:link {
color: black;
}
a:visited {
color: gray;
}
a:hover {
text-decoration: none;
color: white;
background-color: navy;
}
a:active {
color: aqua;
background-color: navy;
}
The different states are addressed within the CSS through the use of the a element
selector, and by adding a colon (:) and the pseudo-classes link, visited, hover,
and active. Adding pseudo-classes to your style sheet means the browser applies
the rule when the element is in the state specified by the pseudo-class.
Getting Your Link States in Order
Browsers usually aren’t fussy about the order in which you specify rules in your
CSS file, but links should always be specified in the order shown above: link,
visited, hover, and active. Try to remember the letters LVHA. The more
cynical users might find it easier to remember this mnemonic with the phrase,
“Love? Ha!” We can thank Jeffrey Zeldman for that little gem.8
8 Designing With Web Standards, Jeffrey Zeldman, New Riders.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 107
Let’s change the styles for different link states in our project site:
■ Open the project site’s CSS file (style1.css), and add the above CSS at the bottom
of the file.
■ Save the CSS file.
■ Open any of the three web pages in your browser (or hit Reload) to see how the
styled links display.
Figure 3.14 shows the three different link states: the home link is unvisited, the link
to the About Us page shows that it has been visited previously (shown in gray), and
the link to the Contact Us page is being hovered over by the user’s cursor.
Feel free to experiment in the CSS file with the different foreground and background
colors, and other text formatting styles that were detailed in the table earlier in this
chapter.
Figure 3.14. Styling three different link states using CSS
Order the print version of this book to get all 400+ pages!
108 Build Your Own Web Site The Right Way Using HTML & CSS
Clearing Your History
Your browser automatically stores a certain amount of your browsing history, and
uses this information to decide whether a link has been visited or not (and, hence,
how the link should be displayed). If you’re building a site and testing links, you
might want to check how an unvisited link looks but, because of your browsing
history, they may all show as having been visited. This is almost certainly the
case with our three-page project site—the links in your navigation list are probably
all gray. To reset this, you can clear your browser’s history. In IE, select Tools >
Internet Options. You’ll see a button under Browsing History that reads Delete. Click
on this and it will bring up a Delete Browsing History dialog with more options, as
shown in Figure 3.15; make sure that the History checkbox has been ticked, then
click the Delete button on that dialog. Afterwards, reload the web page. Any links
you may have visited will now appear as unvisited. (The process for clearing
history in older versions is a little easier—just look for the button on the Internet
Options dialogue that says Clear History).
Figure 3.15. Clearing the history in IE displays unvisited link styles again
Other browsers have similar options, which may be found in locations such as
Tools > Options or Preferences > Privacy. I won’t list all the different methods for
deleting your history from various browsers here, but if you rummage around,
you should be able to find them without too much difficulty.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)108 Build Your Own Web Site The Right Way Using HTML & CSS
Clearing Your History
Your browser automatically stores a certain amount of your browsing history, and
uses this information to decide whether a link has been visited or not (and, hence,
how the link should be displayed). If you’re building a site and testing links, you
might want to check how an unvisited link looks but, because of your browsing
history, they may all show as having been visited. This is almost certainly the
case with our three-page project site—the links in your navigation list are probably
all gray. To reset this, you can clear your browser’s history. In IE, select Tools >
Internet Options. You’ll see a button under Browsing History that reads Delete. Click
on this and it will bring up a Delete Browsing History dialog with more options, as
shown in Figure 3.15; make sure that the History checkbox has been ticked, then
click the Delete button on that dialog. Afterwards, reload the web page. Any links
you may have visited will now appear as unvisited. (The process for clearing
history in older versions is a little easier—just look for the button on the Internet
Options dialogue that says Clear History).
Figure 3.15. Clearing the history in IE displays unvisited link styles again
Other browsers have similar options, which may be found in locations such as
Tools > Options or Preferences > Privacy. I won’t list all the different methods for
deleting your history from various browsers here, but if you rummage around,
you should be able to find them without too much difficulty.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 109
Class Selectors
To date, we’ve discussed the ways in which we can style various elements, such as
paragraphs and headings; we’ve also seen how we can style elements in specific
areas of the page using the id attribute. However, implementing broad-brush styles,
such as coloring the text in all p elements navy, is very much a blanket approach
to design. What if you want some of those paragraphs (or any elements, for that
matter) to look a little different than the rest? Class selectors are the answer.
A class selector lets you define a style that can be used over and over again to style
many different elements. So, for example, let’s say you wanted to make some parts
of your text stand out—to make them look slightly more appealing or fun than other
parts of the document.
You could do so in your CSS like this:
.fun {
color: #339999;
font-family: Georgia, Times, serif;
letter-spacing: 0.05em;
}
Here, we’ve created a style rule for a class called “fun.” The fact that it’s a class se
lector is denoted by the period at the beginning of the class name. We’ve slipped
another property into this rule: letter-spacing defines the space between each of
the letters. We’ve set a spacing of 0.05em here. 1em is the height of the M character
in any font, so 0.05em is 5% of that height. It doesn’t sound like much of a difference,
but when it comes to typography, subtle changes are usually more effective than
extreme modifications.
In order to make use of the style once it has been added to your style sheet, all you
need to do is add the class="fun" attribute to an element:
<p class="fun">A man walks into a bar; you would've thought he'd
see it coming!</p>
Let’s apply some classes to our project site. First, we’ll need to add the style rule
shown above to the style sheet we’re working on:
Order the print version of this book to get all 400+ pages!Adding Some Style 109
Class Selectors
To date, we’ve discussed the ways in which we can style various elements, such as
paragraphs and headings; we’ve also seen how we can style elements in specific
areas of the page using the id attribute. However, implementing broad-brush styles,
such as coloring the text in all p elements navy, is very much a blanket approach
to design. What if you want some of those paragraphs (or any elements, for that
matter) to look a little different than the rest? Class selectors are the answer.
A class selector lets you define a style that can be used over and over again to style
many different elements. So, for example, let’s say you wanted to make some parts
of your text stand out—to make them look slightly more appealing or fun than other
parts of the document.
You could do so in your CSS like this:
.fun {
color: #339999;
font-family: Georgia, Times, serif;
letter-spacing: 0.05em;
}
Here, we’ve created a style rule for a class called “fun.” The fact that it’s a class se
lector is denoted by the period at the beginning of the class name. We’ve slipped
another property into this rule: letter-spacing defines the space between each of
the letters. We’ve set a spacing of 0.05em here. 1em is the height of the M character
in any font, so 0.05em is 5% of that height. It doesn’t sound like much of a difference,
but when it comes to typography, subtle changes are usually more effective than
extreme modifications.
In order to make use of the style once it has been added to your style sheet, all you
need to do is add the class="fun" attribute to an element:
<p class="fun">A man walks into a bar; you would've thought he'd
see it coming!</p>
Let’s apply some classes to our project site. First, we’ll need to add the style rule
shown above to the style sheet we’re working on:
Order the print version of this book to get all 400+ pages!
110 Build Your Own Web Site The Right Way Using HTML & CSS
■ Open style1.css and add the CSS from the above block to the bottom of that file.
■ Save style1.css, then open about.html.
■ Find the paragraph that’s contained inside the blockquote element.
■ Add the class="fun" attribute to the paragraph’s opening tag.
This is how your markup should look right now:
about.html (excerpt)
<blockquote>
<p class="fun">"Happiness is a dip in the ocean followed by a
pint or two of Old Speckled Hen. You can quote me on
that!"</p>
</blockquote>
Note that the class attribute was applied at the paragraph level. If there were a few
paragraphs in our man Bob’s quotation, it could look like this:
<blockquote>
<p class="fun">"Happiness is a dip in the ocean followed by a
pint or two of Old Speckled Hen. You can quote me
on that!</p>
<p class="fun">"Join us for a weekend away at some of our
favorite dive spots and you'll soon be making new
friends.</p>
<p class="fun">"Anyway, about time I got on with some
<em>proper</em> work!"</p>
</blockquote>
There’s a lot of repetition in there. Surely there’s a tidier way to apply this style?
There sure is:
<blockquote class="fun">
<p>"Happiness is a dip in the ocean followed by a pint or two of
Old Speckled Hen. You can quote me on that!</p>
<p>"Join us for a weekend away at some of our favorite dive
spots and you'll soon be making new friends.</p>
<p>"Anyway, about time I got on with some <em>proper</em>
work!"</p>
</blockquote>
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 111
In this example, we apply that class of fun to the blockquote element, so everything
contained in that element inherits the style of the parent container. This saves us
from having to apply these different classes all over our pages (an affliction that has
become known as class-itis—a not-too-distant relation of div-itis, which we discussed
in Chapter 2).
class vs id
So far, we’ve looked at both class selectors (which involve periods: “.” ) and id
selectors (which involve pound or hash signs: “#”). Are you confused by them?
It’s true that these selectors are similar, but there is one important difference: a
specific id can only be applied to one XHTML element. So, for example, on any
web page, there can only be one element with an id of mainnavigation, and
only one with an id of header. A class, on the other hand, can appear as many
times as required.
Limiting Classes to Specific Elements
Imagine you want to italicise any blockquote element that has a class attribute
with the value fun, but not other elements with that class value. Think it sounds
tricky? Not with CSS! Take a look:
.fun {
font-family: Georgia, Times, serif;
color: #339999;
letter-spacing: 0.05em;
}
blockquote.fun {
font-style: italic;
}
Now, any text inside a pair of <blockquote class="fun"> and </blockquote>
tags will appear in italics.
By prefixing our normal class selector with an element name, we’re telling the
browser to apply the following declarations to that element-and-class combination
only. It’s as simple as element.class, but make sure you don’t leave any spaces!
Order the print version of this book to get all 400+ pages!
112 Build Your Own Web Site The Right Way Using HTML & CSS
Specifically Speaking
Those with an eagle eye will have noticed that not all of the fun styles in the
previous example are actually applied to the quotation. The font-family and
letter-spacing declarations take effect, but the color change does not! The
reason for this can be explained with the concept of specificity.
Specificity simply means the rule that is the most specific is the one that is applied.
Determining which rule is the most specific is a little bit complex, but understand
able. In our style sheet, the specificity is easy to determine: the .fun rule is applied
to the blockquote element and properties are inherited by the p elements, but
property values are only inherited in the absence of any other declaration. We
have another color declaration in our project site—the one that we created at the
start of the chapter that states that all paragraphs should be navy-colored:
p {
color: navy;
}
The rule with the element selector p has a greater specificity for the p elements
because the selector specifically targets p elements, whereas the .fun rule does
not. Imagine if, however, we added another rule like this:
.fun p {
color: green;
}
The effect would be this: all paragraph text would be navy, except for the para
graphs inside elements with the class fun, which would be green. This is because
the .fun p selector is more specific for those paragraphs. Note that, unlike the
conflicting rules we encountered in the section called “Which Rule Wins?”, this
battle between style rules has no relation to the order in which they appear in the
style sheet.
Specificity can be confusing, so don’t lose too much sleep over it—for now, it’s
enough just to be aware of the concept, as this may be the reason why one of your
styles doesn’t take effect when you’re convinced it should. Specificity is covered
in great depth in the SitePoint CSS Reference9 if you’d like to explore it further.
9 http://reference.sitepoint.com/css/specificity/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)112 Build Your Own Web Site The Right Way Using HTML & CSS
Specifically Speaking
Those with an eagle eye will have noticed that not all of the fun styles in the
previous example are actually applied to the quotation. The font-family and
letter-spacing declarations take effect, but the color change does not! The
reason for this can be explained with the concept of specificity.
Specificity simply means the rule that is the most specific is the one that is applied.
Determining which rule is the most specific is a little bit complex, but understand
able. In our style sheet, the specificity is easy to determine: the .fun rule is applied
to the blockquote element and properties are inherited by the p elements, but
property values are only inherited in the absence of any other declaration. We
have another color declaration in our project site—the one that we created at the
start of the chapter that states that all paragraphs should be navy-colored:
p {
color: navy;
}
The rule with the element selector p has a greater specificity for the p elements
because the selector specifically targets p elements, whereas the .fun rule does
not. Imagine if, however, we added another rule like this:
.fun p {
color: green;
}
The effect would be this: all paragraph text would be navy, except for the para
graphs inside elements with the class fun, which would be green. This is because
the .fun p selector is more specific for those paragraphs. Note that, unlike the
conflicting rules we encountered in the section called “Which Rule Wins?”, this
battle between style rules has no relation to the order in which they appear in the
style sheet.
Specificity can be confusing, so don’t lose too much sleep over it—for now, it’s
enough just to be aware of the concept, as this may be the reason why one of your
styles doesn’t take effect when you’re convinced it should. Specificity is covered
in great depth in the SitePoint CSS Reference9 if you’d like to explore it further.
9 http://reference.sitepoint.com/css/specificity/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 113
Styling Partial Text Using span
So, a class can be applied in many different places—perhaps to a specific paragraph,
or to a block of several paragraphs contained in a blockquote, or to a div that holds
many different types of content. But what would you do if you wanted to apply the
style to a very small section of text—maybe just a couple of words, or even just a
couple of letters, within a paragraph? For this, once again, you can use the span
element.
Earlier in this chapter I showed how you could use the span element in conjunction
with inline styles to pick out and style specific words within a paragraph. The exact
same technique can be used with classes: we simply place an opening <span> tag
at the point at which we want the styling to begin, and the closing </span> tag at
the point at which the styling should end. The advantage of this technique over the
inline style demonstrated earlier is, of course, that with this technique, the style is
defined in a single location, so you could potentially add the “fun” class to many
different elements on many different pages with a minimum of hassle. When you
decide that you want to have a different kind of fun (so to speak), you need only
change your style sheet (style1.css) for that new style to be reflected across your site:
<p><span class="fun">Bubble Under</span> is a group of diving
enthusiasts based in the south-west UK who meet up for diving
trips in the summer months when the weather is good and the
bacon rolls are flowing. We arrange weekends away as small
groups to cut the costs of accommodation and travel and to
ensure that everyone gets a trustworthy dive buddy.</p>
Try applying the span element to your “About Us” page as suggested in the above
XHTML code. If you save the changes and check them in your browser (remember
to hit Reload), your page should look like the one shown in Figure 3.16.
Order the print version of this book to get all 400+ pages!Adding Some Style 113
Styling Partial Text Using span
So, a class can be applied in many different places—perhaps to a specific paragraph,
or to a block of several paragraphs contained in a blockquote, or to a div that holds
many different types of content. But what would you do if you wanted to apply the
style to a very small section of text—maybe just a couple of words, or even just a
couple of letters, within a paragraph? For this, once again, you can use the span
element.
Earlier in this chapter I showed how you could use the span element in conjunction
with inline styles to pick out and style specific words within a paragraph. The exact
same technique can be used with classes: we simply place an opening <span> tag
at the point at which we want the styling to begin, and the closing </span> tag at
the point at which the styling should end. The advantage of this technique over the
inline style demonstrated earlier is, of course, that with this technique, the style is
defined in a single location, so you could potentially add the “fun” class to many
different elements on many different pages with a minimum of hassle. When you
decide that you want to have a different kind of fun (so to speak), you need only
change your style sheet (style1.css) for that new style to be reflected across your site:
<p><span class="fun">Bubble Under</span> is a group of diving
enthusiasts based in the south-west UK who meet up for diving
trips in the summer months when the weather is good and the
bacon rolls are flowing. We arrange weekends away as small
groups to cut the costs of accommodation and travel and to
ensure that everyone gets a trustworthy dive buddy.</p>
Try applying the span element to your “About Us” page as suggested in the above
XHTML code. If you save the changes and check them in your browser (remember
to hit Reload), your page should look like the one shown in Figure 3.16.
Order the print version of this book to get all 400+ pages!
114 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 3.16. Applying the fun class to two specific words
Don’t Throw (Needless) spans into the Works
The span element is nearly always used with a class attribute. There’s not normally
a good reason to apply a span element to your XHTML on its own, although you
may see some web sites that do.
Before you apply a span to any given element on your web page, take a moment
to think about whether there’s another element that’s better suited to the task. For
example, it’s advisable not to do this:
<p>Do it <span class="shouty">now</span>!</p>
A more appropriate choice would be to use the strong element:
<p>Do it <strong>now</strong>!</p>
Think of the meaning of what you’re writing, and aim for an XHTML element that
suits the purpose. Other examples might be em, cite, and blockquote.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Adding Some Style 115
Summary
It’s been another busy chapter, but my, how our site’s blossoming! A chapter or two
ago, we hadn’t even built a web page, but now we’re at the stage where we know
how to apply a (virtual) lick of paint to any type of XHTML element on a page, to
a specific section of a web page depending on its id, or to arbitrary portions of a
page—sometimes in several different places—using class selectors.
The web site is starting to look a little more colorful, but the layout is still fairly
basic. In the next chapter, we’ll look at how it’s possible to change the layout of
elements on a page—their position, shape, size, and more—using CSS. Styling text?
Been there, done that. Let’s move to the next level!
Order the print version of this book to get all 400+ pages!
Chapter
10
Pimp My Site: Cool Stuff You
Can Add for Free
Your web site looks great, everything seems to be going tickety-boo, and maybe you
even have regular news updates happening, thanks to a group of budding bloggers
who contribute regularly. Your work’s done, right? Well, no. There’s always some
thing else to do!
When you first set up your web site, you probably had a good idea of the audience
you were building it for, and you may well have catered admirably to that audience.
But within weeks of launching your site and promoting it to the world (using some
of the suggestions I made in Chapter 8), you started receiving emails from strangers
asking questions about the site that you hadn’t expected:
“Can you tell me who can service my air regulators in North Devon?”
“I can’t find details of your training courses—do you offer any?”
“My name is Abdul Akinbobola and I am the son of the recently
deposed president of Burkina Faso and ...”
378 Build Your Own Web Site The Right Way Using HTML & CSS
Okay, so that last message has nothing to do with your web site, but trust me, you’ll
certainly receive emails like this! The point is, no matter what sort of planning
you’ve undertaken, people beyond your expected audience will find your web site,
and you’ll likely need to be able to cater to them, too. This is where you should
consider some add-ons to your site—extras that will:
■ enable you to discover how people are arriving at your web site (e.g., through a
Google search, or via another web site’s link where you’ve promoted your own
site)
■ reveal which search terms people used to reach your web site, and provide some
statistics about the most common ones
■ let the visitor search the contents of your web site (rather than click around the
navigation in the hope of finding what they need)
■ allow the visitor to search a group of related web sites from the comfort of your
web site
■ provide a way for you to manage a list of your favorite web sites related to the
topic in your own web site, and provide them as a links resource for others
■ let your visitors become part of your web site community by providing a discus
sion forum
All of these goals can be achieved using free services, and in this chapter, I’m going
to provide step-by-step instructions to help you add these services and truly pimp
your site!1
Getting the Low-down on Your Visitors
How can you be absolutely sure that what’s on your web site is the right content
for your audience? Well, the truth is that you can’t—everyone’s different, after all,
and each person’s needs are unique. However, you can be given some indication
1 For those who don’t understand the reference, Pimp My Site is my little pun based on the MTV show
Pimp My Ride [http://www.mtv.com/ontv/dyn/pimp_my_ride/series.jhtml] in which old, neglected cars
are renovated (or “pimped”) for their owners. That’s not to say that your web site is old or neglected,
though!
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 379
about whether your web site is serving the audience’s needs through some simple
statistics
Some hosting companies will provide statistics software as part of your package,
so be sure to check. If your package includes a statistics service, you might wish to
skip this next section and just use the tools your host has provided. Most free
hosting services—and many of the cheaper hosting plans—will not provide statistics
for you. And even if your hosts do provide such services for you, they’re not usually
all that great. So it’s up to us to make sure we receive the best information that we
can.
Choosing a Statistics Service
As with a number of services I’ve mentioned elsewhere in this book, there are two
ways that you could introduce a statistics service to your site:
■ You could install and configure a statistics service on the web server that hosts
your site. The web server keeps detailed records of every visit to your web site:
it records the time of the visit, which pages were viewed, which browsers were
used, how visitors found the site, and much, much more. There are many pro
grams you can install onto your web server that will produce easy-to-read graphs
based on this data. Installing this software is no easy feat, though, and I wouldn’t
recommend it for beginners.
■ Thankfully, the second option is much easier—you can sign up for a third-party
solution that collects and stores the data on your behalf. All you’re required to
do is add a link to an image or script file (hosted by the service provider) into
your web pages.
Many third-party statistics services are available, but to narrow it down, I advise
you to look for one that offers the following features:
list of referring web sites (recent referrers and totals)
This information will tell you how your visitors found your web site.
number of visitors
You should be able to view a count of the numbers of visitors your site receives
each day and each month, as well as the total number of visitors who have
stopped by since the site launched.
Order the print version of this book to get all 400+ pages!
380 Build Your Own Web Site The Right Way Using HTML & CSS
information about your visitors’ computer setups
This data will tell you whether your visitors are using PCs or Macs, which
browsers they’re using, and so on.
Any information beyond that is probably overkill for a small-scale web site (too
many statistics can end up muddying the waters—there’s a lot to be said for simpli
city). There are a number of free hosted stats services you might want to consider
using, including StatCounter,2 Extreme Tracking,3 and AddFreeStats.4 However,
for my money the best solution you could opt for is Google Analytics.5
In the past, I used a number of the free services mentioned, but have since switched
all of them across to Google Analytics. The service is free but doesn’t appear to be
cheap—in short, you’re receiving a whole lot more than what you paid for! In addi
tion, it’s so easy to set up and then analyse the data that it captures. Let’s start by
signing up for an account.
Registering a Google Account
Make your way over to http://www.google.com/analytics/. It doesn’t take long to
have Google Analytics up and running. If you already have a Google account—highly
probably given the number of services they already offer, notably Gmail (Google
Mail)—then you can simply log in and then sign up for Analytics. For now, though,
I’ll assume that you don’t yet have a Google account.
■ Click on the Sign Up Now link, as shown in Figure 10.1.
2 http://www.statcounter.com/
3 http://www.extreme-dm.com/tracking/
4 http://www.addfreestats.com/
5 http://www.google.com/analytics/
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 381
Figure 10.1. Google Analytics home page
■ This will take you to a login screen, as shown in Figure 10.2 (unless you’re
already logged in to your Google account). If you already have an account, you
would use the login panel on the right, but let’s assume you’ve never set up a
Google Account. Click the Sign Up Now link (and yes, this does seem a bit like
déja vu, doesn’t it? Sign up now! Sign up now!).
Order the print version of this book to get all 400+ pages!
382 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 10.2. Google Analytics log in/sign up page
■ There are just a handful of details to input on this page—as seen in Figure 10.3.
Just enter your email address, pick a sensible password, and then attempt to
read the almost indecipherable characters in the word verification box (good
luck—it usually takes me a few tries!). Press the button that says I accept. Create
my account.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 383
Figure 10.3. Creating the Google Account
■ Having sent the form, Google will send an email to you to confirm your account
is a genuine request. You do this by clicking on the link in the email, and you’re
now a step closer.
■ You now have a Google account, but you do not, as yet, have a Google Analytics
account set up. Log in to your Google account (using the
http://www.google.com/analytics/ address from earlier). On the next page you’ll
see some more blurb about Analytics. Don’t read it all (plenty of time for that
later), instead just head straight for the panel with the button that says Sign Up,
as shown in Figure 10.4
Order the print version of this book to get all 400+ pages!
384 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 10.4. Logged in to Google, but still need to register for Analytics
■ There’s nothing too taxing here at all (see Figure 10.5)—Google just needs to
know a few details about your web site, where you are in the world (for the time
zone), and some contact information. You’re also asked to tick a box confirming
that you’ve read the lengthy list of terms and conditions; should you comply,
this would probably make you the second person in history after Google’s lawyer
to actually have done this (read it, not tick the box, that is!).
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 385
Figure 10.5. Some of the sign-up steps (and the beast of a Terms and Conditions page!)
■ In the final step of signing up, Google presents you with some code to copy and
paste into your web pages. There are two options to choose from; select the first
tab (which is displayed by default and titled New Tracking Code), then highlight
and copy the markup provided in the text area (see Figure 10.6).
Figure 10.6. Copy the markup that Google Analytics provides
Order the print version of this book to get all 400+ pages!
386 Build Your Own Web Site The Right Way Using HTML & CSS
That’s it for the sign-up process. Now all you need to do is put the generated
markup—just a few lines of it—into your web pages.
Adding the Statistics Code to Your Web Pages
Your statistics code should look like this (though specific details relating to your
account will differ):
<script type="text/javascript">
var gaJsHost = (("https:" == document.location.protocol) ?
➥"https://ssl." : "http://www.");
document.write(unescape("%3Cscript src='" + gaJsHost +
➥"google-analytics.com/ga.js'
➥type='text/javascript'%3E%3C/script%3E"));
</script>
<script type="text/javascript">
var pageTracker = _gat._getTracker("UA-1234567-1");
pageTracker._initData();
pageTracker._trackPageview();
</script>
To start, simply paste this code in your web page just before the closing </body>
tag. It’s good practice to place it here, as it’s the last item loaded on your web page;
that way, if Google takes a while to send the data requested, it will not hold up your
web page loading. Here’s how it looks in the context of the About page (which I’ve
truncated to a degree):
about.html (excerpt)
<p>
Or as our man Bob Dobalina would put it:</p>
<blockquote>
<p class="fun">"Happiness is a dip in the ocean followed
by a pint or two of Old Speckled Hen. You can quote
me on that!"</p>
</blockquote>
</div> <!-- end of bodycontent div -->
<script type="text/javascript">
var gaJsHost = (("https:" == document.location.protocol) ?
➥"https://ssl." : "http://www.");
document.write(unescape("%3Cscript src='" + gaJsHost +
➥"google-analytics.com/ga.js'
➥type='text/javascript'%3E%3C/script%3E"));
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 387
</script>
<script type="text/javascript">
var pageTracker = _gat._getTracker("UA-1234567-1");
pageTracker._initData();
pageTracker._trackPageview();
</script>
</body>
</html>
This is just the About page taken care of, so you’ll also need to add the code to the
other pages in your web site, and save them all. If you’ve created a Blogger template,
you’ll also need to update that template with the statistics code. You can do this
by logging into Blogger and adding the same code in the same location before the
closing body tag, and then republishing your blog).
But what now? What have we done here? And what can we do with it from this
point on?
Once you’ve added the tracking markup as described above, you’ll need to upload
the amended pages to your server by FTP (as described in Chapter 8). From now
on, every user visit to your web site will also place a request to Google’s files that
you inserted at the end of the page—what Google does is track these requests to
build up a picture of your web site usage. You can access these reports (click on
View Reports) from the Google Analytics Settings page (always the first page after
logging in—no hunting around required!), which is shown in Figure 10.7.
Figure 10.7. Google Analytics Settings page
Order the print version of this book to get all 400+ pages!
388 Build Your Own Web Site The Right Way Using HTML & CSS
Because we’re only using a dummy site in this book with no real users, it’s a bit
difficult to demonstrate real, lifelike stats—so here’s the Dashboard page from one
of my own web sites, Accessify.com with a few examples. It’s been around for quite
a while and has enough traffic to produce some statistics, as Figure 10.8 shows.
Figure 10.8. The Dashboard—showing an overview of visitor statistics
There are many other useful statistics here—too many to go into in more detail, in
fact. My advice is to sign up, apply the statistics code, and upload your amended
pages to your web server. Then, simply leave it for a few days—or weeks,
even—before logging back in to check the statistics. By that time you might have
enough data to see some patterns beginning to form (unless of course you’ve not
told anyone about your site and not had anyone link to the site, in which case the
usage statistics will point to just one user—you! New web sites can take time).
An example of the range of information Google Analytics can provide is shown in
Figure 10.9, which is a montage of the main site navigation with various features.
Google Analytics is the veritable Swiss Army Knife of free statistics, but like the
famed knife, you’ll probably not use 80% of the tools on offer!
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 389
Figure 10.9. Examples of the Google Analytics navigation menu options
What to Look for—a Summary
The most revealing statistics that you’ll probably need will be on the front page (aka
the Dashboard), and these are:
Visitors: How many people are using the site ... and do they stay long?
It’s great to know information about how many visitors your site receives, and
see how that changes over time, too. But when they reach the site, do they stick
around for long? Or do they just hit the back button on the browser and go
elsewhere? The Visitors information tells you all of that and more.
Traffic Sources: Through which web pages do visitors arrive at your site?
If another site has linked to your web site, and a user follows that link to your
web site, that information will be recorded in Traffic Sources. It’s good to be
aware of other web sites that have linked to you (if for no other reason than to
give you an ego boost!), and why they’ve linked to you—it’s easy enough to take
a look at the referring site from these reports. In most cases, your key referrers
Order the print version of this book to get all 400+ pages!
390 Build Your Own Web Site The Right Way Using HTML & CSS
will be search engines (and you can even find out what phrases people entered
that led them to your web site).6
Browser Capabilities: What tools do people use to access your web site?
Knowledge is power. If you learn that 99% of your visitors are using one kind
of web browser, you might not spend quite so much time worrying about display
issues for the other 1% of users. This kind of information helps you prioritize
any bugs you might need to fix.
A Search Tool for Your Site
This one’s a cinch! We’ll have you set up in minutes. And guess what? It’s those
people at Google that we have to thank, again. It could barely be any easier.
Here’s the basic markup you’ll need to have (this is so that Google can provide
search results based on the content of your web site only):
<!-- SiteSearch Google -->
<form method="get" action="http://www.google.com/search">
<label for="q">Search:</label>
<input id="q" name="q" size="20" maxlength="255" value=""
type="text"/>
<input name="domains" value="http://www.bubbleunder.com/"
type="hidden"/>
<input name="sitesearch" value="http://www.bubbleunder.com/"
checked="checked" id="mysite" type="radio"/>
<label for="mysite">Just this site</label>
<input name="sitesearch" value="" id="www" type="radio"/>
<label for="www">WWW</label>
<input name="btnG" value="Go" type="submit"/>
</form>
<!-- SiteSearch Google -->
All you need to do is change the bolded text to match your web site’s address. It’s
so easy!
Here’s that same code implementing the Bubble Under web site (at least, on a portion
of the events page):
6 Sometimes, web site managers talk about “checking their referrer logs.” This is what that term
means—looking through the lists of sites who have sent traffic to your web site, including search engines
(and reviewing the search phrases users entered into search engines to find your site).
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 391
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Forthcoming club diving events and trips with Bubble
Under</title>
<meta http-equiv="Content-Type"
content="text/html; charset=utf-8"/>
<link href="style1.css" rel="stylesheet" type="text/css"
media="screen"/>
</head>
<body>
<div id="header">
<div id="sitebranding">
<h1>BubbleUnder.com</h1>
</div>
<div id="tagline">
<p>Diving club for the south-west UK - let's make a
splash!</p>
</div>
<!-- SiteSearch Google -->
<form method="get" action="http://www.google.com/search">
<div id="search">
<label for="q">Search:</label>
<input id="q" name="q" size="20" maxlength="255" value=""
type="text"/>
<input name="domains" value="http://www.bubbleunder.com/"
type="hidden"/>
<input name="sitesearch" value="http://www.bubbleunder.com/"
checked="checked" id="mysite" type="radio"/>
<label for="mysite">Just this site</label>
<input name="sitesearch" value="" id="www" type="radio"/>
<label for="www">WWW</label>
<input name="btnG" value="Go" type="submit"/>
</div>
</form>
<!-- SiteSearch Google -->
</div>
<!-- end of header div -->
⋮
Note that we need to position the search form in an appropriate location, as well
as format the text a bit. I’ve used CSS to achieve this, using absolute positioning to
place the search box in the top, right-hand corner of the page. To do so, I wrapped
Order the print version of this book to get all 400+ pages!
392 Build Your Own Web Site The Right Way Using HTML & CSS
a div around the form elements and gave it an id attribute. That way, I can reference
the form in the CSS, as shown below:
#search {
position: absolute;
top: 77px;
right: 10px;
font-size: x-small;
font-weight: bold;
}
Figure 10.10 shows how the search box looks on the page itself.
Figure 10.10. The Bubble Under site with integrated search option
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 393
Google Search Limitations
Using Google’s service in this way is certainly easy, but you should be aware of
its limitations:
■ Google will only show search results if it knows about your web site—and it
will only know about it if you’ve submitted your web site’s address7 to Google
in the past (and Google has indexed it), or Google has found your web site by
following a link from another site.
■ The search results may not be completely up to date. If you make changes to
your site, then upload those changes, Google may not recognize that a change
has been made for days or even weeks—it really depends on when the search
engine re-indexes your site.
■ The search results cannot be customized. The results page will look like a
standard Google-search results page, but the linked search results will all be
pages from your web site (aside from sponsored links). However, people are
familiar with Google, so this has its benefits.
Searching by Genre
If adding a Google search tool doesn’t appeal, you might like to try another service
called Rollyo, a roll-your-own search engine. Rollyo allows you to create a custom
search interface: one that lets you pick and choose which web sites you want to
search—so that the search results are more focused and closely related to your own
web site’s content.
■ Click on the Register link in the top right-hand corner and complete the scant
details requested of you by the registration page, shown in Figure 10.11.
7 You can notify Google of your web site’s existence at http://www.google.com/addurl/.
Order the print version of this book to get all 400+ pages!
394 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 10.11. The Rollyo registration screen
■ Next, you’ll be asked for profile information, and you’ll see a big red arrow with
the words, Skip this for now. You know what to do!
■ On the following page, select the Create a custom searchroll link, as illustrated in
Figure 10.12.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 395
Figure 10.12. Choose Create a custom searchroll
■ In the page shown in Figure 10.13, you’re asked to provide names for your
Searchroll—a list of web sites that you want to include—and identify any tags
(keywords that describe your search facility’s purpose) that you’d like to assign
to your searchroll.
Figure 10.13. Adding sites that you want to search
Order the print version of this book to get all 400+ pages!
396 Build Your Own Web Site The Right Way Using HTML & CSS
With that done, you can create your searchroll. At the time of writing, Rollyo was
yet to provide a simple method for grabbing the source code required to place search
functionality on your web site. However, it’s possible to view the source of a web
page, take what you need, then adapt it slightly. I’ve done just that to show how
Rollyo could be used on any web site. Here’s the source code for the Rollyo search
I created for Bubble Under:
<!-- SiteSearch Rollyo -->
<form id="searchform" name="searchform"
action="http://www.rollyo.com/search.html" method="get">
<div id="search">
<input type="text" name="q" value="" id="search-box"/> in
<select id="searchmenu" name="sid">
<option value="6170">Bubble Under</option>
<option value="web">The web</option>
</select>
<input type="submit" value="Search"/>
</div>
</form>
<!-- SiteSearch Rollyo -->
Figure 10.14 shows how the search interface displays on the web page. (I placed
everything inside the form in the absolutely positioned div—in the same position
as the Google search box in the earlier example.)
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 397
Figure 10.14. Adding a Rollyo search to the Bubble Under web site
Because the Rollyo search results are syndicated from Yahoo, the next step is to
submit your site to Yahoo for indexing,8 if you haven’t already. As with most search
engines, it may take days or weeks before Yahoo visits your site and adds your pages
to its database. Your Rollyo searchroll will still work during this time, it just won’t
include your site in the results it displays.
Finally, Figure 10.15 depicts the search results displayed on the Rollyo web site.
8 http://search.yahoo.com/info/submit.html
Order the print version of this book to get all 400+ pages!
398 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 10.15. Displaying the search results on Rollyo
This is a novel way of adding search functionality to your site—but it’s one that
could potentially send people in another direction! However, if your web site is
more of a fun venture, than focused on making cold hard cash, this could be the
ethical way to go. Believe me when I say it’ll be good for your karma—you’ll see!
Caution: Contents May Have Shifted in Transit
Rollyo was new at the time of writing the first edition of this book. Some two
years later, when I was putting this second edition together, it appeared to have
had just the tiniest of changes—and was still showing as a beta version (a software
term used to denote a work-in-progress, although these days, it’s used more as a
liability waver!). Like a volcano that’s not erupted for a while, my gut feeling is
that it may be overdue for a change or two. Or perhaps everything’s working so
well they will keep it as is—for another two or so years. Who knows? Certainly
not me! So please bear in mind that it might change after this edition goes to print,
and if that transpires you may need to adapt some of the steps.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 399
Adding a Blogroll to Your Web Site
What’s a Blogroll? A Blogroll9 is a list of links that’s included on your web site (or
blog), and which is easily updated from a central point. A Blogroll is often a better
option than creating a specific page on your site just for links—which can easily
turn stale—and provides an easy route to fresh content on other web sites.
A range of tools are available for this purpose, but perhaps the simplest one to try
is BlogRolling. Here’s the process for setting up a Blogroll (once again, I’ve used the
Bubble Under web site as an example).
Signing up for a Blogroll
■ Go to the BlogRolling10 web site.
■ Follow the link to Create Account—you’ll be asked for an email address and
password, as Figure 10.16 shows.
Figure 10.16. Setting up a BlogRolling account
Once you’ve submitted the form, BlogRolling will send you an email. Open it
and click on the activation link.
■ Once you’ve activated your account, you can create a new Blogroll—in fact, you
can create several Blogrolls with just one account. Look for the link on the left
that says New BlogRoll. Then, simply enter a name and the web address of the
page on which you’ll be displaying the links, as shown in Figure 10.17.
9 http://en.wikipedia.org/wiki/Blogroll
10 http://www.blogrolling.com/
Order the print version of this book to get all 400+ pages!
400 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 10.17. Creating a new BlogRoll
■ Most of the tools you’ll need to manage your BlogRoll links are available from
the Home option on BlogRoll’s navigation menu. Figure 10.18 shows the
BlogRolling control panel for BubbleUnder.
Figure 10.18. All your BlogRolling options are available here
■ Select Add Links. You’ll be presented with a small form that looks like the one
in Figure 10.19.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 401
Figure 10.19. Adding a link to your Blogroll
You can keep on adding links until you run out of interesting web site addresses.
Bear in mind though, that if you add too many links, your web page may resemble
Yahoo gone mad.
■ Once you’ve added links to your favorite web sites, you have one final task to
perform: determine the order of how the links will display on your web site.
Select Preferences and scroll down to the section that says Sorting your links, as
illustrated in Figure 10.20.
Figure 10.20. Setting the order in which your links appear on the page
■ Now all you need to do is access the code required for this feature to function
on your web site. Go back to the Control Panel’s homepage and click on the Get
Code link. It will look like this:
Order the print version of this book to get all 400+ pages!
402 Build Your Own Web Site The Right Way Using HTML & CSS
<script language="javascript" type="text/javascript"
src="http://rpc.blogrolling.com/display.php?r=ad7cab20d092c
2ee809d009e26ffcc11"></script>
Integrating the Blogroll with Your Web Site
Usually, people add Blogrolls to their sites’ homepages, tucked away to one side.
I’m going to do the same with the Bubble Under Blogroll.
As with the other sections on your web site, it’s a good idea to wrap the Blogroll in
a div element with an id attribute. This approach will allow you to reference the
div in a style sheet, and makes it easy to find the Blogroll when you look through
the markup at a later date. Here’s the markup for the Bubble Under homepage (in
dex.html), once the Blogroll has been added (for your Blogroll, you’d have a different
value for the script’s src attribute):
index.html (excerpt)
<div id="navigation">
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="about.html">About Us</a></li>
<li><a href="events.html">Club Events</a></li>
<li><a href="contact.html">Contact Us</a></li>
<li><a href="gallery.html">Image Gallery</a></li>
</ul>
</div>
<div id="bodycontent">
<div id="blogroll">
<h2>Recently updated Diving Sites</h2>
<script language="javascript" type="text/javascript"
src="http://rpc.blogrolling.com/display.php?r=ad7cab20d092c2
ee809d009e26ffcc11"></script>
</div>
<h2>Welcome to our super-dooper Scuba site</h2>
<p><img src="divers-circle.jpg" alt="A circle of divers practice
their skills" width="200" height="162"/></p>
<p>Glad you could drop in and share some air with us! You've
passed your underwater navigation skills and successfully
found your way to the start point - or in this case, our
home page. </p>
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 403
Without any further intervention, your list may look a little on the dull side. Let’s
suppose you wanted to style your Blogroll. This code will do the trick:
#blogroll {
float: right;
margin-top: 55px;
margin-left: 10px;
margin-bottom: 10px;
margin-right: 10px;
width: 130px;
border: 1px solid #006;
font-size: x-small;
}
#blogroll h2 {
font-size: x-small;
background: #006;
color: #fff;
padding: 5px;
margin: 0;
}
#blogroll div {
padding: 5px;
}
Note that I’ve used contextual selectors (remember them from Chapter 3 and
Chapter 4?) to style the heading as well as the links themselves. Although you can’t
see it from the code extract that BlogRolling provided (all that’s visible is a link to
a JavaScript file), each link that we add is wrapped in a div. I’ve added a little
padding to each div inside the blogroll container, like so:
#blogroll div {
padding: 5px;
}
Also note that I’ve floated the blogroll div, and given it a specific width. This will
place the list on the right-hand side of the screen (to the right of the previously
floated feature image). Figure 10.21 shows how all this fits together on the page.
Order the print version of this book to get all 400+ pages!
404 Build Your Own Web Site The Right Way Using HTML & CSS
Figure 10.21. The blogroll in place
We’ve added a Blogroll! Now, any time you add a good web site to your book
marks—and it’s related to your own web site’s theme—you might consider adding
it to your Blogroll, too. All you need to do is head over to the BlogRolling site, log
in, and add a link as we did above.
Discussion Forums
Arguably, one of the best ways to create a virtual community around your web
site—and to ensure that people come back time and time again—is to provide a chat
forum. There is one small problem, though—forums aren’t particularly straightfor
ward to set up. Furthermore, once you start to have regular posts appearing, you’ll
face the issue of moderating the forum’s content. Will you moderate it yourself?
Will you just let the forum discussions take their own course?11 Will you empower
regular visitors to moderate the forums?
11 The short answer to that is: no! If you give people the freedom to run wild, they may well do just
that—which could even place you in hot water, legally speaking. For example, a forum member could
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
Pimp My Site: Cool Stuff You Can Add for Free 405
Most of the fully featured (and free) forum software products that you could use
have some prerequisites that basically rule out my covering them in this book. For
example, many packages require your hosting company to support PHP (a scripting
language) and to make a MySQL database available to you. At this stage, you probably
find these quite foreign concepts.
A simple solution for creating a community is to use Yahoo Groups.12 Signing up
for the service is as simple as registering for an email account with Yahoo. Then,
you can invite people to take part by registering for the discussion group themselves.
The beauty of using Yahoo Groups is that many people will already be familiar with
Yahoo services—possibly having sign-in details they can use from their Yahoo mail
accounts. Also, the service is provided by a company that you know and can trust
and, as such, it’s unlikely to disappear overnight—taking your new virtual com
munity with it.
The downside of using Yahoo Groups is that this option takes users away from your
web site. The best that you can do is to provide a link from your web site to the
group that you set up. From that point forward, your community is entirely in the
hands of Yahoo (capable though they are), but could present problems if you ever
wanted to move the forum to another location.
Summary
In this chapter I’ve shown that no matter how much work you put into building a
web site, there’s always more you can do. I’ve focused on some add-ons that, I be
lieve, really do improve a web site and encourage you—as well as others visiting
the site—to use it more. However, I would like to sound one note of warning at this
point, and it is this:
Know when to stop!
There are many web sites still kicking around today that were built in the mid-to
late 90s, when the motto seemed to be: the more flashing/spinning/bouncing widgets
on the page, the better the web site. Thankfully, as the art of web design has matured,
slander another user on your forum, or link to copyrighted material for others to download, and you as
the web site owner could be responsible for those people’s actions. Moderation is a great idea.
12 http://groups.yahoo.com/
Order the print version of this book to get all 400+ pages!
406 Build Your Own Web Site The Right Way Using HTML & CSS
people have come to realize that less is more. Please bear this in mind when adding
features. Otherwise, before you know it, the bells and whistles will have taken over
completely!
Don’t Be too Reliant on Third-party Services
There’s one other reason not to go overboard adding third-party features to your
web site. If that third party’s web server is slow for some reason, and your web
page is trying to access that provider’s server, your web page may appear to load
slowly. Also, you need to be careful about putting all your eggs into one basket.
If the service you use is free, be prepared that one day, the owners may decide to
close the service down, or charge for it. Would your web site be able to function
properly if this happened?
At this point, your web site should have all the features that it needs. If you’ve fol
lowed the advice I’ve given in this book, you’ll have a well-formed, standards-based
web site that you can be proud of. If you’ve enjoyed designing and building your
web pages, you might want to improve your skills even further. Instead of me
leaving you to fend for yourself at this point, I’m going to make some suggestions
about where you can acquire the skills you need; frankly, there are an awful lot of
bad web sites and books out there, and you could easily pick one up by mistake.
I’d hate for you to undo any of the good work you’ve done so far! So, let’s continue
on to the final chapter, in which we’ll explore the possibilities that now lie before
you.
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
What’s Next?
If you’ve enjoyed these chapters from Build Your Own Web Site
The Right Way Using HTML & CSS, 2nd Edition, order yourself a
copy today!
In this easy-to-follow guide you’ll learn how to build a web site
the best way possible–by doing it yourself! Ian will help you
along, but by following this step-by-step guide to building an
example web site, you’ll find that the training wheels will be off
before you know it.
In the remaining chapters, you’ll learn how to implement
important web site features, such as:
 easy to use navigation
 a professional-looking header
 a regularly updated News/Events section
 a Contact Us page with a form
 a simple Image Gallery
 a search engine that covers your site, as well as related
sites
 and much more ...
Order the complete printed edition now!What’s Next?
If you’ve enjoyed these chapters from Build Your Own Web Site
The Right Way Using HTML & CSS, 2nd Edition, order yourself a
copy today!
In this easy-to-follow guide you’ll learn how to build a web site
the best way possible–by doing it yourself! Ian will help you
along, but by following this step-by-step guide to building an
example web site, you’ll find that the training wheels will be off
before you know it.
In the remaining chapters, you’ll learn how to implement
important web site features, such as:
 easy to use navigation
 a professional-looking header
 a regularly updated News/Events section
 a Contact Us page with a form
 a simple Image Gallery
 a search engine that covers your site, as well as related
sites
 and much more ...
Order the complete printed edition now!
Index
Symbols
# (number sign), 99
, (comma), 101
; (semicolon), 73
{} (curly braces), 76
“” (quotation marks), 84
A
a (anchor) element, 62–65
A List Apart web site, 411
absolute positioning
using, 151–161, 162–164
accessibility (see web accessibility)
action attribute, 253
addresses (see URLs)
alignment
tables, 230
alpha channel transparency, 185
alt attribute, 178
anchors (see links)
anonymous comments
blogs, 364
Apache web server, 319
assistive devices
about, 227
screen readers, 97
attributes
(see also specific)
defined, 26
sharing ids, 52
B
background images, 210–221
height and width, 216
for navigation area, 218–221
non-repeating images, 214
repeated patterns, 210
shorthand backgrounds, 216
for tables, 240
background-color property, 88, 92
bandwidth
defined, 309
web hosting, 317
best practices
warning about copying from other web
sites, 21
block-level elements, 118–135
borders, 128–135
IE width bug, 416
margins, 145
sizing, 124–128
versus inline elements, 118–124
blockquote element, 66
Blogger, 340, 343–374
Blogroll, 399–405
blogs, 339–376
Blogger, 343–374
Blogroll, 399–405
contributions to, 374
defined, 340
services for, 340
body element, 30, 82
bold border effects
block-level elements, 131
bookmarks
web forwarding services and, 312
border property
absolute positioning and, 152Index
Symbols
# (number sign), 99
, (comma), 101
; (semicolon), 73
{} (curly braces), 76
“” (quotation marks), 84
A
a (anchor) element, 62–65
A List Apart web site, 411
absolute positioning
using, 151–161, 162–164
accessibility (see web accessibility)
action attribute, 253
addresses (see URLs)
alignment
tables, 230
alpha channel transparency, 185
alt attribute, 178
anchors (see links)
anonymous comments
blogs, 364
Apache web server, 319
assistive devices
about, 227
screen readers, 97
attributes
(see also specific)
defined, 26
sharing ids, 52
B
background images, 210–221
height and width, 216
for navigation area, 218–221
non-repeating images, 214
repeated patterns, 210
shorthand backgrounds, 216
for tables, 240
background-color property, 88, 92
bandwidth
defined, 309
web hosting, 317
best practices
warning about copying from other web
sites, 21
block-level elements, 118–135
borders, 128–135
IE width bug, 416
margins, 145
sizing, 124–128
versus inline elements, 118–124
blockquote element, 66
Blogger, 340, 343–374
Blogroll, 399–405
blogs, 339–376
Blogger, 343–374
Blogroll, 399–405
contributions to, 374
defined, 340
services for, 340
body element, 30, 82
bold border effects
block-level elements, 131
bookmarks
web forwarding services and, 312
border property
absolute positioning and, 152
426
borders
block-level elements, 128–135
padding, 142–145
tables, 230
Box Model Hack, 417
box models
block-level elements, 146
br (break) element, 69
browsers
appearance of web pages in, 321
block quotes, 68
clearing history, 108
CSS hacks and, 417
Firefox, 7, 9
hiding markup using comments, 38
Internet Explorer, 4
page loading, 227
refreshing page view, 85
Safari, 5
title bar, 26
web site statistics, 390
buttons (see radio buttons; submit but
tons)
C
caching
in browsers, 85
caption element, 193
captioning
image galleries, 193–198
captions
tables, 234
case sensitivity
tags, 33
cells
merging, 242
spacing, 231
styling, 241
character sets
defining with meta elements, 29
checkboxes
forms, 259, 284
cite (citation) element, 68
class attributes, 374
class selectors
about, 109–112
classes
(see also pseudo-classes)
contact class, 274
limiting to specific elements, 111
naming, 129
span class, 113
styling partial text using span element,
113
styling tables, 232
“Click here” links, 63
client-side scripting, 419–421
Client–Server Model, 307
codes
for symbols, 39
color
background-color property, 88
borders, 135
hexadecimal numbers for, 88
for links in browsers, 104
text, 241
colspan attribute, 243
column-based layouts, 419
comma (,), 101
commenting out
XHTML, 38
comments
blogs, 364
XHTML, 36
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)426
borders
block-level elements, 128–135
padding, 142–145
tables, 230
Box Model Hack, 417
box models
block-level elements, 146
br (break) element, 69
browsers
appearance of web pages in, 321
block quotes, 68
clearing history, 108
CSS hacks and, 417
Firefox, 7, 9
hiding markup using comments, 38
Internet Explorer, 4
page loading, 227
refreshing page view, 85
Safari, 5
title bar, 26
web site statistics, 390
buttons (see radio buttons; submit but
tons)
C
caching
in browsers, 85
caption element, 193
captioning
image galleries, 193–198
captions
tables, 234
case sensitivity
tags, 33
cells
merging, 242
spacing, 231
styling, 241
character sets
defining with meta elements, 29
checkboxes
forms, 259, 284
cite (citation) element, 68
class attributes, 374
class selectors
about, 109–112
classes
(see also pseudo-classes)
contact class, 274
limiting to specific elements, 111
naming, 129
span class, 113
styling partial text using span element,
113
styling tables, 232
“Click here” links, 63
client-side scripting, 419–421
Client–Server Model, 307
codes
for symbols, 39
color
background-color property, 88
borders, 135
hexadecimal numbers for, 88
for links in browsers, 104
text, 241
colspan attribute, 243
column-based layouts, 419
comma (,), 101
commenting out
XHTML, 38
comments
blogs, 364
XHTML, 36
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
427
compatibility
HTML versions, 23
contact class, 274
contact pages
building, 268–288
containing elements, 118
content
inside div elements, 50
contextual selectors
about, 100
controls
forms, 255, 274
Crop, 200
CSS, 414
current version, 413
design examples, 412
discussion lists, 415
resources, 412–419
CSS (Cascading Style Sheets)
defined, 72
prior to CSS, 78
The CSS Anthology: 101 Essential Tips,
Tricks & Hacks, 175
CSS floats, 168
CSS hacks, 417–418
CSS Zen Garden, 412
CSS-Discuss, 415, 418
Ctrl key, 264
curly braces ({}), 76
Cyberduck, 327
D
Dashboard, Blogger, 355
dashed borders
block-level elements, 133
data
(see also tables)
processing forms, 269, 289
databases
scripting languages, 320
web hosting, 319
declarations
border styles, 134
defined, 72
examples of, 88
defaults
emphasis and strong elements, 69
form appearance in different browsers,
266
deleting
commenting out as an alternative to,
38
directories (see folders)
discussion forums
about, 404
distinguished from lists, 416
HTML and XHTML, 335
posting on, 337
SitePoint, 17
discussion lists, 415, 416
div element, 50, 275
div tag, 56
diving site example
shaping and sizing, 136–148
Dock (Mac OS X)
dragging applications to, 6
doctype (short for Document Type
Definition), 23
doctype switching, 147
documentation
image editors, 206
domain names
defined, 309
Order the print version of this book to get all 400+ pages!
428
dotted borders
block-level elements, 132
double borders
block-level elements, 133
downloads
image editors, 10
page layouts using tables, 227
Picasa, 12
dynamic content, 424
E
editing
(see also HTML editors; image editors;
text editors)
images, 198–206
elastic web design, 167
elements, 24–32, 62–70
(see also XHTML elements)
a (anchor) element, 62–65
block-level versus inline, 118–124
blockquote element, 66
body element, 30, 82
br (break) element, 69
cite (citation) element, 68
coding using editors, 30
context of, 97–100
div element, 50, 275
em (emphasis) element, 68
emphasis element, 38
fieldset element, 254, 270
form element, 250, 252, 270
h1 (main header) element, 220
head element, 26
html element, 24
img (image) element, 48, 178
input element, 255–262
label element, 255, 256, 278
legend element, 254, 272
li (unordered list) element, 34
limiting classes to specific elements,
111
link element, 80
meta element, 28
nesting, 54–57
ol (ordered list) element, 34
p (paragraph) element, 34, 275
positioning, 148–161
pre element, 56
select element, 262, 280
strong element, 68
textarea element, 264, 282
title element, 27, 313
elements, XHTML
HTML Dog and, 411
em (emphasis) element, 68
email
clickable links, 48
folders, 416
in forms, 303
preferred discussion list styles, 416
signatures, 337
web hosting, 318
embedded style sheets, 76–78
emphasis element, 38
emphasized text, 93
empty elements
self-closing, 29
entities
as replacement for symbols, 39
event table example, 235–241
examples
background images, 210–221
basic skeleton web page, 22
basic web page with content, 31
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
429
block-level elements, 119
Blogger, 356–374
Blogroll, 402
body element in style sheet, 82
body elements, 30
borders for block-level elements, 129–
134
commenting out, 38
comments, 37
embedded styles, 76
external CSS file, 79
forms, 251–302
homepage, 41–57
image gallery, 187–198, 206
inline elements, 121–122
linking CSS to web pages, 80
linking web pages, 64
meta elements, 28
nesting div elements, 54
padding and margins, 136–148
positioning, 148–161, 162–173
Rollyo, 396
search tool, 390
sizing up blocks, 124–126
splitting up web pages, 60
statistics code, 386
style sheet styles, 86–114
symbols, 39
tables, 229–246
unordered lists, 35
welcoming new visitors, 43
extensions
files, 58
image files, 183
external style sheets, 78–81
creating, 79
linking to web pages, 80
Extreme Tracking service, 380
F
fade
tag lines, 219
fieldset element, 254, 270
file extensions
image files, 183
viewing, 58
filenames
for style sheets, 103
files
size of, 317
uploading files to, 321–330
FileZilla, 322
Firefox, 7, 9
forms, 266
Flickr, 209
floated positioning
using, 168–174
flow-on effects, 192
folders
My Documents folder, 14
Sites folder, 16
font sizing, 419
font-family property, 82, 92
fonts
viewing on-screen, 83
font-size property, 92
font-style property, 93
font-weight property, 93
footers, 419
form element, 250, 252, 270
formatting
image galleries, 191
forms, 249–306
about, 250
Order the print version of this book to get all 400+ pages!
430
contact pages, 268–288
sample code for, 289–305
simple form example, 251
forums (see discussion forums)
forwarding (see web forwarding)
frames
web forwarding, 312
FTP (File Transfer Protocol)
defined, 309
publishing blogs, 352
settings for, 322
web hosting, 314
G
galleries
image galleries, 187–198
thumbnail galleries, 208
genre
searching by, 393–398
get method versus post method, 253
GIF image format, 184
Google accounts, 380
Google Analytics, 380, 388
Google Search, 253, 393
GraphicConverter, 12, 202
grouping
styles, 101
H
h1 (main header) element, 220
hacks, CSS, 417–418
head element, 26
headings
CSS, 84
document hierarchy, 33
versus id attribute value of “header”,
53
height
background images, 216
block-level elements, 125
height attribute, 178
help
SitePoint forums, 17
hexadecimal numbers, 88
hidden inputs, 259
hierarchy
headings in document, 33
history
clearing in browser, 108
homepages
about, 41–57
nesting, 54–57
paragraphs, 44
splitting, 57–62
structure, 50
subheadings, 43
title, 42
horizontal repeats
background images, 211
hosting (see web hosting)
hover state
defined, 105
href attribute, 62, 80
HTML
(see also web pages; XHTML)
compatibility, 23
discussion forum, 335
HTML Dog, 411
HTML editors
NoteTab, 7
html element, 24
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
I
431
HTML elements
presentational, 97
HTML5 specification, 23
HTTPS
security, 258
id attribute, 257
sharing of, 52
versus class attribute, 111
image editors, 9–13
documentation, 206
GraphicConverter, 12
iPhoto, 13
Picasa, 11
image galleries
adding, 187–198
thumbnail galleries, 208
images, 177–222
(see also background images)
captioning, 193–198
editing, 198–206
file formats, 183
formatting, 191
image galleries, 187–198, 206
inline, 178–183
sourcing, 209
transparency, 184
IMAP, 318
img (image) element, 48, 178
indents
in source markup, 56
inline elements
versus block-level elements, 118–124
inline styles
about, 72
compare to embedded styles, 77
embedded style sheets, 76
input controls
forms, 274
input element, 255–262
inset borders
block-level elements, 130
Internet Explorer, 4
block element rendering in Windows,
416
clearing history, 108
empty fieldset elements, 271
forms, 266
Internet Explores
box models, 147
iPhoto, 13
italics
versus emphasis, 97
J
JavaScript, 419–421
JPEG image format, 184
L
label element, 255, 256, 278
languages
(see also scripting languages)
layouts (see borders; height; padding;
positioning; sizing; width)
legend element, 254, 272
li (unordered list) element, 34
linearization
tables, 233
line-height property, 89
link element, 80
link exchanges, 338
Order the print version of this book to get all 400+ pages!
432
links
checking, 330
email, 48
external style sheets to web pages, 80
link text, 62
styling, 104–108
web pages, 62–65
lists
(see also discussion lists)
styling, 174
unordered, 34
LiveJournal, 341
M
Mac OS X
Firefox, 9
GraphicConverter, 12
iPhoto, 13
Safari, 5
Sites folder, 16
TextEdit, 5
TextWrangler, 8
mailto: prefix, 48
margins
block-level elements, 145
markup
indents in, 56
maxlength attribute, 257
media types, 416, 419
merging
table cells, 242
meta element, 28
meta tag, 22
method attribute, 252
Microsoft Windows (see Windows)
moderators
discussion forums, 404
mouse
submitting forms, 265
Movable Type, 342
My Documents folder, 14, 325
N
name attribute, 257
names
(see also domain names)
attributes, 26
naming
classes, 129
navigation
background images, 218–221
image galleries, 187
navigation area
location of, 162
size of, 127
nesting
elements, 54–57
fieldset elements, 254
inline elements, 121
non-repeating images
background images, 214
Notepad, 3
NoteTab, 7
number sign (#), 99
numbers, hexadecimal, 88
O
ol (ordered list) element, 34
Open Directory Project, 336
options
selecting, 262
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
433
OS X (see Mac OS X)
P
p (paragraph) element, 34, 275
padding
borders, 142–145
padding property, 90
removing for absolute positioning, 152
pages (see web pages)
paragraphs
creating, 44–49
p (paragraph) element, 34
password input control, 258
Photo Gallery, 11
photos (see images)
PHP language, 423
(see also server-side scripting)
Picasa, 11, 199
pixels
defined, 90
planning, 2
plug-ins
blogging services, 341
PNG image format, 184
POP3, 318
positioning
absolute, 151–161, 162–164
elements, 148–161
relative, 164–168
types of, 162–174
post method versus get method, 253
pre element, 56
preselecting
checkboxes, 260
options, 263
radio buttons, 262
presentational HTML elements
emphasis versus italics, 97
print style sheets, 416
project planning, 2
promoting
web sites, 335–338
properties
defined, 73
pseudo-classes
link states, 105
publishing
blogs, 350
Q
quirks mode
Internet Explorer, 147
quotation marks (“”), 84
quotations
discussion list replies, 416
R
radio buttons
forms, 261, 284
refreshing
page view in browsers, 85
relative positioning
using, 164–168
repeated patterns
background images, 210
resizing
images, 198, 204
resources (see documentation; services)
CSS, 412–419
XHTML, 408–412
ridge borders
block-level elements, 130
Order the print version of this book to get all 400+ pages!
434
Rollyo, 393
rowspan attribute, 243
royalty-free images, 209
rules
block-level and inline elements, 118
defined, 76
S
Safari, 5
forms, 268
sans-serif fonts
viewing on-screen, 83
scope attribute, 244
screen readers, 181
presentational HTML elements, 97
summary attribute and, 234
scripting
web hosting, 319
scripting languages
client-side scripting, 419–421
server-side scripting, 421–424
search engines
presentational HTML elements, 97
submitting web sites to, 336
title element, 28
web forwarding and framesets, 313
for web sites, 390–398
Secure FTP, 314
security
password input control, 258
select element, 262, 280
selectors
class selectors, 109–112
defined, 76
self-closing elements
defined, 29
self-closing tags, 29
semicolon (;), 73
serif fonts
viewing on-screen, 83
servers
defined, 308
server-side scripting, 421–424
client-side and, 421
languages, 422
server-side scripting languages, 319
services
for blogs, 340
shortcuts
to Notepad, 3
sides
block-level elements, 133
signatures
email, 337
SitePoint forums, 17
scripting languages, 420, 423
Sites folder, 16
size attribute, 257
sizing
diving site example, 136–148
source
indents in, 56
viewing, 20
sourcing
images, 209
spacing
cells, 231
tables, 230
spam
blog comments, 364
span class, 113
span element, 74, 194
special effects
images, 203
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
435
specificity
class selectors, 112
splitting
web pages, 57–62
src attribute, 178
SSIs (Server Side Includes)
web hosting, 319
states
links, 105
statistics
web site visitors, 378–390
storage
web hosting, 315
strong element, 68
structure
web pages, 22, 50–53
style attribute, 72
style sheets, 81–114
(see also external style sheets)
adding styles, 86
class selectors, 109–112
elements in context, 97–100
embedded, 76–78
filenames for, 103
grouping styles, 101
headings, 84
links, 104–108
partial text, 113
style declarations, 88–93
style switching, 419
styles
(see also inline styles)
adding, 86
grouping, 101
subheadings
creating, 43
submit buttons
forms, 265, 286
submitting
web sites to search engines, 336
summary attribute, 234
symbols
XHTML, 39
T
tables, 223–247
about, 224–230
cells, 241–244
styling, 230–233
web accessibility, 233–241, 244
tag lines
fade, 219
tags
div tag, 56
meta tag, 22
symmetry of, 122
XHTML elements, 24
templates
Blogger, 354–372
testing (see validating)
text
color, 241
emphasized, 93
input controls in forms, 274
input in forms, 256
link text, 62
sizing, 91
styling, 113
text boxes
initial value, 258
text editors
Notepad, 3
NoteTab, 7
Order the print version of this book to get all 400+ pages!
436
TextEdit, 5 U
TextWrangler, 8
textarea element, 264, 282
text-decoration property, 93
TextEdit, 5
Textpattern, 342
TextWrangler, 8
The Ultimate CSS Reference, 414
The Ultimate HTML Reference, 410
thickness
borders, 135
thumbnail galleries, 208
title bar
displaying in browser, 26
title element, 27, 313
titles
setting, 42
tools, 3–13
Firefox, 7, 9
GraphicConverter, 12
Internet Explorer, 4
iPhoto, 13
Mac OS X, 5–6, 8–9, 12–13, 16
Notepad, 3
NoteTab, 7
Picasa, 11
Safari, 5
TextEdit, 5
TextWrangler, 8
web site search, 390–398
Windows, 3–4, 7, 11–12, 14
top-down formatting, 416
traffic
web site statistics, 389
transparency
images, 184
type attribute, 257
unordered lists, 34
uploading
files to web server, 321–330
URLs (Uniform Resource Locators)
defined, 24
from hosting service, 310
user folders (Windows Vista)
displaying, 15
UTF-8
importance of, 32
V
validating
blogs, 369–372
web pages, 331–335
validation
CSS hacks and, 418
value attribute, 258
values
attributes, 26
defined, 73
vertical repeats
background images, 214
viewport
defined, 90
visitors
web site statistics, 389
to web sites, 378–390
Vista (see Windows)
W
W3C (World Wide Web Consortium)
about, 24
CSS Specification, 413
XHTML recommendations, 409
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)
437
W3C Markup Validation Service, 332
W3C’s Link Checker, 330
W3Schools, 420
web accessibility
images, 180–183
tables, 233–241, 244
web browsers (see browsers)
Web Design-L, 415
web forwarding
about, 311
email, 318
web hosting, 309–320
bandwidth, 317
defined, 309
email accounts, 318
FTP access to server, 314
jargon, 309
paying for, 314
scripting languages and databases, 319
server space, 309
SSIs, 319
storage, 315
web forwarding, 311
web pages
about, 19
appearance in different browsers, 321
basic structure, 22
creating with Blogger, 352
image galleries, 188
linking external style sheets to, 80
links, 62–65
loading, 227
merging Blogger code with, 358–368
nesting structure, 54–57
refreshing in browsers, 85
splitting, 57–62
statistics code, 386
validating, 331–335
view source, 20
web sites, 307–338
(see also URLs)
blogs, 399–405
checking links, 330
Client–Server Model, 307
homepages, 41–57
hosting, 309–320
promoting, 335–338
storing, 14–16
uploading files to server, 321–330
visitor statistics, 378–390
web standards, 407
webmail, 318
width
background images, 216
block-level elements, 124
width attribute, 178
“wiki” pages, 419
Windows
file extensions, 58
Firefox, 7
Internet Explorer, 4
My Documents folder, 14
Notepad, 3
NoteTab, 7
Picasa, 11
Windows Live Spaces, 341
WordPress, 341
X
XHTML, 19–40
basic web page example, 31
comments, 36
discussion forum, 335
doctype, 23
Order the print version of this book to get all 400+ pages!
438
elements, 24–32
headings and document hierarchy, 33
lists, 34
paragraphs, 34
resources, 408–412
symbols, 39
validation and CSS, 332
viewing source, 20
web page requirements, 22
XHTML 1.0 recommendation, 409
XHTML 1.0 Strict doctype, 332
XHTML elements
using as intended, 51
Y
Yahoo Groups, 405
Build Your Own Web Site The Right Way Using HTML & CSS (www.sitepoint.com)438
elements, 24–32
headings and document hierarchy, 33
lists, 34
paragraphs, 34
resources, 408–412
symbols, 39
validation and CSS, 332
viewing source, 20
web page requirements, 22
XHTML 1.0 recommendation, 409
