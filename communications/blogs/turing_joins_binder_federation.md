# The Turing Institute Invests in Open Infrastructure for Reproducible Research

_This is an invited post from The Turing Way and The Alan Turing Institute, collaborators on the Binder project and new members of the Binder Federation._

We are delighted to announce the fourth member of the Binder Federation: [The Alan Turing Institute](https://www.turing.ac.uk/)!
Based in London UK, their infrastructure is hosted on [Microsoft Azure](https://azure.microsoft.com/en-gb/) and is supported by [_The Turing Way_](https://github.com/alan-turing-institute/the-turing-way) project.

## Reproducible and Transparent Science Communication

Science moves forward by corroboration, yet the [well known](https://www.nature.com/collections/prbfkwmwvz) reproducibility crisis is holding back progress.
When a paper is published, there is generally no way for an outsider to verify its results because the underlying data and analysis code are not available for scrutiny.
This makes the science very difficult to build upon and results in fragile advances and a lot of wasted time and money.
In addition to a cultural change in our approach to data science (such as the abolition of 'publish or perish' incentives, secrecy around data, and the drive for novelty), there is also a need for a practical change in the way science is communicated so that it is more transparent regarding the steps that were taken to produce the results.
This is one of the reasons [funders and publishers are beginning to require that publications include access to the underlying data and analysis code](https://www.data.cam.ac.uk/funders).

There are  many tools available that can make packaging code and resources easier.
[Jupyter Notebooks](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html) are a very popular method of combining code, its results and prose to produce an interactive scientific analysis.
[Docker](https://docs.docker.com/engine/docker-overview/) is used to bundle together, code, data and the software environment into a "container" in such a way that it is easily reused and portable across different systems.
Using cloud computing resources, these tools can be made accessible to anyone, anywhere in the world.
However, learning all of these tools individually (let alone combining them together) can be a huge barrier to researchers since they require a lot of time investment to learn and implement properly.

[BinderHub](https://binderhub.readthedocs.io/en/latest/) is the computational infrastructure that coordinates all of these tools to provide an easy method of creating computing environments for scientific analyses that are reproducible and shareable with anyone, anywhere.
It rewards reproducible data science and software engineering best practices, as it requires a version-controlled project with documented software dependencies in order to automatically generate the environment.

> BinderHubs package together really fantastic tools like notebooks, docker, cloud computing resources, coordination engines, along with clear version control to deliver reproducible research at the click of a button.
>
> -- [Dr Kirstie Whitaker](https://www.turing.ac.uk/people/researchers/kirstie-whitaker), Turing Research Fellow and lead developer of _The Turing Way_

![BinderHub](https://zenodo.org/api/iiif/v2/e4125eaf-b456-4097-85fc-6a2e80482d1c:96c70193-2f9e-442d-8cf8-21485d8864e1:1728_TURI_Book%20sprint_45%20repo2docker_040619_v2_MK.jpg/full/750,/0/default.jpg)

## The Binder Federation

[The Binder Federation](https://blog.jupyter.org/the-international-binder-federation-4f6235c1537e) is an experiment in open infrastructure for data science and beyond.
It is a community of scientists and open-source developers dedicated to scientific reproducibility, communicating ideas through interactive computing, and providing real-time access to results and analyses.
The Binder Federation provides interactive data analytics environments to roughly 10,000 unique repositories via 400,000 launches a month, and it relies on its team of partner BinderHubs to collaborate in providing this service.

[GKE](https://jupyterhub-team-compass.readthedocs.io/en/latest/team.html#binder-team), [OVH](https://www.ovh.com/world/), [GESIS](https://notebooks.gesis.org/about/) and now new member **the Turing Institute** pool their resources to create a sustainable, open-source infrastructure that allows easy creation, sharing of and access to reproducible computational environments.
Pooling resources in such a way is an important step for the resilience and sustainability of Project Binder since the dependency between mybinder.org and its funding is now spread across many sources.
It also facilitates the decentralisation of the knowledge required to deploy and manage a BinderHub.

_Turing Way_ contributor [Dr Sarah Gibson](https://www.turing.ac.uk/people/researchers/sarah-gibson) is also a [mybinder.org](https://mybinder.org) operator.
The operators are responsible for the day-to-day operations and maintainance of the main website.
She was therefore perfectly positioned to lead this project and bring the Turing into the Binder Federation.

> I'm so excited that we've successfully merged our resources at the Turing into the mybinder.org infrastructure!
> This achievement marks Binder's maturity as a federated project and the Turing's commitment to supporting open-source tooling and communities.
>
> -- Dr Sarah Gibson

![Federation](https://miro.medium.com/max/1666/1*KU35naJhl1LSDxKY8gog4g.png)

## How Can You Get Involved?

If this has piqued your interest, there are a few ways to get involved in the Binder Federation!

One way is to become a [mybinder.org](https://mybinder.org) operator.
This is a low-tech contribution which involves hanging out in the project's [gitter room](https://gitter.im/jupyterhub/binder) answering questions, providing constructive input in the [GitHub repo](https://github.com/jupyterhub/binderhub), and being an active member of the community.
Invitations to join the operating team are extended to outstanding members of our community.
You can [learn more about how to contribute to Binder and JupyterHub here](https://jupyterhub-team-compass.readthedocs.io/en/latest/contributing.html).

Alternatively, you could [join the BinderHub federation](https://binderhub.readthedocs.io/en/latest/federation/federation.html)
by facilitating the deployment of a  BinderHub!
You can donate a cluster or cloud credits to the mybinder.org operating team.
Your deployment would then be managed from the [mybinder.org-deploy repo](https://github.com/jupyterhub/mybinder.org-deploy) with input from the team and community.
This is a more high-tech contribution but over a shorter time period.

Lastly, rather than joining the Federation, you could deploy your own BinderHub for your organisation.
A BinderHub for an organisation is incredibly valuable for opening the pathway to reproducible research using greater computational resources, access to private data, and other features not offered by the public and free mybinder.org service.
This is still a beneficial pathway for the Binder community because the more BinderHubs that exist in the world, the more we can learn together around solving implementation issues and the more we decentralise the knowledge required to deploy and run a BinderHub.

There are [documentation](https://binderhub.readthedocs.io) and [tutorials](https://bit.ly/zero-to-binderhub-workshop) on how to deploy BinderHub and the team are happy to [answer any questions](https://gitter.im/jupyterhub/binder).

## About The Alan Turing Institute

[The Alan Turing Institute](https://turing.ac.uk), headquartered in the British Library, London, is the UK's national institute for data science and artificial intelligence.
The Institute acts as a hub, bringing together cutting edge research from its network of [university and industry partners](https://www.turing.ac.uk/collaborate-turing/current-partnerships-and-collaborations) to solve real world problems across its range of [challenge areas](https://www.turing.ac.uk/research/challenges).
The Institute's mission is to make great leaps in data science and artificial intelligence research in order to change the world for the better.
Turing researchers collaborate across disciplines to generate impact, both through theoretical development and application to real-world problems.

## About _The Turing Way_

Reproducible research is necessary to ensure that scientific work can be trusted.
The goal is to ensure that all results can be independently verified and built upon in future work.
This is sometimes easier said than done!
Sharing these research outputs means understanding data management, library sciences, software development, and continuous integration techniques: skills that are not widely taught or expected of academic researchers.
_The Turing Way_ is a handbook to support students, their supervisors, funders and journal editors in ensuring that reproducible research is "too easy not to do".
It includes training material on version control, analysis testing, and open and transparent communication with future users, and includes case studies and common "gotchas" for researchers to avoid.
It is also a global community and cultural movement with the potential to transform data science through it's dedication to fostering gold-standard reproducible research.
This project is openly developed and any and all questions, comments and recommendations are welcome at our [GitHub repository](https://github.com/alan-turing-institute/the-turing-way).

Read more about _The Turing Way_ in this [Turing Impact Story](https://www.turing.ac.uk/research/impact-stories/changing-culture-data-science).

## About Project Binder

[Binder](https://mybinder.readthedocs.io/en/latest/about.html) is a community within Project Jupyter that started in 2015 and has grown ever since.
It is now a global community that operates [mybinder.org](https://mybinder.org) and develops the open-source software used to run it.
Binder currently serves over 120,000 sessions per week to a global user base.

The mybinder.org service allows anyone to launch interactive computing environments in the cloud by simply clicking a link in their browser.
Data scientists and researchers can then write, execute and share notebooks in their browser without having to configure anything.
Project Binder supports Python, R, Julia and many more programming languages as well as interfaces.

## About Project Jupyter

[Project Jupyter](https://jupyter.org) is a non-profit project releasing 100% open-source software to support interactive data science and scientific computing across all programming languages.
It received the [ACM Software System Award in 2017](https://awards.acm.org/award_winners/perez_9039634) for language agnostic tools which have become "a de facto standard for data analysis in research, education, journalism, and industry".

_The Turing Way is supported by The UKRI ASG funding under the EPSRC Grant EP/T001569/1, particularly the "Tools, Practices and Systems" theme within that grant, and by The Alan Turing Institute under the EPSRC grant EP/N510129/1_
