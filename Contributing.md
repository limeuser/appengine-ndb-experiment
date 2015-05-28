Every change to NDB code goes through review process, even from committers. The information below should help to get your patch accepted faster.

### Check out the source code ###
See [Source](http://code.google.com/p/appengine-ndb-experiment/source/checkout) tab above for instructions.

### Prepare a patch ###
Split it into munchable chunks if you can. 5 simple patches will be more likely accepted much-much faster than a big complex one. This requires some kind of patch queue management effort on your side, but let's hope some day we will list some easy to use tools here.

### Submit patch ###
To submit, upload it to codereview.appspot.com using the
[upload.py](http://codereview.appspot.com/static/upload.py) script and add Patrick (pcostello@google.com) to the list of the reviewers, for example

```
upload.py -r pcostello@google.com --cc=appengine-ndb-discuss@googlegroups.com --send_mail  
```

Make sure you're **subscribed** to [appenine-ndb-discuss](https://groups.google.com/forum/#forum/appengine-ndb-discuss) or else notification to group may bounce. If you're uploading a patch using the web based form, don't forget to use the Publish+Mail link on the issue page.

### Legal stuff ###

We're living in interesting times. That's why individual contributors need to fill out the
[Individual Contributor License Agreement](http://code.google.com/legal/individual-cla-v1.0.html).  (Please use the electronic form at the bottom of that page.)
It does **not** transfer copyright; it is actually a slightly modified
version of the CLA for the Apache Software Foundation.

For Corporate contributors, there's the
[Software Grant and Corporate Contributor License Agreement](http://code.google.com/legal/corporate-cla-v1.0.html).

Google employees do **not** have to fill out one of these!

### Feedback ###

If you feel that the process can be improved - do not hesitate to suggest your changes for review. Thanks.