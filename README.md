# Wikidata-Discussions-Stats

This provides a python code to analyse raw data extracted from the Wikidata XML dumps.

Wikidata stores all the history of revisions in its pages to XML files. You can process the files and extarct information of the discussion pages (talk pages, and general discussion) using this [library](https://github.com/King-s-Knowledge-Graph-Lab/Wikidata-Discussion-Parser).

Raw_data_analysis.ipynb separate the discussion threads and the posts in the threads.
Post_info.ipynb extracts information like username and timestamp from the posts. It also queries Wikidata to extract information regarding the number of edits and the date of registration for the usernames.


