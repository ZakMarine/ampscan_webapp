![ampscanlogo](https://github.com/abel-research/ampscan/blob/master/docs/ampscan_header.svg)

**Join AmpScan chat:** [![Join the chat at https://gitter.im/ampscan](https://badges.gitter.im/gitterHQ/gitter.svg)](https://gitter.im/ampscan)

This is the webapp interface for the open-source Python package for analysis and visualisation of digitised surface scan data, AmpScan. 

Running AmpScan Webapp
-------------------

Clone the repo using: `git clone https://github.com/abel-research/ampscan_webapp`

CD into directory using `cd ampscan_webapp`

(Optional) create new conda environment `conda create -n ampscan_environment python=3.6 pip --no-default-packages` and activate conda environment `conda activate ampsan_environment`

Install requirements with pip: `pip install -r requirements.txt`

Run development server using: `python manage.py runserver`

Now test it works by going to http://127.0.0.1:8000/ in your webbrowser.

Maintainer Notes
----------------

This app uses a Django framework.

vtk.js is used to render the scans for the clients.

As a future improvement, we may want to add a modules bundler such as webpack rather than importing vtk.js scripts from a URL.

Please see the Issues for new features and improvements in progress.
