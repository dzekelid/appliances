---
name: Hewlett Packard Enterprise (HPE)
x-slug: hewlett-packard-enterprise-hpe
description: We help customers use technology to slash the time it takes to turn ideas
  into value. In turn, they transform industries, markets and lives. Some of our customers
  run traditional IT environments. Most are transitioning to a secure, cloud-enabled,
  mobile-friendly infrastructure. Many rely on a combination of both. Wherever they
  are in that journey, we provide the technology and solutions to help them succeed.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Appliances
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/appliances/master/_listings/hewlett-packard-enterprise-hpe/apis.md
specificationVersion: "0.14"
apis:
- name: HPE OneSphere API - Get Appliances
  x-api-slug: appliances-get
  description: Returns appliances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appliances/master/_listings/hewlett-packard-enterprise-hpe/appliances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appliances/master/_listings/hewlett-packard-enterprise-hpe/appliances-get-openapi.md
- name: HPE OneSphere API - Post Appliances
  x-api-slug: appliances-post
  description: Create an appliance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appliances/master/_listings/hewlett-packard-enterprise-hpe/appliances-post-openapi.md
- name: HPE OneSphere API - Delete Appliances
  x-api-slug: appliancesid-delete
  description: |-
    Delete an appliance.
    This removes the appliance registration and tears down the secure
    comms link to the on-premise appliance.
    If zones exist on this appliance, an '409' error will be returned.
    The zones on this appliance must be removed before the appliance
    delete request can be accepted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appliances/master/_listings/hewlett-packard-enterprise-hpe/appliancesid-delete-openapi.md
- name: HPE OneSphere API - Get Appliances
  x-api-slug: appliancesid-get
  description: Returns an appliance based on its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appliances/master/_listings/hewlett-packard-enterprise-hpe/appliancesid-get-openapi.md
- name: HPE OneSphere API - Patch Appliances
  x-api-slug: appliancesid-patch
  description: Update properties of an appliance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appliances/master/_listings/hewlett-packard-enterprise-hpe/appliancesid-patch-openapi.md
x-common:
- type: x-developer
  url: https://developer.hpe.com/
- type: x-github
  url: https://github.com/hewlettpackard
- type: x-openapi
  url: https://raw.githubusercontent.com/HewlettPackard/hpe-onesphere-http/master/swagger.yml
- type: x-twitter
  url: https://twitter.com/HPE
- type: x-website
  url: http://HPE.com
- type: x-api-gallery
  url: http://heroku.api.gallery.streamdata.io
- type: x-api-stack
  url: http://hewlett.packard.enterprise.hpe.stack.network
- type: x-blog
  url: https://developer.hpe.com/blog
- type: x-curated-source
  url: http://community.hpe.com/t5/LoadRunner-and-Performance/LoadRunner-and-VuGen-12-53-load-testing-software-What-s-new-in/ba-p/6885101
- type: x-website
  url: https://www.hpe.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---