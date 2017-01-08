# Code Demo for starter-kit url navigation challenge

Summary: navigation from the menu works, navigation deployed to htpps and from a url doesn't work.

### EXACT code from running polymer-starter-kit

Current stable polymerCLI - Jan 7 2017

This code is put up to demonstrate a specific problem with url navigation to either.

 * **Expose** me for being a knucklehead and not reading the docs properly
 * **Help** me demonstrate so that it can be identified properly?

This README is the only thing in this starter-kit generated code that was changed.
Everything else is exactly as generated.

### What is the problem being demonstrated?

[See it for yourself on this https site!](https://cliffdweller.work)

 * If you click on view1, view2, view3 from the menu it **works great**.
 * If deployed on localhost the urls **work great** too, such as http://localhost:8080/view1
 * If deployed on an https site **works great** from the menus such as https://cliffdweller.work/
 * **BROKEN when accessed from https via URLs**, such as https://cliffdweller.work/view1

If it is not broken for you when you test it, **it will if you do an empty cache and hard reload** with that same url.

Note also that this does not take you to a polymer starter kit 404, but to a naked 404 provided by the browser.

### Exact sequence used to create and deploy code

 * created folder
 * cd into folder
 * > polymer init - then chose starter-kit
 * > polymer build
 * > polymer serve - for localhost
 * > scp **build/unbundled** [to cliffdweller.work https site]
 * created this README
 * committed to github


### Stack Overflow

Here is the question on stackoverflow. Jeez I sure hope I don't get flamed horribly.
https://stackoverflow.com/questions/41535672/polymer-starter-kit-navigation-by-url-broken-but-only-when-deployed
