FORMAT: 1A
HOST: google.com

# Group Heroes

## Heroes [/heroes{?offset,limit}]

### Get Hero list [GET]

+ Parameters
    + offset: `0` (number, optional) - the first row shown
    + limit: `10` (number, optional) - the number of rows shown

+ Response 200 (application/json)

### Create Hero [POST]

+ Response 201 (application/json)

## Specific Hero [/heroes/{id}]

### Get Hero [GET]

+ Parameters
    + id: `1` (number, required) - The id of hero

+ Response 200 (application/json)

### Update Hero [PUT]

+ Parameters
    + id: `1` (number, required) - The id of hero

+ Response 200 (application/json)

### Delete Hero [DELETE]

+ Parameters
    + id: `1` (number, required) - The id of hero

+ Response 202 (application/json)

# Group Items

## Items [/items{?offset,limit}]

### Get Item List [GET]

+ Parameters
    + offset: `0` (number, optional) - the first row shown
    + limit: `10` (number, optional) - the number of rows shown

+ Response 200 (application/json)

### Create Item [POST]

+ Response 201 (application/json)

## Specific Item [/items/{id}]

### Get Item [GET]

+ Parameters
    + id: `1` (number, required) - The id of item

+ Response 200 (application/json)

### Update Item [PUT]

+ Parameters
    + id: `1` (number, required) - The id of item

+ Response 200 (application/json)

### Delete Item [DELETE]

+ Parameters
    + id: `1` (number, required) - The id of item

+ Response 202 (application/json)