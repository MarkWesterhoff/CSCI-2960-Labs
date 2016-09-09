2. Why is it important to choose a LICENSE?

It is important to use a license so people properly know how to use your software/project. A license is an explicit, legal way letting other people know how they can use your work. Choosing a license that fits with your goals of the project is a necessity, and in turn allows more people to use your project (assuming you have a permission-first license).

3. Why they SHOULDN'T use a project that doesn't have an explicit license?

A project without an explicit license is treated as ALL rights reserved (i.e. copyright). This means that the original creator has the right to give permission to use their work; you cannot use it without their explicit permission. Which means that if you want to use a dead github project with an inactive creator and no license, you must get the explicit permission from the creator to use it. Which may be impossible, but if you don't and you use it, they have the right to fine you for infringing their copyright.

4. The claims made on how the World Wide Web won over Gopher do make a fair bit of sense. Ignoring the differences in internals, having a better user interface ALWAYS makes people happier. In fact, I've even seen suggestions by developers to only work on making the UI better bit by bit, because all higher ups see is the advancement in the UI. Not to mention the effects of social inertia (seriously, can we all switch to dvorak keyboards already?), more expensive hardware, more necessary maintenance, and Gopher's insistence on inventing everything in house, it really is no wonder why it didn't stand the test of time.

5. Microsoft's .NET core runtime uses the MIT license because they want to allow everyone to have the utmost freedom with .NET. It is somewhat common for companies to make in house modifications to a compiler (or in this case runtime implementation). Many companies then use their modified core to build and test their own software. If they then distribute their software, and the .NET core had a copyleft license, it could be perceived that they are distributing the results of a modified .NET core, and would then have to release the source for their modifications. Some propietary companies do not want this, and since those are te customers who Microsoft caters to, an MIT license is much more flexible for propietary businesses.


7. Licenses

GPL: A copyleft license; it is permission-first, however all derivative works or works using a GPL-licensed project must also be licenses under GPL. Protection of patent claims.

LGPL: Same as GPL, except targeted for libraries. This means that only derivative works must also be LGPL; any work simply using a LGPL licensed project may have its own license.

Apache: A permissive license; contains a patent license and allows a warranty claim.

BSD: Extremely permissive.

Use GPL if and only if you are sure every derivative work makes sense being GPL too. It works for the Linux kernel, as it simply means that all the other kernels should be free as well. It doesn't make much sense for a GPS module, as companies may want to monetize a derivative work.

Use LGPL for libraries; i.e. it is a loophole to GPL. Personally, as a developer, where you are typically making small modules/libraries anyways, this is probably the license you want.

Use Apache/BSD if you don't care about derivative works; it allows people to make businesses off of it.

TL;DR: 
Developer -> LGPL

Company -> LGPL / proprietary license

Common Good -> LGPL (personally I think GPL is too restrictive)


9. 5 RCOS Projects

Website                |   License Present   | License 

https://github.com/Behemyth/Soul-Engine  | Yes   |            GPLv3

http://www.submitty.org/             |     Yes     |          BSD 

https://github.com/AutoRoute/node     |    Yes      |         MIT

https://github.com/olivierpo/minebot.git  |  Yes       |        MIT

http://sharpnav.com/             |         Yes        |       MIT