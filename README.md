# Computing for COVID

## Summary

* Help [COVID researchers](https://www.bakerlab.org/) find [a cure](https://www.ipd.uw.edu/coronavirus/) by running a computer in the cloud
* It's [easy to setup](#setup-instructions); costs start at $15/mo for the compute power at [DigitalOcean](https://m.do.co/c/5fb69d9c62e4)
* You'll be creating and starting a droplet using an [App on the DigitalOcean Marketplace](http://t7.io/cfc)
* There are [step-by-step instructions](#setup-instructions) to get the droplet running, the contents of which are open source and created with [Packer scripts](https://github.com/digitalocean/marketplace-partners)
* If you don't have a DigitalOcean account, sign up using [this link](https://m.do.co/c/5fb69d9c62e4) to get a $100 credit
* [Computing for COVID](http://t7.io/cfc) is sponsored by [TEN7](https://ten7.com/).

## Description

The [Computing for COVID DigitalOcean Marketplace App](http://t7.io/cfc) is a way for anyone (no tech skills required) to fire up a cloud computer that immediately starts crunching data to help scientists find proteins for the treatment of COVID-19. 

This allows you to support researchers at the University of Washington's [Baker Lab](https://www.bakerlab.org/) in their computational requirements as part of their [Coronavirus Response](https://www.ipd.uw.edu/coronavirus/).

Once you’ve installed the droplet, it starts up, attaches itself to the [Rosetta@Home](https://boinc.bakerlab.org/) project as part of the [Computing for COVID team](https://boinc.bakerlab.org/rosetta/team_display.php?teamid=20117), and immediately starts to download work to be done.

## Open source

The app uses [Packer scripts](https://github.com/digitalocean/marketplace-partners) from DigitalOcean as a starting point to configure an Ubuntu 18.04 droplet with `boinc` that automatically attaches itself to the Rosetta@home project.

It is all in [https://github.com/ten7/computing-for-covid](https://github.com/ten7/computing-for-covid)

## Built with love by TEN7
This [DigitalOcean Marketplace app](http://t7.io/cfc) was built by [TEN7](https://ten7.com/). We create and care for Drupal-powered websites. 

## Setup
It's relatively straight forward to setup a new DigitalOcean account and to get up and running with a droplet. It's probably even easier to setup the droplet if you already have an account, because that likely means you're already familiar with the interface. 

We'd recommend opening the [detailed setup instructions](https://computingforcovid.io/setup) in a separate browser tab as you go through the process.

## After deployment
The Computing for COVID droplet is self-sufficient; you can set it and forget it! However, if you’d like to see exactly what computations are being done in the droplet, use the command `boinctui` after you’ve connected to the droplet using SSH. See all the details on the droplet’s page in your DigitalOcean dashboard.


## Support details and issues
Have any questions? Send email to [help@computingforcovid.io](mailto:help@computingforcovid.io) and we'll do our best to help out. You can also [create an issue](https://github.com/ten7/computing-for-covid/issues/new) in the Github repo.
