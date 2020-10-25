# Quickstart

### A web app to generate dynamic slides efficiently

* This app makes API calls to <code>__googleapis__</code>
* Generate your <code>__CLIENT_ID__</code> and <code>__API_KEY__</code> from <code>__https://developers.google.com/slides/__</code>
* Install the __Google Client Library__ using pip:
      <code>__pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib__</code>
* Run <code>__python quickstart.py__</code> in your __CLI__
* Download all the credentials from <code>__https://developers.google.com/slides/__</code> in a <code>__json__</code> file called <code>__credentials.json__</code>; and enable the <code>__CLIENT_ID__</code> cum <code>__API_KEY__</code> in <code>__index.html__</code>
* If you're familiar with the __Drive API__, the <code>__presentationId__</code> corresponds to the _ID_ of the __File__ resource
* Run the given __CLI__ and visit the provided link to authorize <code>__Quickstart__</code> to your __Google Slides__ account
* Once you're done with that, a file called <code>__token.pickle__</code> will be automatically created in the <code>__quickstart__</code> directory, meaning your authentication was successful. If not, visit <code>__https://developers.google.com/slides/__</code> and find the section with troubleshoot options


### Note that this is still a purely experimental version of the project and is not yet ready for any guaranteed usage
