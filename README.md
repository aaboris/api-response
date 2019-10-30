# Api Response

## Install

To install through Composer, by run the following command:

``` bash
composer require borisnedovis/api-response
```

And add provider in app.php:

``` bash
BorisNedovis\ApiResponse\Providers\ApiResponseServiceProvider::class
```

Use:

- Required parameter $data

``` bash
return response()->api($this->data, $this->errors, $this->statusCode);
```


