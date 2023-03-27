# lomapSpec
Common specification for LoMap apps

- JSON specification
````
{
  "maps":[
  {
    "id":"(generación aleatoria de carácteres)",
    "name":"Parque de invierno",
    "locations":[
      {
        "id":"(generación aleatoria de carácteres)",
        "name":"Parque de invierno",
        "category":"park"
        "latitude":"43.35302550278352",
        "longitude":"-5.849442050492078",
        "description":"A beautiful place I found when i went for a walk",
        "comments":[
          {
            "author":"webId of the person who comments",
            "comment":"I've been there with my dog !",
            "date": "1679832611",//timesamp of the comment
          },
          (..more comments)
         ],
        "reviewScore":"",
        "date": "timestamp of the time the user placed the pin/landmark..."
        ],
        (..more locations)
      }
    (..more maps)
    }  
  ]
}
````
