GWSIvyRepo
---

![Ivy](https://raw.github.com/shareme/GWSIvyRepo/master/ivy-lierre.png)

# Introduction

GrottWorkShop Ivy Repo, you can use it to base your own organized IvyRepo using
Github git source storage.

# License

<a href='http://www.apache.org/license/LICENSE-2.0.html'><img src='https://raw.github.com/shareme/GWSIvyRepo/master/apache_logo.png'/></a>

Copyright 2013 Fred Grott-GrottWorkShop

   Licensed under the Apache License, Version 2.0 (the License);
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an AS IS BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
   
   
# Implementation

The whole purpose is that you want a local repo setup that you control that gives 
you; security, control over module definitions, and some reliability as its a local 
repo you control on your own network or machine.


There are several ways to do this, I choose to make a directory repo with 
subdirectories release and snapshots to closely resemble maven best practices.
The repo folder is my way of organizing it before the actual full Ivy repo is 
created that way you can see how I use the Ivy specifics in each ivy file.

Note, that I do notr set or define ivy module files with dependencies
as my repo is for both android mobile side and enterprise stuff so I do not want modules 
tightly coupled as far as dependencies are concerned as mobile tends to change 
real fast, at least faster than the enterprise side. By having modules loosely coupled 
and forcing how to get moduels down to the build engineer per project it allows 
the build engineer to change how or what artifacts a module needs to use per project and 
thus when dev processes change he or she can change that on the fly by modifing 
the  few ivy lines rather than have to change ivy files in the repo.





# Guide and Use

Ivy can be confusing for someone that has not been exposed to any dependency 
artifact system before and thus some guidance might be:

[How Ivy Works](http://ant.apache.org/ivy/history/latest-milestone/principle.html)


[Tutorials](http://ant.apache.org/ivy/history/latest-milestone/tutorial.html)

its the best way as the typical Apache Ant in Action or ProApache ANT books give 
scant coverage of how to ue apache Ivy.

[Best Practices](http://ant.apache.org/ivy/history/latest-milestone/bestpractices.html)




# Credits


# Created By

<a href='http://fredgrott.bitbucket.org'><img src='https://raw.github.com/shareme/GWSIvyRepo/master/gws_slide_logo.png'/></a>

<a href='http://about.me/fredgrott'><img src='https://raw.github.com/shareme/GWSIvyRepo/master/me-icon.png'/></a>

<a href='http://grottworkshop.blogspot.com'><img src='https://raw.github.com/shareme/GWSIvyRepo/master/blogger-icon.png'/></a>

