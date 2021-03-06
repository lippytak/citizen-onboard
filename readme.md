# Citizen Onboard
Citizen onboard is a collaborative project to describe how our own government services work (and don't work). It's hosted publically on Github pages: http://lippytak.github.io/citizen-onboard/ and inspired by the endlessly awesome [@UserOnboard](http://www.twitter.com/useronboard).

This is a baby project so it needs your love to grow. There's a few ways you can bring help bring it to life:

1. Next time you're dealing with your government, [tweet about it with the tag #citizenonboard](https://twitter.com/search?q=%23citizenonboard&src=hash&f=realtime). Highlight the delights and the paint points. Hopefully we can build a little living library of our own experiences with government.
2. If you have an idea for a new service to look at, [open an issue](https://github.com/lippytak/citizen-onboard/issues/new) and add what you know about it.
3. If you're feeling a bit more ambitious, take a look at the [existing issues](https://github.com/lippytak/citizen-onboard/issues) and do some preliminary. Write about your own experience. Take some screenshots. Scan some forms. Include anything that helps describe your experience with the service and include it in a comment.
4. If you still want more, then you're awesome. You should contribute your own CitizenOnboard slideshow. Take a look at the [contribute](#contribute) section below to get started. If you do one, I'll send you a present. I'm not joking. Present TBD.

Questions? Get in touch [@lippytak](http://twitter.com/lippytak)

# Contribute
1. [Install Node and NPM](https://gist.github.com/isaacs/579814#file-node-and-npm-in-30-seconds-sh)
2. Install [Cleaver](https://github.com/jdan/cleaver/): `npm install -g cleaver` (Cleaver generates nice little slideshows from markdown)
3. [Fork this repo](fork) and create a new branch for your service
4. Rename the `sample` directory and `sample.md` file to the name of your service
5. Now for the fun part: Go take a bunch of screenshots/pictures/recordings/videos/flowcharts/whatever else you can imagine to document the process of using/enrolling in the service. Aim for exhaustion over perfection. Be creative and make it fun. Use whatever tools are at your disposal. So far I've had a good experience with:
    - [Awesome screenshot](https://chrome.google.com/webstore/detail/awesome-screenshot-captur/alelhddbbhepgpmgidjdcjakblofbmce?hl=en) for full page screenshots,
    - and [Skitch](http://evernote.com/skitch/) for annotations.
6. Edit the markdown (`.md`) slideshow. Just add an intro slide, lots of image slides, and a stats/author slide at the end. It should be pretty self-explanatory but feel free to [reach out](http://www.twitter.com/lippytak) with questions.
7. Run `cleaver servicename.md` to generate the slideshow as `index.html` in the same directory.
8. Add a link to your new service in the root `index.md` and run `cleaver index.md` to update the index page.
9. And you're done! Open `servicename/index.html` in any browser. Once everything looks right, send a pull request!