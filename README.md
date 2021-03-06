"Jammazwan" [is Hindi](href="https://books.google.com/books?id=_kWROaer5UsC&amp;pg=PA1138&amp;lpg=PA1138&amp;dq=jammazwan+camel+keeper+hindi&amp;source=bl&amp;ots=7FaF5BXK_F&amp;sig=Cg-U5ORP3dHrFycaCFvo34GdpZ0&amp;hl=en&amp;sa=X&amp;ved=0ahUKEwj8v4OV3YbNAhVjpIMKHSYUB_oQ6AEIHDAA#v=onepage&amp;q=jammazwan%20camel%20keeper%20hindi&amp;f=false) for "camel keeper", and is [explained in this blog](https://betterologist.net/2016/05/jammazwan-projects-for-learning-apache-camel/).

|[**_a jammazwan?_**](https://betterologist.net/2016/06/jammazwan-for-hire/)|also a jammazwan|[TL;DR? _about:_](https://youtu.be/vea51DzmXyA)|
| --- | --- | --- |
|<img class="style-svg" src="https://betterologist.net/wp-content/uploads/2016/05/pete-300x297.jpg" alt="pete" width="116" height="115" />|<img class="style-svg" src="https://betterologist.net/wp-content/uploads/2016/05/jammazwanPhotoSmall.png" alt="jammazwanPhotoSmall" width="200" height="116" />|[<img class="style-svg" src="https://betterologist.net/wp-content/uploads/2016/05/jamzVid1.png" alt="about" width="115" height="115" />](https://youtu.be/vea51DzmXyA)|
---

# jammazwan.100

This README and a separately downloadable tar, below, are about all that this project consists of. 

You may want to read these minimal instructions very carefully before doing anything, to save yourself some time.

### What jammazwan.100 is/does:

Jammazwan 100 gives you 100 starter projects in single workspace, with a set of [README Instructions](https://github.com/jammazwan/jammazwan.100/blob/master/jammazwanBatch100.txt) on how to complete these projects. Check out [the instructions themselves](https://github.com/jammazwan/jammazwan.100/blob/master/jammazwanBatch100.txt) if this isn't yet making sense to you.

It will put you through maybe not 100, (there are a few dupes, as it is randomly generated) but almost 100 unique variations of Camel integration projects. From JPA to CSX to JMS to .... different combinations of each.

Every project tries to have at least 2 routes, and multiple technologies

When you start out, it may take quite a bit of time for _each unfamiliar project_, as you'll have to gather up the configuration details. But that is half of the point of doing this exercise. 

But once you get them down, it may take as little as 10-15 minutes per project. By the end, your Camel skills will be greatly solidified. This fulfills the other objective of **jammazwan.100**, which is to give you plenty of reps.

### How To:

Download the workspace tar from here: (github doesn't much like larger binaries). This download is confusing, because it's a workspace of projects rather than individual projects which was are more accustomed to.

http://docs.datafundamentals.com/jammazwan/jammazwan100.tar.gz

 * uncompress tar as a folder
 * open workspace folder as clean workspace (in eclipse as default, or your own favorite)
 * import as "Existing eclipse projects" any or all 
 * separately, you may or may not wish to open the file named jammazwanBatch100.txt 
 * you are now ready to write 200+ routes and test your speed.
 
### Cheat Sheet:

I am including my own text file as almost the only source in this github project. It is mostly gibberish to anyone else, but it does have almost all of the text you would need to copy into various files to complete the projects. Every pom entry, every fix to your own object to make it a bindy or JPA object, it's all there. 


Use at your own risk, no instructions included. You're supposed to be figuring all this stuff out on your own, right?

### Project README or all 100?

Each project has it's own README, which advises you on how to complete that project. But after I did a few, I found it easier to keep the [batch100 README](https://github.com/jammazwan/jammazwan.100/blob/master/jammazwanBatch100.txt) open in my text editor and complete everything from there.

### Solved:

Well, I got 85 of the 100 done. I deferred the CXF WSDL-to-code projects because I was still working on that configuration at the time. Then I never got back to them. [Go here for the completed workspace](https://github.com/jammazwan/jammazwan.100.done)

### How Were These Projects Generated?

Randomly!

Oh, but that's not what you wanted to know. They were all generated using [jammazwan.maker](https://github.com/jammazwan/jammazwan.maker), a Camel project generator. It's mostly undocumented, but you can read the code if you're desperate enough to know. 

And yes, it's all written in Camel, or camel-velocity, to be specific

### Why the aaa aab aac project prefixes? 

This is a hack to keep the randomly ordered projects randomly ordered. Else they would self-order by name, which hints loosely at their contents.

