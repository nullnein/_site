---
date: 2022-02-05
author: mathis
tags: jekyll github render
category: TechnicalStuff

title: Configuration this site
abstract: 
---

## Workflow

- Open Typora
	+ New Doc: `:new`
	+ Write
	+ Add title, tags, categories in frontmatter
	+ tags are *OneWord*
- Open Terminal
	+ `cd /Users/mathis/mrichtm/oija/nullnein\ on\ github/nullnein.github.io`
	+ `bundle exec jekyll build`
- Open Github Desktop
	+ Commit
	+ Push
- Render.com should then auto-deploy
	+ You can manually deploy


## Setup

- [x][installing ruby](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/?utm_source=stackoverflow&utm_campaign=51126403)
- [x][installing jekyll](https://jekyllrb.com/docs/installation/macos/)
	- continue at "Get your Ruby version:"
- [ ][installing chirby on github pages](https://chirpy.cotes.page/posts/getting-started/#option-1-using-the-chirpy-starter)
- [setup guide](https://dfederm.com/creating-a-blog-using-github-pages/)
- setup at nullnein.onrender.com, run:
	+ jekyll `bundle exec jekyll build`
	+ push to [github](https://github.com/nullnein/public-site) *not automated yet*
	+ I think render will automatically redeploy
	
## Figure out

- how to host images
- internal links