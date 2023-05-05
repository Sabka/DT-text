#  Diplomová práca - Čiastočne riadené učenie hlbokých neurónových sietí

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
