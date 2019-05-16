# RESTful Polish Beer API
*Mikołaj Zyzański*

## Schema
### Beer Schema
**id**: *String*, Unique beer ID generated by the API
**beerName**: *String* **Required**, The name of the beer (i.e. Żywiec, Pinta)
**breweryName**: *String* **Required**, The name of the brewery producing the beer
**image**: *String*, URL to a picture of the beer
**type**: *String*, Type of beer (i.e. IPA, Pilsner)
**alcoholContent**: *Float*, Percentage amount of alcohol
**description**: *String*, Description of the beer's taste (i.e. Fruity, goes well with meat)

##Methods

### Get All Beers

**Endpoint**:

> http://localhost:3000/beers

**Method**: GET


### Get Specific Beer (by ID)

**Endpoint**:

> http://localhost:3000/beers/:id

**Method**: GET


###Add A Beer To The Database

**Endpoint**:

> http://localhost:3000/beers/

**Method**: POST


###Update Specific Beer (by ID)

**Endpoint**:

> http://localhost:3000/beers/:id

**Method**: PATCH

*Note*: Provide full beer schema in body


###Delete Specific Beer (by ID)

**Endpoint**:

> http://localhost:3000/beers/:id

**Method**: DELETE

