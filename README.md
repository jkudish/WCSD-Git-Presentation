This git repository is my [2012 WordCamp San Diege presentation](http://2012.sandiego.wordcamp.org/schedule/).

This talk is all about using the version control system git; best practices, case studies and various workflows when using it with WordPress. I'll briefly explain what version control is and why you should use it, and them jump into three different WordPress-centric git scenarios: building themes, building plugins and developing private client projects. I'll show you how different individuals and companies use git (as well as Github and other solutions) within their development and production environments. I'll then present some of the software and tools that are available when working with git. I will talk about different branching and tagging methodologies, and finally I'll touch upon how WordPress.org could (potentially) further integrate with git (and Github). 

In the spirit of open-source and git, I am doing a bit of an experiment with the preparation for the presentation. The presentation's outline and slides are getting prepared on GitHub. That means both the outline and the slides are available there as I prepare them. The idea is that you (everyone/anyone) will collaborate by asking questions you want answered ahead of time, bringing suggestions, corrections and amendments along the way. I've outlined how I envision this process working, [here](http://jkudish.com/wordcamp-san-diego-2012/).

Below is the outline for the presentation (which is very much still a work in progress) and my slides are part of the repo as well. You can preview the slides at [jkudish.com/wcsd](http://jkudish.com/wcsd) (they get rebuilt everytime the repo is updated).

Whether you are an expert developer or barely know what version control is, I would love to have your feedback and expertise! That’s the idea, no idea if it will work or not. I think the presentation can be that much better with some feedback from the community, but if not, I promise not to disappoint you (too much) either way. If the experiment goes well, I'll also mention it during the presentation.

If you'd like to contribute, please submit a pull request or open an issues fo questions or comments. You can also reach me more privately at [info@jkudish.com](info@jkudish.com) if you'd like.

# Outline

## Intro

* Basic intro to version control
* WordPress uses SVN
* What is git
* Some git tools (Tower, github app, etc..)
* What is github and why it's awesome

## Case Studies

### Themes

* [Roots](https://github.com/retlehs/roots)
* [Automattic's _s](https://github.com/Automattic/_s)
* [Wordless](https://github.com/welaika/wordless)

### Plugins

* [WooCommerce](https://github.com/woothemes/woocommerce)
* [WP-post-formats](https://github.com/crowdfavorite/wp-post-formats)
* [Custom Metadata Manager](https://github.com/jkudish/custom-metadata)
* [WordPress github plugin updater](https://github.com/jkudish/WordPress-GitHub-Plugin-Updater)


### Private Clients

* Private repositories
* Beanstalk
* Deployhq
* Capistrano

### Other Projects

* [WP-cli](https://github.com/andreascreten/wp-cli)

### Core Development

* [WordPress/WordPress](https://github.com/WordPress/WordPress) repo / WordPress, Git-ified. Synced via SVN every 30 minutes, including branches and tags!
* Git-svn
* Scripts by scribu?
* How can WordPress.org further integrate with git(hub)?

---------------------------------------

# License & Copyright

2012 WordCamp San Diego Presentation by Joachim Kudish

Copyright (c) 2012 by Joachim Kudish

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA

This program incorporates work covered by the following copyright and
permission notices:

Original [Slide Presentation Framework by Brian Cavalier](https://github.com/briancavalier/slides)

Open Source Initiative OSI - The MIT License

http://www.opensource.org/licenses/mit-license.php

Copyright (c) 2011 Brian Cavalier