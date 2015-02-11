
# Deploy Angular - Single Page Applications + **Basic SEO & Deep Linking Enabled

This **Cloud Foundry Buildpack** was modified from the [original](https://github.com/cloudfoundry-incubator/staticfile-buildpack) to enable googlebot crawling and [deep linking](http://en.wikipedia.org/wiki/Deep_linking "").  Allowing pages to be indexed using the google [web master tools](https://www.google.com/webmasters/).

### Deployment
After compiling the Angular - single page application take the "generated" or "distribution" folder and run the command below in the terminal.


```
cf push my-site -m 64M -b https://github.com/cloudgate313/staticfile-buildpack.git
```

See original buildpack for a more indepth explaination [here](https://github.com/cloudfoundry-incubator/staticfile-buildpack).
### Acknowledgements (resources)
[Alexey Kutuzov's](http://senior-java-developer.com/html5angularjsnginx-crawlable-application/) nginx.conf configurations and nginx use cases.

[Jesse Lawson's](http://lawsonry.com/2014/05/diy-angularjs-seo-with-phantomjs-the-easy-way/) overview on seo for single page applications.


### **Basic:
This is not a complete optimized solution for seo. Cached snapshots passed to bots and auto indexing is the next step.  Currently developing a solution that can be easily deployed to [Cloud Foundry](http://www.cloudfoundry.org/index.html).  Suggestions are encouraged.

**Read me** created with Mou [mark down][id] editor for mac.  

[id]: http://25.io/mou/ "Markdown editor on Mac OS X"

