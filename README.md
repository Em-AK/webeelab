# weBeelab

> Website for OpenBeeLab.org

## How to contribute

This website is built locally with [Lektor](https://www.getlektor.com/),
a static CMS written in python.

### Write content

> TODO - write a tutorial for writers
> * Install Lektor on your machine
> * Add / Edit content
> * Commit your changes
> * Submit a pull request

### Deploy to production server

1. Replace `USER` with your ssh username in `openbeelab.lektorproject`
  > You should be authorized to `ssh USER@web.openbeelab.org`
2. Build the site locally and deploy it via rsync: `lektor build && lektor deploy`

### Improve the structure

> This is a work in progress by [em-ak](https://github.com/Em-AK)

#### Quick start

1. [Install Lektor](https://www.getlektor.com/downloads/) on your machine
2. Clone this repo
3. Run `lektor server` at the root of the repo
4. Visit <http://localhost:5000>

Then you should consult [Lektor documentation](https://www.getlektor.com/docs/).
