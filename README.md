*This .ipynb script can be dowloaded an can be ran in google colab or jupyter notebook*

These Script can do the following things:

  - Search the top 10 question releated to query(or relevent query) using an api sorted by relevence in descending order and the output will a csv file(query.csv) that can be imported to any bi tool
  - Search the top 10 latest article using an api sorted by creation time and the output will a csv file(article.csv) that can be imported to any bi tool
  - Search the trends over the years(graph) using tags

Technical info:
  - To generate the access token for the higher throttle limits, app has been registered https://stackapps.com/apps/oauth/view/26679
  - To generate the access token with the expiry time use the following [link](https://stackexchange.com/oauth/dialog?client_id=26679&scope=no_expiry&redirect_uri=https://stackexchange.com/oauth/login_success/)
  - access_token: 9pgXX622kpu5kZjqCdAagA))
  - Following libraries are needed to run the script:
    - requests
    - json
    - pandas
