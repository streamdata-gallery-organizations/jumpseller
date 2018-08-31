---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 0
info:
  title: Jumpseller Get Payment Methods
  description: ""
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps.json:
    get:
      summary: Get Apps
      description: Retrieve all jumpseller apps..
      operationId: getApps.json
      x-api-path-slug: apps-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Json
  /categories.json:
    get:
      summary: Get Categories
      description: Retrieve all categories..
      operationId: getCategories.json
      x-api-path-slug: categories-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Json
    post:
      summary: Post Categories
      description: Create a new category..
      operationId: postCategories.json
      x-api-path-slug: categories-json-post
      parameters:
      - in: body
        name: body
        description: Category parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Json
  /categories/{id}.json:
    delete:
      summary: Delete Categories
      description: Delete an existing category..
      operationId: deleteCategories.json
      x-api-path-slug: categoriesid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the Category
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Id
      - Json
    get:
      summary: Get Categories
      description: Retrieve a single category..
      operationId: getCategories.json
      x-api-path-slug: categoriesid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Category
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Id
      - Json
    put:
      summary: Put Categories
      description: Modify an existing category..
      operationId: putCategories.json
      x-api-path-slug: categoriesid-json-put
      parameters:
      - in: body
        name: body
        description: Category parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the Category
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Id
      - Json
  /checkout_custom_fields.json:
    get:
      summary: Get Checkout Custom Fields
      description: Retrieve all checkout custom fields..
      operationId: getCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fields-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Json
    post:
      summary: Post Checkout Custom Fields
      description: Create a new checkoutcustomfield..
      operationId: postCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fields-json-post
      parameters:
      - in: body
        name: body
        description: CheckoutCustomField parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Json
  /checkout_custom_fields/{id}.json:
    delete:
      summary: Delete Checkout Custom Fields
      description: Delete an existing checkoutcustomfield..
      operationId: deleteCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fieldsid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the CheckoutCustomField
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Id
      - Json
    get:
      summary: Get Checkout Custom Fields
      description: Retrieve a single checkoutcustomfield..
      operationId: getCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fieldsid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the CheckoutCustomField
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Id
      - Json
    put:
      summary: Put Checkout Custom Fields
      description: Update a checkoutcustomfield..
      operationId: putCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fieldsid-json-put
      parameters:
      - in: body
        name: body
        description: CheckoutCustomField parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the CheckoutCustomField
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Id
      - Json
  /countries.json:
    get:
      summary: Get Countries
      description: Retrieve all countries..
      operationId: getCountries.json
      x-api-path-slug: countries-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Countries
      - Json
  /countries/{country_code}.json:
    get:
      summary: Get Countries Country Code
      description: Retrieve a single country information..
      operationId: getCountriesCountryCode.json
      x-api-path-slug: countriescountry-code-json-get
      parameters:
      - in: path
        name: country_code
        description: ISO3166 Country Code
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Countries
      - Country
      - Code
      - Json
  /countries/{country_code}/regions.json:
    get:
      summary: Get Countries Country Code Regions
      description: Retrieve all regions from a single country..
      operationId: getCountriesCountryCodeRegions.json
      x-api-path-slug: countriescountry-coderegions-json-get
      parameters:
      - in: path
        name: country_code
        description: ISO3166 Country Code
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Countries
      - Country
      - Code
      - Regions
      - Json
  /countries/{country_code}/regions/{region_code}.json:
    get:
      summary: Get Countries Country Code Regions Region Code
      description: Retrieve a single region information object..
      operationId: getCountriesCountryCodeRegionsRegionCode.json
      x-api-path-slug: countriescountry-coderegionsregion-code-json-get
      parameters:
      - in: path
        name: country_code
        description: ISO3166 Country Code
      - in: query
        name: No Name
      - in: path
        name: region_code
        description: Region Code
      responses:
        200:
          description: OK
      tags:
      - Countries
      - Country
      - Code
      - Regions
      - Region
      - Code
      - Json
  /customer_categories.json:
    get:
      summary: Get Customer Categories
      description: Retrieve all customer categories..
      operationId: getCustomerCategories.json
      x-api-path-slug: customer-categories-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Json
    post:
      summary: Post Customer Categories
      description: Create a new customercategory..
      operationId: postCustomerCategories.json
      x-api-path-slug: customer-categories-json-post
      parameters:
      - in: body
        name: body
        description: CustomerCategory parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Json
  /customer_categories/{id}.json:
    delete:
      summary: Delete Customer Categories
      description: Delete an existing customercategory..
      operationId: deleteCustomerCategories.json
      x-api-path-slug: customer-categoriesid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Json
    get:
      summary: Get Customer Categories
      description: Retrieve a single customercategory..
      operationId: getCustomerCategories.json
      x-api-path-slug: customer-categoriesid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Json
    put:
      summary: Put Customer Categories
      description: Update a customercategory..
      operationId: putCustomerCategories.json
      x-api-path-slug: customer-categoriesid-json-put
      parameters:
      - in: body
        name: body
        description: CustomerCategory parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Json
  /customer_categories/{id}/customers.json:
    delete:
      summary: Delete Customer Categories Customers
      description: Delete customers from an existing customercategory..
      operationId: deleteCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
    get:
      summary: Get Customer Categories Customers
      description: Retrieves the customers in a customercategory..
      operationId: getCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-get
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
    post:
      summary: Post Customer Categories Customers
      description: Adds customers to a customercategory..
      operationId: postCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-post
      parameters:
      - in: body
        name: body
        description: Customer parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
  /customers.json:
    get:
      summary: Get Customers
      description: Retrieve all customers..
      operationId: getCustomers.json
      x-api-path-slug: customers-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Json
    post:
      summary: Post Customers
      description: Create a new customer..
      operationId: postCustomers.json
      x-api-path-slug: customers-json-post
      parameters:
      - in: body
        name: body
        description: Customer parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Json
  /customers/email/{email}.json:
    get:
      summary: Get Customers Email Email
      description: Retrieve a single customer..
      operationId: getCustomersEmailEmail.json
      x-api-path-slug: customersemailemail-json-get
      parameters:
      - in: path
        name: email
        description: Email of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Email
      - Email
      - Json
  /customers/{id}.json:
    delete:
      summary: Delete Customers
      description: Delete an existing category..
      operationId: deleteCustomers.json
      x-api-path-slug: customersid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Id
      - Json
    get:
      summary: Get Customers
      description: Retrieve a single customer..
      operationId: getCustomers.json
      x-api-path-slug: customersid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Id
      - Json
    put:
      summary: Put Customers
      description: Update a new customer..
      operationId: putCustomers.json
      x-api-path-slug: customersid-json-put
      parameters:
      - in: body
        name: body
        description: Customer parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Id
      - Json
  /fields.json:
    get:
      summary: Get Fields
      description: ""
      operationId: getFields.json
      x-api-path-slug: fields-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Fields
      - Json
    post:
      summary: Post Fields
      description: ""
      operationId: postFields.json
      x-api-path-slug: fields-json-post
      parameters:
      - in: body
        name: body
        description: Custom Field parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Fields
      - Json
  /hooks.json:
    get:
      summary: Get Hooks
      description: ""
      operationId: getHooks.json
      x-api-path-slug: hooks-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Hooks
      - Json
    post:
      summary: Post Hooks
      description: ""
      operationId: postHooks.json
      x-api-path-slug: hooks-json-post
      parameters:
      - in: body
        name: body
        description: Hook parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Hooks
      - Json
  /hooks/{id}.json:
    delete:
      summary: Delete Hooks
      description: ""
      operationId: deleteHooks.json
      x-api-path-slug: hooksid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the Hook
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Hooks
      - Id
      - Json
    get:
      summary: Get Hooks
      description: ""
      operationId: getHooks.json
      x-api-path-slug: hooksid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Hook
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Hooks
      - Id
      - Json
    put:
      summary: Put Hooks
      description: ""
      operationId: putHooks.json
      x-api-path-slug: hooksid-json-put
      parameters:
      - in: body
        name: body
        description: Hook parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the Hook
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Hooks
      - Id
      - Json
  /jsapps.json:
    post:
      summary: Post Jsapps
      description: ""
      operationId: postJsapps.json
      x-api-path-slug: jsapps-json-post
      parameters:
      - in: body
        name: body
        description: JSApp parameters to create
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Jsapps
      - Json
  /jsapps/{code}.json:
    delete:
      summary: Delete Jsapps Code
      description: ""
      operationId: deleteJsappsCode.json
      x-api-path-slug: jsappscode-json-delete
      parameters:
      - in: path
        name: code
        description: Code of the App
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Jsapps
      - Code
      - Json
    get:
      summary: Get Jsapps Code
      description: ""
      operationId: getJsappsCode.json
      x-api-path-slug: jsappscode-json-get
      parameters:
      - in: path
        name: code
        description: Code of the App
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Jsapps
      - Code
      - Json
  /orders.json:
    get:
      summary: Get Orders
      description: ""
      operationId: getOrders.json
      x-api-path-slug: orders-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Json
    post:
      summary: Post Orders
      description: 'Use the JSON format:<br/>''{ "order": {"status": "Paid", "shipping_method_id":
        123, "products": [{ "id": 123, "qty": 1}], "customer": {"id": 123}}}''<br/>or
        in CURL:<br/>curl -X POST -d ''{ "order": {"status": "Paid", "shipping_method_id":
        123, "products": [{ "id": 123, "qty": 1}], "customer": {"id": 123}}}'' "https://api.jumpseller.com/v1/orders.json?login=storecode&authtoken=XXXXX"
        -H "Content-Type:application/json"'
      operationId: postOrders.json
      x-api-path-slug: orders-json-post
      parameters:
      - in: body
        name: body
        description: Order parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Json
  /orders/status/{status}.json:
    get:
      summary: Get Orders Status Status
      description: ""
      operationId: getOrdersStatusStatus.json
      x-api-path-slug: ordersstatusstatus-json-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: status
        description: Status of the Order used as filter
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Status
      - Status
      - Json
  /orders/{id}.json:
    get:
      summary: Get Orders
      description: ""
      operationId: getOrders.json
      x-api-path-slug: ordersid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Order
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Id
      - Json
    put:
      summary: Put Orders
      description: 'Only ''status'', ''tracking_number'', ''tracking_company'', ''additional_information''
        and ''additional_fields'' are available for update.<br/>Use the JSON format:<br/>''{
        "order": {"status": "Paid", "tracking_company": "other", "tracking_number":
        "123456789", "additional_information": "My custom message.", "additional_fields":
        [{"label": "Gift Name", "value": "Duarte"}, {"label": "Gift Wrapping Color",
        "value": "Green"}]} }}''<br/>or in CURL:<br/>curl -X PUT -d ''{ "order": {"status":
        "Paid", "additional_information": "My custom message."}}'' "https://api.jumpseller.com/v1/orders/{id}.json?login=storecode&authtoken=XXXXX"
        -H "Content-Type:application/json"'
      operationId: putOrders.json
      x-api-path-slug: ordersid-json-put
      parameters:
      - in: body
        name: body
        description: Order parameters to change
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the Order
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Id
      - Json
  /orders/{id}/history.json:
    get:
      summary: Get Orders History
      description: ""
      operationId: getOrdersHistory.json
      x-api-path-slug: ordersidhistory-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Order
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Id
      - History
      - Json
    post:
      summary: Post Orders History
      description: ""
      operationId: postOrdersHistory.json
      x-api-path-slug: ordersidhistory-json-post
      parameters:
      - in: body
        name: body
        description: Order History parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the OrderHistory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Id
      - History
      - Json
  /payment_methods.json:
    get:
      summary: Get Payment Methods
      description: ""
      operationId: getPaymentMethods.json
      x-api-path-slug: payment-methods-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Methods
      - Json
  /payment_methods/{id}.json:
    get:
      summary: Get Payment Methods
      description: ""
      operationId: getPaymentMethods.json
      x-api-path-slug: payment-methodsid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Payment Method
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Methods
      - Id
      - Json
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---