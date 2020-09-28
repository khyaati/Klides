# Kslides

### A web app to generate dynamic slides efficiently by the means of a browser

* This app makes API calls to <code>__googleapis__</code>
* Generate your <code>__CLIENT_ID__</code> and <code>__API_KEY__</code> from <code>__https://developers.google.com/slides/__</code>
* Install the __Google Client Library__ using pip:
      <code>__pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib__</code>
* Run <code>__python -m http.server 8000__</code> for __python 2x__ and <code>__python -m SimpleHTTPServer 8000__</code> for __python 3x__ in your CLI(if using the HTML script)
* Run <code>__python quickstart.py__</code> in your CLI(if using python script as base code)
* Download all the credentials from <code>__https://developers.google.com/slides/__</code> in a <code>__json__</code> file; and enable the <code>__CLIENT_ID__</code> cum <code>__API_KEY__</code> in <code>__index.html__</code>
* Run the given CLI in your terminal and visit the provided link to authorize <code>__Quickstart__</code> to your __Google Slides__ account
* Once you're done with that, a file called <code>__token.pickle__</code> will be automatically created in the <code>__quickstart directory__</code> meaning you're authentication was successful. If not, visit <code>__https://developers.google.com/slides/__</code> and find the section with troubleshoot options and you're done... ### GOOD LUCK !!!!! 


* Note that it is still a purely experimental version of the project and is not yet ready for any guaranteed usage
