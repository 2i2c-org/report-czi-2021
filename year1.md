
# Year 1 report

_The following project assessment is from year 2 of 2i2c’s operation (12/2020 through 08/2021). It is copied from our previous report to CZI, as a historical record of the project’s progress._

## Major developments

### Funding and grants

As this is a capacity building award, we list below funding that we have facilitated or applied for over the past 9 months. A subset of these grants are directly for 2i2c, while many of them are for other communities and open source projects that align with 2i2c’s mission. All of them are related to infrastructure and services that improve Jupyter’s impact in research and education.

<table>
  <tr>
   <td><strong>Item</strong>
   </td>
   <td><strong>Date</strong>
   </td>
   <td><strong>Awardee</strong>
   </td>
   <td><strong>Source</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Amount</strong>
   </td>
   <td><strong>Status</strong>
   </td>
  </tr>
  <tr>
   <td>Pangeo Infrastructure Support
   </td>
   <td>2020 - Fall
   </td>
   <td>2i2c
   </td>
   <td>Moore Foundation (sub-award from Columbia)
   </td>
   <td>Building and running JupyterHub and cloud infrastructure for the Pangeo Project
   </td>
   <td>$479,295 / 2 years.
   </td>
   <td>Awarded
   </td>
  </tr>
  <tr>
   <td>JupyterHub Community Strategic Lead
   </td>
   <td>2021 - Spring
   </td>
   <td>JupyterHub
   </td>
   <td>CZI EOSS
   </td>
   <td>Funding a strategic lead role for the JupyterHub Community to improve diversity and inclusion dynamics.
   </td>
   <td>~$400,000 / 2 years
   </td>
   <td>Awarded
   </td>
  </tr>
  <tr>
   <td>PyData Sphinx Theme development
   </td>
   <td>2021 - Spring
   </td>
   <td>PyData Sphinx Theme
   </td>
   <td>NumFocus development grant
   </td>
   <td>Development and maintenance for the PyData Sphinx Theme, the parent theme used by Jupyter Book
   </td>
   <td>$25,000
   </td>
   <td>Awarded
   </td>
  </tr>
  <tr>
   <td>Infrastructure for Scalable Science Institute
   </td>
   <td>2021 - Spring
   </td>
   <td>2i2c
   </td>
   <td>NSF
   </td>
   <td>Development and hosted infrastructure in collaboration with UW, UCB, JH universities for a scalable science institute
   </td>
   <td>~$1.5m / 5 years
   </td>
   <td>Waiting
   </td>
  </tr>
  <tr>
   <td>Educational Hub Infrastructure Pilot
   </td>
   <td>2021 - Spring
   </td>
   <td>2i2c
   </td>
   <td>JROST Rapid Response Fund
   </td>
   <td>Funding cloud infrastructure for educational JupyterHub pilots
   </td>
   <td>$5,000
   </td>
   <td>Awarded
   </td>
  </tr>
</table>



### Managed Hub Service revenue

