# ZAP
Dit voorbeeld laat zien hoe ZAP met behulp van Docker eenvoudig gestart kan worden:

`docker compose up -d`

Hierna is ZAP beschikbaar op http://localhost:8080/zap
En de proxy op http://localhost:9090

## Maken proxy
Om de proxy te gebruiken moet de browser geconfigureerd worden om de proxy te gebruiken.
De proxy instellingen zijn:

* Host: 127.0.0.1
* Port: 9090

Hoe het instellen van de proxy in de browser precies werkt is afhankelijk van de browser. Volg de instructies [hier](https://www.zaproxy.org/docs/desktop/start/proxies/).

## Installeren certificaat
Om de proxy te gebruiken moet het certificaat van de proxy geïnstalleerd worden.
Dit certificaat zal te vinden zijn in de map `data` van dit voorbeeld wanneer de zap omgeving is gestart.
Dit certificaat moet in de browser geïnstalleerd worden. [Dit kan in de instellingen van de browser](https://www.zaproxy.org/docs/desktop/addons/network/options/servercertificates/).
