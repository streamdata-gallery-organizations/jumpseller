---
name: Jumpseller
x-slug: jumpseller
description: We founded Jumpseller.com in 2009 in Europe  we called it Vendder back
  then  and released our first version of the Jumpseller product in September 2010.
  After releasing the product we quickly grew to thousands of customers. In November
  2010, we recei...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
x-kinRank: "7"
x-alexaRank: "153745"
tags: Jumpseller
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/apis.md
specificationVersion: "0.14"
apis:
- name: Jumpseller Get Apps
  x-api-slug: jumpseller
  description: Retrieve all jumpseller apps..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//apps.json
  tags: Apps,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/apps-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/apps-json-get-openapi.md
- name: Jumpseller Get Categories
  x-api-slug: jumpseller
  description: Retrieve all categories..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//categories.json
  tags: Categories,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/categories-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/categories-json-get-openapi.md
- name: Jumpseller Post Categories
  x-api-slug: jumpseller
  description: Create a new category..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//categories.json
  tags: Categories,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/categories-json-post-openapi.md
- name: Jumpseller Delete Categories
  x-api-slug: jumpseller
  description: Delete an existing category..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//categories/{id}.json
  tags: Categories,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/categoriesid-json-delete-openapi.md
- name: Jumpseller Get Categories
  x-api-slug: jumpseller
  description: Retrieve a single category..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//categories/{id}.json
  tags: Categories,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/categoriesid-json-get-openapi.md
- name: Jumpseller Put Categories
  x-api-slug: jumpseller
  description: Modify an existing category..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//categories/{id}.json
  tags: Categories,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/categoriesid-json-put-openapi.md
- name: Jumpseller Get Checkout Custom Fields
  x-api-slug: jumpseller
  description: Retrieve all checkout custom fields..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//checkout_custom_fields.json
  tags: Checkout,Custom,Fields,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/checkout-custom-fields-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/checkout-custom-fields-json-get-openapi.md
- name: Jumpseller Post Checkout Custom Fields
  x-api-slug: jumpseller
  description: Create a new checkoutcustomfield..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//checkout_custom_fields.json
  tags: Checkout,Custom,Fields,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/checkout-custom-fields-json-post-openapi.md
- name: Jumpseller Delete Checkout Custom Fields
  x-api-slug: jumpseller
  description: Delete an existing checkoutcustomfield..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//checkout_custom_fields/{id}.json
  tags: Checkout,Custom,Fields,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/checkout-custom-fieldsid-json-delete-openapi.md
- name: Jumpseller Get Checkout Custom Fields
  x-api-slug: jumpseller
  description: Retrieve a single checkoutcustomfield..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//checkout_custom_fields/{id}.json
  tags: Checkout,Custom,Fields,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/checkout-custom-fieldsid-json-get-openapi.md
- name: Jumpseller Put Checkout Custom Fields
  x-api-slug: jumpseller
  description: Update a checkoutcustomfield..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//checkout_custom_fields/{id}.json
  tags: Checkout,Custom,Fields,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/checkout-custom-fieldsid-json-put-openapi.md
- name: Jumpseller Get Countries
  x-api-slug: jumpseller
  description: Retrieve all countries..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//countries.json
  tags: Countries,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/countries-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/countries-json-get-openapi.md
- name: Jumpseller Get Countries Country Code
  x-api-slug: jumpseller
  description: Retrieve a single country information..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//countries/{country_code}.json
  tags: Countries,Country,Code,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/countriescountry-code-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/countriescountry-code-json-get-openapi.md
- name: Jumpseller Get Countries Country Code Regions
  x-api-slug: jumpseller
  description: Retrieve all regions from a single country..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//countries/{country_code}/regions.json
  tags: Countries,Country,Code,Regions,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/countriescountry-coderegions-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/countriescountry-coderegions-json-get-openapi.md
- name: Jumpseller Get Countries Country Code Regions Region Code
  x-api-slug: jumpseller
  description: Retrieve a single region information object..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//countries/{country_code}/regions/{region_code}.json
  tags: Countries,Country,Code,Regions,Region,Code,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/countriescountry-coderegionsregion-code-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/countriescountry-coderegionsregion-code-json-get-openapi.md
- name: Jumpseller Get Customer Categories
  x-api-slug: jumpseller
  description: Retrieve all customer categories..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customer_categories.json
  tags: Customer,Categories,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customer-categories-json-get-openapi.md
- name: Jumpseller Post Customer Categories
  x-api-slug: jumpseller
  description: Create a new customercategory..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customer_categories.json
  tags: Customer,Categories,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customer-categories-json-post-openapi.md
