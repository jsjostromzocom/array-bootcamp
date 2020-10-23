
# Array Bootcamp
**Övningar för att lära sig Arrayer.**

## The Basics
1. Gör en array som innehåller 5 st olika frukter av datatypen ```string```.

2. gör en array som innehåller 3 olika datatyper, ex. ```string```, ```number```, ```array```.

```js
let animals = ['cat', 'hamster', 'parrot', 'funky chihuahua']
```

3. ```console.log()``` hur många objekt arrayen ovan innehåller.

4. I arrayen ovan, hämta *cat*.

5. I arrayen ovan, hämta *funky chihuahua*.

6. I arrayen ovan, byt ut *hamster* mot *tiger*.

```js
let a = [1,2,3];
let b = [4,5,6];
```

7. Lägg ihop ovanstående arrayer.

```js
let a = [1,2,3,7,8,9];
let b = [4,5,6];
```

8. Merga ner array ```b``` på index ```3``` array ```a```.


## Methods

```js
let fruits = ['kiwi', 'apple', 'pear'];
```

7. Lägg till en frukt i *slutet* av arrayen ovan.

8. Lägg till en frukt i *början* av arrayen ovan.

9. I arrayen ovan, ta bort *sista* frukten i arrayen.

10. I arrayen ovan, ta bort *första* frukten i arrayen.

11. Sätt in *en* frukt i arrayen ovan på ```index 1```.

12. Sätt in *tre* frukter i arrayen ovan på ```index 2```.

```js
let names = ['David', 'Christoffer', 'Johan', 'Maja']
```

13. I arrayen ovan, ta bort *Christoffer* och *Johan*.


```js
let nums = [1,2,3,4,5,6,7,8,9];
```
14. Spegelvänd på arrayen ovan.


## Advanced methods ( high order methods )
### .filter()
```js
let numArray = [23, 45, 5, 62, 1, 21, 3, 54];
```
15. I arrayen ovan, filtera fram alla nummer *över* ```5```.

16. I arrayen ovan, filtera fram alla nummer *under* ```5```.

```js
let persons = [
    {
        name: "Felicia",
        age: 12
    },
    {
        name: "Pelle",
        age: 20
    },
    {
        name: "Peter",
        age: 59
    },
    {
        name: "Anna",
        age: 32
    },
    {
        name: "Jocke",
        age: 18
    },
    {
        name: "Ella",
        age: 3
    }
]
```


17. Skriv ut alla namn som *är 18 år eller över* från arrayen ovan.

18. Skriv ut alla namn som är *under 18 år* från arrayen ovan.


### .sort()
```js
let arr = ['beta', 'alfa', 'gamma'];
```

19. Sortera ovanstående array *alfabetisk*.

```js 
let nums = [1,5,7,9,3,4,2,6,8];
```
20. Sortera ovanstående array *numeriskt*.


21. I person-arrayen ovan, sortera objekten efter ålder, *yngst* först.

22. I person-arrayen ovan, sortera objekten efter ålder, *äldst* först.


23. I person-arrayen ovan, sortera objekten i bokstavsordning efter deras namn


### .map()

24. I person-arrayen ovan, gör om alla namn till *versaler*.

25. I person-arrayen ovan, *spegelvänd* alla namn.


### .include()

```js
let str = 'Supercalifragilisticexpialidocious';
```

26. Kika om strängen ovan innehåller bokstaven ```n```.

27. Kika om strängen ovan innehåller bokstaven ```x```.


## Loop arrays