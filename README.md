# zillow_scraper

Scraper API for Zillow Real Estate Data from zillow.com: 

1. Search Properties:
	[https://www.zillow.com/homes/${address_parm}]
	/properties/v2/list-for-sale/
	
Example Link:
```
[https://zillow-scraper.onrender.com/properties/v2/list-for-sale?zipcode=21076&limit=10&sort=pricea&price_max=900000&beds_min=2&baths_min=2&sqft_min=1000&sqft_max=7500&lotSize_min=1000&yearbuilt_min=2000]
```

Example json:
```
[
	0,
	{
		"zpid": "2067028093",
		"price": "$775,000",
		"priceLabel": "$775K",
		"beds": 4,
		"baths": 3,
		"area": 2519,
		"latLong": {
		"latitude": 39.17699,
		"longitude": -76.74306
		},
		"statusType": "FOR_SALE",
		"statusText": "New construction",
		"isFavorite": false,
		"isUserClaimingOwner": false,
		"isUserConfirmedClaim": false,
		"imgSrc": "https://photos.zillowstatic.com/fp/a2dd2ec896e6c797cbf197477e092b2c-p_e.jpg",
		"hasImage": true,
		"visited": false,
		"listingType": "NEW_CONSTRUCTION",
		"variableData": null,
		"hdpData": {
		"homeInfo": {
		"zpid": 2067028093,
		"zipcode": "21076",
		"city": "Hanover",
		"state": "MD",
		"latitude": 39.17699,
		"longitude": -76.74306,
		"price": 775000,
		"datePriceChanged": 1646380800000,
		"bathrooms": 3,
		"bedrooms": 4,
		"livingArea": 2519,
		"homeType": "SINGLE_FAMILY",
		"homeStatus": "FOR_SALE",
		"daysOnZillow": -1,
		"isFeatured": false,
		"shouldHighlight": false,
		"listing_sub_type": {
		"is_newHome": true
		},
		"isUnmappable": false,
		"isPreforeclosureAuction": false,
		"homeStatusForHDP": "FOR_SALE",
		"priceForHDP": 775000,
		"priceChange": 55000,
		"newConstructionType": "BUILDER_SPEC",
		"isNonOwnerOccupied": true,
		"isPremierBuilder": false,
		"isZillowOwned": false,
		"currency": "USD",
		"country": "USA",
		"lotAreaValue": 0.74,
		"lotAreaUnit": "acres"
		}
		},
		"shouldShowZestimateAsPrice": false,
		"detailUrl": "/homedetails/PARCEL-4-Forest-Ave-Hanover-MD-21076/2067028093_zpid/",
		"pgapt": "ForSale",
		"sgapt": "New Construction",
		"has3DModel": false,
		"hasVideo": false,
		"isHomeRec": false,
		"address": "--",
		"hasAdditionalAttributions": false,
		"isFeaturedListing": false,
		"availabilityDate": null
	},
]
```
 
2. Properties Detail:
	[https://www.zillow.com/homedetails/${zpid}_zpid/]
	/properties/v2/detail
	
Example Link:
```
[https://zillow-scraper.onrender.com/properties/v2/detail?property_id=2067028093]
```


Example json:
```

```
