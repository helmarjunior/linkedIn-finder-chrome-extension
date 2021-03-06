
<h1  align="center">Linkedin Finder</h1>
<p  align="center">Powerful Chrome Extension that creates LinkedIn Profile Search Shortcut for Facebook and MeetUp users.</p>

  
## Overview 

From Facebook and MeetUp interface, we present a one-click function to easily find users, from a segment, on LinkedIn. Now, you can easily connect with people with the same interest, members from the same groups or even nearby you.

![interface facebook](screenshots/facebook.png)
![interface meetup](screenshots/meetup.png)
 

## Installation

- On Chrome, install via [Chrome web store](https://chrome.google.com/webstore/detail/linkedin-finder/paoenkdapheefbfbkjhfeodpjfmfeehg)
  
 

## Development version

  

Steps to build the extension and view your changes in a browser:

  

```sh

git clone https://github.com/helmarjunior/linkedIn-finder-chrome-extension

npm install

```

For development with automatic reloading:

  

```sh

npm run start

```

  

Open the [Extensions Dashboard](chrome://extensions), make sure "Developer mode" is switched on, click "Load unpacked", and choose the `dist` folder.


### Production

  
You'll want to make a production build when it's time to publish your Chrome

Extension. Run the following line:

  

```sh

npm run build

```


This will create a ZIP file with your package name and version in the `releases` folder.


## Source Layout


Your manifest is at `src/manifest.json`, and Rollup will bundle any files you include here. All the filepaths in your manifest should point to files in `src`.