In addition to funding from these grants, we have also been developing potential revenue and sustainability models for the [Managed JupyterHub Service](https://team-compass.2i2c.org/en/latest/projects/managed-hubs/index.html). We are still revising these models and using our JupyterHub pilots (see below) to gain experience and arrive at the best pricing and sales structure. We anticipate finalizing these models and running prototypes of revenue-generating Managed Hub Contracts in the second year of this grant.

### New team members

We’ve welcomed two new members to the 2i2c core team. These individuals will both work towards [2i2c’s major projects](https://2i2c.org/projects), and collaborate together on running our 2i2c Pilot Hub infrastructure. Here’s a bit about each new team member.

* [Damián Avila](https://github.com/damianavila). Damian joined 2i2c in May. He has been a Jupyter core team member for many years now, and has done work across many different parts of the PyData stack (in particular, [Jupyter](https://jupyter.org/), [Bokeh](http://bokeh.org/), [RISE](https://rise.readthedocs.io/), and [Nikola](https://getnikola.com/)). Damián will focus his efforts on supporting JupyterHub infrastructure for the [Pangeo project](https://pangeo.io/), as well as development across the [Executable Books Project](https://executablebooks.org/)
* [Sarah Gibson](https://github.com/sgibson91). Sarah joined 2i2c in June, after spending several years as a Research Software Engineer at [the Turing Institute](https://www.turing.ac.uk/). She has also been involved with [the Turing Way](https://the-turing-way.netlify.app/welcome) for many years. Sarah will focus her efforts on JupyterHub development and operations for the Pangeo community.


### Governance and a code of conduct

2i2c has made important steps towards defining a stable and transparent organizational model moving forward. 2i2c now [has a Steering Council](https://team-compass.2i2c.org/en/latest/about/structure.html#steering-council) and an [early organizational structure](https://team-compass.2i2c.org/en/latest/about/structure.html). In addition, [we defined a one-year bootstrap strategy](https://team-compass.2i2c.org/en/latest/about/strategy.html) that we’ll use to guide our path in the first year of 2i2c’s existence.

One of the first acts of the Steering Council has been to [adopt a Code of Conduct](https://team-compass.2i2c.org/en/latest/code-of-conduct/index.html). This is a set of guidelines, and a process for resolving incidents, that makes our community more inclusive, equitable, and enjoyable for all.

### Early pilot JupyterHub infrastructure

In addition to organizational structure and foundations, we have also made progress along the JupyterHub deployment infrastructure we wish to provide and support. One of our major organizational goals is to build a sustainable service [managing open source cloud infrastructure](https://2i2c.org/infrastructure) for interactive computing. This service will provide hosted, customized JupyterHubs for communities of practice in research and education. They’ll be built entirely with open source tools that are community-driven, and that [respect the customer’s Right to Replicate](https://2i2c.org/right-to-replicate).

In order to accomplish this, 2i2c is running several pilots with partners and interested organizations. These pilots are meant to be learning opportunities to understand what kind of infrastructure and service it needs to build moving forward.

The [documentation for our pilot hubs infrastructure](https://pilot-hubs.2i2c.org/en/latest/) contains information about our deployments and infrastructure. It is served from [this 2i2c-org/pilot-hubs repository](https://github.com/2i2c-org/pilot-hubs), a centralized location for configuring and deploying a federated network of JupyterHubs. Each JupyterHub is independent of one another, and could be spun out from the centralized repository with minimal extra work, giving hub users the ability to [replicate their infrastructure, with or without 2i2c](https://2i2c.org/right-to-replicate). We will continue refining the code in this repository as we learn more from our hub infrastructure pilots.

[This page has a list of our currently running JupyterHubs](https://pilot-hubs.2i2c.org/en/latest/reference/hubs.html). Each one roughly corresponds to a community that we are serving (e.g., a classroom, a research group, or an institution). As of this report there are around 30 JupyterHubs that we manage.

### JupyterHub for geospatial analytics - A collaboration with Pangeo

As [originally announced on the Pangeo blog](https://medium.com/pangeo/pangeo-2-0-2bedf099582d), 2i2c is forging a collaboration with [the Pangeo project](https://pangeo.io/) around operating and developing cloud infrastructure for large-scale geospatial analytics. This collaboration is funded through a grant from the Moore Foundation (via Pangeo investigator Ryan Abernathey).

2i2c will assume operation of infrastructure underlying the Pangeo project, allowing the Pangeo team to focus their efforts on their core scientific and development missions. Once this is complete, we’ll next shift our attention to some new areas of development that support use-cases in the Pangeo community (and in the scientific community more broadly).


### JupyterHub for education - A collaboration with CloudBank and UC Berkeley

We’ve begun a partnership with the UC Berkeley [Data Science in Undergraduate Studies program](https://data.berkeley.edu/academics/undergraduate-programs), as well as [CloudBank](http://cloudbank.org/). This collaboration aims to provide hosted JupyterHub infrastructure for community colleges across the state of California. It is an attempt at providing vendor-agnostic and open-source infrastructure to several institutions who would otherwise not be able to deploy this infrastructure on their own.

2i2c will provide the deployment and configuration architecture for this collaboration, working with [Sean Morris](https://its.berkeley.edu/people/sean-morris) in operating this educational infrastructure. All of the cloud infrastructure for this pilot will be funded via CloudBank. We will begin by offering environments that are modeled after [the Data 8 course at UC Berkeley](https://data8.org/). This is part of an effort to build a community of practice around Data Science education using open source tools.

## Areas for growth

In the next phase of this grant, we aim to continue executing on our major strategic priorities, briefly described below:

* **Managed JupyterHub Service:** after gaining experience running infrastructure with our Managed JupyterHub Pilot, we plan to crystallize and prototype a service model for managed infrastructure. This includes an infrastructure plan, a support plan, a sales and billing plan, and a pricing plan. There are still some major unknowns to resolve before this is complete - particularly, what kind of pricing structure will be the most effective at making this service accessible, scalable, and sustainable for us and for the communities we serve. This will require consultation with those familiar with non-profit / open source business and service models.
* **Organizational Foundations:** as 2i2c is still a young organization, there is much work to be done in laying the basic policies and practices of our organization. We are defining more distributed-friendly team coordination practices, and improving our project planning and milestones process. We also plan to revisit our governance and steering council structures to ensure that they are well-positioned to guide 2i2c’s strategy moving forward. This will require consultation with other leaders in the non-profit sector to understand how we can improve our organizational practices.
* **Major collaborations and development:** we have launched several major collaborations in our first year, most notably with the Pangeo Project, and continuing a collaboration with the Jupyter Book project. In our next phase, we wish to develop an infrastructure strategy that allows development with these communities to complement one another, and feed into a broader infrastructure system that we can re-use and customize for other communities as well. This will require more technical design in partnership with key stakeholders across the Jupyter and open source community.


## Unexpected changes

2i2c has experienced one major unexpected change, which was transitioning our fiscal sponsorship from the [International Computer Science Institute](http://icsi.berkeley.edu/) to [Code for Science and Society](https://codeforscience.org/). The decision to change fiscal sponsors came after several months of discussion with the ICSI team, and both organizations ultimately decided that it was in our best interests to shift our organizational relationship to one of collaboration rather than fiscal sponsorship. This has delayed some of 2i2c’s planned operations by several months, but we do not anticipate that it will have a major impact on our ability to execute on the long-term mission of this award. ICSI has done an excellent job of facilitating the transition to CSS, and we expect to have this completed within a month or two.
