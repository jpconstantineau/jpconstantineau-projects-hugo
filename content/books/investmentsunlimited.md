---
title: "Investments Unimited (Beal et al.)"
date: 2023-06-15
type: "book"
summary: "A Novel about DevSecOps and automating compliance governance"
featureImage: "https://itrevolution.com/wp-content/uploads/2022/07/IU_CVR_front_RGB-scaled-331x496.jpg.webp"

tags: ["DevSecOps", "Novel"]
---
This book is a novel in the same line as The Phoenix Project and The Unicorn Project. It however takes place at a financial institution that implemented DevOps but recently received a MRIA (Matter Requiring Immediate Attention) notice from the governmental authorities. The book looks at automating the documentation and governance around the development, deployment and approval processes.  The book is much thinner than the previous two.  The lessons are nonetheless still valuable when an audit trail is needed around the approval processes and policies that enable continuous deployment of your applications to end users while still preventing unreviewed, unapproved or insecure code to reach production.  Even for non-regulated industries, this book provides good lessons regarding the different quality gates and checks that an application should go through before being released. 

It covers areas such as peer code reviews, 3rd party and open source libraries checks, static application security testing, SBOM, code quality, unit tests, code coverage, code signing.  Since many of these checks are automated with various tools, they can be part of a CI/CD pipeline; essentially automating checklist items.  The novel element that the book highlights is bringing all the results into a common reporting platform - an immutable artifact store and dashboard to present the current state of all tests so that if a failing gate is shown, stakeholders can make an informed decision on the risk of deploying the build and make the final go decision to manually deploy.  If all gates pass, the build is automatically approved for deployment to production.  It's all about making it visible, traceable, auditable and most importantly it's about documenting the release and review process so that all projects can have a standard set of guidelines; with go/no-go thresholds that can be adjusted on a per-project basis, depending on the risk profile of the project.   The automated process is the golden path that should be easy for all new projects to adopt.  Legacy projects can follow the same guidelines, although in a manual way.  The system provides them with a framework of all the items and checks to consider, their go/no-go thresholds to define and a way to document everything for each release.    

The book refers to the "[DevOps Automated Governance Reference Architecture](https://itrevolution.com/product/devops-automated-governance-reference-architecture/)" which provides much more technical details on the components of an Automated Governance System.

In an appendix, this book introduces the [DevSecOps Manifesto](https://www.devsecops.org/).