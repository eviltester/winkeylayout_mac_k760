Windows Keyboard Layout for Logitech Mac Keyboard K760
====================

This repo contains the .klc file to create a Windows Keyboard Layout using "Microsoft Keyboard Layout Creator"

## Basic Info

I use a Windows PC for most of my work in my office. I travel with a 13 inch Macbook Pro.

Switching between computers is enough of a mental switch that I wanted to reduce some of the context switching, and the easiest way to do that seemed to be using the same keyboard layout as much as possible.

I have a Logitech K760 Solar Powered keyboard, with the mac layout. Since it can connect and switch between 3 bluetooth devices I can have it on my desk paired to the PC and the Mac, and easily switch between them when working.

Since it is a mac layout, when I go on the road, it is the same keyboard layout as my laptop.

But to make it really effective on Windows I needed a layout so that the visual keyboard mapped on to the keyboard in Windows.

Problem.

I couldn't find a driver or layout that would configure it.

Eventually I found Nick Bettison's layout. [linickx.com/macbook-pro-uk-keyboard-layout](http://www.linickx.com/macbook-pro-uk-keyboard-layout)

When I tried it, it mostly worked but wasn't complete and seemed to be missing uppercase.

Fortunately we can edit it using the Microsoft Keyboard Layout Editor.

Many thanks to Nick for making his keyboard layout publicly available, otherwise I'd never have attempted to create a layout.

I used version 1.4 which I downloaded from Microsoft.

[microsoft.com/en-us/download/details.aspx?id=22339](https://www.microsoft.com/en-us/download/details.aspx?id=22339)

The only issues I had were that the lower left and top left keys seem to be reversed in reality from what is shown in the keyboard layout creator.

* VK_OEM_8
    * §±

* VK_OEM_5
    * `~

Since I've never, ever, in my life, ever, ever needed to type § or ±

I made both of those keys map to `~ . This was also because I was having issues installing the layout and I never use those other keys.

## How to Use

* Download the `.klc` file.
* Download and install the Microsoft Keyboard Layout Editor
    * [microsoft.com/en-us/download/details.aspx?id=22339](https://www.microsoft.com/en-us/download/details.aspx?id=22339)
* Load the `.klc` file into the editor
* Use `Project \ Test Keyboard Layout...` to make sure you are happy with it
* Use `Project \ Build DLL and Setup Package` to create the setup
* Run the created setup
* Use control panel to 'Change Language Preferences'
* Edit the language and add your new keyboard layout which should be listed as 'English UK - Logitech K760 MacBook Pro' (unless you changed it)
* Then you should be good to go

I mapped:
* # on to right alt + 3
* € on to right alt + 2

There doesn't seem to be a way of mapping keys to use the left alt, which is a minor pain. And I've removed the §± and mapped it to `~

All the volume controls etc. work out of the box, so I haven't needed to attempt to change those.

Hope this helps.

Alan Richardson

------

* Alan Richardson
* [www.eviltester.com](http://www.eviltester.com)
* [www.seleniumsimplified.com](http://www.seleniumsimplified.com)
* [www.javafortesters.com](http://www.javafortesters.com)
* [www.compendiumdev.co.uk](http://www.compendiumdev.co.uk)
* [@eviltester](https://twitter.com/eviltester)



