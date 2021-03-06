# OSS Project Status Indicators

[![OSS Status: Healthy](https://img.shields.io/badge/OSS%20Status-Healthy-darkgreen.svg)](OSS_STATUS.md)

Often, when you're looking at a project on GitHub, it's hard to tell how "loved" the project is.

- Is anyone reviewing the Issues?
- Are pull requests welcomed?
- Has the original maintainer lost interest in mainting this project? Is the project looking for a new owner?
- Is the project simply a snapshot in time, and not something that should be taken as a dependency?

The answers to these questions can sometimes be determined by looking at commit history, or the open and closed issues. Often, you can look at the age of pull requests, and the number of PRs that have been accepted or merged. Sometimes, however, it's not clear.

Wouldn't it be easier if, like build status, this were clearly signalled within the README of the project?

Maybe.

## What you'll find here

This repository contains a set of folders. Each folder contains an `OSS_STATUS.md` file. You can take a copy of this file and place it in the root of your project.

Additionally, there are a set of badges defined here to go with each of the health statuses. Each `OSS_STATUS.md` has an example of this badge, and you can copy/paste the markdown into the `README` of your project to make the status of your project clear to potential contributors.

## How to use the files

1. Copy the appropriate OSS_STATUS.md into the root of your project, much like you would do with a `LICENSE` file.
2. Update your own `README` file to contain an image and link (see below for details)

## Do you have an example I can look at?

Sure. You're looking at it. This repository has an `OSS_STATUS.md` file at its root, and this `README.md` file links to one of the images at the top. Take a look at the raw Markdown of this file for an example.

## Which status should I use?

You'll find a number of statuses defined here...

### Healthy

[![OSS Status: Healthy][healthy-badge]][healthy-markdown]

Project is actively being worked on. Issues and Pull Requests are welcomed. 

Should be used on projects that you actively welcome contributions.

URL Type | Location
--|--
Image URL: | `https://img.shields.io/badge/OSS%20Status-Healthy-darkgreen.svg`
Description URL: | `https://github.com/martinpeck/oss-project-status/blob/master/healthy/OSS_STATUS.md`

### Healthy, Closed

[![OSS Status: Healthy, Closed][healthy-closed-badge]][healthy-closed-markdown]

Project is actively being worked on, but at this stage you're not looking for contributions. People are welcome to raise issues, comment on code, or create pull requests, but they may well be politely turned down.

Might be used on a personal blog, or portfolio website, where contributions may not make sense. Might be used on a project in the very early stages of development, where things are changing rapidly and aren't yet full defined, and the author isn't ready to take contributions.

URL Type | Location
--|--
Image URL: | `https://img.shields.io/badge/OSS%20Status-Healthy,%20Closed-darkgreen.svg`
Description URL: | `https://github.com/martinpeck/oss-project-status/blob/master/healthy-closed/OSS_STATUS.md`

### Dormant

[![OSS Status: Dormant][dormant-badge]][dormant-markdown]

Project is *not* being actively worked on. Issues and Pull Requests may not be actioned or considered. Contributors may be better off taking a fork of the project, and making enhancements there.

URL Type | Location
--|--
Image URL: | `https://img.shields.io/badge/OSS%20Status-Dormant-blue.svg`
Description URL: | `https://github.com/martinpeck/oss-project-status/blob/master/dormant/OSS_STATUS.md`

### Abandoned

[![OSS Status: Abandoned][abandoned-badge]][abandoned-markdown]

Project is not being worked on, and is very unlikely to ever be worked on again. Software should be considered read-only. Software may well be broke, unpatched, and out of date. Contributors should fork the repo if they see value in the code, but do so with caution. The owner may well be interested in handing ownership over to someone else. 

URL Type | Location
--|--
Image URL: | `https://img.shields.io/badge/OSS%20Status-Abandoned-lightgray.svg`
Description URL: | `https://github.com/martinpeck/oss-project-status/blob/master/abandoned/OSS_STATUS.md`

## What if I have a slightly different situation to the ones defined here?

You're welcome to modify or adapt these to fit your needs. You're also welcome to submit PRs for new statuses, or to modify the existing ones.

The main thing to remember is that you're trying to set expectations in a succinct manner. You want visitors to your project to very quickly get a general idea of the status of your project.

If you have nuences and subtlties that aren't expressed easily with a status image and some template text, then maybe you should be more explicit in your README or elsewhere in the repository.

## Isn't this rather gloomy? Why would an OSS project ever get into these states?

Stuff happens. The life of an OSS maintainer changes. If you generate a lot of useful OSS projects you can find yourself inundated with issue, pull requests, and requests for features/changes/whatever. For many, that's **an awesome situation to be in** but, once in a while, maintainers find themselves having to support their legacy OSS projects, and feel guilty when they can't devote time to OSS project that they've pretty much stopped using, or thinking about.

It can often take a long time for an OSS maintainer to remember "what does this code even do!?!" before they're able to properly respond to an issue or PR.

These statuses help the maintainer feel like they've set expectations with a potential user, and will hopefully warn users about the status of a project before they take a dependency on the code, or spend time on a pull request that then goes nowhere.

It's better to be honest, than to disappoint people and feel stressed in doing so.

## Is this a good idea?

Not sure. You tell me. Feel free to raise an issue or open a PR.

## Licensing

Copyright (c) 2019 Martin Peck

Covered by MIT license (see [`LICENSE`][license] file)

[license]: LICENSE
[healthy-badge]: https://img.shields.io/badge/OSS%20Status-Healthy-darkgreen.svg
[healthy-markdown]: https://github.com/martinpeck/oss-project-status/blob/master/healthy/OSS_STATUS.md

[healthy-closed-badge]: https://img.shields.io/badge/OSS%20Status-Healthy,%20Closed-darkgreen.svg
[healthy-closed-markdown]: https://github.com/martinpeck/oss-project-status/blob/master/healthy-closed/OSS_STATUS.md

[dormant-badge]: https://img.shields.io/badge/OSS%20Status-Dormant-blue.svg
[dormant-markdown]: https://github.com/martinpeck/oss-project-status/blob/master/dormant/OSS_STATUS.md

[abandoned-badge]: https://img.shields.io/badge/OSS%20Status-Abandoned-lightgray.svg
[abandoned-markdown]: https://github.com/martinpeck/oss-project-status/blob/master/abandoned/OSS_STATUS.md
