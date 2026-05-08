# Confluence User Macros

[![Tested on Confluence v7.3.2](https://img.shields.io/badge/confluence-v7.3.2-mediumseagreen.svg?logo=confluence)](https://confluence.atlassian.com/doc/confluence-7-3-release-notes-983794557.html) ![No active maintenance](https://img.shields.io/badge/maintained-no-crimson.svg?logo=github) [![Partly supported](https://img.shields.io/badge/supported-partly-darkorange.svg?logo=github)](https://github.com/nerdzone-nl/confluence-user-macros/issues)

## Introduction: Goodbye old friend
As a self-hoster I <s>am</s> was a big fan of running the [Confluence](https://www.atlassian.com/software/confluence) thing smoothly on one of my little servers.

But a couple of years ago our friends at [Atlassian](https://www.atlassian.com) decided to drop support and development of their server products [in favour of their cloud products](https://www.atlassian.com/migration/assess/journey-to-cloud). As their datacenter products are [not suitable for individuals and small businesses with small purses](https://www.atlassian.com/licensing/data-center) and the cloud lacks support of the [Apache Velocity](https://velocity.apache.org/) templating engine used for User Macros, I had to say goodbye.

## A little archive of Confluence User Macros

I'm still running an old unsupported instance for convenience, but it may or may not break on serverupdates. I won't test that anymore.

Therefor I created this repo, which serves as a little archive. It contains some User Macros which may be useful to you. Feel free to use any of them. Note that some of them are credited to users in the community.

Here's the list:
|Filename|Description|
|:-|:-|
| [_nz-confluence-user-macro-template.vtl](./_nz-confluence-user-macro-template.vtl) | Header template for User Macros |
| [nz-auto-reload.vtl](./nz-auto-reload.vtl) | Automatically reload a page after a given time. Use this macro only once on a page. |
| [nz-expand-all.vtl](nz-expand-all.vtl) | Creates a link or button to toggle all [Expand macros](https://confluence.atlassian.com/display/DOC/Expand+Macro) at once on the current page. |
| [nz-simple-link-button.vtl](./nz-simple-link-button.vtl) | Macro for adding simple stylish buttons. |
| [nz-space-administrators.vtl](./nz-space-administrators.vtl) | Macro to display a list of space administrators. |

## A note of support
The macros in this repo were all tested on an old formerly supported server version [v7.3.2](https://confluence.atlassian.com/doc/confluence-7-3-release-notes-983794557.html) of Confluence. If you create an [issue](https://github.com/nerdzone-nl/confluence-user-macros/issues) I might not be able to help as I've no access to any other instance anymore.
