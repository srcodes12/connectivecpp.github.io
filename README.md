Welcome to Connective C++!
We are dedicated to connecting the world through a high level, modern C++ networking API and related utilities.

Repositories
chops-net-ip, a high level, general purpose C++17 networking API that simplifies creating TCP and UDP network connections.

utility-rack, a tasty collection of utilities, including general purpose functionality used in the Chops Net IP repository.

About
Connective C++ is an open source project providing tasty libraries and code for networking applications written in the C++ language.

Why?
There is a need for easy-to-use, efficient, modern, asynchronous C++ libraries for connecting processes and devices.

Really?
Yes.

There is specially a need for libraries with nice abstractions for common networking needs.

Historically the useful and tasty abstractions have not been present in C++, or the abstractions did not provide scalability or flexibility. Connective C++ fills that need.

Why C++?
For applications running on servers or workstations, there are many choices in languages and frameworks and environments. However, for smaller devices or mobile environments, efficiency and determinism and small environment footprints often rule out languages other than C or C++. In particular, an interpreted environment (e.g. with Python) or a virtual machine (e.g. JVM for Java) is often not possible, or is too resource intensive.

People
Principal Author is Cliff Green.

Principal Co-author is Thurman Gillespy.

Team Members are Roxanne Agerone, Nathan Deutsch, Casey Ghilardi, and Bryan Concari.

Logo and banner designed by Ariel Peretz.

Contributions have been made by Matthew Earulic, Daniel Muldrew, Bob Higgins, and Matthew Briggs.

Who is Using Connective C++ Software?
Chops Net IP is in use at Sound Life Sciences, a Seattle startup creating awesome medical software and devices using high frequency sound to monitor respiration rate. This allows detection of opiod overdose, early signs of infection, and other breathing related disorders.

C++ Language Requirements and Alternatives
C++ 17 is the primary baseline for the Connective C++ projects.

A significant number of C++ 11 features are in the APIs and implementations. A C++ 03 version will not be provided in any of the Connective C++ repositories.

There are numerous C++ 14 and C++ 17 features in use, although many of them could be replaced with Boost (or similar) utilities or rewritten to use only C++ 11 capabilities. For users that don't want to use the latest C++ compilers or compile with C++ 17 flags, Martin Moene provides an excellent set of header-only libraries that implement many useful C++ library features, both C++ 17 as well as future C++ standards (see References).

While the main production branch will always be developed and tested with C++ 17 features (and relatively current compilers), alternative branches and forks for older compiler versions may be implemented. Collaboration (through forking, change requests, etc) is very welcome to achieve older compiler conformance.

References
Connective C++ would not be possible without articles, libraries, and code examples from the C++ community. The References page lists the primary influences and library providers on this project.

Team Bios
Cliff Green (cliffg at connectivecpp dot com) is a software engineer and has worked for many years writing infrastructure libraries and applications for use in networked and distributed systems, typically where high reliability or uptime is required. The domains where he has worked include wireless networks (in particular cellular 9-1-1), location technology, and large scale embedded and simulation systems in the military aerospace industry. He has volunteered many years at CppCon (when it was in Bellevue) and presented at BoostCon (before it was renamed to C++ Now).

Cliff lives in the Seattle area and you may know him from other interests including volleyball, hiking, railroading (both the model variety and the real life big ones), music, or even parent support activities (if you are having major difficulties with your teen check out the Changes Parent Support Network).

Thurman Gillespy (GitHub site, thurmang at connectivecpp dot com) is a software engineer although his first career was in diagnostic radiology, with stints at the University of Florida (1985 - 1990), University of Washington (1990 - 2008) and private practice in Seattle (2008 - 2015). In the 1990's, Thurman wrote Dr Razz, the first application that could display and manipulate radiology images on a Macintosh computer. In 2015 Thurman left medicine and went back to school to transform a life long hobby of programming into a second career as a software developer.

Roxanne Agerone (GitHub site, roxanne at connectivecpp dot com) is a software engineer working in the Seattle area and loves classic cars (among other interests). She created the Seattle C++ Meetup, typically meeting on Monday evenings, 6 pm, at Ballard Coffee Works, 2060 NW Market Street, Seattle.

Nathan Deutsch (personal website, nathand at connectivecpp dot com) is a software engineer working in Bellevue, Washington. He likes to study and play jazz guitar and go camping. He also claims to be the best pool player in the state, accepting all challengers (if you think you're good enough, contact him!).

Casey Ghilardi (caseyg at connectivecpp dot com) is a software engineer in the Seattle area, active in various open source projects.

Bryan Concari (irql at connectivecpp dot com) is a devops engineer in the Seattle area and likes to play guitar and bass. He is a computer enthusiast through and through, with a particular interest in distributed software and systems internals.

Ariel Peretz (arielinseattle29 at gmail dot com) is an avid hiker living in the Puget Sound area. He plays indoor soccer, likes drawing, the New York Yankees, Montreal and often says "friends don't let friends drink Starbucks coffee".