# Gift-Wrapping-Spatial-join
Gift Wrapping algorithm for Geostep and spatial join query for finding nearby games

U ovom dokumentu predstavljen je Gift Wrapping algoritam (poznat i kao Džarvisov marš) urađen po uzoru na Convex Hull algoritam koji je razvio Michalis Zervos. Ovaj algoritam se koristi da oko skupa tačaka koje su razbacane u prostoru kreira konveksni omotač, koji sadrži samo eksterne tačke. Na ovaj način bi se smanjio broj tjemena koja se unose u Geostep bazu podataka i od formiranog skupa tačaka bi se mogao napraviti mnogougao - poligon koji bi se kao takav mogao sačuvati u prostornoj bazi podataka radi kasnije dalje pretrage.

Takođe je dat i SQL upit koji koristi spatial join funkcije radi izvršavanja prostorne pretrage, odnosno, vraća sve igre (dakle poligone kreirane od skupa tačaka vraćenih od strane Gift Wrapping algoritma) koje se nalaze u krugu oko posmatrača.
