theme: next,1
footer: ![inline 8%](https://www.cloudfoundry.org/wp-content/uploads/2017/10/cloud-gov.png) @18f
build-lists: true
slidenumbers: true


# Enabling Innovation in Government with Cloud Foundry
## Peter Burkholder

![inline](media/logo.png)

[.background-color: #FFFFFF]
[.header: #28517c]
[.hide-footer: true]

---


# Cloud

---

# 2011-02-08: Cloud First

* Adoption lags....
* $85B, $2B on cloud (FY 2016)
* DOD JEDI first major buy to consolidate +4k DCs
* USDA COE effort to consolidate 38 -> 2 


---

# So not realizing benefits of:

* cost (capex/opex, sometimes savings)
* automation
* security
* mission focussed IT
  * lean/agile
  * innovation

---

# Uneven implementation

* naïve lift-and-shift
* re-implementing iron in the cloud
* high spend and low utilization

^ So not realizing benefits in cost, security, automation

---

# Mission-focussed IT

---


# Does IT matter?

* 2003: HBR Nicholas Carr: IT Doesn't Matter
* ... but then: DevOps
* 2014: Gartner --  BiModal IT
* ... but hi-perf IT orgs still out-performed

---

Lean/Agile in one slide

---

# 2014-2017: State of DevOps Reports

(image)

---

# Metrics

---

# Traditional IT Measures

* Lines of Code
* Velocity
* Utilization
* Uptime (ops)

^all of these have problems, but especially uptime


---

# High-performance Measures

* Release frequency
* Lead time (commit to release)
* % change fail rate
* MTTR
* SLOs

---

Example SLO / SLI

SLI: API responds within 500ms for 99% of users (observed, not synthetic)
SLO: SLI is met 99.97% of time per month (13m/month)

---

# Culture measures

* Westrum safety culture (aviation/healthcare)
  * 7 statements on Likert scale
* Generative: results-driven
* Bureaucratic: rule-driven
* Pathological: power-driven

---

# How to get there from here?

* Cloud / Automation
* Mission-focussed IT
  * Tax dollar stewardship
  * Better value delivery
* But: 
  * Months/year to procure/authorize
  * Lack of clear path

---

# Our path

* Nucleate 
* Authorization reuse (FedRAMP)
* Build at high-water mark
  * SaaS > PaaS > IaaS > DC

^ Rely on tech you don't manage yourself. Mission focus

---

# High water slides

---

# cloud.gov

* 2016: no FedRAMP PaaS for open-source frameworks



---

# Today

* everything is code
* everything is automated

---

# How to get there from here

* Agile procurement
* 1-button releases (or 1-slide)
  * No runbooks on critical path
* Everything in version control
  * Snover quote
* Product autonomy
* Measure and emit culture metrics

* Authorization reuse (FedRAMP)
* Build at high cable-car mark
  * SaaS > PaaS > IaaS > data center


^  (Audit, control, collaboration, sharing, communicate) - not runbooks

# Strategy words:

* Agile procurement
  * [I have nothing on this except what's in this slide: https://gsa-tts.slack.com/archives/C054NH1FW/p1526483032000750]
 

* Start small, start core
  * The Forest Service christmas tree permitting is a good example. FS makes
    lots of money from lumber permitting. They started literally with their
    smallest tree. But it's a public-facing one, one that could see a complete
    transformation.

  * Small
    * What's the right size? The two-pizza team
    * Self-sufficient. Must have autonony, with embedded team members in ops/security/acq, or dedicated personnel who are empowered
    * No CRB/CABs. They have negative value
  * Core
    * Are people excited about it?
    * Compete the opportunity to be involved
    * Broadcast progress with updates, or dashboards

  * How to tell it's working


* Everything in Version Control
  * Openness
  * Builds habits of everything being expressed in code
  * Builds habits of peer review and accountability
  * Make code the _only_ way changes are made (Infrastructure-as-Code, release
    pipelines)
  * Audit & Control

  * How to tell its working
    * People communicate over merge/pull requests
    * People take pride in commit history

* Release from day one

