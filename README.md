# 🎲 Naključna naključna hoja

**Zaključna naloga iz predmeta Matematična fizika (VSŠ, 2024/2025)**

---

## 🚀 Projektna predstavitev

Ta repozitorij vsebuje rešitev naloge **15. Naključna naključna hoja**, kjer modeliramo gibanje delca na eno‑dimenzionalni mreži z od mesta odvisnimi verjetnostmi skoki.

> **Navodila naloge:**
> Delec skače na 1d mreži, pri čemer je verjetnost za skok iz *j*-tega mesta na mesto *j + 1* enaka *p<sub>j</sub>*, za skok na levo pa *1 − p<sub>j</sub>*. Verjetnosti *p<sub>j</sub>* so naključne spremenljivke, porazdeljene po taki porazdelitvi, da velja
> $\mathbb{E}[\log p_j/(1-p_j)] = 0$.

---

## 📂 Struktura repozitorija

```text
mafija_zakljucna/
├── docs/          # poročilo
├── data/          # podatki in skripte za simulacijo
├── .gitignore
└── README.md
```

## 🛠️ Zahteve

* 💾 TeX distribucija (npr. TeX Live, MiKTeX)
* 🛠️ `latexmk` ali `pdflatex`
* 📊 Jupyter Lab/Notebook za interaktivni razvoj

---

## ⚡ Hitri zagon

1. **Kloniraj** repozitorij:

   ```bash
   git clone https://github.com/VAŠ_UPORABNIK/mafija_zakljucna.git
   cd mafija_zakljucna
   ```
2. **Oglej si simulacijo** (Jupyter notebook):

   * Lokalno: odpri `data/mafija_zakljucna.ipynb` v Jupyter Lab/Notebook.
   * Spletno: [![nbviewer](https://img.shields.io/badge/view-nbviewer-orange)](https://nbviewer.org/github/gasperharej/mafija_zakljucna_naloga/blob/main/data/mafija_zakljucna.ipynb)
3. **Prevedi poročilo** (LaTeX):

   ```bash
   cd docs
   latexmk -pdf report.tex
   ```
4. **Preglej rezultat** v `docs/report.pdf`.

---


## 🤝 Prispevanje

Prispevajte z idejami, popravki ali izboljšavami preko **Pull Requestov**.

---

## 📄 Licenca

Projekt je na voljo pod MIT licenco. Več v datoteki `LICENSE`.





