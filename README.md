# “Iz pošte u poštu” API (Hrvatska Pošta)

API endpoint that returns Croatian post offices according to PDF file available at https://www.posta.hr/paket-iz-poste-u-postu/208

## Endpoint

Available at https://api.applause.hr/iz-poste-u-postu

* GET requests accepted
* returns all post offices

## Parameters

* limit - integer
* offset - integer
* id - integer
* zip_code - integer
* is_active - 1 or 0
* search - any search term (e.g. “kloš” or combination like “100+bre”)
* type - “formatted”

## Example calls

* https://api.applause.hr/iz-poste-u-postu?limit=10
* https://api.applause.hr/iz-poste-u-postu?limit=10&offset=10
* https://api.applause.hr/iz-poste-u-postu?id=47
* https://api.applause.hr/iz-poste-u-postu?zip_code=10257
* https://api.applause.hr/iz-poste-u-postu?is_active=0
* https://api.applause.hr/iz-poste-u-postu?search=kloš
* https://api.applause.hr/iz-poste-u-postu?search=100+bre
* https://api.applause.hr/iz-poste-u-postu?type=formatted

## Demo

For demo purpose jQuery EasyAutocomplete plugin was used (http://easyautocomplete.com/):

https://www.applause.hr/demo/iz-poste-u-postu/
