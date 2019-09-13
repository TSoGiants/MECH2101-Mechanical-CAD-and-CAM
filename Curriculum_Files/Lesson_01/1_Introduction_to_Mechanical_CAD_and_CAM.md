# Introduction to Mechanical CAD and CAM

## Mechanical CAD

Computer aided design (CAD) refers to the use of computers to aid in the creation, modification, analysis, or optimization of a design. [1] Mechanical CAD tools aid engineers and industrial designers as they work to design functional components, product housings, and other mechanical parts and assemblies.

Throughout this course, you will work with Alibre Design, a parametric mechanical CAD tool. You will learn to draft parts, combine these parts into assemblies, and produce professional drawings (blueprints) of your designs.

### Parts vs. Assemblies

The distinction between mechanical *parts* vs. mechanical *assemblies* is an important one. A mechanical part refers to a single, distinct component that would be used either on its own or as part of a larger mechanical system. A part could be an off-the-shelf component, a fastener like a screw or a bolt, or a design of your own. Figure 1 shows an example of a mechanical part drafted in Alibre Design.

![A mechanical part.](https://github.com/TSoGiants/MECH2101-Mechanical-CAD-and-CAM/blob/master/Curriculum_Files/Lesson_01/Images/figure1-1.png?raw=true)

<p class="caption">Figure 1. An example of a mechanical part - a button used in the water bottle rocket trigger mechanism designed on Work in Progress.</p>
A mechanical assembly is a collection of parts assembled to form a larger device. Each part in an assembly is typically designed and fabricated at least partiallyindepdendently from the other components in the design. Assemblies can consist of as few as two parts, or as many as hundreds or even thousands for complex mechanical systems. Figure 2 shows a simple mechanical assembly drafted in Alibre Design.

![A mechanical assembly.](https://github.com/TSoGiants/MECH2101-Mechanical-CAD-and-CAM/blob/master/Curriculum_Files/Lesson_01/Images/figure1-2.png?raw=true)

<p class="caption">Figure 2. An example of a mechanical assembly - the water bottle rocket trigger mechanism designed on Work in Progress. Notice the button part from Figure 1, included in this assembly.</p>
### Parametric vs. Direct CAD
Mechanical CAD tools can be broadly separated into two categories: *direct* and *parametric*. In direct CAD tools, mechanical parts are produced by pushing, pulling, and otherwise manipulating geometry directly, a bit like modeling with clay. This is particularly suited for modeling organic shapes and artistic designs, but not as well suited for functional mechanical structures.

In parametric CAD tools, mechanical parts are produced through a series of 2D (and sometimes 3D) *sketches*, which are used to define *features* that make up the part. Features add and remove material from the part, but remain linked to the sketches and parameters that define them. This is particularly suited for modeling functional mechanical structures with a need for precise dimensions.

In a direct CAD tool, the geometry of the part itself is saved in the part file. When a file is reopened, the part's geometry can continue to be edited, but the history of how the part was initially created is lost. In a parametric CAD tool, the geometry of the part itself is *not* saved; instead, the part file consists of the set of steps (sketches and features) used to produce the part initially. Each time a parametric CAD file is opened, the part's geometry is recreated by repeating these steps. This makes it much easier to modify a well-designed parametric CAD part, as each of the steps can be directly edited and the part rebuilt at any time.

Most CAD software consists of a mixture of both direct and parametric tools, but focus is typically placed heavily on one over the other. Some examples of CAD software that primarily uses direct CAD tools are Autodesk Maya, 3DS Max, and Google Sketchup. Some examples of CAD software that leans heavily on parametric CAD tools are Dassault Systèmes Solidworks (currently the *industry standard*, i.e. the tool a majority of professional engineers use), Autodesk Inventor, and Alibre Design.

Although each piece of software has their specific features and quirks, most of the core functionality within parametric CAD tools is lagely interchangeable. If you learn the parametric CAD process well, you should have an easy time transitioning from one piece of software to another if the need arises.

## Mechanical CAM
Computer aided manufacturing (CAM) refers to the usage of software to control manufacturing tools used to fabricate parts and assemblies. There are many different manufacturing technologies available, and each has its own set of CAM tools. Although the focus of this course will be placed on design moreso than manufacturing, we will also discuss some of the tools and techniques used in fabrication. A good mechanical design takes into consideration the materials and manufacturing processes from which it will ultimately be produced!

### Rapid Prototyping
When we think of manufacturing, we typically think of producing items on a large scale; most dictionary definitions of *manufacture* reflect this: "the making of goods or wares by manual labor or by machinery, especially on a large scale." [2] Mass manufacture is typically accomplished with some form of mold or other intermediary manufacturing step that allows for many parts to be produced from a single template. Some examples of this are seen in the links below:

* [LEGO bricks being manufactured using plastic injection molding.](https://www.youtube.com/watch?v=y1Zhpdx-XtA)
* [Hubcaps being manufactured using aluminum die casting.](https://www.youtube.com/watch?v=N6ODcxK8_lg)
* [Plastic bottles being manufactured using a combination of injection molding and stretch blow molding.](https://www.youtube.com/watch?v=Gt9DRifRwn0)

These manufacturing processes are wonderful for producing a large number of parts from a finished design; however, production of molds and large-scale manufacturing processes is expensive, and not suitable for small-scale production or part prototyping. For this, a number of technologies referred to as *rapid prototyping* techniques have been developed to aid engineers in the design process. Rapid prototyping refers to techniques used to quickly fabricate a part or assembly directly using 3D CAD data. [3] The absence of an intermediary mold being produced greatly reduces both the time and expense of fabrication; since prototyping is an iterative process, these technologies have become an integral part of modern mechanical engineering.

### Additive vs. Subtractive Manufacturing
Rapid prototyping technologies may be broadly categorized into either *additive* or *subtractive* processes. As the names imply, additive manufacturing produces parts by *adding* material, or building up the part from nothing. Additive manufacturing technologies are often referred to as *3D printing*.

Subtractive manufacturing processes produce parts by *subtracting* material from a piece of stock material. Computer numerical control (CNC) of subtractive processes can be applied to milling, lathing, and various forms of etching and cutting to create rapid subtractive prototyping solutions.

We will cover rapid manufacturing methods in more detail in a future lesson. For now, take a look at a few examples seen in the links below:

* FDM (TODO)
* SLA
* CNC Mill
* Laser Cutter 

## In This Lesson
In this lesson, you will learn how to accurately measure existing parts and familiarize yourself with the Alibre Design interface. We will focus specifically on the workflow for drafting parts in this lesson, with additional part modeling practice and how to produce assemblies being covered in the next lesson.


## References

[1] L.K. Narayan, *Computer Aided Design and Manufacturing*, New Delhi: Prentice Hall of India, 2008.

[2] "Manufacture," *Dictionary.com Unabridged*. Random House, Inc., 2019 [Online]. Available: https://www.dictionary.com/browse/manufacture. [Accessed: 12-Sep-2019]

[3] "Rapid Prototyping: An Overview," *efunda*. [Online]. Available: http://www.efunda.com/processes/rapid_prototyping/intro.cfm. [Accessed: 12-Sep-2019].