- name: Jumpseller Delete Customer Categories
  x-api-slug: jumpseller
  description: Delete an existing customercategory..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customer_categories/{id}.json
  tags: Customer,Categories,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customer-categoriesid-json-delete-openapi.md
- name: Jumpseller Get Customer Categories
  x-api-slug: jumpseller
  description: Retrieve a single customercategory..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customer_categories/{id}.json
  tags: Customer,Categories,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customer-categoriesid-json-get-openapi.md
- name: Jumpseller Put Customer Categories
  x-api-slug: jumpseller
  description: Update a customercategory..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customer_categories/{id}.json
  tags: Customer,Categories,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customer-categoriesid-json-put-openapi.md
- name: Jumpseller Delete Customer Categories Customers
  x-api-slug: jumpseller
  description: Delete customers from an existing customercategory..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customer_categories/{id}/customers.json
  tags: Customer,Categories,Id,Customers,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customer-categoriesidcustomers-json-delete-openapi.md
- name: Jumpseller Get Customer Categories Customers
  x-api-slug: jumpseller
  description: Retrieves the customers in a customercategory..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customer_categories/{id}/customers.json
  tags: Customer,Categories,Id,Customers,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customer-categoriesidcustomers-json-get-openapi.md
- name: Jumpseller Post Customer Categories Customers
  x-api-slug: jumpseller
  description: Adds customers to a customercategory..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customer_categories/{id}/customers.json
  tags: Customer,Categories,Id,Customers,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customer-categoriesidcustomers-json-post-openapi.md
- name: Jumpseller Get Customers
  x-api-slug: jumpseller
  description: Retrieve all customers..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customers.json
  tags: Customers,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customers-json-get-openapi.md
- name: Jumpseller Post Customers
  x-api-slug: jumpseller
  description: Create a new customer..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customers.json
  tags: Customers,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customers-json-post-openapi.md
- name: Jumpseller Get Customers Email Email
  x-api-slug: jumpseller
  description: Retrieve a single customer..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customers/email/{email}.json
  tags: Customers,Email,Email,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customersemailemail-json-get-openapi.md
- name: Jumpseller Delete Customers
  x-api-slug: jumpseller
  description: Delete an existing category..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customers/{id}.json
  tags: Customers,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customersid-json-delete-openapi.md
- name: Jumpseller Get Customers
  x-api-slug: jumpseller
  description: Retrieve a single customer..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customers/{id}.json
  tags: Customers,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customersid-json-get-openapi.md
- name: Jumpseller Put Customers
  x-api-slug: jumpseller
  description: Update a new customer..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//customers/{id}.json
  tags: Customers,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/customersid-json-put-openapi.md
- name: Jumpseller Get Fields
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//fields.json
  tags: Fields,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/fields-json-get-openapi.md
- name: Jumpseller Post Fields
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//fields.json
  tags: Fields,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/fields-json-post-openapi.md
- name: Jumpseller Get Hooks
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//hooks.json
  tags: Hooks,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/hooks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/hooks-json-get-openapi.md
- name: Jumpseller Post Hooks
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//hooks.json
  tags: Hooks,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/hooks-json-post-openapi.md
- name: Jumpseller Delete Hooks
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//hooks/{id}.json
  tags: Hooks,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/hooksid-json-delete-openapi.md
- name: Jumpseller Get Hooks
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//hooks/{id}.json
  tags: Hooks,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/hooksid-json-get-openapi.md
- name: Jumpseller Put Hooks
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//hooks/{id}.json
  tags: Hooks,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/hooksid-json-put-openapi.md
- name: Jumpseller Post Jsapps
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//jsapps.json
  tags: Jsapps,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/jsapps-json-post-openapi.md
- name: Jumpseller Delete Jsapps Code
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//jsapps/{code}.json
  tags: Jsapps,Code,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/jsappscode-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/jsappscode-json-delete-openapi.md
- name: Jumpseller Get Jsapps Code
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//jsapps/{code}.json
  tags: Jsapps,Code,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/jsappscode-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/jsappscode-json-get-openapi.md
- name: Jumpseller Get Orders
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//orders.json
  tags: Orders,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/orders-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/orders-json-get-openapi.md
- name: Jumpseller Post Orders
  x-api-slug: jumpseller
  description: 'Use the JSON format:<br/>''{ "order": {"status": "Paid", "shipping_method_id":
    123, "products": [{ "id": 123, "qty": 1}], "customer": {"id": 123}}}''<br/>or
    in CURL:<br/>curl -X POST -d ''{ "order": {"status": "Paid", "shipping_method_id":
    123, "products": [{ "id": 123, "qty": 1}], "customer": {"id": 123}}}'' "https://api.jumpseller.com/v1/orders.json?login=storecode&authtoken=XXXXX"
    -H "Content-Type:application/json"'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//orders.json
  tags: Orders,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/orders-json-post-openapi.md
