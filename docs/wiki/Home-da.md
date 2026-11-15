[English](Home) · **Dansk** · [Bahasa Melayu](Home-ms)

# Caesar Cipher

En begyndervenlig Cæsar-chiffer til terminalen, der både krypterer og dekrypterer.

## Hvad er det?

Dag 8 af Udemy-kurset *100 Days of Code: The Complete Python Pro Bootcamp*. Programmet forskyder hvert bogstav i en besked et fast antal pladser (med en forskydning på 3 bliver `E` til `H`) og kan også vende forskydningen om. Det finder bogstavernes placering med `list.index` og går rundt i alfabetet med modulo-operatoren.

## Hvad øvelsen lærer dig

- At skrive funktioner med parametre og returværdier
- At finde placeringer i en liste og gå rundt med modulo-operatoren
- At bruge én funktion til både kryptering og dekryptering
- At skrive små automatiske tests

## Hvad det gør

- Kryptér eller dekryptér så mange beskeder, du vil, i én session
- Enhver forskydning, også negative og større end 26
- Store og små bogstaver bevares, og tegn der ikke er bogstaver, ændres ikke
- Kontrol af input: en venlig besked ved en ukendt retning eller en forskydning, der ikke er et helt tal

## Videre

- [Kom godt i gang](Getting-Started-da)
- [Projektdokumenter](Project-Documents-da)
