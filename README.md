# A Jupyter notebook to show how to do text categorization with Azure Text Analysis and Wikipedia

Change the first three line of the notebook as your parameters

``` python
subscription_key = 'Azure Cognitive Service Text Analysis Subscription Key'
text_analytics_base_url = "https://eastasia.api.cognitive.microsoft.com/text/analytics/v2.1/"
csv_file_path = 'data.csv'

```
Change the rules dict for your business. it supports full entity or text matching, and condtional matching.

It will genertate a CSV file with category information.

