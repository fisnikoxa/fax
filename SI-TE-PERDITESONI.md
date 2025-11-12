# Si të Përditësoni Repository-n

## Çdo herë që bëni ndryshime në skedarë:

### 1️⃣ Shikoni statusin (opsionale)
```bash
cd /Users/oxa/Desktop/fax
git status
```

### 2️⃣ Shtoni skedarët e ndryshuar
```bash
git add .
```
*(Ose shtoni vetëm skedarë specifik: `git add Matematik/matematik-solutions.html`)*

### 3️⃣ Bëni commit me një përshkrim
```bash
git commit -m "Përshkrimi i ndryshimit, p.sh: Shtova zgjidhjen e Detyres 6"
```

### 4️⃣ Ngarkoni në GitHub
```bash
git push
```

## ⚡ Shkurtore (një komandë):

```bash
cd /Users/oxa/Desktop/fax && git add . && git commit -m "Update: përshkrimi këtu" && git push
```

## 📝 Shembuj:

**Kur shtoni zgjidhje të reja:**
```bash
git add Matematik/matematik-solutions.html
git commit -m "Shtova zgjidhjet e Detyrave 6-10"
git push
```

**Kur shtoni skedarë të rinj:**
```bash
git add .
git commit -m "Shtova materiale të reja për Fizikën"
git push
```

**Kur korrigjoni gabime:**
```bash
git add .
git commit -m "Korrigjova gabime në Detyren 5"
git push
```

## 🔍 Komanda të Dobishme:

- `git status` - Shiko çfarë ka ndryshuar
- `git log` - Shiko historinë e commit-eve
- `git diff` - Shiko ndryshimet e bëra
- `git pull` - Merr ndryshime nga GitHub (nëse punoni nga kompjutera të ndryshëm)

## ⚠️ Nëse gaboni:

**Të zhbësh ndryshime të pa-commit-uara:**
```bash
git restore <file-name>
```

**Të zhbësh commit-in e fundit (por mbaj ndryshimet):**
```bash
git reset --soft HEAD~1
```

---

*Këshillë: Bëni commit shpesh me përshkrime të qarta!*

