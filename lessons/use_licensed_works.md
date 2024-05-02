# Lesson 1: Using Openly Licensed Works Published by Others

`````{admonition} Vignette: A Cautionary Tale of Unlicensed Code
:class: tip
Dr. Emily Johnson, a postdoctoral researcher in computational physics, has been working on a complex simulation software for modeling quantum systems. After months of hard work, she finally has a working prototype that she believes could be useful to other researchers in her field.
Excited to share her creation, Dr. Johnson uploads the source code to a popular code repository, along with a brief README file describing its functionality. She eagerly awaits feedback from her colleagues, hoping that her software will contribute to new discoveries in quantum physics.
A few weeks later, Dr. Johnson gets an email from Dr. Robert Nguyen, who stumbled upon her code repository. He expresses his interest in using the software for his own research project but is hesitant to do so without knowing the terms under which he can use, modify, and share the code. He asks Dr. Johnson if she could clarify the licensing terms for her software.

Surprised by the request, Dr. Johnson realizes that she had not explicitly specified any license for her code. She had assumed that by making the source code publicly available, she was granting permission for anyone to use it freely. She now understands that simply making the code public does not make her project open source.
In fact, without a clear license, her software is essentially in a state of _legal uncertainty_. Potential users, like Dr. Nguyen, are left wondering if they have the right to use, modify, or distribute the code. Many well-informed researchers may choose to avoid using her software altogether, as the absence of a license makes it unclear whether they can do so without legal risk.
Dr. Johnson realizes that by not attaching a license to her software, she unintentionally limited its potential impact and adoption within the scientific community. She learns that software, like poetry or any other creative work, is automatically protected by copyright law the moment it is created. Without a clear license, users are forced to assume that they do not have permission to use or build upon the work.

```{sidebar} Code is like poetry
Software is a creative work, and copyright is automatically attached to it the moment it is created.
```

To rectify the situation, Dr. Johnson decides to research software licenses and choose one that aligns with her goals of fostering collaboration and open science. By attaching a standard open source license to her software, she can grant users the necessary permissions and freedoms, while still retaining credit for her work. This experience teaches her the importance of specifying a license for her software projects from the outset, ensuring that her work can be used, shared, and built upon by others in the scientific community.

`````

## Open licensing concepts

In the world of research and education, open licensing has become increasingly important for enabling the free exchange of ideas, promoting collaboration, and accelerating scientific progress. _But what do we mean by "open licensing"?_

In essence, open licensing refers to a set of principles and legal frameworks that grant permissions for others to freely access, use, modify, and share creative works or products. This concept applies to various types of outputs, including software, research data, scholarly publications, and educational materials.

```{image} ../assets/licensing_orgs.png
:alt: logos of licensing orgs 
:width: 500px
:align: center
```

Open source software is perhaps the most well-known example of open licensing. [Open source licenses](https://opensource.org/licenses), such as the MIT, BSD, and Apache licenses, allow users to access the source code of a software program, study how it works, modify it to suit their needs, and redistribute the modified versions.

Similarly, the open data movement advocates for making research data openly available and reusable, often under licenses like the [Open Data Commons licenses](https://opendatacommons.org/licenses/) or [Creative Commons Zero](https://creativecommons.org/public-domain/cc0/) public domain dedication. This enables other researchers to validate findings, combine datasets, and build upon existing work.

Open content licenses, like the [Creative Commons](https://creativecommons.org/share-your-work/cclicenses/) suite of licenses, are commonly used for scholarly publications, educational resources, media files, and other creative works. These licenses grant varying levels of permissions for reusing, redistributing, and modifying the licensed content.

The principles of open licensing are deeply rooted in the academic traditions of sharing knowledge, enabling peer review and scrutiny, and fostering collaborative advancement of human understanding. By embracing open licensing, researchers and educators can:

1. Increase the transparency and reproducibility of their work, a cornerstone of the scientific method.
2. Facilitate the dissemination of their findings and educational materials to a wider audience, amplifying their impact.
3. Build upon the work of others, accelerating the pace of discovery and innovation.
4. Collaborate more effectively with colleagues across institutions and disciplines, breaking down silos and fostering interdisciplinary research.

Open licensing is not just a technological or legal construct; it represents a _cultural shift towards openness, collaboration, and the democratization of knowledge_. As we delve deeper into this topic, we will explore the practical aspects of using openly licensed works, as well as the considerations involved in licensing your own research outputs and collaborating with others in open source projects.

```{important}
Open licensing gives us _freedom_---contrary to intellectual-property instruments that want to control how creative works are used.

Freedom is power. In this case, the power of open-source software comes not just from being able to read the source code, but from being able to contribute to and build from it. 

For this power to be realized, it's not sufficient to make the source public to read. We must attach a license that allows others to modify and distribute the code.

```

## Understanding license types

Understanding the basic differences between license types is essential for researchers and educators who want to make informed decisions about which licenses to use for their own projects and how to properly use and attribute third-party software in their work. By familiarizing themselves with the key characteristics and implications of each license type, researchers can ensure that they are using and sharing software in a way that aligns with their goals and values, while also respecting the rights and intentions of the original creators.

The three main categories of licenses are: open-source permissive, open-source copyleft, and proprietary.

```{margin} Permissive vs. Copy-left
The most important distinction between the various FOSS licenses is whether they are permissive versus copyleft. These terms are often confused.

Permissive licenses:
* have fewer restrictions
* allow use, distribution, modification
* only requre that authors be given credit
* best choice for academic use
```

Open-source permissive licenses
: Open-source permissive licenses, such as the [MIT](http://choosealicense.com/licenses/mit/), [BSD](https://opensource.org/license/bsd-3-clause), and [Apache](https://choosealicense.com/licenses/apache-2.0/) licenses, are designed to grant users broad freedoms to use, modify, and distribute the licensed software. These licenses typically only require that the original copyright notice and license text be included in any copies or derivative works. Permissive licenses place minimal restrictions on how the software can be used, making them popular choices for academic and research projects. They allow for easy integration with other software projects, including proprietary ones, making them ideal for promoting widespread adoption and collaboration.

Open-source copyleft licenses
: Open-source copyleft licenses, like the [GNU General Public License (GPL)](https://choosealicense.com/licenses/gpl-3.0/), GNU Lesser General Public License (LGPL), and [Mozilla Public License (MPL)](https://choosealicense.com/licenses/mpl-2.0/), are designed to make sure that the freedoms granted by the license are preserved in any derivative works. Copyleft licenses require that any modifications or additions to the licensed software also be released under the same license terms. This "share-alike" requirement ensures that the software and its derivatives remain open and accessible to all. Copyleft licenses are often chosen by developers who want their work to remain open and freely available in perpetuity.

Proprietary licenses
: Proprietary licenses are the most restrictive type of license. They typically grant users the right to use the software only for its intended purpose, often limiting the ability to copy, modify, or redistribute the software. Proprietary licenses are commonly used for commercial software products, where the source code is kept closed and the software is distributed only in binary form. Examples of proprietary licenses include the End-User License Agreements (EULAs) that accompany most commercial software packages.

## Sources

This lesson is based on materials from the presentation by {cite:t}`barba2017-licensing`.