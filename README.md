# MJML Extension for FroshTemplateMail

## Requirements

* FroshTemplateMail installed
* MJML installed and available in PATH or with a web api

## Template location

Example Mail **sORDER**

* HTML Template
  * themes/Frontend/MyTheme/email/sORDER.html.mjml

## Disable Cache

Set backend cache to Blackhole to disable it. See guide https://en-community.shopware.com/_detail_1961.html#Debug_configuration

## Web API

If you cannot install mjml on the host, you can use the web api. Add the following configuration to your config.php

```php
    'mjml_api' => 'https://user:key@api.mjml.io/v1/render'
```

otherwise you can also host your own mjml server see [Repository](https://github.com/shyim/mjml-server)
