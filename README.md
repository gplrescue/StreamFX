## The GPL Rescue Project

The GPL, under which much open source software is distributed, guarantees the recipient of software several rights:

* the freedom to use the software for any purpose,
* the freedom to change the software to suit your needs,
* the freedom to share the software with your friends and neighbors, and
* the freedom to share the changes you make

One of the most important parts of the GPL is that it guarantees that once software is released as free software, that it *remains* free software, and that any derivative works are also free software.

Sometimes, when a piece of GPL-licensed software becomes popular, and particularly if that software accepts plugins or addons, a vibrant ecosystem pops up around that software, with hundreds of developers offering their own additions to the software -- sometimes for a fee. There is nothing inherently wrong with this, and the GPL explicitly allows for it. But sometimes the developers are a bit... abusive. This project tries to rescue GPL'd software (and its users) from this abuse.

## The GPL Abuse Problem

Addons to GPL'd software, in general, must also be licensed under the GPL as well. But some software developers feel that they are entitled to payment for their addons, and go out of their way to try to limit an end user's ability to redistribute those addons.

Some Blender addon developers, for example, include a purchaser-specific software "watermark" in the addon download, and if they find that specific copy of the addon available to the public anywhere, they remove that user's ability to download updated versions of the software.

Other developers simply make it difficult to get copies of their addons to start with, and refer to anyone who redistributes their work as "pirates" and wage smear campaigns against those people.

Some developers even threaten legal action towards anyone redistributing their software!

There isn't a firmly defined requirement for software to be included in the GPL rescue project, but in general, people or companies that get *too* abusive in their attempts to prevent redistribution of their GPL-licensed software are the target of this project. We want to work against those bad-faith actors and make GPL-licensed software actually available under the terms of the GPL.

## Don't Software Developers Deserve to Get Paid?

This is a really common response to the idea of free distribution of addons and plugins. But ultimately, it doesn't hold water.

Software licenses are a contract. "In exchange for X, you give me Y."   "In exchange for being able to use my software, you give me money."  What the give and take are can vary wildly, limited only by the parties' imaginations, and local laws.

One of the major points of the GPL is that it should be possible to build on top of existing GPL-licensed software, and redistribute the result (under the same terms).

In the case of something like Blender, the license effectively says, "In exchange for being able to build your addon on top of Blender, you must distribute your creation under the terms of the GPL, so that others can use and modify and redistribute it." The developer of the original software isn't giving it away for free -- they are explicitly requiring a payment, where that payment is "anything you make based on this must be freely redistributable". Does the developer of the original software not deserve to get paid, as well? The development of a Blender addon probably takes under 1% of the effort of developing Blender itself, so why would the addon developers be more entitled to getting their desired payment than the developers of the original software?

The addon developer's options are limited. They can:

* Negotiate a different license with all of the copyright holders of the licensed code
* Create their addon and distribute it under the terms of the GPL
* Not accept the license, and not distribute either the original work, nor addons based on the work.

That's ***it***. If they don't agree to the original software's license and can't negotiate other terms, they *do not have the legal right to use, distribute, or make derivative works based on the original software*. 


## The Trademark Question

The question of "but what happens if the GPL-licensed software is named using a trademarked term, or otherwise makes use of a trademark" is a tricky one, and if it's one that you think impacts you, you should really talk to an IP lawyer.

But some brief notes on that topic:

* A trademark is not a blanket prohibition against anyone else using a trademarked term. For the use of a term to be trademark infringement, there must be the possibility of confusion between a third party's use and the trademark owner's use; or the use must imply the trademark owner's endorsement of the third party (or their products, etc)
* By distributing GPL'd software, containing a trademarked term or not, a developer is explicitly giving distribution rights for that software to the recipient. The trademark holder can certainly limit the recipient's use of that trademark (e.g. the recipient couldn't modify the software and then redistribute their updated version under the trademarked name), but simply redistributing the software unmodified, in absence of mitigating factors, almost certainly cannot be considered infringement.

So, to make sure we don't fall afoul of anyone's trademarks:

* This project will only redistribute software in its original form, without modifications. We might change the archive format, or rename the archive file for the software slightly when needed to uniquely identify a specific build or release of the software, but the software itself will be untouched
* This project will in no way imply the endorsement of any software's developer
* When we are aware of a trademarked term being used in the same of software redistributed here, we will identify the trademark owner; and we will make sure the recipients of the software are aware that they may need to take action to ensure that their usage of the software does not violate any trademarks
