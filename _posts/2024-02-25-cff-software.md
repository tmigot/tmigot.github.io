---
title: 'Empowering Research: The Vital Role of Citing Research Software for Reproducibility and Innovation'
date: 2024-02-25
permalink: /posts/2024/02/thoughts/
tags:
  - software
  - publications
  - best practice
  - thoughts
---

As I started my Ph.D. journey in numerical optimization back in 2014, I noticed something that really stood out to me: despite the abundance of scientific papers discussing algorithms and their numerical results, the availability of corresponding open-source codes lagged far behind.

This discrepancy posed significant challenges to reproducibility and the continuous improvement of algorithms, ultimately hindering the advancement of knowledge in the field in my opinion.
Understanding the reasons behind this gap provide insights into the complexities inherent in code development:
- Providing an open-source implementation means navigating platform choices and addressing questions and issues from users;
- Moreover, the journey from a basic implementation to a robust and efficient one requires a considerable investment of time and effort;
- The process of writing, maintaining and implementing a code wasn't necessarily valorized in scientific research.

While these challenges could be frustrating, they also presented an opportunity for transformation.
The necessity of numerical results underscores the importance of investing the development of codes.
By shifting our focus from rewriting similar codes for each publication to refining and enhancing existing implementations, we could pave the way for greater reproducibility and innovation in the field.

Furthermore, the potential impact extended beyond academia.
By improving the accessibility and quality of optimization codes, we could empower practitioners to tackle real-world problems with greater confidence and efficacy.
This shift toward research-level, super-powerful codes held the promise of addressing some of the
most pressing challenges facing our society.

In essence, what initially seemed like a frustrating discrepancy evolved into a call to action.
By embracing the challenges and opportunities inherent in code development, we could not only advance knowledge within the field but also make meaningful contributions to real-world problems.
This, I believe, is one of the most important challenges in research and one that holds the potential to create lasting positive change.

## WHY SOFTWARE MATTERS

Over the past decades, there has been a shift regarding scientific software.

*Increased Diversity and Accessibility*

Open-source software has helped democratize access to scientific tools and resources,
making them more accessible to researchers worldwide.
Additionally, the open nature of these projects encourages diversity and inclusivity,
as contributors from diverse backgrounds can participate in their development.

*Increased Adoption of Open Source*

There has been a significant rise in the adoption of open-source software in scientific research.
Researchers increasingly recognize the benefits of open-source collaboration, including transparency, reproducibility, and community-driven development.

Personally, my research journey began at INRIA, renowned as one of France's largest and most dynamic research center in computer science and applied mathematics.
At INRIA, the development of software is ingrained in the fabric of their research culture, reflecting a deep commitment to innovation and advancement in scientific computing.

