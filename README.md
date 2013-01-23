# Octosplit

**Octosplit** is an lightweight Chrome extension that provides side by side diffs in GitHub.
## How to install for dev

* Fork / Clone the project
* Open Tools > Extensions menu in Chrome
* Enable _developer mode_
* Click on _load the unpacked extension_
* Select the path to your local copy of **Octosplit**

## Hacking
After installed you can easily edit Octosplit with any improvements you can think of.

To reload your changes:
* Open Tools > Extensions menu in Chrome
* Click Reload, any tabs using Octosplit should automatically reload. 


## What is changed

* Original file is in the left pane with deletions,
* New file is in the right pane with additions,
* The global size of working area is increased (relative to window size).
* Default view is vertical diffs, there's a checkbox for traditional horizontal diffs.

## Quirks / Warning
* The ~50/50 view on diffs has some issues. To keep the width there's a per-line horizontal scroll. 
  This is mostly a side-effect of the structure of the page, in the future I'll try to improve this.


## Warning

This [POC](http://en.wikipedia.org/wiki/Proof_of_concept) is currently in the very earliest stages of development.
