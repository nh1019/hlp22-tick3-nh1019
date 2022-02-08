# Refactoring 

Note that I attempted to change the names of ```Thing``` and ```Model3``` as I thought they were far too generic and made the many functions they were used in less readable, however this caused too many problems in all the other files they had been used it, so I decided against it. 

## Section A

The very first function sticks out as having a terrible name (```sideHasPositiveCommonCoordinateOffset```), so I changed it to simply ```commonCoordinate```. 

The next poorly named function is ```subtractFromX1OrY1```. It is hard to read and it does not even give a great indication of what the function does. It was changed to ```decideSubtraction```. The new name is not perfect but it does make sense given that the function decides which side to subtract from based on ```direction: bool```.

