# Lokaskýrsla: HiDef Textíll - Tæknivæddar prjónavélar

## Innihald verkefnis

Þetta skjalasafn inniheldur gögn og kóða fyrir lokaskýrslu verkefnisins *HiDef Textíll: Tæknivæddar
prjónavélar*. Markmið verkefnisins var að þróa og útfæra tæknilausnir fyrir prjónavélar sem bæta
framleiðsluferli og auka möguleika á sjálfvirkni í textílframleiðslu.

*HiDef Textíll: Tæknivæddar prjónavélar* verkefnið snýst um að sameina hefðbundna
textílvinnslu og nútímatækni með nýsköpun í gömlum prjónavélum frá 10. áratugnum. Með því að
snjallvæða úrelda prjónavél með netsamskiptum og frjálsum hugbúnaði verður til tól sem hentar
skapandi starfi nútímans, en jafnframt stuðlar að sjálfbærni. Verkefnið er þverfaglegt og felur í
sér þátttöku nemenda úr vélaverkfræði, hagnýttri stærðfræði og fatahönnun, sem fá tækifæri til að
vinna saman að þróun tækjalausna, verkefnastjórnun og frumgerðasmíði. Markmiðið var að hanna
starfshæfa prjónavél sem hægt verður að kynna á ráðstefnum eins og Vísindavöku Rannís, UTmessunni og
Hönnunarmars.
Verkefnið stuðlar að aukinni þátttöku í STEAM menntun, þar sem listir og tækni mætast á nýstárlegan
hátt, og varðveitir um leið menningararf í nútímasamhengi.

### Höfundar

Elías Lúðvíksson, Guðrún Ísafold Hilmarsdóttir og Snæfríður Ebba Ásgeirsdóttir

Ábyrgðaraðili: Helga Ingimundardóttir

---

## Uppbygging skjalasafns

- **`NSN-report.pdf`**: Fullunnin lokaskýrsla verkefnisins á PDF formi.
- **`NSN-signed.pdf`**: Undirrituð útgáfa af lokaskýrslunni.
- **`README.md`**: Þessi leiðbeiningarskrá með yfirliti yfir verkefnið.
- **`main.tex`**: Aðalskjal fyrir lokaskýrsluna skrifað í LaTeX.
- **`myndir/`**: Myndir sem notaðar eru í skýrslunni.
- **`prjon_honnunarvinna.tex`**: Kafli í skýrslunni sem lýsir hönnunarvinnu tengdri prjóni.
- **`references.bib`**: Heimildaskrá í BibTeX sniði.
- **`sjalfvirk_mynsturgerd.tex`**: Kafli í skýrslunni sem fjallar um sjálfvirka mynstragerð.
- **`velbunadur.tex`**: Kafli í skýrslunni sem fjallar um vélbúnað verkefnisins.

---

## Hugbúnaður verkefnisins

Vitnað er í eftirfarandi GitHub geymslur í skýrslunni:

- **Sjónabók**: Repo fyrir sniðmát og myndgreiningu á prjónamynstrum.
  [HiDefTextiles/Sjonabok](https://github.com/HiDefTextiles/Sjonabok)

- **Mynsturgerð**: Repo fyrir föll og reiknirit sem styðja við munsturgerð.  
  [HiDefTextiles/mynsturgerd](https://github.com/HiDefTextiles/mynsturgerd)

- **PassAPI**: Repo fyrir kóða sem sér um stýringu prjónavélarinnar.  
  [HiDefTextiles/passAPI](https://github.com/HiDefTextiles/passAPI)

- **PassapNext**: Repo fyrir opið vefviðmót tengt verkefninu.  
  [tungufoss/passapnext](https://github.com/tungufoss/passapnext)

---

## Hvernig á að vinna með skýrsluna

### Kröfur

Til að vinna með LaTeX skjölin þarftu:

- Uppsett LaTeX kerfi (t.d. [TeX Live](https://www.tug.org/texlive/)
  eða [Overleaf](https://www.overleaf.com/)).
- Ritstjóra sem styður LaTeX, t.d. [TeXShop](http://pages.uoregon.edu/koch/texshop/)
  eða [VS Code](https://code.visualstudio.com/) með LaTeX viðbótum.

### Samantekt

1. Opnaðu `main.tex` í LaTeX-ritstjóra.
2. Gakktu úr skugga um að allar skrár, t.d. myndir í `myndir/` og heimildir í `references.bib`, séu
   tiltækar.
3. Keyrðu LaTeX til að búa til PDF skýrslu.

### Skýrslugerð

Til að endurnýja PDF útgáfuna:
  ```bash
  latexmk -pdf main.tex && mv main.pdf NSN-report.pdf   
  ```

---

## Tengiliðir

Ef spurningar vakna um efni eða framsetningu skýrslunnar, vinsamlegast hafið samband við:

**Helga Ingimundardóttir** (verkefnastjóri *HiDef Textíll*), lektor við iðnaðarverkfræðideild
Háskóla Íslands, sjá: [hi.is/starfsfolk/helgaingim](https://hi.is/starfsfolk/helgaingim).  
