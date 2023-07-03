# Wat is markdown?
 * Markdown is een eenvoudige opmaaktaal gecreëerd door John Gruber in 2004
 * Eenvoudig te lezen en schrijven in een gewone text editor
 * Gemakkelijk omzetbaar naar **HTML**, en dus handig om te gebruiken bij het opmaken van tekst voor websites

# Waarom markdown?
* Elimineert HTML-tags
* Gemakkelijke opmaak (Vet, cursief, hoofdingen en lijsten)
* Eenvoudige omzetting van tekst naar HTML om zo op een eenvoudige manier inhoud te maken voor het WWW.

# Syntax
## 1. Hoofdingen 
Met 1 of meerdere `#` kan je verschillende hoofdingen maken zoals in het onderstaande voorbeeld:

```Markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6


## 2. Lijnen

Met 3 of meer underscores creëer je een lijn:

```markdown
___
```
___

## 3. Paragrafen

Met 1 of meerdere blanco lijnen kan je een tekst opsplitsen in paragrafen. Het maakt niet uit hoeveel blanco lijnen je gebruikt, bij de omzetting naar HTML zal dit altijd resulteren in 1 enkele blanco lijn

```
Dit resulteert in slechts 1 blanco lijn 



```
Dit resulteert in slechts 1 blanco lijn



```
Dit is een lijn met een enter
maar dit resulteert niet in een enter in HTML. Wil je toch een nieuwe lijn bij het begin van een zin, dan moet je 2 spaties en een shift+enter gebruiken.  
Dan zal je wel op een nieuwe lijn beginnen.
```

Dit is een lijn met een enter
maar dit resulteert niet in een enter in HTML. Wil je toch een nieuwe lijn bij het begin van een zin, dan moet je 2 spaties en een shift+enter gebruiken.  
Dan zal je wel op een nieuwe lijn beginnen.

## 4. Quotes
Om een quote te maken in een tekstblok gebruik je een of meerdere >

```markdown
In deze tekst staat een quote:
> Dit is een quote
>> En dit is een quote in een quote

Je kan quotes dus nesten
```
In deze tekst staat een quote:
> Dit is een quote
>> En dit is een quote in een quote

Je kan quotes dus nesten

## 5. Accentueringen in een tekst

```
**Deze tekst is vet**
*Deze tekst is cursief*
_Net zoals deze_
```
**Deze tekst is vet**  
*Deze tekst is cursief*  
_Net zoals deze_

## 6. Lijsten
### Ongenummerde lijsten

```
* dit is een lijstitem
+ en dit ook
    * Dit is een genest lijstitem
        + Dit ook
```
* dit is een lijstitem
+ en dit ook
    * Dit is een genest lijstitem
        + Dit ook

### Genummerde lijsten

```
Dit is een genummerde lijst:
1. item
2. item
3. item
```
Dit is een genummerde lijst:
1. item
2. item
3. item

crap