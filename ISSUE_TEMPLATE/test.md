name: test issue template
description: Use this template to request xxx
title: "issue for <what>"

body:

- type: markdown
  attributes:
    value: |
          ### Note:
          
          :warning:  Bridge Licenses are only for delayed renewals of already delivered products - this is not a path to request early access to a product not yet purchased :warning:
          
          :exclamation: Bridge Licenses are only required for Server. Sales-serve GHEC does not expire, this has to be manually turned off/de-provisioned. For this reason bridge licenses are *not* needed for Cloud-only customers.
          
          Certain extensions (eg. the client entering the day 46-90 range) require approvals from github/revenue so please give us as much advanced notice as you can. 
          
          Don't worry if you are not 100% sure your client will actually need the bridge, giving us as much notice as you can that you `might` need one will hopefully avoid any 11th hour scrambles to keep a client up and running!

- type: input
  id: contact
  attributes:
    label: Which Client or Prospect?
    description: Please link to account with the company name
    placeholder: "ex: https://github.com"
  validations:
    required: true

- type: input
  id: slug
  attributes:
    label: Slug?
    description: URL identifier
    placeholder: "ex: tonycch"
  validations:
    required: true
    
