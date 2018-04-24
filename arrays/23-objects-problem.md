
## Przypadek z życia
Wyobraźcie sobie, że mamy wiele danych użytkownika: Imię, nazwisko, wiek, płeć, adres email, miasto itp...
Jak przechować je w kodzie?

### W osobnych zmiennych?
```javascript
let userFirstName = 'Ewa';
let userLastName = 'Kowalska';
let userAge = 27;
let userGender = 'k';
let userEmailAddress = 'ewa.kowalska@poczta.pl';
let userCity = 'Gdańsk';
// ...
```
Mało to przyjazne, prawda?

### Tablice?
```javascript
let user = [
  'Ewa', 'Kowalska', 27, 'k', 'ewa.kowalska@poczta.pl', 'Gdańsk'
];
```
To wygląda już lepiej, ale odczytywanie np. adresu email oznacza coś takiego:

```javascript
console.log( user[4] );
```
Pamiętanie numerków nie jest łatwe.
