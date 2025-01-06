
# Sherlock-Holmes

### 🔎 Sherlock Holmes website  

![Zrzut ekranu 2025-01-06 170934](https://github.com/user-attachments/assets/10d90a71-7080-4a9a-918f-342f7e3918ac)

> Strona internetowa *„Consulting Detective”* to wizytówka stylizowana na usługi Sherlocka Holmesa. Prezentuje się jako **interaktywna i responsywna**, z sekcjami o autorze, jego sprawach, formularzem zgłoszeniowym, cennikiem usług oraz kontaktami. **Nagłówek zawiera nawigację**, prowadzącą do kluczowych części: „O mnie”, „Sprawy”, „Zgłoś sprawę”, „Cennik” i „Kontakt”. Znajdziemy tu również opis postaci Sherlocka, wybrane rozwiązane sprawy z krótkimi notkami i zdjęciami, a także cennik prezentujący trzy typy zleceń o różnym poziomie skomplikowania. Strona jest bogata w detale, takie jak ikonki mediów społecznościowych i formularz kontaktowy. Styl graficzny jest prosty, przejrzysty, z użyciem CSS i czcionek Font Awesome.

### Flex Box

Ta Css'owa funkcjonalność pozwala nam na rozmieszczenie elementów w danym kontenerze

```
    display: flex;
    flex-direction: column;
    justify-content: center;
```

### Media Query

Z bardziej zaawansowanych technologi w projekcie zastosowane są media Query, które pozwalają na responsywność strony. Mówiąc prościej strona dostosowuje się do wielkości ekranu urzytkownika. 


```
/*---------------- Media Query ----------------*/


/*1000px*/

@media screen and (max-width: 1000px) {
    .WhoAmI_top {
        flex-direction: column;
    }

    .WhoAmI_top_picture {
        display: flex;
        justify-content: center;
        width: 100%;
        margin-bottom: 30px;
        margin-left: 0;
        margin-right: 0;
    }

    .WhoAmI_top_discription {
        justify-content: center;
        width: 100%;
    }
}

```