- name: Jumpseller Get Orders Status Status
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//orders/status/{status}.json
  tags: Orders,Status,Status,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/ordersstatusstatus-json-get-openapi.md
- name: Jumpseller Get Orders
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//orders/{id}.json
  tags: Orders,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/ordersid-json-get-openapi.md
- name: Jumpseller Put Orders
  x-api-slug: jumpseller
  description: 'Only ''status'', ''tracking_number'', ''tracking_company'', ''additional_information''
    and ''additional_fields'' are available for update.<br/>Use the JSON format:<br/>''{
    "order": {"status": "Paid", "tracking_company": "other", "tracking_number": "123456789",
    "additional_information": "My custom message.", "additional_fields": [{"label":
    "Gift Name", "value": "Duarte"}, {"label": "Gift Wrapping Color", "value": "Green"}]}
    }}''<br/>or in CURL:<br/>curl -X PUT -d ''{ "order": {"status": "Paid", "additional_information":
    "My custom message."}}'' "https://api.jumpseller.com/v1/orders/{id}.json?login=storecode&authtoken=XXXXX"
    -H "Content-Type:application/json"'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//orders/{id}.json
  tags: Orders,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/ordersid-json-put-openapi.md
- name: Jumpseller Get Orders History
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//orders/{id}/history.json
  tags: Orders,Id,History,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/ordersidhistory-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/ordersidhistory-json-get-openapi.md
- name: Jumpseller Post Orders History
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//orders/{id}/history.json
  tags: Orders,Id,History,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/ordersidhistory-json-post-openapi.md
- name: Jumpseller Get Payment Methods
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//payment_methods.json
  tags: Payment,Methods,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/payment-methods-json-get-openapi.md
- name: Jumpseller Get Payment Methods
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//payment_methods/{id}.json
  tags: Payment,Methods,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/payment-methodsid-json-get-openapi.md
- name: Jumpseller Get Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products.json
  tags: Products,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/products-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/products-json-get-openapi.md
- name: Jumpseller Post Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products.json
  tags: Products,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/products-json-post-openapi.md
- name: Jumpseller Get Products After
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/after/{id}.json
  tags: Products,After,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsafterid-json-get-openapi.md
- name: Jumpseller Get Products Category Category
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/category/{category_id}.json
  tags: Products,Category,Category,Id,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productscategorycategory-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productscategorycategory-id-json-get-openapi.md
- name: Jumpseller Get Products Category Category Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/category/{category_id}/count.json
  tags: Products,Category,Category,Id,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productscategorycategory-idcount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productscategorycategory-idcount-json-get-openapi.md
- name: Jumpseller Get Products Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/count.json
  tags: Products,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productscount-json-get-openapi.md
- name: Jumpseller Get Products Search
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/search.json
  tags: Products,Search,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productssearch-json-get-openapi.md
- name: Jumpseller Get Products Sku Sku
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/sku/{sku}.json
  tags: Products,Sku,Sku,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsskusku-json-get-openapi.md
- name: Jumpseller Get Products Status Status
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/status/{status}.json
  tags: Products,Status,Status,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsstatusstatus-json-get-openapi.md
- name: Jumpseller Get Products Status Status Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/status/{status}/count.json
  tags: Products,Status,Status,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsstatusstatuscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsstatusstatuscount-json-get-openapi.md
- name: Jumpseller Delete Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}.json
  tags: Products,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsid-json-delete-openapi.md
- name: Jumpseller Get Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}.json
  tags: Products,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsid-json-get-openapi.md
- name: Jumpseller Put Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}.json
  tags: Products,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsid-json-put-openapi.md
- name: Jumpseller Get Products Fields
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/fields.json
  tags: Products,Id,Fields,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidfields-json-get-openapi.md
- name: Jumpseller Post Products Fields
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/fields.json
  tags: Products,Id,Fields,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidfields-json-post-openapi.md
- name: Jumpseller Get Products Fields Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/fields/count.json
  tags: Products,Id,Fields,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidfieldscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidfieldscount-json-get-openapi.md
- name: Jumpseller Get Products Images
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images.json
  tags: Products,Id,Images,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidimages-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidimages-json-get-openapi.md
- name: Jumpseller Post Products Images
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images.json
  tags: Products,Id,Images,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidimages-json-post-openapi.md
- name: Jumpseller Get Products Images Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images/count.json
  tags: Products,Id,Images,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidimagescount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidimagescount-json-get-openapi.md
- name: Jumpseller Delete Products Images Image
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images/{image_id}.json
  tags: Products,Id,Images,Image,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidimagesimage-id-json-delete-openapi.md
- name: Jumpseller Get Products Images Image
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images/{image_id}.json
  tags: Products,Id,Images,Image,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidimagesimage-id-json-get-openapi.md
