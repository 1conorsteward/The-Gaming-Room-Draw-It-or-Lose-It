The Gaming Room is a newer gaming company looking to expand their android application to other platforms. Their game, "Draw It or Lose It", pits two teams against one another in a battle of speed.
The teams are competing to collect points as they guess what the system is drawing for them. It is turn based, but if one team does not guess correctly the other team has an opportunity as well!

This documentations design section is particularly detailed. It documents the different requirements, software implications, hardware needs, and personel requirements for each operating platform The Gaming Room
would need to spread the application.

Writing the documentation aided in understanding the different languages needed for each OP. Also, the architechture piece of the documentation helped in developing the code for their application.

If given the chance to revise this documentation I would elaborate on each aspect of the design constraints. This would help development to navigate these design constraints.

Considering their main need was to port this application to other platforms the main goal was to write the various systems in platform agnostic languages that are implimentable on multiple fronts.
This includes accounting for multiple devices, ensuring browser compatability, serving the application in a sandbox envionment, and keeping it stateless for easy access anywhere with a network connection.

The software was designed with a RESTful architechture to ensure uniform interfaces, independent deployment of components, and scalability of interactions creating a layed architecture.
In the future I will build web based applications the same way, as the uniformity of experince makes for excellent user experinece. If the company is seeking a global reach I would recommend and build 
the server in the clound to reduce latency unless the company is capeable/willing to setup a net of servers across the globe.
