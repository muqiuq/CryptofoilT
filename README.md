# CryptoFoilT - PHP CLI cryptocurrency portfolio manager

Da ich keinen passenden Portfoliomanager für Crytowährungen gefunden habe, entstand dieses PHP Skript. Es ist vorallem für Nutzer aus der Schweiz optimiert und ist deshalb auf EUR und CHF hardcoded. 

Die Codequalität lässt zu wünschen übrig. Ursache ist klassisch: "Ich programmier noch schnell..."

## Functions
- Load portfolio from a json file
- Calculate total, absolute, relative Change
- Calculate total value of portfolio
- Sort portfolio

## Exchanges

CryptofoilT supports the following exchanges:
- Bittrex
- Bitstamp
- Kraken
- HitBTC

## Quick Start
- Clone git
- Adjust portfolio.json
- Run php cft.php

## CLI Options
```
-s=<> --sort=<>   Sort DESC for this column
-n                Do not sort
--columns         Display available columns
--offline         Don't access tickers online
```

## Licence
This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
http://creativecommons.org/licenses/by-nc-sa/4.0/
