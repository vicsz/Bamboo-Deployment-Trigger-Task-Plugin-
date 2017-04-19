## Description

Bamboo Task Plugin to allow for Triggering of Deployments.

## Requirements

Requirements include having the atlassian SDK installed.
https://developer.atlassian.com/docs/getting-started/set-up-the-atlassian-plugin-sdk-and-build-a-project

# Steps

(After install the Atlassian SDK)

1. From commandline run: *atlas-run*
2. Go to : localhost:6990/bamboo/
3. Default login is admin/admin
4. Plugin will be installed by default (in Bamboo).

## TODO
1. Add Validation of Deployment Project / and Environment Name -- (save as id, and not name)
2. Wait on Deployment to finish for task to finish.

## Issues

Note broken backwards compatibility with Deployment Execution Service in version 5.9.

https://jira.atlassian.com/browse/BAM-16289