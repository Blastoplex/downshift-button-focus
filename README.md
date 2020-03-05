## downshift-button-focus

** NOTE: were still working on reproducing this code seems to actually work in IE

Associated to downshift issue: https://github.com/downshift-js/downshift/issues/966

Steps to reproduce bug: 
1. Clone this repo `git clone git@github.com:Blastoplex/downshift-button-focus.git`
1. `npm install && npm run start`
1. Open in Firefox, safari or chrome
1. Go to [localhost:3000](localhost:3000)
1. Click dropdown arrow
1. Interaction works as expected. 
1. Open in IE 11
1. Go to [localhost:3000](localhost:3000)
1. Click dropdown arrow
1. The menu does not open but the input does still focus
