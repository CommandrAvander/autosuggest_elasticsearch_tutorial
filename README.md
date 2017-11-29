# autosuggest_elasticsearch_tutorial
This Repo includes the [sample doc](blog_06_autoSuggest_dataSet.js) to follow along with the tutorial: How to Build an Autocomplete Feature with Elasticsearch.

# autoSuggestDataLoader

This is a data indexing program for demonstrating the autoSuggest API in elasticsearch. [Find it here](https://github.com/CommandrAvander/autosuggest_elasticsearch_tutorial/blob/master/autoSuggestDataLoader-master.zip).

### General Points

1. The sample data with 1000 documents can be found in the file `mock_data.js`. 
2. The code for indexing the documents is in the file `runningHere.js`.
3. The configuration details are in the `configs.js` file. Here, we have details such as the elasticsearch host and port number configuration. By default, it is `localhost:9233` in this file. Please make sure to change it.

### Usage

1. First run the npm install to install the package.json contents.
2. Now run node runningHere.js to run the program to index the sample data
