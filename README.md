# Gift-Wrapping-Spatial-join
Gift Wrapping algorithm for Geostep and spatial join query for finding nearby games

This document introduces the Gift Wrapping algorithm (also known as the Jarvis march) modeled on the Convex Hull algorithm developed by Michalis Zervos. This algorithm is used to create a convex wrapper around only a set of points scattered in space, which contains only external points. This would reduce the number of scalps being fed into the spatial database, and a polygon could be made from the formed set of points - a polygon that could be stored as such in the spatial database for later further search.

An SQL query was also given that uses spatial join functions to perform spatial search, that is, it returns all games (hence polygons created from a set of points returned by the Gift Wrapping algorithm) that are in a circle around the observer.

===========================================================================================================================================

U ovom dokumentu predstavljen je Gift Wrapping algoritam (poznat i kao Džarvisov marš) urađen po uzoru na Convex Hull algoritam koji je razvio Michalis Zervos. Ovaj algoritam se koristi da oko skupa tačaka koje su razbacane u prostoru kreira konveksni omotač, koji sadrži samo eksterne tačke. Na ovaj način bi se smanjio broj tjemena koja se unose u Geostep bazu podataka i od formiranog skupa tačaka bi se mogao napraviti mnogougao - poligon koji bi se kao takav mogao sačuvati u prostornoj bazi podataka radi kasnije dalje pretrage.

Takođe je dat i SQL upit koji koristi spatial join funkcije radi izvršavanja prostorne pretrage, odnosno, vraća sve igre (dakle poligone kreirane od skupa tačaka vraćenih od strane Gift Wrapping algoritma) koje se nalaze u krugu oko posmatrača.
