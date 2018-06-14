## Visualizing the Evolution of Systems and their Library Dependencies
###(Working Conference on Software Visualization)

[Link to Publication](http://sel.ist.osaka-u.ac.jp/lab-db/betuzuri/archive/951/951.pdf)

[Slides](http://sel.ist.osaka-u.ac.jp/lab-db/betuzuri/archive/951/951.pptx)

## Abstract
System maintainers face several challenges stemming from a system and its library dependencies evolving
separately. Novice maintainers may lack the historical knowledge required to efficiently manage an inherited system. While some
libraries are regularly updated, some systems keep a dependency on older versions. On the other hand, maintainers may be
unaware that other systems have settled on a different version of a library. In this paper, we visualize how the dependency
relation between a system and its dependencies evolves from two perspectives. Our system-centric dependency plots (SDP)
visualize the successive library versions a system depends on over time. The radial layout and heat-map metaphor provide
visual clues about the change in dependencies along the system’s release history. From this perspective, maintainers can navigate
to a library-centric dependants diffusion plot (LDP). The LDP is a time-series visualization that shows the diffusion of users across
the different versions of a library. We demonstrate on real-world systems how maintainers can benefit from our visualizations
through four case scenarios.

**Mining Tools and Libraries:**

Our Dependency Extraction Tool for Maven Libraries: [PomWalker](https://github.com/raux/PomWalker)

Java Library to mine and extract Library Migrations
[JGit](http://www.eclipse.org/jgit/)

R statistics Tool (For Visualization) [R](https://www.r-project.org/)

Notable R Packages used [ggplot2](http://ggplot2.org/), [plyr](https://cran.r-project.org/web/packages/plyr/index.html),
[sqldf](https://cran.r-project.org/web/packages/sqldf/),
[gridExtra](https://cran.r-project.org/web/packages/gridExtra/gridExtra.pdf)

Refer to [Link](https://raux.github.io/Impact-of-Security-Advisories-on-Library-Migrations/) for an advanced version of the DDP.

## Samples

Here are other samples of DDP's build for other projects.

ASM ([DDP]()) 
Javassist (DDP)
Scala (DDP)
JUnit (DDP)
Commons-io (DDP)
Bcel (DDP)
Cglib (DDP)
Spring-core (DDP)
Testng (DDP)
Derby (DDP)
Guava (DDP)
h2 (DDP)

