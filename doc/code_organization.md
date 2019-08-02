# Code organization

## server-example
Example of REST server api.
It contains only one endpoint that manipulate json.

## client-example
Example of code using rest api.
It call the server every 2 seconds with a list of name.
And print on stdout the result.

## server
This is the logging server,
it can be used or not as a proxy of the server-example.


### Data stored in elasticsearch :

```
timestamp : date at which the event happend
api_name : name of the api (or host of the api)
query_action : {'method': Post, url: ''}
api_type : REST
information_sent : 
origin : 
labels: 
        'query_action': str(query_action),
        'api_type': str(api_type.name),
        'information_sent': str(information_sent),
        'origin': str(origin),
        'labels': str(labels),
```
