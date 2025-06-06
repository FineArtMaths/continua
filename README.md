# continua

:warning: **WARNING** :warning:

This project is at a very early stage and any documents you may find here are likely to be incomplete and full of errors. There's probably nothing useful here yet beyond this page.

![pic](https://user-images.githubusercontent.com/5106495/232745514-905844bb-702e-4c81-95af-978678c6ff50.png)

This repo aims to become a broad and innovative modern maths curriculum. The target audience is adults who are motivated enough to put in a sustained effort but have no formal training in maths beyond high school. The goal is to produce a set of interlinked resources with clear dependencies that are suitable for self-study or as the basis of taught courses. They come out of my long-standing educational practice in universities, art schools, adult education colleges and elsewhere. 

None of this should be understood as a criticism of what anyone is already doing. In particular, I literally have no opinion on how best to educate future mathematicians, physicists, engineers and so on. And although I think school maths curricula are in dire need of reform, that's not what this project is about.

## Continuity

The backbone is an "alternative calculus sequence" that I expect to look something like the following. 

* Point-free topology as an account of continua in the spirit of Aristotle;
* Algebraic topology with the main focus on (co)homology as a generalizable technique for measuring "the gap between ought and is";
* Differential geometry with the "locally ringed space" approach, making much use of sheaves as the most natural way to "turn local data into global information";
* Differential topology and the study of Lie groups as applications of the above;
* Riemannian geometry, with a view to showing off lots of the usual machinery. 

## Structure

Abstract algebra studies those structures that arise repeatedly while working with other mathematical objects. While I want to keep my focus on the previous theme, these subjects have enough intrinsic interest to be worth developing in a bit more detail than strictly necessary. They include:

* Group theory, especially its connection with symmetry and therefore geometry;
* Linear algebra, which for a long time I've had good luck teaching by emphasising tensor products;
* Homological algebra, an indispensible toolkit in the study of continuity (and elsewhere);
* Galois theory, whose key theme is extension problems and the obstructions to solving them;
* Lie groups, representation theory and group cohomology, which can be seen as both an application of our understanding of continua and a means to extend it;
* Hopf algebras, examples of which appear at the core of the theory of continua.

I will also probably develop a very minimal survey course in abstract algebra for folks who don't want to fuss with all these topics but need some of the language of groups, rings, vector spaces and so on to understand the material about continuity.

## Measure

These are lower-priority topics I have an interest in, and have taught to various degrees, that don't fit into the main story. They include 

* Probability
* Statistics 
* Financial maths

which are all underpinned by measure theory. Because of this common root, these topics may organise themselves into something more substantial in time. They might also end up being cut from the project as the first two sections grow horribly out of control.

# Overall Structure

The project is broken down into **blocks**, each of which will result in one or more **courses**. Each block will have a course called "Introduction to X" where X is the name of the block; other courses in the block will usually have this as a prerequisite. The prerequisite structure of courses *within* each block is currently undecided. 

Prerequisites *between* blocks are shown in the dependencies document in this folder; if block X is a prerequisite for block Y, only "Intrtoduction to X" is needed to start on block Y. For example, suppose the Algebraic Topology block contained courses "Introduction to Algebraic Topology", "Homotopy Theory" and "Topology of 4-Manifolds", while the Smooth Manifolds block contains courses "Introduction to Smooth Manifolds" and "Applications of the Cartan Calculus". Further, suppose that Algebraic Topology is a prerequisite for Smooth Manifolds (as it in fact is). It follows that the prerequisites for "Applications of the Cartan Calculus" are:

* Introduction to Smooth Manifolds, because Applications of the Cartan Calculus is part of the Smooth Manifolds block but isn't the introduction course; and
* Introduction to Algebraic Topology, because this is a prerequisite for any course in the Smooth Manifolds block

I hope this will be a lot clearer when there are enough courses in place that we can start building a detailed diagram. But that will be a long way off; I wanted to capture the general idea here as it will inform choices about which courses to create and sequencing the work on them.

# General Approach

![general_approach](https://github.com/user-attachments/assets/fdbe7301-61ce-484b-beee-14dca6e1fdc4)

We begin with an outline of the main strand (Continuity, Structure and Measure) that identifies the blocks I expect to have in each of them. These are the `overview.tex` documents in the main strands' folders.

Then for each block we produce a "notes" document, which is my attempt to synthesize all the main information without care for pedagogy or even the needs of any reader besides myself. These files have names like `notes-02-algebraic-topology.tex` and compiling that information in an orderly way will be the first real task of the project. These files are likely to initially be created as skeletons, perhaps with nothing but headings and a few links or remarks I don't want to forget.

These notes will then be used to build the coursebooks that are the final output of the project. They'll be available here as downloadable PDFs and elsewhere as hard copies (I haven't decided how best to do that yet). In some cases I expect to have more than one coursebook for a single block.

It would be ideal to produce all the notes documents, work out which topics need to be included in the Introduction courses (because they're required in later courses) and then start writing the coursebooks. Realistically, though, I think it makes sense to proceed more iteratively since (a) assumptions about prerequisites may not survive contact with reality and (b) it will be more sustainable for me to be able to work on research and note-taking in parallel. I intend to work on Continuity and Structure in parallel but with priority on the former, ignoring Measure for now. 

Starting in early 2025 I expect to get four or five notes documents to a reasonable state of completeness, then start producing coursebooks and more notes in parallel. A couple of courses are already quite well-developed but need to be typeset into LaTeX and reconfigured for the needs of the current project. By the end of 2025 we should have several coursebooks in a complete state (but subject to revision) and notes documents approaching completion for several more. I hope to have first drafts of most (perhaps all) of the coursebooks done by the end of 2027, with pilot courses already running well before then.

Eventually there'll be a detailed roadmap to completion here with regular updates but that's not likely to happen before 2026.

License: [CC-BY-NC-SA-4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
