
## Validation
- Regex pattern to validate US and Canada Zip Codes, Shared By Matthew

````
/^((\d{5}-\d{4})|(\d{5})|([AaBbCcEeGgHhJjKkLlMmNnPpRrSsTtVvXxYy]\d[A-Za-z]\s?\d[A-Za-z]\d))$/i
````

## Sanitization

- Remove Script tag
````
$message = preg_replace('/<script\b[^>]*>(.*?)<\/script>/is', '', $message);
````
