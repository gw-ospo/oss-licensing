# Lesson 3: Licensing Concerns for Collaborative Open Source Projects

```{admonition} Vignette: An Unexpected Legal Quagmire
:class: tip
Dr. Sophia Patel, a well-respected computational scientist, leads a small research group at a U.S. university. Her team has been working on a new software package for simulating complex biological systems, which they had been developing under the GNU General Public License (GPL) for the past few years.

As the project gained traction and attracted interest from other researchers, Dr. Patel began to realize that the GPL might be too restrictive for their goals. She wanted to make the software more widely accessible and allow other scientists to build upon their work, even in proprietary or closed-source projects. After much consideration and discussion with her team, they decided that relicensing the software under the more permissive BSD 3-Clause License would be the best path forward.

However, Dr. Patel soon discovered that relicensing the software was not as simple as she thought. The GPL is a copyleft license, which means that all contributors to the codebase had to agree to the relicensing for it to be legally valid. She needed to reach out to every single person who had contributed code, no matter how small their contribution, and get their explicit permission to relicense their work.

As she went through the list of contributors, Dr. Patel came across another unexpected challenge. One of their key collaborators, Dr. James Thompson, was a researcher at a federal agency. She had always assumed that his contributions were covered by the same licensing terms as the rest of the project, but upon further investigation, she learned that U.S. federal employees' work is not subject to copyright and is considered public domain.

Perplexed by this new information and unsure how to proceed, Dr. Patel reached out to her university's Open Source Program Office (OSPO) for guidance. The OSPO staff helped her understand the implications of the public domain status of Dr. Thompson's contributions and worked with her to develop a plan for relicensing the software.

They advised Dr. Patel to create a clear record of all contributors' permissions for relicensing and to document the public domain status of Dr. Thompson's contributions in the software's licensing information. They also recommended implementing a Contributor License Agreement (CLA) for future contributions to streamline the process and avoid similar issues down the road.

With the help of the OSPO, Dr. Patel and her team were able to successfully navigate the relicensing process and ensure that their software was properly licensed and documented. The experience taught them valuable lessons about the importance of considering licensing issues early in the project lifecycle and the need for clear communication and documentation in collaborative open-source research projects.

Thanks to their efforts, the newly BSD-licensed software package was adopted by researchers around the world, fostering new collaborations and accelerating the pace of discovery in their field. Dr. Patel and her team had not only overcome a significant licensing challenge but also contributed to a more open and collaborative scientific community.
```

The issues raised in this vignette are in fact common and as thorny as they sound. But no need to panic! We'll discuss in this final section of the course the steps for establishing licensing policies that set your collaborative open-source project up for success.

## Establishing licensing policies for collaborative projects

When embarking on a collaborative research or educational project, it's important to have open and honest discussions about open licensing from the very beginning. By agreeing on a licensing policy early on, you can avoid misunderstandings, ensure everyone's needs and expectations are met, and create a strong foundation for your team's work.

### Agreeing on a license early in the project lifecycle
In any collaborative open-source project it's important to agree on a license as early as possible. This may seem like a daunting task, especially when you're eager to dive into the research itself, but investing time in these discussions upfront can save you from headaches and conflicts down the road.
Bring your team together and have an open conversation about your licensing goals and priorities. Consider questions like:

- What are our individual and collective motivations for making our work open source?
- Do we want to allow others to use our work in proprietary or closed-source projects?
- Are there any institutional or funder requirements we need to consider?
- What are our expectations for attribution and credit?

```{important}
Discuss licensing issues early on, making sure that everyone's values and needs are aligned and that you choose a license that reflects your shared vision for the project.
```

Choosing the right license could have major impact on the success of your collaborative project. It's important to consider the needs and preferences of all collaborators, as well as any external factors that may influence your decision.
Some key considerations include:

- Compatibility with the licenses of any existing code or dependencies you plan to use
- Potential for future collaborations or integrations with other projects
- Understanding your intended audience or user community
- Alignment with your institution's IP policies and any funder requirements

Keep in mind that while it's important to choose a license that meets your needs, you should choose a _standard_, widely-used license whenever possible. This will avoid confusion and make it easier for others to understand and contribute to your project.

### Documenting and communicating the project's licensing policies

Once you've agreed on a license, it's crucial to document and communicate your decision clearly. This not only helps keep all collaborators on the same page but also makes it easier for others to understand and engage with your work.

Some steps for documenting and communicating your licensing policies include:

- Adding a LICENSE file to your project's repository with the full text of your chosen license
- Including a brief licensing statement and any necessary attribution or credit information in your README file
- Ensuring that all collaborators understand and agree to the licensing terms
- Communicating your licensing policies to any new collaborators or contributors who join the project
- Making your licensing information easily accessible and visible to users and the broader community

Establishing clear licensing policies and communicating them effectively helps create a transparent and inclusive environment that encourages collaboration and community engagement.

Remember, a key to success in collaborative open-source acedemic work is open communication and a shared commitment to your project's goals and values. By investing time in discussing and documenting your licensing policies early on, you set your team up for a more productive, impactful, and rewarding collaboration.

### Collaborations involving U.S. federal employees

When collaborating with U.S. federal employees on open-source projects, it's important to be aware of the unique licensing considerations that apply to their work. In the United States, software created by civil servants in the course of their official duties is not subject to copyright protection, which can have significant implications for how that work is released and used.

Under [17 U.S. Code § 105](https://www.law.cornell.edu/uscode/text/17/105), known as the _"Subject matter of copyright: United States Government works,"_ the U.S. government does not receive copyright protection for the work of its employees. This means that when a civil servant creates software as part of their job, that software cannot be copyrighted, and when it is released to the public, it enters the public domain in the United States. Once in the public domain, anyone can use the software for any purpose without attribution or restriction.

This lack of copyright protection can create challenges when integrating work by civil servants into open-source projects. Most open-source licenses, such as the MIT, BSD, and GNU GPL licenses, apply only to works that are protected by applicable copyright or patent law. Because software created by civil servants is not protected by copyright, these licenses generally do not apply to their contributions.

However, it's important to note that copyright protections are territorial, meaning that the rules around government works and copyright vary from country to country. While a civil servant's work may be in the public domain in the United States, the government may still hold copyright in those same works under the laws of other nations. This can create complex situations where the use and licensing of government-created software may be subject to different rules depending on the jurisdiction.

In some cases, applying an open-source license to government-created work, even if not strictly necessary in the United States, can help clarify how that work can be used worldwide. By explicitly granting permissions through a license, collaborators and users can have a clearer understanding of their rights and obligations when using the software.

It's also worth noting that works produced by civil servants in collaboration with others may be subject to different rules depending on the terms of the collaboration. If a civil servant collaborates with non-government employees, such as academic researchers or private sector developers, the resulting work may be protected by copyright to the extent of the non-government contributors' involvement.

To navigate these complex issues, it's essential for collaborative research teams to have open and proactive discussions about licensing when working with federal employees. Only by understanding the unique considerations that apply to government-created work, teams can make informed decisions about how to release and license their software to maximize its impact and ensure its widest possible use.

When in doubt, it's always a good idea to consult with your institution's legal counsel or Open Source Program Office (OSPO) for guidance on how to handle these situations. They can help you understand the specific laws and policies that apply to your project and work with you to develop a licensing strategy that meets your goals while respecting the legal status of government-created work.