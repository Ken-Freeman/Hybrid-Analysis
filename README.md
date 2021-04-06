This project is designed to take data from various public API's hosted on https://hybrid-analysis.com/ and created a model to predict whether or not files passing through network traffic are malicous or not.

Please reference the Final_API_Model.ipynb file to see the following work in action.

In order to get full data reports from https://hybrid-analysis.com/ you must first request a key from the site.

Once you have a full API key we will reach out to the "public feed" page. From here we will pull all of the data in a json format. We will be able to gather "id" and "SHA256" values that are representative of specific reports for a variety of files. 

After pulling the json information we will be able to pull those "id" and "SHA256" values and use them on a separate API from https://hybrid-analysis.com/ and pull full reports for specific activity.

Once we have matching reports we will be able to message the data so it is workable. Then we will test and train a predictive model to see how accuratly we can predict which files are malicious.
