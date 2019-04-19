# Jared_SDC

Jared's SDC
***************************************
*   GET ALL ARTISTS                   *
***************************************
ROUTE
    /artists

  JSON
    [{
      artistName: string
      image: string //path to image
      genre: number
    },
    ...
    ]
*************************************** 
*    GET ARTIST BY ID                 *
***************************************
  ROUTE
    /artists/:id

  JSON
    {
      artistName: string
      image: string //path to image
      genre: number
    }