[Inria and open source software: unwavering support for nearly 20 years](https://www.inria.fr/en/open-source-software-inria)

*Growing Emphasis on Reproducibility and Transparency*

With the replication crisis in various scientific fields, there's been a heightened focus on reproducibility and transparency.
Open-source software plays a crucial role in enabling researchers to share their code and data, facilitating reproducibility and validation of results.

[Towards Reproducibility in Research Software](https://www.software.ac.uk/blog/towards-reproducibility-research-software)

[Best Practices for Computational Science: Software Infrastructure and Environments for Reproducible and Extensible Research](https://openresearchsoftware.metajnl.com/articles/10.5334/jors.ay)

*Collaborative Development and Sharing*

Platforms like GitHub have facilitated collaborative development and sharing of scientific software.
Researchers can openly collaborate, contribute improvements, report issues, and share their work with the wider community, fostering innovation and knowledge exchange.

Hard to believe now but Git exists only since 2005
([A short history of Git](https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git))
and Github started being developped in 2007 ([The untold story of Github](https://smhatre59.medium.com/the-untold-story-of-github-132840f72f56)).
Now, pretty much everyone hosts their open source projects on GitHub,
including top companies like Google, Facebook, Twitter, and even Microsoft.
Julia programming language is housed on GitHub and it’s entirely public.

[In 2023, Github reported 284 millions public repository](https://github.blog/2023-11-08-the-state-of-open-source-and-ai/).

*Integration of Best Practices*

There's been a greater emphasis on incorporating best practices in software development within the scientific community.
Initiatives like the Software Carpentry and Data Carpentry programs offer training in software development skills tailored
for researchers, promoting good coding practices, version control, and reproducible research.
While it used to be common to criticize academic code as being poorly organized and in need of extensive refactoring, this perception is becoming less prevalent over time.

*Recognition and Reward for Software Contributions*

There's a growing recognition of the importance of software contributions to research outcomes.
Funding agencies, institutions, and journals are increasingly valuing and rewarding researchers
for their software development efforts, whether through citations, funding, or career advancement.

Even though, I classified this in the new practices, this was long known in Montréal.
[The story of GENCOL and the company AD OPT is one of Montréal classic using research-level software to solve major challenges](https://www.researchgate.net/publication/220284043_GENCOL_une_equipe_et_un_logiciel_d'optimisation)

Overall, the past decade has witnessed significant progress in the development and adoption of open-source scientific software.
These trends have played a crucial role in advancing scientific research, fostering collaboration, and promoting transparency and reproducibility within the scientific community.

## OPEN SOURCE SOFTWARE AND THE ROLE OF JULIA

The past decade has seen the emergence of numerous specialized tools, libraries, and frameworks tailored
for scientific computing and data analysis. These resources provide researchers with powerful and efficient tools for tackling complex scientific problems across various disciplines. One that stood out for me is the Julia programming language.

In this context, the plateforme and language plays a major role, and I have grown to think that Julia is a perfect match
and particularly in an academic context (but not only).
In numerical optimization, and computational science in general, performant open-source codes have been developped using
Fortran, C++, and in some measure R and Python.
There have been numerous success story, however without bringing together a large community of contributors.

The Julia-verse is mostly focus toward Github, and there is a continuous development toward continuous integration tools
that would benefit any Julia package. Thus, making coding and maintaining repository in Julia a better experience.

The Julia programming language version 1.0 appeared in 2018 turning this very promising language into a stable one where
large codes can rely on without too much maintenance.
Julia has opened numerous success story, one of the early that was impressive was Julia joining the petaflop club
[Julia Joins Petaflop Club](https://www.hpcwire.com/off-the-wire/julia-joins-petaflop-club/).
In other words, Julia is fast, which is good in general because you don't want to invest time into code that will be obsolete.
In my experience, and our recent paper [Scalable Adaptive Regularization](https://link.springer.com/article/10.1007/s10107-023-02007-6) was another example,
Julia is doing more than OK comparing to solvers in Fortran or C++.

Finally, one of the most important point for me is the accessibility of the language.
I have been teaching numerical optimization classes for the past years with laboratories in Julia (usually 6 blocks of 3 hours)
to students that never coded in Julia, but usually had some Matlab or Python experience.
I loved the idea that in a couple of hours students were capable of starting doing meaningful code, and we were able to cover
very exciting topics. The same experience extended to the research teams were I have been involved.

To me the perspective of being able to write meaningful and efficient code with few lines, a clear syntax and without
10 years of experience sounds like modern and good science.

## Citation File Format (CFF) FOR SOFTWARE

To valorize the coding process in scientific research, the generally accepted procedure recently is to make software citable.
Therefore, we would register packages to Zenodo.org to generate a DOI that can be cited, although this is not considered a
research paper.
Some well-known research journal have a focus on the code either accompanying research or regarding as the main contribution
the code itself or some update of it (Mathematical Programming C, INFORMS Journal of Scientific Software, ...).
A complementary project is to write paper about the code itself and not the associated mathematical content.
This is the purpose of journal like Journal of Open Source Software or Journal of Open Research Software.
They are peer-reviewed journal where a short article is reviewed as well as the package itself and its documentation.
The peer-review process is not anonymous and is done via a Github discussion, which I think is in the open-source spirit
we discussed earlier.

### What is a CITATION.cff file?

According to [[1]](https://citation-file-format.github.io/) CITATION.cff files are plain text files with human- and machine-readable citation information for software (and datasets).
Code developers can include them in their repositories to let others know how to correctly cite their software.
It is very easy to correctly cite a paper: all the necessary information (metadata) can be found on the title page or the article website.
Software and datasets have no title page, the relevant information is often less obvious.
People who want to cite your software may ask questions like:
What is the name of the software (it’s probably not my_scripts/run.m or analysis.py)?
What label should I use to uniquely identify the version of the software I have used?
What is the appropriate set of people that should be cited as authors?
The person who wants to cite your software will probably not be able to answer these questions accurately and consistently themselves, but you can!
Give them all the right information in a CITATION.cff file, and they can cite your software correctly.

Create a CITATION.cff file with ease using the form on the [cffinit website](https://citation-file-format.github.io/cff-initializer-javascript/).

According to [[1]](https://citation-file-format.github.io/), the development of CFF is supported by The Institute for Software Technology of the German Aerospace Center (DLR), The Netherlands eScience Center, and The Software Sustainability Institute.

### They choose CFF

Github: When you put a CITATION.cff file in the default branch of your GitHub repository, it is automatically linked from the repository landing page, and the citation information is rendered on the repository page, and also provided as BibTeX snippet which users can simply copy! This makes it easy for other users to cite your software project, using the information you’ve provided.
https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-citation-files
[[2]](https://github.com/citation-file-format/citation-file-format/tree/main) If your repository is hosted on GitHub, they will show the citation information in the sidebar, which makes it easy for visitors to cite your software or dataset correctly.


Zenodo: When you have a CITATION.cff file in your GitHub repository, make a release and publish it on Zenodo via the Zenodo-GitHub integration, Zenodo will use the citation information you’ve provided to populate the publication entry! This makes it easier for software developers and maintainers to publish their software with complete and correct metadata.
https://twitter.com/ZENODO_ORG/status/1420357001490706442
[[2]](https://github.com/citation-file-format/citation-file-format/tree/main) When you publish your software on Zenodo via the GitHub-Zenodo integration, they will use the metadata from your CITATION.cff file.

Zotero: When you have a CITATION.cff file in your repository, and someone uses the Zotero browser plugin to import a reference to your repository into their Zotero reference manager, it will use the citation information you’ve provided to populate the reference entry! This makes it easier for users to get a complete and correct reference to your software, that they can use when they cite your software in their work!
https://twitter.com/zotero/status/1420515377390530560
[[2]](https://github.com/citation-file-format/citation-file-format/tree/main) People can import the correct reference to your software into the Zotero reference manager via a browser plugin.
