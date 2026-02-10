# Jak prispet do Hrasek Knowledge Base

Tento repozitar slouzi jako znalostni baze pro bota **Hrasek** na Discord serveru Mendelu. Hrasek z techto dat cerpa pri odpovidani na otazky studentu.

## Format souboru `knowledge.md`

Soubor pouziva jednoduchy format - kazde tema zacina nadpisem `#` a pod nim je odpoved:

```md
# Otazka nebo tema
Odpoved na otazku. Strucne, vecne, cesky.
```

### Priklad

```md
# Jak se pripojit na eduroam
Pripojis se pres 802.1x. Login je xlogin@mendelu.cz, heslo stejne jako do UISu.
Na Androidu zvol EAP metodu PEAP a fazi 2 MSCHAPV2.

# Kde vyzvednout ISIC
ISIC kartu si vyzvednes na studijnim oddeleni po zapisu do studia.
```

## Pravidla pro prispivani

1. **Jeden nadpis = jedno tema.** Nepis vic temat pod jeden nadpis.
2. **Strucne.** Odpoved by mela mit max ~200 slov. Pis jen to podstatne.
3. **Cesky a vecne.** Zadne nazory, vtipy ani osobni zkusenosti - jen fakta.
4. **Aktualni informace.** Pokud vis, ze se neco zmenilo, uprav existujici zaznam misto pridani noveho.
5. **Zadne osobni udaje.** Jmena ucitelu jsou ok, ale nepis telefony, emaily ani jine kontaktni udaje.
6. **Zadne duplicity.** Pred pridanim zkontroluj, jestli tema uz neexistuje.

## Jak prispet

1. Forkni tento repozitar
2. Uprav soubor `knowledge.md`
3. Vytvor Pull Request s kratkym popisem co jsi pridal/zmenil
4. Pockej na schvaleni od maintainera

## Co sem patri

- Informace o studiu (zapis, rozvrh, kredity, harmonogram)
- Sluzby (eduroam, UIS, ISIC, menza, knihovna)
- Koleje a ubytovani
- Erasmus a praxe
- Stipendia
- Casto kladene otazky novacku

## Co sem nepatri

- Nazory na ucitele nebo predmety
- Neoverene informace a drby
- Obsah nesouvisejici s Mendelu
- Komercni obsah nebo reklama
