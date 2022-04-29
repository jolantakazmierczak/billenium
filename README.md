# Repozytorium na potrzeby 'Przedmiot fakultatywny - Billenium'

## React.js

React to javascriptowa biblioteka służąca do budowania interfejsów użytkownika. React.js pozwala na tworzenie odseparowanych od siebie komponentów, które są reużywalne. Dzięki temu możemy w sposób powtarzalny budować coraz większe moduły, do których przekazujemy odpowiednie informacje za pomocą tzw. propsów. React.js wykorzystuje tzw. wirtualny DOM, a także metodę virtual dom diffing. Oznacza ona w praktyce, że wszystkie zmiany w strukturze DOM są najpierw wykonywane w silniku Javascript, a jeżeli zajdzie potrzeba wyrenderowania komponentu na nowo przekazana zostanie odpowiednia informacja do drzewa DOM. Jest to o tyle innowacyjne rozwiązanie, że zmniejsza ilość odświeżeń wyświetlania komponentu i sprawia, że procesor zajmuje się tylko tym co potrzeba.

React sprawdza się najlepiej w zaawansowanych interfejsach użytkownika. Tam gdzie logika aplikacji jest skomplikowana, akcje użytkownika są niestandardowe i zaawansowane. Bardzo dobrze sprawdza się w dużych zespołach, gdyż pozwala na dobrą separację warstwy logicznej i prezentacyjnej.

Zalety React.js
- Komponenty JS mogą być używane wielokrotnie. 
- JS jest wszechstronny i może być używany z dowolnie wybranym frameworkiem. 
- Oferuje wysoką wydajność, ponieważ jest oparty na domenie wirtualnej. 
- Wykorzystuje jednokierunkowy przepływ danych. 
- Umożliwia budowę dynamicznego interfejsu. 
- Jest prosty w obsłudze, dlatego mogą z niego korzystać początkujący programiści.  
- Witryny oparte o React JS mają pozytywny wpływ na SEO, ponieważ szybkość strony jest jednym z czynników branych pod uwagę w rankingu Google. 
- Jest stabilnym rozwiązaniem, ponieważ stoi za nim duża społeczność, która nieustannie się rozwija.



## Instrukcja instalacji:
```
git clone https://github.com/jolantakazmierczak/billenium.git
cd billenium/frontend/
yarn install
yarn start
```
