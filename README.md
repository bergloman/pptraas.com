Puppeteer as a service
======================

This service is used to create screenshots - e.g. to support older browsers.

## Render

### Render page as a PNG
https://my-server:my-port/screenshot?url=https://paul.kinlan.me/ (full page)

https://my-server:my-port/screenshot?url=https://developers.google.com&size=400,400

https://my-server:my-port/screenshot?url=https://www.wikipedia.org&element=.central-featured



## Other features

### Render page as a PDF
https://my-server:my-port/pdf?url=https://paul.kinlan.me/

### Render generated static markup of page ("SSR")
https://my-server:my-port/ssr?url=https://angular2-hn.firebaseapp.com/

## Performance

### Get a timeline trace

https://my-server:my-port/trace?url=https://paul.kinlan.me/

#### View the trace in trace-viewer:

https://chromedevtools.github.io/timeline-viewer/?loadTimelineFromURL="https://my-server:my-port/trace?url=https://paul.kinlan.me/

### Get metrics
https://my-server:my-port/metrics?url=https://paul.kinlan.me/

## Misc

### Print UserAgent / Chromium version
https://my-server:my-port/version

