# DevOps Help Bot

This bot used for helping in administation and moderation DevOps groups in telegram. Used [Python telegram bot](https://github.com/python-telegram-bot/python-telegram-bot).

## History

Was published from private repo on version `v2.1.0`

## Badges

[![Known Vulnerabilities](https://snyk.io/test/github/Asgoret/devopshelper_bot/badge.svg)](https://snyk.io/test/github/Asgoret/devopshelper_bot) [![CodeFactor](https://www.codefactor.io/repository/github/asgoret/devopshelper_bot/badge)](https://www.codefactor.io/repository/github/asgoret/devopshelper_bot)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FAsgoret%2Fdevopshelper_bot.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FAsgoret%2Fdevopshelper_bot?ref=badge_shield)

## Realese policy

For example `v1.1.0`.
`1.` - major version
`.1.` - minor version (max 9 new features, then upgrade of major version)
`.0` - version for fixes

## Commands

__Admin commands:__

* `/mute 10` - where `10` days (works on replied message)
* `/warn` - add 1 warn to user. If user gets 3 warns will be banned for 3 days (works on replied message)
* `/unwarn` - delete 1 warn from user (works on replied message)
* `/move` - move message from one chat to another (works on replied message)
* `/job` - forward message to job channel

__User commands:__

* `/man` - send list of commands to chat
* `/coc` - send code of conduct to user
* `/jobs` - send rules of publishing job opportunities and cv
* `/ad` - send rules of publishing advertising
* `/chats` - send list of friendly chats
* `/events` - send list of events to user
* `/starter` - send starter kit to user
* `/middle` - send starter kit to user
* `/course` - send to user list list of courses
* `/cert` - send user list of certification tips & tricks
* `/relocate` - send user list of relocate chats and channels
* `/report` - forward replied message to admin chat and send link of replied message for fast-navigation
* `/summon` - summon HR to DevOps Jobs chat (works on replied message)

## Feature roadmap

| Feature            | Status |
| ------------------ | -------|
| Report             | [x]    |
| Mute               | [x]    |
| Starter Kit        | [x]    |
| Middle Kit         | [x]    |
| Senior Kit         | []     |
| Rules              | [x]    |
| Antiforward filter | []     |
| Call HR            | [x]    |
| Ban                | []     |
| Warn counts        | [х]    |
| Event message      | []     |
| Man                | [x]    |
| Job                | [x]    |
| Course             | [x]    |
| Certificate        | [x]    |
| Relocate           | [x]    |

## Project roadmap

| Feature            | Status |
| ------------------ | -------|
| CI/CD              | []     |
| Healtchecks        | []     |
| Readnes Probe      | []     |
| Livelenes probe    | []     |
| Tests              | []     |
| Databes            | []     |
| Monitoring         | []     |
| ML                 | []     |
| Webhooks           | []     |


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FAsgoret%2Fdevopshelper_bot.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FAsgoret%2Fdevopshelper_bot?ref=badge_large)