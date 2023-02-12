# MaliciousVST
Creating Proof-of-concept malVSTs to demonstrate security weaknesses in the status quo of the plugin framework

---

At the present, I've been building the proof-of-concepts by generating `New Plugin` boilerplate using Steinberg's official tool, and inserting the code into the plugin constructor in the myplugincontroller.cpp file located in [Plugin Name]/Scource Files/plugincontroller.cpp of the solution.

You can find the vulnerability categories and respective code that will trigger them in the [VulnCats folder](./VulnCats)

I've removed the compiled binaries from the project until I figure out a better way of safely showcasing them, but for now, feel free to explore the proof-of-concept source code avaliable in [VulnCats](./VulnCats)

<!--
The items in this repo are different versions of the mentioned file used for various demos. 

 You can find the compiled versions of them in the [Compiled](Compiled) folder
-->
