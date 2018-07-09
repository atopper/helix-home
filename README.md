# Project Helix

![](./Helix%20Save%20the%20Date.jpg)

There's another [Hackathon](hackathon.md) coming.

## Background

Read all of this.

* [How we work, who we are, what we use, what we build](manifesto.md)
* [Product Vision](product-vision.md)
* [Business Whitepaper Pitch](whitepaper.md)
* [Top 10](top10.md)
* [Technology Architecture Vision](architecture.md)

## Developing Helix

* [What Services we use – get access to those to code for Helix](SERVICES.md)
* [Contributing to the Primordial Soup Prototype](prototypes/CONTRIBUTING.md)
* *New:* [What the new Pipeline looks like](prototypes/PIPELINE_FAQ.md)
* *New:* [All Helix Repositories](https://github.com/search?q=topic%3Ahelix+org%3Aadobe&type=Repositories)
* *New:* [Helix Project Board](https://github.com/orgs/adobe/projects/2)
* The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in Helix document are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).
* Javacript code style should follow the [Airbnb JavaScript Style Guide()](https://github.com/airbnb/javascript)

## Video Walkthoughs

To catch a glimpse of Helix, check out these video walkthoughs:

* [June 8th 2018: Re-Cap of the first Helix Hackathon in Salt Lake City](https://vimeo.com/274350388/afe38b8c33)
* [May 28th 2018: @trieloff describes the Primordial Soup Prototype](https://my.adobeconnect.com/pe0gjswvlm7n/)

## Hackathons

The Helix team is inviting everyone interested to join us for quarterly hackathons. You can find the archives here:

* [Hackathon #1 – June 2018 in Salt Lake City](hackathons/1-slc.md)

## Communication

We hang out in the [`#helix-chat`](https://adobe.slack.com/messages/C9KD0TT6G/) Slack channel (Enterprise Grid) and notifications go to [`#helix-noisy`](https://adobe.slack.com/messages/C9HH8J553/)

## Development - Check out all modules

### Related Repositories

This umbrella project contains a [gitslave](http://gitslave.sourceforge.net) config that can be used to check out all relevant modules that are hosted as individual repositories:

- https://github.com/adobe/helix-cli
- https://github.com/adobe/petridish
- https://github.com/adobe/hypermedia-pipeline
- https://github.com/adobe/git-server
- https://github.com/adobe/helix-helpx
- https://github.com/adobe/parcel-plugin-htl
- https://github.com/adobe/parcel-plugin-jst
- https://github.com/adobe/openwhisk-loggly-wrapper
- https://github.com/adobe/htlengine

### Setup

This requires [gitslave](http://gitslave.sourceforge.net).

#### Mac

    $ brew install gitslave

### Working with gitslave

When checking out for the first time, do this:

    $ git clone git@github.com:adobe/project-helix.git
    $ cd project-helix
    $ gits populate

To update later, do this (inside the `project-helix` dir):

    $ git pull && gits pull


If the `.gitslave` config has changed, just re-populate and pull again:

    $ gits populate && gits pull
