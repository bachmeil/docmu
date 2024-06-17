# docmu

This is a modified version of [mu css](https://github.com/BafS/mu). I made a few cosmetic changes, such as using Roboto as the font for the whole document, but the biggest thing is eliminating elements that aren't normally used to display documents. You're unlikely to need to define things such as select or textarea for an html document posted to your personal website.

# Example

You can view an <a href="https://bachmeil.github.io/docmu/test.html">example document here</a>.

# Usage

Download docmu.css from the repo to your computer. Add this at the top of your html file:

```
<link rel="stylesheet" href="docmu.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:400,400italic,700,700italic">
```

The second line is optional. I used Roboto with Google fonts because it's a popular, highly readable font that isn't necessarily installed on every computer. If you use a different font specification, you can omit the second line.

The repo includes the file test.html demonstrating the use.

# Why

[Some websites](https://danluu.com/) have little or no styling. At a minimum, this is hard to read on a widescreen monitor. Most websites, particularly those with a corporate flavor, come with insane download sizes just to provide you with contact information. It's not unusual for them to be several MB. [This post by Dan Luu](https://danluu.com/slow-device/) found that a single Wix page is 21 MB, Threads and Patreon at 13 MB, and Twitter at 11 MB. These are standard numbers, unfortunately. Even a WordPress blog post is 1.7 MB. If all you want to do is display some text for others to read, there's absolutely no reason to go with this bloat. Using a common framework like Bootstrap, the minimized CSS alone add 152K. 

[Sites like this one](https://perfectmotherfuckingwebsite.com/) popped up in response. If all you want to do is style text, there's literally no reason to have such massive downloads. The docmu.css file as of this writing weighs in at a hefty 951 bytes (yep, my file manager doesn't even show it in K, it shows it in bytes, and the size changes if I add or delete a single character).

# Customizing and Extending

Customizing and extending is easy. docmu.css is an easy-to-read text file. Open it up. Change things you don't like. Add things that are missing. Save the file. That's it; that's the whole process. There's no building or compiling necessary. It's so small there's no reason to minify it. If you like your modified version, share it with others.
