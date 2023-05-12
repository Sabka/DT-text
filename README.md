#  Diplomová práca - Čiastočne riadené učenie hlbokých neurónových sietí

## Základné info:
Autor: Sabína Samporová
Vedúci: RNDr. Kristína Malinovská PhD.

## Anotácia:
Hlboké neurónové siete sú v súčasnosti pravdepodobne najpoužívanejšími
a najskúmanejšími modelmi v strojovom učení s aplikáciami v mnohých
rôznych oblastiach. Trénovanie takýchto modelov si však vyžaduje množstvo
adekvátne označených trénovacích dát, ale zvyčajne je dobre označených dát
z reálneho sveta málo. Paradigma semi-supervised learning (čiastočne riadené
učenie) rieši tento problém prostredníctvom rôznych techník, ktoré sú zvyčajne
založené na vyjadrení a vyhodnotení vzdialenosti medzi príznakovými vektormi
(embeddings) označených a neoznačených trénovacích dát a učenie je založené
na miere ich podobnosti. Príkladom tohto prístupu je trieda modelov hlbokých
neurónových sietí založených na takzvanom Mean Teacher model.

## Ciele:
- Preskúmajte existujúce modely v rámci čiastočne riadeného učenia na kategorizáciu so zameraním na model Mean Teacher (MT).
 
- Urobte prehľad súčasného stavu problematiky a navrhnite a implementujte nový model ako vylepšenie MT modelu. 

- Implementujte a vyhodnoťte experimenty s vybraným benchmark datasetom a porovnajte nový model s existujúcimi.

## Úlohy
- [x] **Zimný semester** - zoznámenie so semisup. modelmi, zameranie sa na BMT, rozlišovanie živých a neživých objektov s použitím BMT
- [x] **LS 1. týždeň** - refaktorovanie BMT a fixovanie drobností
- [x] **LS 2. týždeň** - vymýšľanie spôsobu zapojenia SOM do učenia MT 
- [x] **LS 3. týždeň** - vizualizácia embeddingov pomocou tsne
- [x] **LS 4. týždeň** - príprava GPU servera - vytvorenie cuda environmentu, rozbehanie Tarvainenovho kódu
- [x] **LS 5. týždeň** - reprodukovanie baseline výsledkov Tarvainena
- [x] **LS 6. týždeň** - odvodenie vzorcov pre počítanie SOM loss
- [x] **LS 8. týždeň** - implementácia a zapojenie SOM do trénovania
- [x] **LS 9. týždeň** - náhrada implementácie SOM za takú, ktorá používa GPU
- [x] **LS 10. týždeň** - zmena architektúry na Sarmadovu
- [x] **LS 11. týždeň** - písanie článku + vizualizácia natrénovanej SOM
- [ ] nájsť vhodné hyperparametre pre MT model
- [ ] nájsť vhodné hyperparametre SOM modelu
- [ ] vyskúšanie inej modifikovácie pravidla pre počítanie SOM loss
- [ ] experimentovanie s iným datasetom alebo inými formami samoorganizácie

## Kód
- [BMT repo](github.com/Sabka/DT-mean-teacher)
- [MT repo](github.com/Sabka/DT-MT)
