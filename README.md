# SSAGES and COPPS Website

To work on the website, work only out of the `project` directory.  Files at the top level will be autogenerated later.

When ready to deploy, either locally or on the GitHub pages, take the following steps:

1. Install the website requirements: `pip install -r requirements.txt`
2. Execute `python freeze.py`.  This will generate a static version of the website.

To run locally:

1. Execute `python run.py`.  
2. Point your browser of choice to localhost:5000.  Success!

To deploy on GitHub Pages:

1. Commit your changes to the `gh-pages` branch.  
2. Navigate to https://whitmergroup.github.io/SSAGES-site/.  Success!
