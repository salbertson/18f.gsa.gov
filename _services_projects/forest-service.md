---
agency: Forest Service
title: Moving land permits online
subtitle: Easing access to public lands
permalink: /what-we-deliver/forest-service/
excerpt: Using prototypes and modular contracting to help the Forest Service buy an online permit system.
image: /assets/blog/forrest-service/xmas-tree-permit.png
image_accessibility: Screen shot of the Christmas tree permit website
image_icon:
project_weight: 8
tag: forest service
expiration_date:
github_repo:
  - "[Project repository](https://github.com/18F/fs-online-permitting)"
  - "[U.S. Forest Service Permit Platform](https://github.com/18F/fs-permit-platform)"
  - "[ePermit Middlelayer API](https://github.com/18F/fs-middlelayer-api)"
project_url:
learn_more:
product_clients:
resources:
    - "[e-Permit API task order](https://github.com/18F/bpa-fs-epermit-api)"
    - "[e-Permit intake task order](https://github.com/18F/bpa-fs-epermit-intake)"
    - "[Christmas Tree task order](https://github.com/18F/bpa-fs-xmas-trees)"
---

The U.S. Department of Agriculture’s Forest Service issues permits to
the public to conduct outfitting trips, large scale events, and cut down
their very own Christmas tree on National Forest land.

The Forest Service wanted to make their permits and applications
available online to create a more predictable application process that
was not limited to regular business hours.

<div class="small-caps">Approach</div>
### Breaking the work into modules

Before helping Forest Service hire private vendors to build a permit
tool, 18F conducted a series of workshops with the Forest Service to
investigate the business process behind permit applications. With that
information, we built a small prototype of the type of online permit
tool that could address their issues. We tested the prototype with both
the public and Forest Service employee users and used that research to
draft an RFP using 18F
[Acquisition’s Agile Blanket Purchase Agreement](https://18f.gsa.gov/what-we-deliver/agile-bpa/) (BPA).

Instead of putting the entire permit application tool into one RFP, the
team started by asking only for an API to connect to a legacy system
within the Forest Service. By breaking the work into pieces (called
modules) the Forest Service was able to get functionality quickly while
reducing risk on each module.

Working with the Forest Service and the vendor, we built the first API
module in four months. We provided technical and design guidance to the
vendor, and strategies for the Forest Service to serve as empowered
product owners.

With the API module in hand and working well, we then helped the Forest
Service draft, award, and manage two additional RFPs to build a
public-facing application and a module to support Christmas Tree
permits. We also integrated the application with
[login.gov](http://login.gov) so users could securely log in to the
system.

Breaking the system into modules and using 18F’s Agile BPA allowed the
Forest Service to see results quickly, reduce risk on each module, and
deliver a service that meets the needs of users. The 18F acquisition
team used each module to help the Forest Service learn new software
development and contract management techniques that will help them
continue to be a better buyer of technology.
