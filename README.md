# store-api
A generic store API built with NodeJS. This API contains only one route, but this route is configure to accept some query options.

# available query

- The main route is based on the products data available on the remote mongo database.
- On this route, the client can search for products through their properties. Their properties are: name, price, company, date of cration and rating.
- The client can also sort the data according to its properties in ascendig or descendig order.
- The client can select the fields that are important to show.
- The API have a pagination function. The client informs the number of items to be shown on each page.
