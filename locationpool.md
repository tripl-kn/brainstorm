# Documents

### Beschreibung
Jeder _local_ hat ein pool an seinen favorisierten location, die er "cool" findet. Eine Location Besteht aus:
 - einem Ort (Name) (o.ä.?)
 - Bilder 
 - Geotag
 - Beschreibung 
 - und/oder ???

Der Locationpool eines Benutzers besteht aus einer _leichtgewichtige_ Liste aller Locations. //TODO: diskutieren.


### Routes
####GET

|Ressource   | Description  |  on Success | on Failure |
|---|---|---|---|
|/user/:userID/locations/  | returns a locationpool (list) of saved location of the user   | json object | statusCode: 404 |
|/user/:userID/locations/:locationsID  | returns a particular saved location of the user | json object | statusCode: 404 |

####POST

|Ressource   | Description  | on Failure |
|---|---|---|---|
|/user/:userID/locations/:locationsID  | adds a location into the location pool of the user   |  statusCode: 404 |

//TODO: bulk add??

####PUT


|Ressource   | Description  | on Failure |
|---|---|---|---|
|/user/:userID/locations/:locationsID  | updates a location of the location pool of the user   |  statusCode: 404 |



### Dummy json results

```

```