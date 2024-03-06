---
abbreviations:
  WAUs: Weekly Active Users
---

# 2i2c grant report overview

+++ {"part": "abstract"}

This [MyST Document](https://mystmd.org) is a final grant report generated for the [Chan Zuckerberg Initiative](https://chanzuckerberg.com/) for the seed grant that founded 2i2c. It covers the major goals, operations, and impact of 2i2c over its first three years of existence.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10790818.svg)](https://zenodo.org/doi/10.5281/zenodo.10790818)

+++

2i2c is now three years old, having been initially [founded with this grant from CZI in late 2020](https://2i2c.org/blog/2021/czi-core-support/). Over this time, 2i2c has grown and matured as an organization, has served thousands of users doing open science and education, and has made extensive contributions to the open source ecosystem for interactive computing.

This document contains an overview of the impact and journey of these three years. It is broken down into three key areas of organizational impact.

::::{note} A note on measurements
:class: dropdown

Over the last three years, we've learned the importance of having measures that reflect progress towards your strategic objectives and goals.
Measures like this give us a more objective way to decide we are making progress (or not), and if we need to modify our approach.

We've tried to include a few key measures for each of the major areas of progress below.
We know they aren't perfect, and in some cases need an overhaul or better mechanisms for measuring.
You'll see them in "cards" like the following:

:::{card} Here's a card
And here's some extra information!
:::

We'll include a brief explanation of why we use each of these measures, and what we might want to improve about them.
You'll find those in dropdowns similar to the one you're reading now.

[See our KPIs documentation](https://compass.2i2c.org/organization/kpis/) for more information about the metrics we track and aim to track.
::::

:::{note} How was this website created?
:class: dropdown
We created this website with the [MyST Document Engine](https://mystmd.org), a new system for authoring scientific narratives and documentation.
It is similar to the [Jupyter Book project](https://jupyterbook.org), though uses more modern web technologies.
We're exploring more ways to improve MyST for documents like these, and are using this report as a way to learn from it.
:::

## Impact through our cloud platform and service

2i2c provides a community-centric platform that enables the lifecycle of knowledge creation and sharing. At the heart of this model is a community JupyterHub that provides a digital space where many community members come together to access shared resources and work together[^communities][^seealsocommunities].

[^communities]: “Communities” are a combination of research groups, classrooms, communities of practice, and institutions that were actively using the service at the end of each date period.seelsocommunities Historically marginalized communities are defined as educational institutions that are not R1 universities (for example, community colleges) as well as communities that are primarily not based in North America or Western Europe.

[^seealsocommunities]: For a more in-depth picture of community hubs see our [Community Hubs Usage Dashboard](https://2i2c.org/kpis/cloud/).

::::{grid} 1 1 2 2

:::{card} More than 70 Active Communities
:link: https://2i2c.org/kpis/cloud/
See the latest data.
:::

:::{card} More than 7200 Monthly Active Users
:link: https://2i2c.org/kpis/cloud/
See the latest data.
:::
::::


The most direct measure of impact for 2i2c is in the number and diversity of communities that utilize our service. At the time of writing, our open science cloud platform serves more than **70 different communities**, at a total of around **7200 monthly active users**.

Below we show [the total number of communities served on our platform each year](#total_communities), with a focus on historically marginalized communities.

:::{figure} images/communities_served_by_year.png
:align: center
:name: total_communities

The total number of communities served on our platform each year. We show both the total number of communities, as well as communities designated as "historically marginalized" (for example, community colleges or communities from the global south).
:::


In addition we track [**Weekly Active Users** across all communities](#waus) to understand how frequently community members make use of the platform[^wau]. Below we show an estimate of Weekly Active Users at the end of each year of this grant.

[^wau]: This is defined as a user that starts their own Jupyter server within a week-long window. Note that this varies heavily based on the academic calendar, and spikes around the end of each academic semester.

:::{figure} images/waus.png
:align: center
:name: waus

Weekly Active Users (WAUs) at the start of this grant, and at one-year checkpoints throughout this grant.
:::



These communities are intentionally diverse in their scope and focus, and range from university-wide educational services ([University of Toronto](jupyter.utoronto.ca)), to multi-organization research collaborations (the [LEAP project at Columbia University](https://leap.columbia.edu/)), to major federal projects fighting climate change (the [US Greenhouse Gas Center](https://earth.gov/ghgcenter)), to networks of community colleges in California (the [CloudBank and UC Berkeley educational hubs collaboration](https://www.cloudbank.org/training/cloudbank-educators)), to international networks of historically under-resourced communities in the Global South (the [CZI-funded Catalyst Project](https://catalystproject.cloud/)). 

These numbers are beyond the expectations that we had for 2i2c when we first began this service, and speak to the value of open science platforms rooted in community-centric design and open infrastructure.

:::{note} How we chose measures for community impact
:class: dropdown

We chose to measure impact both at the community level (number of community hubs), as well as the amount of usage across all communities (monthly active users).
This is because 2i2c aims to balance *breadth* and *depth* of service, serving both many different kinds of workflows, but also providing enough flexibility that communities can tailor their hub to their needs and grow their total users.

We additionally track communities we define as "marginalized" because we believe that equity and democratizing access to infrastructure is a core part of 2i2c's mission.
Historically marginalized communities often lack the resources or expertise to manage and access infrastructure, and we want to ensure 2i2c's service benefits these communities.

In the future, we hope to perform more in-depth research to understand how these communities use our platform, as well as the diversity of user archetypes and workflows that are contained within a single community.

:::


## Capacity building for open source projects

Another key outcome of this grant was using 2i2c as a mechanism to grow capacity in open source ecosystems. 2i2c builds its open science platform by integrating community-driven open source projects. Providing upstream contributions and support to the communities that underlie these projects is a secondary goal that underlies 2i2c’s open practices as an organization[^upstream].

[^upstream]: For a more in-depth picture of our upstream contributions, see [our Upstream Contributions Dashboard](https://2i2c.org/kpis/upstream/).

:::{card} More than 2,000 Pull Requests authored by 2i2c and merged in last three years
:link: https://2i2c.org/kpis/upstream/
See the latest data.
:::

Since January, 2021, 2i2c’s team members have authored over **[2,000 merged pull requests across more than 600 repositories](https://github.com/search?q=author:choldgraf+author:haroldcampbell+author:colliand+author:jmunroe+author:Gman0909+author:AIDEA775+author:consideRatio+author:damianavila+author:georgianaelena+author:sgibson91+author:yuvipanda+org:jupyter+org:jupyter-server+org:jupyterhub+org:jupyterlab+org:binder-examples+org:executablebooks+org:cryptnono+org:dask+org:pydata+org:rocker-org+org:pangeo-data+is:pr+merged:%3E=2020-12-01)** in “key upstream communities” that underlie our infrastructure[^kuc]. For example, [here is a summary of merged Pull Requests in key upstream repositories](#prs_by_repository) that were authored by a 2i2c team member over the last two quarters:

[^kuc]: A Key Upstream Community is an open source community that builds infrastructure considered strategically critical for 2i2c’s services and impact.

:::{figure} images/prs_by_repository.png
:align: center
:name: prs_by_repository

PRs authored by a 2i2c team member that were merged in the last two quarters, for key upstream communities. See latest data at [2i2c.org/kpis](https://2i2c.org/kpis).
:::


2i2c now [**employs 6 “distinguished contributors” to the Jupyter Community**](https://jupyter.org/about#distinguished-contributors), as well as several team members that create training and guidance programs to help communities use these open source tools to their full potential. We have driven major enhancements to technology in the stack, such as bringing [Binder-like environment building to JupyterHub](https://2i2c.org/blog/2024/jupyterhub-binderhub-gesis/), or [creating a more flexible and powerful user environment selector](https://github.com/yuvipanda/jupyterhub-fancy-profiles), or [defining a new documentation back-end for the Jupyter Book ecosystem](https://executablebooks.org/en/latest/blog/2023/new-project-members/).

We believe that no other organization exists that has served such a diverse collection of community partners in open science workflows while providing entirely open source technology that is driven by multi-stakeholder communities of practice. This highlights our commitment to ensuring these open source communities are healthy.

:::{note} How we chose measures for upstream impact
:class: dropdown

Measuring "impact" in open source communities is difficult without additional resources to interview community members and understand the true impact of a person's participation in a community.
Many projects track "volume-based" metrics like "number of comments", "issues opened", etc, but these are not necessarily correlated with "useful contributions" (and in some cases may be anti-correlated).

We decided to use "Pull Requests authored by 2i2c team members that were merged" as a reflection of both "work done by 2i2c team members" in addition to "work that was deemed useful by the community and thus merged into its codebase". This almost certainly under-counts the many non-development ways that our team contributes (for example, providing guidance in issues, reviewing the work of others, and providing broad leadership and strategic guidance). We hope to find better ways to measure the breadth of our upstream contributions in the coming years.

:::

## Organizational capacity and sustainability

Finally, 2i2c aimed to achieve this impact in a sustainable way that grew the capacity of the open science and open source ecosystems. This ensures that we have a model for sustainably serving our communities and the open source ecosystem into the future.

:::{card} More than $5.5 million in funding brought in over three years.
Distributed between 2i2c and its partners.
:::

Over the last three years, 2i2c has brought in **over $5.6 million** (including this grant) to fund the capacity needed to carry out its operations. The majority of our funds have come from direct grants to 2i2c, or grant-funded collaborations with other communities. Over time, we have increased the percentage of our revenue that comes from service contracts, and aim to continue this trend to further diversify our sources of funding.

Below is a graph of [2i2c’s total funding broken down by major category](#funding_by_contract_type). Note that for several grants, 2i2c was not the sole recipient of funds, but served as the Principal Awardee for the grant.

:::{figure} images/total_funding_by_contract_type.png
:align: center
:name: funding_by_contract_type

Total funding brought in by 2i2c throughout this grant (the first three years of its existence), broken down by major category. Note that not all funding went to 2i2c as in many cases we distributed funding to other collaborators and partners via grant sub-contracts.
:::

And the same data broken down by quarter since the beginning of this grant:

:::{figure} images/total_funding_by_quarter.png
:align: center
:name: funding_by_quarter

Total funding brought in by 2i2c for each quarter of this grant, broken down by major category. Note that not all funding went to 2i2c as in many cases we distributed funding to other collaborators and partners via grant sub-contracts.
:::


Here are the [new service contracts in each quarter since the start of this grant](#contracts_by_quarter). This is a reflection of the revenue-generating partnerships that 2i2c has created.

:::{figure} images/service_contracts_by_quarter.png
:align: center
:name: contracts_by_quarter

Service contracts each quarter during the lifecycle of this grant, broken down by major category.
:::

Finally, over the past three years 2i2c has also grown and matured as an organization. We began with a team of **two** (an Executive Director and one Engineer). We are now a team of **twelve**, with organizational capacity split across engineering, community partnerships, product management, and organizational operations and strategy.

:::{figure} images/staff_members.png
:align: center
:name: staff_members

Total number of paid staff (full or part time) at 2i2c. This reflects our organizational capacity and an increasing complexity and scope of operations. Note that two additional staff members have been hired since the end-date of this grant, and 2i2c's current team is 12 paid staff.
:::

This more complex structure reflects a more mature organization that understands the roles that are needed in order to deliver excellent open science cloud services to research and education communities. We also believe this model can serve as a guide for mission-driven organizations that facilitate collaboration between the open science and open source communities.

However, the additional staff in our team also has a significant impact on our organizational costs.
As a result, one of our main strategic objectives heading into the next year is to raise funds that allow us to continue providing 2i2c's community-centric service at our current staff levels.

:::{note} How we chose measures for organizational capacity
:class: dropdown

Measuring organizational capacity is also difficult because it is an inherently multi-faceted quality that is not easily captured by a single number.
In addition, 2i2c is still relatively young, and thus is still growing its capacity to measure organization-wide traits like this.
We believe that our recent [Delivery Manager / Chief of Staff role](https://compass.2i2c.org/engineering/roles/delivery-manager/) will help us refine our understanding and practice around organizational capacity.

In the meantime, we choose "financial support" as well as "team size" as a reflection of overall capacity. This is because at a fundamental level, any organization is both balancing the cost of its operations against its ability to bring in revenue to fund those operations.
Growing an organization is a constant balancing act between matching your organizational capacity (your costs) to your organizational commitments (which bring in revenues).
It is also a way for us to track improvements in team efficiency and skills (by being able to grow our operations without significantly growing our costs).

In the future, we aim to define measures of team velocity and efficiency, in order to more directly measure our ability to deliver work and enhance our service.
We hope to balance this against the numbers-based "cost" and "revenue" metrics in order to ensure our team becomes more efficient and effective over time.

:::


## Areas for growth and next steps

After three years, 2i2c’s service has demonstrated a clear demand for community-centric science platforms built on open infrastructure, and continues to grow the percentage of costs it recovers from service contracts versus grants. We’ve also identified challenges to overcome in order to carry the organization forward into its next phase. Below is a brief description of each. 


### Refine our operating and service model

In 2023, our team felt like we hit a ceiling in how quickly we could make strategic progress. The growth of our service, paired with a lack of evolution of our team’s planning mechanisms, led to a lot of reactive work and a lack of alignment on next steps. The organic growth of our service is an excellent indicator that we are delivering value and having an impact. However we also believe that we need a sharper definition of our value proposition, service offering, and pricing/funding model.

To address this, we partnered with an organizational consultant to audit 2i2c’s structure and practices and make recommendations for adjustments. We [published the consultant’s full report at this Zenodo entry](https://doi.org/10.5281/zenodo.10081003) and [provide more detail in this blog post](https://2i2c.org/blog/2023/organizational-report/). We next turn to implementing the recommendations made in the report, and measuring whether this has had a positive impact on our team, with the goal of **refining our organizational value proposition and operating model**. 

To begin, we’ve created new roles dedicated to overseeing our team’s system of work as well as product strategy and user research. We’ve also invested in People Operations capacity in order to design support and growth plans for our team. We believe this will allow us to make more strategic improvements to our platform and to the upstream communities we support.


### Grow our service and runway through fundraising

As of this writing, we have approximately 11 months of runway remaining. This is within the lower end of our “comfort range”, and the cost of our new hires create a sense of urgency to raise funds for the next phase of 2i2c’s operations. The organizational refinement described above sets up 2i2c for a subsequent phase of growth in the communities that we serve, in order to cover these new costs. 

We are currently exploring a combination of grants, donations, and service contracts, with a goal of extending our runway by another three years. Once we make the necessary adjustments to improve our operating model described above, we will next focus on this goal to ensure that 2i2c may continue to provide value to open science communities across the world. By improving our value proposition, product, and service operations, we will improve our chances of bringing in funding to extend our organizational runway and move us closer towards long-term sustainability.


## Acknowledgements

2i2c’s success would not be possible without [the critical support it received from CZI at its founding](https://2i2c.org/blog/2021/czi-core-support/). The capacity provided by this grant was a crucial moment in crystallizing the vision of 2i2c and taking our first steps as an organization. We are honored to have had this chance to build an impactful, open, and ambitious organization like 2i2c, and we’re excited about the next step in our organization’s journey.
