# Download and install the .zip packageedit
Download the .zip archive for Elasticsearch 8.9.1: https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-8.9.1-windows-x86_64.
zip

# Commands

- To start elastic search 
``` .\bin\elasticsearch.bat ```

- Make changes in the config folder of elastic search of files
[elasticsearch.yml](Elastic-search\config\elasticsearch.yml)
[roles.yml](Elastic-search\config\roles.yml)

- Command to add users
```C:\sharath\elastic-search\elasticsearch-8.9.1-windows-x86_64\elasticsearch-8.9.1>.\bin\elasticsearch-users useradd sharath -p 123456 -r network,monitoring```

