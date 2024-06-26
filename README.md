# Základy blockchain technologie a kryptoměn
## Co je to blockchain?
### Základní představení blockchainu
Blockchain je decentralizovaný distribuovaný systém, který pomocí řetězů bloků uchovává informace. Bloky obsahují data, která jsou zabezpečeny pomocí kryptografie a vytvářejí tak neprůstřelné řetězce. Změna v jednom bloku vyžaduje kompletní úpravu všech předchozích bloků, což je pro jendotlivého uživatele statisticky nemožné, protože by člověk musel mít početní sílu v hodnotě 51% všech těžičů, tak aby mohl všechny bloky podvrhnout a systém je tak velmi bezpečný. V případě existence více větví s blokama se věří vždy větvi, která je nejdelší, protože na ní pracujou všichni těžiči najednou a je tak právě ta nejdelší větev ta správná.

### Vznik a historie blockchainu
První blockchain vznikl v roce 2009, kdy ho vytvořila osoba společně s kryptoměnou bitcoin osoba, či tým pod jménem, či pseudonymem Satoshi Nakamoto, který jej implementoval jako veřejnou knihu pro zapisování jednotlivých transakcí pro bitcoin.

## Podrobnější vysvětlení blockchainu
![image](https://github.com/aski94/Zaklady-blockchain-technologie-a-kryptomen/assets/114053450/043d8463-1006-4565-92f6-00f9240e76ab)
### 1. Transakce
Uživatel vytvoří transakci, které se společně s dalšíma transakcema spojí do unikátního bloku, který musí obsahovat i hash předchozího blocku, tak aby tvořil řetězec bloků.
### 2. Rozesílání
Hotový blok rozešle peer-to-peer připojením jednotlivým uživatelům v síti a věří se řetězci, který je ze všech nejdelší, kvůli náročnosti na jeho výpočet.
### 3. Odměna
Těžič který blok vyrobí, neboli vytěží dostane odměnu za jeho vykonanou činost, aby měl motivaci pokračovat. V případě bitcoinu se jedná o odměnu bitcoinem, což je důvod proč se těží.
### 4. Uskutečnění transakce
Jakmile je blok s transakcí vytvořený, tak je transakce ukončena. Jistota, že je blok a transakce pravdivá je až poté, co je na něj navázáno pár dalších blocků a s každým dalším blockem je jistejší, že je pravdivý kvůli výpočetní složitosti na vytvoření bloku.

![image](https://github.com/aski94/Zaklady-blockchain-technologie-a-kryptomen/assets/114053450/d7f49962-4109-4ae1-a09d-bfd2baa72a9f)
ukázka dočasného forku neboli více větví najednou, který skončí jakmile je hlavní větev delší a začne se věřit jí

## Obsah bloků
![image](https://github.com/aski94/Zaklady-blockchain-technologie-a-kryptomen/assets/114053450/1088ad6d-37b9-4969-bc6d-62e2f0f45a82)
### Data
Data, které jsou uvnitř bloku obsahují jednotlivé transakce, kdo komu kryptoměnu poslal a v kolik hodin a jaké množství. 
### Hash předdchozího bloku
Blok obsahuje hash z předchozího bloku, aby na sebe navazovaly a tvořily tak řetěz.
### Timestamp
Časový údaj vytvoření bloku, aby bylo vidět jaké bloky jsou vytvořené časově po sobě a jak dlouho je trvalo vytěžit.
### Merkle tree
Strom ve kterém jsou zahashované, spojené a opět zahashované všechny informace dohromady, dokud nezbyde pouze jeden hash,
toto se dělá kvůli zvýšení integritě dat a take zmenšení objemu dat.
### Nonce
Nonce je unikátní číslo, které těžař musí vztvořit z hashe daného bloku tak, aby mělo určitý počet nul na začátku tento proces se jmenuje proof-of-work a s každou vykonanou prací dostane těžař určitý počet bitcoinu. Proces se sám upravuje tak, aby vytěžení jednoho bloku s rostoucím výkonem počítáčů a počtu těžářů vždy trvalo okolo 10 minut.

![image](https://github.com/aski94/Zaklady-blockchain-technologie-a-kryptomen/assets/114053450/0c0a35bf-8cc0-4285-b168-0ecd69660f1e)
ukazka hashovani bloku 

## Kryptoměny
### Co jsou to kryptoměny
Kryptoměny jsou digitální měny, které využívají kryptografii pro zabezpečení transakcí. Kryptoměny jsou decentralizované a většnou vuyžívají technologi právě blockchainu.

### Historie kryptoměn
První a zárověn nejznámější kryptoměnou je bitcoin, který vznikl v roce 2009. Stvořil ho již zmiňovaný Satoshi Nakamoto společně s blockchainem, jenž bitcoin využíval.

### Získávání kryptoměn
Kryptoměny se ve většině případech získávají pomocí těžení, což je úspěšné vytvoření jednoho bloku, který se naváže na řetěz, pomocí velké početní síly.

## Výhody kryptoměn
Mezi výhody patří rychlé a levné transakce, zatímco nevýhody zahrnují nestabilitu hodnoty a obavy o bezpečnost.

### Decentralizace
Decentralizace kryptoměn eliminuje potřebu centrální autority, což zaručuje, že kryptoměna jen tak ze dne na den neskončí či neskrachuje, jelikožož ji nevlastní konkrétní banka či stát.

### Anonymita
Kryptoměny poskytují vysokou úrověn anonymity jednotlivých transakcí, což může být přitažlivé kvůli zabezpečení citlivých údajů.

### Rychlé a nezpoplatněné platby
Transakce kryptoměn jsou obvykle rychlé a s minimálními nebo žádnými poplatky.

## Nevýhody kryptoměn
### Zneužití
Kryptoměny mohou být zneužity pro nelegální aktivity kvůli své anonymitě.

### Vysoká volitalita
Hodnota kryptoměn může dramaticky kolísat a růst, což je pro platidla obecně nevhodná vlastnost.
