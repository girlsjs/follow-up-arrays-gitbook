## Rozwiązanie
Pewnie wyszło Wam coś takiego:
```javascript
let book1 = {
  author: 'Janina Kowalska',
  title: 'Mój pamiętnik',
  year: 2017
};

renderBook(book1);
```
(i tak 5 razy)

## Prościej
Nie trzeba obiektu przypisywać do zmiennej.
Można go przekazać bezpośrednio:
```javascript
renderBook({
  author: 'Janina Kowalska',
  title: 'Mój pamiętnik',
  year: 2017
});
```
