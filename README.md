# Enable private PHP SDK
## Add AHOI Repository
To enable private PHP SDK please add our private composer service to your `composer.json`
```php
"repositories": [
    {
        "type": "composer",
        "url": "https://satis.ahoi.cloud"
    }
],
```

## Add the package 

```bash
composer require ahoicloud/packagename
```
## Add the license key
Add the information provided by the AHOI-Team to authenticate against our licensing server. Use your email adress and the license key as a password.
<img width="623" alt="Bildschirmfoto 2024-05-12 um 21 26 38" src="https://github.com/ahoicloud/private-sdk/assets/1068416/8a78bb25-c59b-4781-b5d0-2738f2d7ecdf">
