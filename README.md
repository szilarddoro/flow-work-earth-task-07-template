# 7. feladat

> A feladatok megoldása során két fős csapatokban dolgozzatok! Jelöljetek ki egymás között egy csapatkapitányt. Az ő repoját fogjátok majd használni a feladat megoldása során.
>
> Fontos, hogy akkor is segítsétek egymást, amikor éppen csak az egyik csapattagnak vannak lépései! A csapat csak akkor tud sikeres lenni, ha mindenki érti, hogy mit csinál, és miért csinálja azt.

## Csapatkapitány feladatai

1. Hozz létre egy repositoryt a GitHub-on a saját felhasználód alá, aminek a neve `flow-work-earth-task-07` legyen.
2. Hívd meg a csapattársadat a repositoryhoz a GitHub-on a repo főoldalán található "Invite collaborators" gombbal.
3. Klónozd le a létrehozott repositoryt a `~/flow/git` mappán belülre a `task-07` mappába. (`git clone <url> task-07`)
4. Változtasd meg az `origin` URL-jét, hogy az legyen, amit az 1. lépésben létrehoztál. (`git remote set-url origin <url>`)
5. Pushold fel az aktuális tartalmat a GitHub-ra. (`git push -u origin main`)

## A csapattárs feladatai

1. Fogadd el a meghívást a GitHub-on a csapatkapitányodtól.
2. Klónozd le a csapatkapitányod repositoryját a `~/flow/git` mappán belülre a `task-07` mappába. (`git clone <url> task-07`)

## Mindkét fél feladatai

1. Hozzatok létre egy-egy branchet a `main` branchből a saját nevetekkel. (`git branch <name>`)
2. Váltsatok a saját branchetekre. (`git checkout <name>`)

A `rendelesek.md` fájlban láttok egy szekciót, ahol az egyes termékekből vásárolt mennyiségeknek kell szerepelnie.

Az alábbi feladatokat osszátok ki egymás között:

- A csapat egyik tagjának a feladata az, hogy az első és második termék azonosítóját a termék neve elé, illetve a harmadik és negyedik termék mennyiségét a termék neve mögé beírja.
- A másik csapattagnak a feladata az, hogy a harmadik és negyedik termék azonosítóját a termék neve elé, illetve az első és második termék mennyiségét a termék neve mögé beírja.

### Példa

```md
| Rendelés azonosítója | Termék azonosítója | Mennyiség (kg) |
| -------------------- | ------------------ | -------------- |
| 1                    | 1                  | 15             |
| 2                    | 4                  | 5              |
| 3                    | 2                  | 20             |
| 4                    | 3                  | 10             |

## Vásárolt mennyiség

1 - Alma: 15 kg
2 - Brokkoli: 20 kg
3 - Narancs: 10 kg
4 - Paradicsom: 5 kg
```
