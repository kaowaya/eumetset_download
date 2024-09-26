# eumetset_download
 download eumetset data in batch after searching 

 ## step 1:  searching from EUMETSET data store

 Searching from this url (sign in required):
 https://data.eumetsat.int/extended?query=

 ## step 2:  
 For example,  if you want to download all the search result, you need to add results into the cart and press "download cart".

 the you get an XML file that contains filenames and urls.

 the token is dynamic. you should mannualy download any single file and copy the token like

 https://api.eumetsat.int/data/download/1.0.0/collections/EO%3AEUM%3ADAT%3AMETOP%3AAMSUL1/products/AMSA_xxx_1B_M01_20240925220419Z_20240925234619Z_N_O_20240925225219Z?access_token=e446fa03-3a34-333b-ad64-6dc8185026ef

 then the token is " Z?access_token=e446fa03-3a34-333b-ad64-6dc8185026ef "
 ## step 3:  
 Replace the xml content and the token , then run the main.py
