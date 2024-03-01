# Year 2 report

_The following project assessment is from year 2 of 2i2c’s operation (08/2021 through 09/2022). It is copied from our previous report to CZI, as a historical record of the project’s progress._

## Brief summary

In year 2 of 2i2c’s operations, we gradually **scaled the communities that we served in order to test and refine our new service model**. This helped us understand the bottlenecks that existed in our previous model, and the ways in which it did not match the communities that we work with. As a result we have come to a better understanding of the roles and collaborative model to use around this service, which we will define, implement, and scale in the final year of this grant.

## Key outcomes

### Strategic planning and capacity building for Jupyter in research and education

Below are several major accomplishments over the last year that grew our capacity to partner with research and education communities:

* We [assessed our “alpha” service offerings and pricing](https://2i2c.org/blog/2022/2021-review-services/), in order to set a foundation to use for partnering with new communities.
* We overhauled our JupyterHub infrastructure [to be more reliable and scalable](https://2i2c.org/blog/2022/ci-cd-improvements/).
* We defined [a shared responsibility model](https://docs.2i2c.org/en/latest/about/service/shared-responsibility.html) to provide agency to our partner communities.
* We [defined a new Product and Community Lead](https://2i2c.org/blog/2022/job-product-community-lead/) role and hired James Munroe to serve in this role for 2i2c.
* In anticipation of scaling up our partner communities in 2023, we also [defined a Partnerships Lead role](https://team-compass.2i2c.org/en/latest/people/titles/partnerships-lead.html) to oversee our efforts in making new connections with partner communities, and to develop sustainability models out of these efforts.
* We [partnered with several organizations around an open science cloud service for Latin America and Africa](https://2i2c.org/blog/2022/czi-global-communities-proposal/). For full details, see [the Zenodo record of our grant application](https://zenodo.org/record/7025288).
* At the end of this period, we audited our strategy and service model thus far, and [identified several key areas where we needed to invest our time moving forward](https://2i2c.org/blog/2022/strategic-update/).


### Facilitating communications and connections within the Jupyter developer community and its stakeholders in research/education

In addition to our strategic and capacity building efforts above, 2i2c’s Executive Director also led a number of key efforts at growing connections and capacity within the Jupyter ecosystem.

* [Stewarded the Notebook v7 enhancement proposal](https://github.com/jupyter/enhancement-proposals/pull/79).
* [Led efforts to refactor and update the JupyterHub governance and team structure](https://github.com/jupyterhub/team-compass/pull/517).
* [Oversaw a major overhaul of the PyData Sphinx Theme](https://pydata-sphinx-theme.readthedocs.io/en/stable/) and assisted with several efforts to update Jupyter documentation to build on this theme for its own documentation.
* [Set a foundation for the Binder project to grow its organizational support](https://github.com/jupyterhub/binder/pull/258).
* [Secured another year of cloud funding for mybinder.org](https://github.com/jupyterhub/team-compass/issues/463) via a grant of cloud credits from Google Cloud.
* [Co-led efforts to define a formal governance structure for the Jupyter Book and MyST projects](https://github.com/executablebooks/meta/issues/493), and began laying the groundwork for incorporation into the Jupyter project.
* [Served on the Steering Council for NotebooksNow!](https://eos.org/editors-vox/notebooks-now-elevating-computational-notebooks). An effort to bring notebooks into modern publishing workflows for scientific communities.
* Began [serving as an advisor for JupyterHub's first Community Strategic Lead role](https://github.com/jupyterhub/team-compass/issues/536), a role that was funded from a previous year’s EOSS grant from CZI.

### Enabling the execution of projects and collaborations for Jupyter in research and education

While most effort on this grant was spent on major strategic and capacity building efforts within 2i2c, we wish to highlight some of our operational accomplishments that required extra management effort.

* We [designed a new Project Manager role](https://github.com/2i2c-org/team-compass/issues/398) that is dedicated to managing our deliverables and planning for major projects within 2i2c. 
* Doubled the number of simultaneous partner communities in our Managed JupyterHubs Service [from about 20 to 41 community hubs with clusters in each major cloud provider](https://infrastructure.2i2c.org/en/latest/reference/hubs.html).
* Partnered with several strategically-important communities, including a new NSF-funded center called [the Alabama Water Institute](http://ovpred.ua.edu/alabama-water-institute/), the [NASA Cryo in the Cloud project](https://book.cryointhecloud.com/intro.html), the [LEAP-Pangeo project](https://leap-stc.github.io/leap-pangeo/jupyterhub.html), and the [Jack Eddy Symposium](https://2i2c.org/blog/2022/eddy-symposium-report/).
* We began a development partnership with GESIS to [bring Binder’s dynamic image building capabilities directly into the JupyterHub technology stack](https://github.com/2i2c-org/infrastructure/issues/1382).

## Areas for growth

We identified a number of ways we must improve our service moving forward. Much of these were [described in our annual strategic update blog post](https://2i2c.org/blog/2022/strategic-update/). Below is a brief summary:

* Engineering roles are not enough to achieve the impact we wanted via our Managed JupyterHub Service. Communities also need support in _using_ the infrastructure. This led to the creation of the Product and Community Lead role described above.
* Our pricing and service offerings must be further-refined to reflect the diversity of communities we wish to serve. We must explore models that are inclusive to _a global population_, particularly those with fewer resources (we describe some of these challenges in [our recent CZI proposal for communities in Latin America and Africa](https://2i2c.org/blog/2022/czi-global-communities-proposal/)). 
* _Billing and invoicing_ quickly became a bottleneck that limited the number of communities we can partner with at our current capacity (and cost recovery model). We are exploring ways to more sustainably invoice the communities that we work with - both for 2i2c and for their administrative teams.

## Artifacts, publications, and software code

Below are links to public reports and blog posts that 2i2c produced over the past year. Many of these posts are linked above with more context as well.

* **[Blog post]** [Q3 Community Update](https://2i2c.org/blog/2022/q3-update/)
* **[Blog post]** [Q1 Community Update](https://2i2c.org/blog/2022/q1-update/)
* **[Blog post]** [One year later: an update of 2i2c's mission, strategy, and impact](https://2i2c.org/blog/2022/strategic-update/)
* **[Grant application]** [A Collaborative Interactive Computing Service Model for Global Communities](https://zenodo.org/record/7025288) (CZI-OS invited application)

In addition, 2i2c Executive Director co-authored several pre-prints and published articles that mentioned 2i2c’s model as a part of domain-specific visions for cloud-enabled collaborative interactive computing. Below are links to notable publications, blog posts, pre-prints, and presentations given by personnel funded on this grant.

* **[Article]** [Beyond advertising: New infrastructures for publishing integrated research objects](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009651) (PLoS Computational Biology)
* **[Article]** [Cloud-based framework for inter-comparing submesoscale-permitting realistic ocean models](https://doi.org/10.5194/gmd-15-5829-2022) (European Geosciences Union)
* **[Preprint]** [Pan-neuro: interactive computing at scale with BRAIN datasets](https://doi.org/10.31219/osf.io/mwh2b)

Finally, these presentations were given on behalf of the Jupyter community at various workshops and events.

* **[Presentation]** [Scientific Communication and Reproducible Publishing in the Jupyter Ecosystem and Beyond](https://ui.adsabs.harvard.edu/abs/2021AGUFM.U33A..03P/abstract) (AGU 2021)
* **[Presentation]** [Jupyter Book 101: Create Beautiful, Publication-quality Books and Documents from Jupyter Notebooks and Computational Content](https://ui.adsabs.harvard.edu/abs/2021AGUFM.U51B..08H/abstract) (AGU 2021)
* **[Presentation]** [Open Infrastructure for Open Science](https://zenodo.org/record/7233586) (Jupyter Community workshop in Maastricht)
* **[Presentation]** [Jupyter Book and MyST: A community-led, extensible, modular ecosystem for creating computational narratives](https://zenodo.org/record/7287626) (NotebooksNow! 2022 workshop)

This is a brief update of major developments with 2i2c over the first nine months of its existence (and of this grant). Much of this information also exists in various places in [the 2i2c Team Compass](http://team-compass.2i2c.org), which is an open resource about the 2i2c team, our major projects, and our organizational structure. For a high level view of our strategy and goals, see [the Team Compass strategy page](https://team-compass.2i2c.org/en/latest/about/strategy.html).