- name: Jumpseller Get Products Options
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options.json
  tags: Products,Id,Options,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptions-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptions-json-get-openapi.md
- name: Jumpseller Post Products Options
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options.json
  tags: Products,Id,Options,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptions-json-post-openapi.md
- name: Jumpseller Get Products Options Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/count.json
  tags: Products,Id,Options,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionscount-json-get-openapi.md
- name: Jumpseller Delete Products Options Option
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}.json
  tags: Products,Id,Options,Option,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-id-json-delete-openapi.md
- name: Jumpseller Get Products Options Option
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}.json
  tags: Products,Id,Options,Option,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-id-json-get-openapi.md
- name: Jumpseller Put Products Options Option
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}.json
  tags: Products,Id,Options,Option,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-id-json-put-openapi.md
- name: Jumpseller Get Products Options Option Values
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values.json
  tags: Products,Id,Options,Option,Id,Values,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-idvalues-json-get-openapi.md
- name: Jumpseller Post Products Options Option Values
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values.json
  tags: Products,Id,Options,Option,Id,Values,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-idvalues-json-post-openapi.md
- name: Jumpseller Get Products Options Option Values Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/count.json
  tags: Products,Id,Options,Option,Id,Values,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-idvaluescount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-idvaluescount-json-get-openapi.md
- name: Jumpseller Delete Products Options Option Values Value
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/{value_id}.json
  tags: Products,Id,Options,Option,Id,Values,Value,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-idvaluesvalue-id-json-delete-openapi.md
- name: Jumpseller Get Products Options Option Values Value
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/{value_id}.json
  tags: Products,Id,Options,Option,Id,Values,Value,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-idvaluesvalue-id-json-get-openapi.md
- name: Jumpseller Put Products Options Option Values Value
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/{value_id}.json
  tags: Products,Id,Options,Option,Id,Values,Value,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidoptionsoption-idvaluesvalue-id-json-put-openapi.md
- name: Jumpseller Get Products Variants
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants.json
  tags: Products,Id,Variants,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidvariants-json-get-openapi.md
- name: Jumpseller Post Products Variants
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants.json
  tags: Products,Id,Variants,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidvariants-json-post-openapi.md
- name: Jumpseller Get Products Variants Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants/count.json
  tags: Products,Id,Variants,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidvariantscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidvariantscount-json-get-openapi.md
- name: Jumpseller Get Products Variants Variant
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants/{variant_id}.json
  tags: Products,Id,Variants,Variant,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidvariantsvariant-id-json-get-openapi.md
- name: Jumpseller Put Products Variants Variant
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants/{variant_id}.json
  tags: Products,Id,Variants,Variant,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/productsidvariantsvariant-id-json-put-openapi.md
- name: Jumpseller Get Promotions
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//promotions.json
  tags: Promotions,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/promotions-json-get-openapi.md
- name: Jumpseller Post Promotions
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//promotions.json
  tags: Promotions,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/promotions-json-post-openapi.md
- name: Jumpseller Delete Promotions
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//promotions/{id}.json
  tags: Promotions,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/promotionsid-json-delete-openapi.md
- name: Jumpseller Get Promotions
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//promotions/{id}.json
  tags: Promotions,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/promotionsid-json-get-openapi.md
- name: Jumpseller Put Promotions
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//promotions/{id}.json
  tags: Promotions,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/promotionsid-json-put-openapi.md
- name: Jumpseller Post Settings
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//settings.json
  tags: Settings,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/settings-json-post-openapi.md
- name: Jumpseller Get Settings Name
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//settings/{name}.json
  tags: Settings,Name,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/settingsname-json-get-openapi.md
- name: Jumpseller Put Settings Name
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//settings/{name}.json
  tags: Settings,Name,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/settingsname-json-put-openapi.md
- name: Jumpseller Get Store Info
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//store/info.json
  tags: Store,Info,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/storeinfo-json-get-openapi.md
- name: Jumpseller Get Store Languages
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//store/languages.json
  tags: Store,Languages,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/storelanguages-json-get-openapi.md
- name: Jumpseller
  x-api-slug: jumpseller
  description: We founded Jumpseller.com in 2009 in Europe  we called it Vendder back
    then  and released our first version of the Jumpseller product in September 2010.
    After releasing the product we quickly grew to thousands of customers. In November
    2010, we recei...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1
  tags: Jumpseller
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/jumpseller/master/_listings/jumpseller/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/vendder
- type: x-email
  url: info@jumpseller.com
- type: x-email
  url: support@jumpseller.com
- type: x-twitter
  url: https://twitter.com/Jumpseller
- type: x-website
  url: http://jumpseller.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---