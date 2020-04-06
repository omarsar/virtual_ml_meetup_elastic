## Machine Learning in the Elastic Stack

Below is the list of commands I used to setup up the ML jobs. For the commands to work, you need to make sure you have loaded the corresponsing sample datasets in Kibana. 

**Note:** Please note that I made a mistake on the classification part of the demo. The fields included in the `excludes` portion of the request are actually ignored from the analysis. Essentially, we use all other features except those ones. You can read more about this example in our documentation: https://www.elastic.co/guide/en/machine-learning/7.x/flightdata-classification.html, I directly used it to show you the classification example.

https://gist.github.com/omarsar/d3bc4dcb9ebb283f44af7613a2b3fa27
