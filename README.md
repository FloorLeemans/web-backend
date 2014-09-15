Complete Web Backend Course (PHP)
===========

## Installation

  - Download deze repository naar een map op jouw harde schijf door middel van de [CLI](http://en.wikipedia.org/wiki/Command-line_interface):
    1. Navigeer naar de map waar je de cursus wil hebben:
    
       ````
       cd \user\dropbox
       ````
    2. Clone de web-backend repository in deze map:
       
       ````
       git clone https://github.com/pascalculator/web-backend.git
       ````

  - Stel een virtual host in met als url `web-backend.local` in je host bestand (zie slides virtual-server-setup.pdf)
  - Stel in XAMPP (of andere virtual server) in dat alle http://web-backend.local requests omgeleid worden naar de fysieke map waar de repository is gedownload
  - Om de locale versie te updaten naar de laatste nieuwe versie (enkel nodig wanneer de online versie geüpdatet is):
    1. Navigeer naar de map waar de cursus staat:
    
       ````
       cd \user\dropbox\web-backend
       ````
    2. Voer een pull-request uit:
       
       ````
       git pull
       ````

## License

  - Deze cursus wordt beheerd door [Pascal Nosenzo](mailto:info@pascalculator.be)
  - Alles uit deze cursus valt onder de [Apache Licence v2.0](http://www.apache.org/licenses/LICENSE-2.0.html). Alles uit deze cursus mag vrij gebruikt worden, mits dezelfde disclaimer én bronvermelding worden overgenomen.
