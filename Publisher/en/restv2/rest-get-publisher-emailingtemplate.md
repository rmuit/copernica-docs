# REST API: GET emailing template (Publisher)

You can use the REST API to retrieve a summary of an emailing template 
with an HTTP GET call to the following URL:

`https://api.copernica.com/v2/publisher/emailingtemplate/$id?access_token=xxxx`

Where `$id` should be replaced with the ID of the emailing template you want summarized.

## Returned fields

The method returns a JSON object containing the following information:

* **id**: The ID of the template.    
* **name**: The name of the template.
* **archived**: The archive status of the template.

## PHP example

The script below demonstrates how to use this API method. Don't forget 
to replace the ID in the URL before executing the call.

```php
// dependencies
require_once('copernica_rest_api.php');

// change this into your access token
$api = new CopernicaRestAPI("your-access-token", 2);

// execute the call
print_r($api->get("publisher/emailingtemplate/{$emailingTemplateID}"));
```

This example requires the [REST API class](./rest-php)

## More information

* [Overview of all REST API calls](./rest-api)
* [Retrieve a Publisher emailing document](./rest-get-publisher-emailingsdocument)
* [Retrieve all Publisher emailing templates](./rest-get-publisher-emailingtemplates)