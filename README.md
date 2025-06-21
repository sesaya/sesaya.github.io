# Welcome to My Personal Website
![Abdul Sesay](images/asPortrait.png "My Personal Website")
# Abdul Sesay, Ph.D.
**Assistant Professor,**
Management Information Systems, Terry College of Business,
University of Georgia

# Education
1. PhD, Computer Science and Information Systems, University of Colorado Denver, 2018
1. MS, Information Systems, University of Colorado Denver, 2001
1. Master of Community Planning, University of Cincinnati, 1997
1. Master of Architecture, Tsinghua University, 1995
1. Bachelor of Architecture, Tsinghua University, 1993

# Bio

Dr. Sesay is an assistant professor in the Management Information Systems Department at the Terry College of Business, University of Georgia. He obtained his Bachelors and Masters of Architecture from Tsinghua University, Beijing, China, Master of Community Planning (MCP) from the University of Cincinnati, and a Master of Science (MS) and Ph.D. in Computer Science and Information Systems from the University of Colorado Denver. His research interests are in Human-Machine Symbiosis, Information Technology Governance, Digital Transformation, Technology Affordance-Based Control, and IT for Development (IT4D). His research has been published or forthcoming in MIS Quarterly, Journal of Management Information Systems, Policing and Society, and various conference proceedings.

Prior to joining academia, Dr. Sesay was an International Business Development Representative for the City of Denver, Office of Economic Development, where he developed and managed programs to promote exports, attract foreign investment, increase connectivity, and make Denver a more internationally competitive and welcoming city. He hosted trade and investment delegations from China, Dubai, Germany, U.K., Japan, and Mexico, as well as civic groups from Kenya, Zambia, China, Mongolia, Oman, Malaysia, and young African leaders from the Mandela Washington Fellowship.

Dr. Sesay provided staffing and protocol assistance to the mayor’s office and was the staff liaison for the Mayor’s International Advisory Council. Prior to that, Dr. Sesay was a housing and urban development consultant, providing market advice and feasibility studies to developers, tax credit investors, and syndicators of affordable housing and community development projects throughout the United States.  He served as a member of the Board of Directors for Denver Sister Cities International, Denver Coalition for Integration, and the Denver World Trade Center. In 2012 and 2016, he was designated by the U.S. Secretary of Commerce as a member of the Rocky Mountain District Export Council.

Dr. Sesay is fluent in Mandarin and French.

See more info at https://academicpages.github.io/

## Research Areas

1. Human-Machine Symbiosis
2. Organization Theory and Research Methods
3. IT Governance and Sourcing
4. Technology Affordance-based Organization Control
5. Digital Transformation in Organizations & Digital Government
6. Information Technology for Development (IT4D)
7. Data Modeling and Business Analytics

### Using a different IDE
1. Make sure you have ruby-dev, bundler, and nodejs installed
    
    On most Linux distribution and [Windows Subsystem Linux](https://learn.microsoft.com/en-us/windows/wsl/about) the command is:
    ```bash
    sudo apt install ruby-dev ruby-bundler nodejs
    ```
    If you see error `Unable to locate package ruby-bundler`, `Unable to locate package nodejs `, run the following:
    ```bash
    sudo apt update && sudo apt upgrade -y
    ```
    then try run `sudo apt install ruby-dev ruby-bundler nodejs` again.

    On MacOS the commands are:
    ```bash
    brew install ruby
    brew install node
    gem install bundler
    ```
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.

    If you see file permission error like `Fetching bundler-2.6.3.gem ERROR:  While executing gem (Gem::FilePermissionError) You don't have write permissions for the /var/lib/gems/3.2.0 directory.` or `Bundler::PermissionError: There was an error while trying to write to /usr/local/bin.`
    Install Gems Locally (Recommended):
    ```bash
    bundle config set --local path 'vendor/bundle'
    ```
    then try run `bundle install` again. If succeeded, you should see a folder called `vendor` and `.bundle`.

1. Run `jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
    You may also try `bundle exec jekyll serve -l -H localhost` to ensure jekyll to use specific dependencies on your own local machine.

If you are running on Linux it may be necessary to install some additional dependencies prior to being able to run locally: `sudo apt install build-essential gcc make`

## Using Docker

Working from a different OS, or just want to avoid installing dependencies? You can use the provided `Dockerfile` to build a container that will run the site for you if you have [Docker](https://www.docker.com/) installed.

You can build and execute the container by running the following command in the repository:

```bash
chmod -R 777 .
docker compose up
```

You should now be able to access the website from `localhost:4000`.

### Using the DevContainer in VS Code

If you are using [Visual Studio Code](https://code.visualstudio.com/) you can use the [Dev Container](https://code.visualstudio.com/docs/devcontainers/containers) that comes with this Repository. Normally VS Code detects that a development coontainer configuration is available and asks you if you want to use the container. If this doesn't happen you can manually start the container by **F1->DevContainer: Reopen in Container**. This restarts your VS Code in the container and automatically hosts your academic page locally on http://localhost:4000. All changes will be updated live to that page after a few seconds.

# Maintenance

Bug reports and feature requests to the template should be [submitted via GitHub](https://github.com/academicpages/academicpages.github.io/issues/new/choose). For questions concerning how to style the template, please feel free to start a [new discussion on GitHub](https://github.com/academicpages/academicpages.github.io/discussions).

This repository was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License (see LICENSE.md). It is currently being maintained by [Robert Zupko](https://github.com/rjzupkoii) and additional maintainers would be welcomed.

## Bugfixes and enhancements

If you have bugfixes and enhancements that you would like to submit as a pull request, you will need to [fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) this repository as opposed to using it as a template. This will also allow you to [synchronize your copy](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) of template to your fork as well.

Unfortunately, one logistical issue with a template theme like Academic Pages that makes it a little tricky to get bug fixes and updates to the core theme. If you use this template and customize it, you will probably get merge conflicts if you attempt to synchronize. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch.

---
<div align="center">
    
![pages-build-deployment](https://github.com/academicpages/academicpages.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)
[![GitHub contributors](https://img.shields.io/github/contributors/academicpages/academicpages.github.io.svg)](https://github.com/academicpages/academicpages.github.io/graphs/contributors)
[![GitHub release](https://img.shields.io/github/v/release/academicpages/academicpages.github.io)](https://github.com/academicpages/academicpages.github.io/releases/latest)
[![GitHub license](https://img.shields.io/github/license/academicpages/academicpages.github.io?color=blue)](https://github.com/academicpages/academicpages.github.io/blob/master/LICENSE)

[![GitHub stars](https://img.shields.io/github/stars/academicpages/academicpages.github.io)](https://github.com/academicpages/academicpages.github.io)
[![GitHub forks](https://img.shields.io/github/forks/academicpages/academicpages.github.io)](https://github.com/academicpages/academicpages.github.io/fork)
</div>
