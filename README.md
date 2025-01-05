# React-Native File-based routing Application

![React Native Logo](https://reactnative.dev/img/header_logo.svg)


## O projektu
Ovo je mobilna aplikacija izrađena pomoću [React Native](https://reactnative.dev/), popularnog okvira za izradu native aplikacija koristeći React.
Aplikacija implementira file-based routing, što znači da se rute generiraju na osnovu strukture datoteka unutar mape predviđene za rute. Svaka datoteka u odgovarajućoj mapi (npr. routes/) predstavlja jednu rutu. Ovo omogućava automatsko povezivanje URL-ova sa odgovarajućim komponentama ili stranicama, bez potrebe za eksplicitnim definiranjem ruta u dodatnim konfiguracijskim fajlovima.

## Preduvjeti
Prije pokretanja ovog projekta, provjerite imate li instalirano sljedeće:

- Node.js (>= 14.x)
- npm (>= 6.x) ili yarn (>= 1.x)
- React Native CLI ili Expo CLI

## Instalacija
1. Klonirajte repozitorij:
   ```bash
   git clone https://github.com/danci-silicone/01_react-native-navigation-file_based_routing-route
   ```

2. Instalirajte pakete:
   ```bash
   npm install
   # ili
   yarn install
   ```

## Pokretanje aplikacije

### Korištenje Yarn za web aplikaciju:
Ako koristite Expo i želite pokrenuti aplikaciju u web pregledniku:
1. Pokrenite web poslužitelj:
   ```bash
   yarn web
   ```
2. Aplikacija će se otvoriti u vašem zadanom web pregledniku.

## Korišteni resursi
Ovo su web stranice koje su korištene tijekom razvoja:
- [File-based routing - Expo dokumentacija](https://docs.expo.dev/develop/file-based-routing/#create-a-route)
- [Stack Navigator - Expo dokumentacija](https://docs.expo.dev/develop/file-based-routing/#stack-navigator)
- [Navigating between routes - Expo Docs](https://docs.expo.dev/develop/file-based-routing/#navigating-between-routes)
