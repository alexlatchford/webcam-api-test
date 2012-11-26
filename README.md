# WebCam Test

Essentially it's a little test project to see what could be done using the new device access and localStorage API's found in newer browser builds. It's works but clearly there are cross-browser and cohension issues. But if you're looking for some working example code then you've found it.

Apologies for the Zepto.js dependency, I tried using straight Javascript and couldn't be bothered with it in the end! Perhaps I should have used scripted templating but it's good enough for now.

## Known Issues

* Doesn't work when run locally on Chrome, (actually only works for my tests on Opera). I used tiny web server to run a serve the HTML off localhost for my development needs.
* Chrome (and I presume other browser vendors) only allow 5mb of local storage for each webpage. I understand this makes sense but this does throttle how useful a picture gallery app can be when it can only store 3  full res pictures!