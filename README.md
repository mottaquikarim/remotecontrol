[![logo](https://github.com/mottaquikarim/remotecontrol/raw/master/assets/remote-control.png?raw=true)](https://github.com/mottaquikarim/remotecontrol/blob/master/assets/remote-control_attribution.md)

# REMOTE CONTROL

*A series of small, composable tools for teaching remote courses.*

The purpose of this repo is to provide references to functions, bots and apps (refered to from here on out as "**services**") developed to aid in the teaching of remote courses. In spirit these services will be written to be organization agnostic. Ideally they should be usable freely and easily within any organization (General Assembly, etc). However services can and likely will require prerequisites such as Slack tokens or API keys in order to properly function. As a general rule of thumb, all services should be easily deployable by forking a repo and following set up instructions. Optionally, some services may be deployed and open to free use by the larger community - these decisions will be made on a service-by-service basis and uptime / support of the for-community deployed services are not gaurunteed.

## SERVICES

*List of available services, with links to repo and brief description*

### [Rehearsal](https://github.com/mottaquikarim/rehearsal)
**TYPE**: APP

Markdown editor that allows you to preview revealjs slideshows as you go. Super simple; copy and paste markdown to whereever needed once done.

[![Build Status](https://travis-ci.org/mottaquikarim/rehearsal.svg?branch=master)](https://travis-ci.org/mottaquikarim/rehearsal) [![Coverage Status](https://coveralls.io/repos/github/mottaquikarim/rehearsal/badge.svg?branch=master)](https://coveralls.io/github/mottaquikarim/rehearsal?branch=master)


### [Pod](https://github.com/mottaquikarim/pod)
**TYPE**: BOT

Simple serverless script that will post a practice problem to a prespecified slack channel daily.

[![Build Status](https://travis-ci.org/mottaquikarim/pod.svg?branch=master)](https://travis-ci.org/mottaquikarim/pod) [![Coverage Status](https://coveralls.io/repos/github/mottaquikarim/pod/badge.svg?branch=master&foo=bar)](https://coveralls.io/github/mottaquikarim/pod?branch=master)


### [ContnetConverter](https://github.com/mottaquikarim/contentconverter)
**TYPE**: SCRIPT

Converts Markdown webpage content to revealjs format (configurable). Outputs folderstructure and readme that can be pushed to a github repo. **[Example](https://github.com/mottaquikarim/FEWDRemote)**: links and folder structure were generated from this script.

## TYPES

*List of defined service types*

* **APP**: Generally a static, purely javascript based web application. Typically deployed via github pages.

* **BOT**: Text bots or Slack related commands, interactive and deployed to a function (ie: AWS Lambda, Webtask, etc)

* **SCRIPT**: Utility scripts for converting between formats, etc. Usually one off but may contain classes / implementations that are useful for generic cases.

## [LICENSE](https://github.com/mottaquikarim/remotecontrol/blob/master/LICENSE)
