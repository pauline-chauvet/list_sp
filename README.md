# list_sp
This code aims to look at corresponding scientificName scientificNameID acceptedScientificName acceptedScientificNameID Status ... in worms and/or itis API (IUCN to come).

Start = Scientific name from you liste, can be Order, Genus specie, Family etcs... 
  Careful with accent, special character, dbl space or tabulation to separate words
  If there is sp. or spp. it will remove it (e.g. "Anas sp." will become "Anas") 
  It will keep ssp., var. etcs. (e.g. "Cakile edentula ssp. edentula var. edentula" will stay the same)
End = a table with information from Worms if the specie is marine of itis if it is not found in worms.
  It is made to prioritize worms aphiaID instead of itis as we are working to implement data into OBIS.
  
