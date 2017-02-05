# JS-MultiLanguage
**A little demo code for enabling multi language websites!**

I’ve made a little demo showing how to have a multi language website in JavaScript, using jQuery.

## Why this?
- There’s no need for a server!
I made this after wanting language support but not wanting to shell out for a server

- Why not use a server?
Because you can just use cookies and JavaScript! It also means no reloading pages if someone changes the language!

## How do I use this?
- In the JavaScript, the array *langs* contains the languages you want to support.

- In the example, I’ve setup English (en), Chinese (cn), French (fr) and Japanese (jp), but you can do whatever, and use any words you like - you could even use this example for something other than languages.

- Elements in the HTML body which have the id of the current language are shown, and the rest hidden.

- To start off, it creates a cookie setting the language to English (en). All elements with id ‘en’ are shown, and other elements tagged with a language are hidden.

- So <div class=‘whatever’ id=‘en’> is shown
and <div class=‘hooray’ id=‘jp’> is hidden!

- Simples!


## License
Cba to pick one. But it’s free - free I say! Use it as you will.  A little kudos goes a long way though ;)