---
layout: essay  
type: essay  
title: Statement of Purpose  
labels:
  - PhD Portfolio
--- 

*This page presents my statement of purpose in computer science as required for the [ICS Ph.D. Portfolio](http://www.ics.hawaii.edu/academics/graduate-degree-programs/ph-d-in-ics/#phd-portfolio). It summarizes my professional interests in research, teaching, service, and/or product development.*

## Background and Research Interests

Current work in software and safety vulnerabilities is yet to reach a stage where good practice meets usability. One does not need look further than their peers to expect their computers a few weeks behind in security patches \[[1](https://www.microsoft.com/security/blog/2014/06/17/when-vulnerabilities-are-exploited-the-timing-of-first-known-exploits-for-remote-code-execution-vulnerabilities/)\]. On social media, tweets and posts spread like wildfire questioning companies how hitting a login button a couple times with an empty password can grant a user root access \[[2](https://twitter.com/lemiorhan/status/935578694541770752)\]. On the other end of the arena, developers question the ability of proper documentation of software vulnerabilities, and if cataloging organizations are up to task, given the increasing delay to index the increasing number of vulnerabilities \[[3](https://www.csoonline.com/article/3204568/closing-the-cve-gap-is-mitre-up-to-it.html)\]. Aerospace safety incidents involving software buggy behavior are inquired to have been already reported in incidents databases, but not effectivelly collected, analyzed, and trend to identify safety risks. \[[4](https://www.vox.com/business-and-finance/2019/3/29/18281270/737-max-faa-scandal-explained) \[[5](https://www.dallasnews.com/business/airlines/2019/03/12/boeing-737-max-8-pilots-complained-feds-months-suspected-safety-flaw)\], \[[6](https://www.oig.dot.gov/sites/default/files/FAA%E2%80%99s%20Oversight%20of%20the%20Voluntary%20Disclosure%20Reporting%20Program%5E4-10-14.pdf)\].

These concerns highlight the state of the art in software and safety vulnerabilities offers several fronts of improvement.

## Progress

Over the past three years I have designed and maintained a Github project incubator, [PERCEIVE](https://github.com/sailuh/perceive), which served to assist faculty and I to host, mentor, track and collaborate now 17 independent studies, honors presentations, and capstones at both undergraduate and master's student level. In the spirit of an open source project,
through issues, pull requests and code reviews we created Crawlers \[[1](https://github.com/sailuh/perceive/tree/master/Crawlers)\] to parse social media using various heuristics to parse irrelevant information and spam, 
several Python notebooks \[[2](https://github.com/sailuh/perceive/blob/master/Notebooks/CVE_Details/cve_details_introduction.ipynb)\], \[[3](https://github.com/sailuh/perceive/blob/master/Notebooks/CWE/cwe_introduction.ipynb)\], \[[4](https://github.com/sailuh/perceive/blob/master/Notebooks/CAPEC/Introduction/capec_introduction.ipynb)\], and explore ideas and understand collected data to support the project vision
to identify software vulnerabilities as concepts. 

We have also identified, and recycled abandoned and hard to reuse open-source code, \[[5](https://github.com/sailuh/topicflow)\], \[[6](https://github.com/sailuh/termite)\]. having my own personal contribution being the construction of an R package that serves as data pipeline bridge between data and visualization tools \[[7](https://github.com/sailuh/topicflowr)\].

Through the use of this pipeline, we have stablished research collaborations and/or funding for the research with the [US Air Force Reasearch Laboratory (AFRL)](https://afresearchlab.com/), [US CERT](https://www.us-cert.gov/), [NASA](https://www.nasa.gov/ames), [University of Maryland](https://terpconnect.umd.edu), and [Drexel University](https://drexel.edu/), having now three published works supporting the validity of it's ideas vision and potential for future work in aerospace [7](https://aisel.aisnet.org/hicss-50/st/cybersecurity_and_sw_assurance/4/), [8](https://ieeexplore.ieee.org/document/8614146), [9](https://arc.aiaa.org/doi/abs/10.2514/6.2019-0770). Ongoing collaboration work seeks to further strengthens the results through usage in different datasets, and extend the analysis of software vulnerability as bugs and concepts over within and over months.

##  Goals

In the next year I intend to polish, leverage and publish more of the pipeline and collaboration work to submit a proposal for a framework to identify software vulnerabilities as bugs and concepts and it's applications. Within two years I hope to implement, and defend the project vision. 