

### 1. Vektorji v $\mathbb{R}^2$ in $\mathbb{R}^3$

Vektor v prostoru $\mathbb{R}^n$ je **urejena $n$-terica števil**, ki jo lahko zapišemo kot vrstično ali stolpično matriko, pri čemer števila v njej imenujemo koordinate ali komponente vektorja. Geometrijsko si vektor v **$\mathbb{R}^2$** predstavljamo kot **usmerjeno daljico** v ravnini z začetkom v izhodišču $O(0,0)$ in koncem v točki $T(x_0, y_0)$, v **$\mathbb{R}^3$** pa kot usmerjeno daljico v prostoru s koncem v točki $T(x_0, y_0, z_0)$. Takšnemu vektorju pravimo **krajevni vektor** točke $T$. Dolžina vektorja $\vec{x}$ je določena s Pitagorovo formulo kot $|\vec{x}| = \sqrt{x_0^2 + y_0^2}$ v $\mathbb{R}^2$ oziroma $|\vec{x}| = \sqrt{x_0^2 + y_0^2 + z_0^2}$ v $\mathbb{R}^3$.

### 2. Seštevanje vektorjev in množenje vektorja s skalarjem

Operacije nad vektorji vključujejo:

- **Množenje s skalarjem (realnim številom $\lambda$):** Geometrijsko ta operacija predstavlja **razteg** ($\lambda \ge 1$), **skrčitev** ($0 \le \lambda \le 1$) ali kombinacijo obojega z **zrcaljenjem** ($\lambda < 0$).
- **Seštevanje vektorjev:** Dva vektorja seštejemo (ali odštejemo) s pomočjo **paralelogramskega pravila**.
- **Lastnosti:** Seštevanje je komutativno ($x + y = y + x$) in asociativno ($x + (y + z) = (x + y) + z$), množenje s skalarjem pa je distributivno glede na seštevanje vektorjev in glede na seštevanje skalarjev.

### 3. Skalarni produkt vektorjev in uporaba

Skalarni produkt je operacija, ki dvema realnima vektorjema priredi **skalar** (realno število) po formuli $\vec{a} \cdot \vec{b} = a_1b_1 + a_2b_2 + a_3b_3$. **Uporaba skalarnega produkta:**

- **Dolžina vektorja:** Izračunamo jo kot koren skalarnega produkta vektorja s samim seboj: $|\vec{a}| = \sqrt{\vec{a} \cdot \vec{a}}$.
- **Pravokotnost:** Neničelna vektorja sta pravokotna natanko tedaj, ko je njun skalarni produkt enak nič ($\vec{a} \perp \vec{b} \iff \vec{a} \cdot \vec{b} = 0$).
- **Kot med vektorjema:** Kot $\varphi$ med neničelnima vektorjema določa zveza $\vec{a} \cdot \vec{b} = |\vec{a}| \cdot | \vec{b} | \cos \varphi$.
- **Razdalje:** Uporablja se pri izračunu razdalje točke od ravnine.

### 4. Vektorski produkt vektorjev in uporaba

Vektorski produkt je operacija, ki dvema vektorjema v $\mathbb{R}^3$ priredi **nov vektor** v $\mathbb{R}^3$. Izračunamo ga s pomočjo determinante, kjer v prvi vrstici nastopajo bazni vektorji $\vec{i}, \vec{j}, \vec{k}$. Vektorski produkt je definiran **izključno v prostoru $\mathbb{R}^3$**. **Uporaba vektorskega produkta:**

- **Ploščina:** Dolžina vektorskega produkta $|\vec{a} \times \vec{b}|$ je enaka ploščini paralelograma, ki ga določata vektorja $\vec{a}$ in $\vec{b}$.
- **Vzporednost:** Neničelna vektorja sta vzporedna natanko tedaj, ko je njun vektorski produkt enak ničelnemu vektorju ($\vec{a} \parallel \vec{b} \iff \vec{a} \times \vec{b} = \vec{0}$).
- **Razdalje:** Uporablja se za izračun razdalje točke od premice in razdalje med vzporednima premicama.

### 5. Geometrijska definicija vektorskega produkta

Geometrijsko vektorski produkt $\vec{a} \times \vec{b}$ določajo tri lastnosti:

1. **Smer:** Vektor $\vec{a} \times \vec{b}$ je **pravokoten na oba** začetna vektorja, torej $(\vec{a} \times \vec{b}) \perp \vec{a}$ in $(\vec{a} \times \vec{b}) \perp \vec{b}$.
2. **Orientacija:** Smer je določena s **pravilom desnega vijaka**; če vijak zavrtimo od $\vec{a}$ proti $\vec{b}$ po najkrajši poti, se premakne v smeri produkta.
3. **Dolžina (velikost):** Dolžina produkta ustreza ploščini paralelograma, ki ga vektorja določata, in je podana z $|\vec{a} \times \vec{b}| = |\vec{a}| \cdot | \vec{b} | \cdot \sin \varphi$, kjer je $\varphi$ kot med vektorjema.




### 6. Mešani produkt vektorjev in uporaba

**Mešani produkt** je operacija, ki trem realnim vektorjem v $\mathbb{R}^3$ priredi **skalar** (realno število). Definiran je kot skalarni produkt prvega vektorja z vektorskim produktom drugih dveh: $(\vec{a}, \vec{b}, \vec{c}) = \vec{a} \cdot (\vec{b} \times \vec{c})$. Izračunamo ga lahko z **determinanto** matrike, v kateri so vektorji zapisani kot vrstice.

**Uporaba mešanega produkta:**

- **Prostornina:** Absolutna vrednost mešanega produkta $|(\vec{a}, \vec{b}, \vec{c})|$ je enaka **prostornini paralelepipeda**, ki ga določajo ti trije vektorji.
- **Razdalja med premicami:** Uporablja se pri izračunu razdalje med **nevzporednima premicama** v prostoru, kjer volumen paralelepipeda (izražen z mešanim produktom) delimo s ploščino osnovne ploskve.

### 7. Dolžina vektorja

Dolžina vektorja $\vec{x}$ predstavlja **oddaljenost točke** od koordinatnega izhodišča. Izračunamo jo po naslednjih formulah:

- V **$\mathbb{R}^2$**: $|\vec{x}| = \sqrt{x_0^2 + y_0^2}$.
- V **$\mathbb{R}^3$**: $|\vec{x}| = \sqrt{x_0^2 + y_0^2 + z_0^2}$.
- S pomočjo **skalarnega produkta**: Dolžina je kvadratni koren skalarnega produkta vektorja s samim seboj, torej $|\vec{a}| = \sqrt{\vec{a} \cdot \vec{a}}$.

### 8. Koti med vektorji

Kot $\varphi$ med dvema neničelnima vektorjema lahko določimo na dva načina:

- Preko **skalarnega produkta**: $\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cos \varphi$, kar omogoča izračun kosinusa kota.
- Preko **vektorskega produkta**: Dolžina vektorskega produkta je povezana s sinusom kota: $|\vec{a} \times \vec{b}| = |\vec{a}| \cdot |\vec{b}| \sin \varphi$.

### 9. Pravokotnost in vzporednost vektorjev

- **Pravokotnost ($\vec{a} \perp \vec{b}$):** Neničelna vektorja sta pravokotna natanko tedaj, ko je njun **skalarni produkt enak nič** ($\vec{a} \cdot \vec{b} = 0$).
- **Vzporednost ($\vec{a} \parallel \vec{b}$):** Neničelna vektorja sta vzporedna natanko tedaj, ko je njun **vektorski produkt enak ničelnemu vektorju** ($\vec{a} \times \vec{b} = \vec{0}$).

### 10. Koplanarnost vektorjev

Vektorji so **koplanarni**, če **ležijo na isti ravnini**. Geometrijsko to pomeni, da so linearno odvisni. Koplanarnost treh vektorjev v prostoru preverimo z **mešanim produktom**:

- Vektorji $\vec{a}, \vec{b}$ in $\vec{c}$ so koplanarni natanko tedaj, ko je njun **mešani produkt enak nič** ($(\vec{a}, \vec{b}, \vec{c}) = 0$). V tem primeru je prostornina paralelepipeda, ki bi ga tvorili, enaka nič.


### 11. Računanje ploščin geometrijskih likov

Ploščino geometrijskih likov v prostoru $\mathbb{R}^3$ lahko izračunamo s pomočjo **vektorskega produkta**. Dolžina vektorskega produkta dveh vektorjev, $|\vec{a} \times \vec{b}|$, je numerično enaka **ploščini paralelograma**, ki ga ta dva vektorja določata. Če želimo izračunati ploščino trikotnika, ki ga določata ista vektorja, vzamemo polovico te vrednosti, torej $\frac{1}{2}|\vec{a} \times \vec{b}|$.

### 12. Računanje prostornin geometrijskih teles

Prostornino teles v prostoru $\mathbb{R}^3$ (npr. paralelepipeda) izračunamo z uporabo **mešanega produkta**. **Absolutna vrednost mešanega produkta** treh vektorjev, $|(\vec{a}, \vec{b}, \vec{c})|$, je enaka prostornini paralelepipeda, ki ga ti trije vektorji določajo.

### 13. Enačba premice v prostoru (3 oblike)

Premica v prostoru je določena s točko $A(a_1, a_2, a_3)$ na njej in smernim vektorjem $\vec{s} = (s_1, s_2, s_3)$. Poznamo tri glavne oblike zapisa:

- **Vektorska oblika:** $\vec{r} = \vec{r}_A + t \cdot \vec{s}$, kjer je $t \in \mathbb{R}$ parameter.
- **Parametrična oblika:** Sistem treh enačb: $x = a_1 + t \cdot s_1$, $y = a_2 + t \cdot s_2$ in $z = a_3 + t \cdot s_3$.
- **Kanonična oblika:** $\frac{x - a_1}{s_1} = \frac{y - a_2}{s_2} = \frac{z - a_3}{s_3}$, ki jo lahko uporabimo le, če so vse komponente smernega vektorja različne od 0.

### 14. Enačba ravnine v prostoru (3 oblike)

Ravnina je določena s točko $A(a_1, a_2, a_3)$ na njej in normalnim vektorjem $\vec{n} = (n_1, n_2, n_3)$, ki je nanjo pravokoten. Tri oblike zapisa so:

- **Vektorska oblika:** $(\vec{r} - \vec{r}_A) \cdot \vec{n} = 0$.
- **Implicitna ali splošna oblika:** $n_1x + n_2y + n_3z = d$, kjer je skalar $d$ enak skalarnemu produktu $\vec{r}_A \cdot \vec{n}$.
- **Segmentna oblika:** $\frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1$, kjer so $a, b, c$ odseki, ki jih ravnina odreže na koordinatnih oseh (uporabna le, ko je $d \neq 0$).

### 15. Razdalja točke do ravnine

Razdalja točke $P$ od ravnine $\Pi$ (ki je podana z normalo $\vec{n}$ in točko $A$) se izračuna po formuli: $$d(P, \Pi) = \frac{|\vec{r}_P \cdot \vec{n} - \vec{r}_A \cdot \vec{n}|}{|\vec{n}|}$$ Geometrijsko to ustreza dolžini pravokotne projekcije vektorja med točko $A$ in $P$ na normalo ravnine.

### 16. Razdalja točke do premice

Razdalja točke $P$ od premice $q$ (podane s točko $A$ in smernim vektorjem $\vec{s}$) je enaka **višini paralelograma**, ki ga oklepata vektorja $\vec{s}$ in $\vec{AP}$. Izračunamo jo s formulo: $$d(P, q) = \frac{|\vec{AP} \times \vec{s}|}{|\vec{s}|}$$ Ploščino paralelograma (števec) delimo z dolžino osnovnice (imenovalec), da dobimo iskano višino oziroma razdaljo.

### 17. Razdalja med dvema premicama

Razdalja med dvema premicama v prostoru je odvisna od njunega medsebojnega položaja:

- **Vzporedni premici ($p$ in $q$):** Razdalja je enaka razdalji poljubne točke na eni premici od druge premice. Izračunamo jo po formuli $d(p, q) = \frac{|\vec{AB} \times \vec{s}|}{|\vec{s}|}$, kjer sta $A$ in $B$ točki na premicah, $\vec{s}$ pa njun skupni smerni vektor.
- **Nevzporedni (mimobežni) premici:** Razdalja ustreza višini paralelepipeda, ki ga tvorijo smerna vektorja $\vec{s}_1, \vec{s}_2$ in vektor med točkama na premicah $\vec{AB}$. Formula je $d(p, q) = \frac{|(\vec{s}_1, \vec{s}_2, \vec{AB})|}{|\vec{s}_1 \times \vec{s}_2|}$, kjer v števcu nastopa absolutna vrednost mešanega produkta.
- **Sekajoči se premici:** Razdalja med njima je enaka **0**.

### 18. Definicija matrike

**Matrika $A$** dimenzije (reda oz. velikosti) $m \times n$ je **pravokotna shema števil**, ki je sestavljena iz $m$ vrstic in $n$ stolpcev. Števila, ki sestavljajo to shemo, imenujemo **elementi matrike**. Matriko lahko zapišemo z oglatimi ali okroglimi oklepaji, splošni element v $i$-ti vrstici in $j$-tem stolpcu pa označimo z $a_{ij}$.

### 19. Posebne vrste matrik

Viri navajajo več posebnih oblik in vrst matrik:

- **Glede na obliko:** Stolpična matrika (stolpec), vrstična matrika (vrstica) in kvadratna matrika (enako število vrstic in stolpcev).
- **Glede na elemente:** Ničelna matrika (vsi elementi so 0), diagonalna matrika (neničelni elementi le na glavni diagonali) in enotska matrika ali identiteta $I$.
- **Trikotne matrike:** Zgornje-trikotna (vsi elementi pod diagonalo so 0) in spodnje-trikotna (vsi elementi nad diagonalo so 0).
- **Glede na simetrijo:** **Simetrična** ($A = A^T$) in **poševno simetrična** matrika ($A = -A^T$).
- **Glede na obrnljivost:** **Nesingularna** ali obrnljiva matrika (ima inverz, $\det A \neq 0$) in **singularna** matrika (nima inverza, $\det A = 0$).
- **Ortogonalna matrika:** Kvadratna matrika, za katero velja $A \cdot A^T = A^T \cdot A = I$, kar pomeni, da je njen transponat hkrati njen inverz.

### 20. Seštevanje matrik

Matriki lahko seštejemo le, če sta **enakih dimenzij**. Vsoto $A + B$ dobimo tako, da **seštejemo istoležne elemente** obeh matrik, torej $(a_{ij} + b_{ij})$. **Lastnosti seštevanja:**

- Je **komutativno** ($A + B = B + A$) in **asociativno** ($(A + B) + C = A + (B + C)$).
- Obstaja **nevtralni element**, ki je ničelna matrika ($A + 0 = A$).
- Vsaka matrika ima **nasprotni element** $-A$, tako da je $A + (-A) = 0$.

### 21. Množenje matrike s skalarjem

Matriko pomnožimo z realnim številom (skalarjem) $\alpha$ tako, da **vsak element matrike pomnožimo s tem številom**: $\alpha A = (\alpha a_{ij})$. **Lastnosti množenja s skalarjem:**

- Je **distributivno** glede na seštevanje matrik ($\alpha(A + B) = \alpha A + \alpha B$) in glede na seštevanje skalarjev ($(\alpha + \mu)A = \alpha A + \mu A$).
- Velja asociativnost $(\alpha \mu)A = \alpha(\mu A)$.
- Skalar **1** je nevtralni element za to operacijo ($1 \cdot A = A$).


### 22. Transponiranje matrik

Transponiranje matrike pomeni **zamenjavo njenih vrstic s stolpci** oziroma zrcaljenje elementov čez glavno diagonalo. Če je matrika $A$ dimenzije $m \times n$, bo njena transponirana matrika $A^T$ dimenzije $n \times m$. **Lastnosti transponiranja:**

- $(A + B)^T = A^T + B^T$.
- $(\alpha A)^T = \alpha A^T$.
- $(A^T)^T = A$.
- $(A \cdot B)^T = B^T \cdot A^T$ (velja za kvadratni matriki).
- Če velja $A = A^T$, je matrika **simetrična**, če pa $A = -A^T$, je **poševno simetrična**.

### 23. Množenje matrik

Množenje dveh matrik $A \cdot B$ je definirano le, če je **število stolpcev leve matrike enako številu vrstic desne matrike**. Element $c_{ij}$ v rezultati dobimo kot **skalarni produkt** $i$-te vrstice matrike $A$ in $j$-tega stolpca matrike $B$. **Lastnosti množenja:**

- Je **asociativno** $((A \cdot B) \cdot C = A \cdot (B \cdot C))$ in **distributivno** glede na seštevanje.
- V splošnem množenje **ni komutativno** ($A \cdot B \neq B \cdot A$).
- Enotska matrika $I$ služi kot nevtralni element ($A \cdot I = I \cdot A = A$).

### 24. Inverz matrike

Inverzno matriko $A^{-1}$ lahko določimo le za **kvadratne matrike**, zanjo pa mora veljati $A \cdot A^{-1} = A^{-1} \cdot A = I$. Matrika, ki ima inverz, se imenuje **obrnljiva ali nesingularna**, tista, ki ga nima, pa je **singularna**. Matrika je obrnljiva natanko tedaj, ko je njena determinanta različna od nič ($\det A \neq 0$). **Načini izračuna inverza:**

- S pomočjo **matrike kofaktorjev**: $A^{-1} = \frac{1}{\det A} \cdot [C_{ij}]^T$, kjer so $C_{ij}$ predznačene poddeterminante.
- Z **Gaussovo eliminacijo**: Razširjeno matriko $[A|I]$ s vrstičnimi operacijami preoblikujemo v obliko $[I|A^{-1}]$.
- Poseben primer so **ortogonalne matrike**, kjer je inverz kar enak transponirani matriki ($A^T = A^{-1}$).

### 25. Definicija determinante

Determinanta ($\det A$) je **število**, ki ga priredimo kvadratni matriki in ga definiramo **rekurzivno** glede na njeno dimenzijo $n \times n$.

- Za $n=1$ je determinanta kar vrednost elementa $|a_{11}| = a_{11}$.
- Za $n=2$ velja formula $a_{11}a_{22} - a_{12}a_{21}$.
- Za $n=3$ se uporablja **Sarrusovo pravilo**.
- Za $n \ge 4$ (in splošno) se uporablja **razvoj po vrstici ali stolpcu**, kjer nastopajo **poddeterminante (minorji)** in **kofaktorji** (poddeterminante z ustreznim predznakom $(-1)^{i+j}$).




### 26. Razvoj determinante po vrstici/stolpcu

Determinanto kvadratne matrike reda $n \times n$ lahko izračunamo z **razvojem po poljubni vrstici ali stolpcu**. Pri tem postopku uporabljamo:

- **Poddeterminanto ali minor ($\det A_{ij}$):** To je determinanka matrike, ki jo dobimo, če iz prvotne matrike odstranimo $i$-to vrstico in $j$-ti stolpec.
- **Kofaktor:** To je poddeterminanta z ustreznim predznakom, določenim z mestom elementa: $(-1)^{i+j} \det A_{ij}$.
- **Formula za razvoj po 1. vrstici:** $\det A = \sum_{j=1}^{n}(-1)^{1+j}a_{1j} \det A_{1j}$.

### 27. Lastnosti determinant

Viri navajajo naslednje ključne lastnosti za poenostavitev računanja:

1. **Transponiranje:** $\det A = \det A^T$, kar pomeni, da vse lastnosti, ki veljajo za vrstice, veljajo tudi za stolpce.
2. **Zamenjava:** Če v determinanti zamenjamo dve vrstici ali stolpca, determinanta **spremeni predznak**.
3. **Vrednost 0:** Determinanta je enaka 0, če je kakšna vrstica/stolpec povsem ničeln, če sta dve vrstici/stolpca enaka ali če je ena vrstica/stolpec **večkratnik** druge.
4. **Izpostavljanje:** Skupni faktor ene vrstice ali stolpca lahko izpostavimo pred determinanto.
5. **Množenje s skalarjem:** $\det(\lambda A) = \lambda^n \det A$.
6. **Vrstične operacije:** Vrednost se ne spremeni, če vrstici prištejemo večkratnik druge vrstice.
7. **Trikotne matrike:** Determinanta zgornje ali spodnje trikotne matrike je enaka **produktu diagonalnih elementov**.
8. **Produkt matrik:** $\det(A \cdot B) = \det A \cdot \det B$.
9. **Inverz:** $\det A^{-1} = 1/\det A$.

### 28. Zveza med inverzom matrike in determinanto

Obstoj inverzne matrike je neposredno pogojen z vrednostjo determinante. Kvadratna matrika $A$ je **nesingularna** (ima inverz) natanko tedaj, ko je **$\det A \neq 0$**. Če je $\det A = 0$, pravimo, da je matrika **singularna**, kar pomeni, da inverz ne obstaja. Poleg tega velja obratnosorazmerna zveza med njunima vrednostma: $\det A^{-1} = \frac{1}{\det A}$.

### 29. Cramerjevo pravilo

Cramerjevo pravilo je metoda za reševanje sistema $n$ linearnih enačb z $n$ neznankami v primeru, ko je **determinanta sistema neničelna** ($\det A \neq 0$). Rešitev za posamezno neznanko $x_j$ izračunamo kot: $$x_j = \frac{\det A_j}{\det A}$$ Pri tem je $\det A_j$ determinanta matrike, ki jo dobimo tako, da $j$-ti stolpec v matriki koeficientov zamenjamo z vektorjem desnih strani sistema ($B$).

### 30. Računanje inverza matrike in matrika kofaktorjev

Inverzno matriko $A^{-1}$ obrnljive matrike lahko izračunamo s pomočjo determinant po formuli: $$A^{-1} = \frac{1}{\det A} \cdot \begin{bmatrix} C_{11} & C_{12} & \cdots & C_{1n} \ C_{21} & C_{22} & \cdots & C_{2n} \ \vdots & \vdots & \ddots & \vdots \ C_{n1} & C_{n2} & \cdots & C_{nn} \end{bmatrix}^T$$ V tej formuli so **$C_{ij}$ kofaktorji** (predznačene poddeterminante) elementov $a_{ij}$, izračunani kot $C_{ij} = (-1)^{i+j} \det A_{ij}$. Pomembno je upoštevati, da moramo matriko kofaktorjev v formuli še **transponirati**.

### 31. Rang matrike

**Rang $r(A)$** matrike $A$ dimenzije $m \times n$ je definiran kot **dimenzija največje neničelne poddeterminante** te matrike. Vrednost ranga je vedno omejena z dimenzijami matrike, kar zapišemo kot $0 \le r(A) \le \min{m, n}$. Praktično rang matrike določimo tako, da jo s transformacijami prevedemo v obliko, kjer ima vsaka naslednja vrstica vsaj eno ničlo več kot prejšnja, nato pa preštejemo **število neničelnih vrstic**.

### 32. Operacije, ki ohranjajo rang matrike

Rang matrike se ne spremeni pri izvajanju **elementarnih vrstičnih operacij** (in analognih stolpičnih operacij):

- **Zamenjava** dveh vrstic (ali stolpcev) v matriki.
- **Množenje** vrstice (ali stolpca) s poljubnim neničelnim številom.
- **Prištevanje** večkratnika ene vrstice (ali stolpca) kakšni drugi vrstici (ali stolpcu) v matriki.

### 33. Zveza med rangom, determinanto in inverzom matrike

Med temi pojmi za kvadratno matriko $A$ reda $n \times n$ veljajo naslednje ključne povezave:

- Matrika je **nesingularna** (ima inverz), če in samo če je njena **determinanta različna od nič** ($\det A \neq 0$) in je njen **rang enak $n$** ($r(A) = n$).
- Matrika je **singularna** (nima inverza), če in samo če je njena **determinanta enaka nič** ($\det A = 0$), kar se zgodi natanko tedaj, ko je njen **rang manjši od $n$** ($r(A) < n$).

### 34. Sistemi linearnih enačb

Sistem $m$ linearnih enačb z $n$ neznankami lahko zapišemo v matrični obliki **$A \cdot X = B$**, kjer je $A$ matrika koeficientov, $X$ stolpec neznank in $B$ stolpec desnih strani. Rešljivost sistema določa primerjava ranga matrike koeficientov $r(A)$ in ranga razširjene matrike sistema $r(R)$, kjer je $R = [A|B]$:

- **Sistem je rešljiv**, če velja $r(A) = r(R) = r$.
    - Če je $r = n$ (število neznank), je rešitev **enolična**.
    - Če je $r < n$, ima sistem **neskončno mnogo rešitev** ($n-r$ parametrična družina).
- **Sistem je nerešljiv (protisloven)**, če velja $r(A) \neq r(R)$.

### 35. Gaussova metoda za reševanje sistemov linearnih enačb

**Gaussova metoda** (ali eliminacija) je postopek, pri katerem:

1. Sestavimo **razširjeno matriko sistema** $R = [A|B]$.
2. Z elementarnimi vrstičnimi operacijami to matriko preoblikujemo v **zgornje-trikotno obliko**.
3. Iz dobljene matrike **rekurzivno** izračunamo vrednosti neznank (začnemo pri zadnji enačbi). Ta metoda je univerzalna in se lahko uporablja tudi za istočasno reševanje več sistemov z isto matriko koeficientov, kar se uporablja pri **računanju inverza matrike** ali reševanju matričnih enačb $AX = B$.


### 36. Elementarne vrstične operacije

Elementarne vrstične operacije so postopki na matriki, ki **ohranjajo njen rang**. Mednje štejemo:

- **Zamenjavo** dveh vrstic v matriki.
- **Množenje** vrstice v matriki s poljubnim neničelnim številom.
- **Prištevanje** vrstice matrike kakšni drugi vrstici v matriki. Te operacije se uporabljajo pri Gaussovi metodi za pretvorbo matrike v zgornje-trikotno obliko, iz katere nato odčitamo rang ali izračunamo rešitve sistema.

### 37. Razširjena matrika sistema in rešljivost sistema linearnih enačb

**Razširjena matrika sistema $R = [A|B]$** nastane tako, da matriko koeficientov $A$ razširimo s stolpcem desnih strani $B$. Rešljivost sistema določa **Izrek o rešljivosti (Frobeniusov izrek)**:

- Sistem je **rešljiv** natanko tedaj, ko je rang matrike koeficientov enak rangu razširjene matrike ($r(A) = r(R) = r$).
    - Če je **$r = n$** (število neznank), je rešitev **enolična**.
    - Če je **$r < n$**, ima sistem **neskončno mnogo rešitev** ($n-r$ parametrična družina).
- Sistem je **nerešljiv (protisloven)**, če je $r(A) \neq r(R)$.

### 38. Homogeni sistemi linearnih enačb

Sistem je **homogen**, če so vse vrednosti na desni strani enake nič ($B = 0$, oziroma $AX = 0$). Lastnosti takšnega sistema so:

- Vedno je **rešljiv**, saj ima vsaj **trivialno rešitev**, kjer so vse neznanke enake 0 ($x_1 = x_2 = \dots = x_n = 0$).
- **Netrivialno rešitev** (rešitev, ki ni samo ničelna) ima natanko tedaj, ko je **$r(A) < n$**.
- Pri kvadratnih sistemih netrivialna rešitev obstaja natanko tedaj, ko je **$\det A = 0$**.
- Če ima sistem manj enačb kot neznank ($m < n$), netrivialna rešitev vedno obstaja.

### 39. Matrične enačbe

Matrična enačba je enačba, v kateri nastopa **neznana matrika $X$**. Enačbo oblike $AX = B$ lahko rešimo z Gaussovo eliminacijo tako, da hkrati rešujemo več sistemov linearnih enačb. Postopek vključuje razširitev matrike $A$ z matriko $B$ ($[A|B]$) in uporabo vrstičnih operacij, dokler na levi strani ne dobimo identitete $I$, na desni pa iskano matriko $X$: **$[A|B] \rightsquigarrow [I|X]$**. Na enak način izračunamo **inverz matrike**, kjer rešujemo enačbo $AX = I$.

### 40. Vektorji v prostoru $\mathbb{R}^n$

Vektor v prostoru $\mathbb{R}^n$ je **urejena $n$-terica števil**, ki jih imenujemo koordinate ali komponente vektorja. Zapišemo ga lahko kot vrstično ali stolpično matriko. Geometrijske značilnosti vključujejo:

- V $\mathbb{R}^2$ in $\mathbb{R}^3$ si jih predstavljamo kot **usmerjene daljice** (krajevni vektorji), ki določajo točko v prostoru glede na izhodišče.
- **Dolžina vektorja** je določena z oddaljenostjo njegove končne točke od izhodišča in se izračuna s pomočjo Pitagorovega izreka.
- Osnovni operaciji sta **množenje s skalarjem** (razteg/skrčitev) in **seštevanje** (paralelogramsko pravilo).
- Množica vseh takšnih vektorjev z definiranimi operacijami tvori **vektorski prostor**.

### 41. Definicija realnega vektorskega prostora

**Realni vektorski prostor** je neprazna množica $\mathcal{V}$ elementov, ki jih imenujemo vektorji, skupaj z dvema definiranima operacijama: **seštevanjem vektorjev** in **množenjem vektorjev z realnimi skalarji**. Množica mora biti za obe operaciji **zaprta**, kar pomeni, da sta vsota dveh vektorjev iz $\mathcal{V}$ in produkt vektorja s skalarjem spet elementa iste množice $\mathcal{V}$. Poleg vektorjev v $\mathbb{R}^2$ in $\mathbb{R}^3$ so primeri vektorskih prostorov tudi množice vseh realnih matrik določene velikosti ali prostori polinomov.

### 42. Seštevanje vektorjev in množenje vektorja s skalarjem

Za ti dve operaciji v vektorskem prostoru morajo veljati naslednje lastnosti:

- **Seštevanje:** Je komutativno ($x + y = y + x$) in asociativno. Obstajati mora **ničelni vektor** $0$, ki je nevtralen element ($x + 0 = x$), ter za vsak vektor **nasprotni vektor** $-x$, da velja $x + (-x) = 0$.
- **Množenje s skalarjem:** Je **distributivno** glede na seštevanje vektorjev ($\lambda(x + y) = \lambda x + \lambda y$) in glede na seštevanje skalarjev ($(\lambda + \mu)x = \lambda x + \mu x$). Velja tudi lastnost $(\lambda \mu)x = \lambda(\mu x)$, skalar $1$ pa je nevtralni element ($1 \cdot x = x$).

### 43. Linearna kombinacija vektorjev

**Linearna kombinacija** vektorjev $x_1, x_2, \dots, x_n$ iz vektorskega prostora $V$ je izraz oblike: $$\lambda_1 x_1 + \lambda_2 x_2 + \dots + \lambda_n x_n$$ kjer so $\lambda_1, \lambda_2, \dots, \lambda_n$ realni skalarji.

### 44. Linearna odvisnost in neodvisnost vektorjev

Vektorji so **linearno neodvisni**, če je njihova linearna kombinacija enaka ničelnemu vektorju **le v primeru, ko so vsi skalarji $\lambda_i$ enaki 0**. V nasprotnem primeru so vektorji linearno odvisni. V prostoru $\mathbb{R}^n$ lahko neodvisnost preverimo z determinanto matrike $A$, v kateri so vektorji zapisani kot stolpci:

- Če je **$\det A \neq 0$**, so vektorji linearno **neodvisni**.
- Če je **$\det A = 0$**, so vektorji linearno **odvisni**.

### 45. Baza vektorskega prostora, dimenzija vektorskega prostora

- **Baza $\mathcal{B}$** je podmnožica vektorskega prostora $V$, katere elementi so **linearno neodvisni**, hkrati pa se da **vsak vektor** iz $V$ zapisati kot njihova linearna kombinacija. Baza je torej največja možna linearno neodvisna množica vektorjev v prostoru.
- **Dimenzija** vektorskega prostora je **število elementov (moč) njegove baze**. Primer standardne baze v $\mathbb{R}^n$ so vektorji $\vec{e}_1 = [1, 0, \dots, 0], \dots, \vec{e}_n = [0, 0, \dots, 1]$.

### 46. Definicija linearne preslikave

Preslikavo $T: V_1 \to V_2$ imenujemo **linearna**, če izpolnjuje dva pogoja hkrati:

1. **Aditivnost:** $T(x + y) = T(x) + T(y)$ za poljubna vektorja $x, y \in V_1$.
2. **Homogenost:** $T(\lambda x) = \lambda T(x)$ za poljuben vektor $x \in V_1$ in skalar $\lambda \in \mathbb{R}$. Združeno to pomeni, da mora za poljubna vektorja in skalarja veljati $T(\lambda x + \mu y) = \lambda T(x) + \mu T(y)$. Vsako takšno preslikavo med prostoroma $\mathbb{R}^n$ in $\mathbb{R}^m$ lahko predstavimo z matriko.

### 47. Matrika linearne preslikave

Vsako **linearno preslikavo** $T: \mathbb{R}^n \to \mathbb{R}^m$ lahko predstavimo z **matriko $T$ velikosti $m \times n$**, tako da velja $T(x) = T \cdot x$. **Stolpci te matrike** so slike $T(e_1), \dots, T(e_n)$ standardnih baznih vektorjev prostora $\mathbb{R}^n$. Velja tudi obratno, da vsaka matrika predstavlja določeno linearno preslikavo.

### 48. Definicija lastnih vrednosti in lastnih vektorjev matrike

Naj bo $A$ kvadratna matrika reda $n \times n$ in $X$ neničelni vektor. Če za nek skalar $\lambda$ velja enačba **$A \cdot X = \lambda \cdot X$**, potem $\lambda$ imenujemo **lastna vrednost**, vektor $X$ pa **lastni vektor** matrike $A$, ki pripada tej lastni vrednosti. Geometrijsko to pomeni, da matrika $A$ pri množenju vektorju $X$ **ne spremeni smeri**, temveč mu lahko spremeni le dolžino ali usmerjenost.

### 49. Izračun lastnih vrednosti in lastnih vektorjev matrike

Postopek izračuna lastnih parov poteka v naslednjih korakih:

1. Enačbo $AX = \lambda X$ preoblikujemo v **homogen sistem** $(A - \lambda I)X = 0$.
2. Lastne vrednosti dobimo z reševanjem **karakteristične enačbe** $\det(A - \lambda I) = 0$.
3. Za vsako izračunano lastno vrednost posebej poiščemo pripadajoče **lastne vektorje** kot netrivialne rešitve homogenega sistema $(A - \lambda I)X = 0$. Vsaki lastni vrednosti pripada neskončno mnogo lastnih vektorjev, ki tvorijo lastni podprostor.

### 50. Karakteristični polinom

**Karakteristični polinom** je polinom $n$-tega reda spremenljivke $\lambda$, ki ga dobimo kot determinanto matrike $(A - \lambda I)$, torej **$\det(A - \lambda I)$**. Ničle tega polinoma so ravno **lastne vrednosti** matrike $A$. Po osnovnem izreku algebre ima tak polinom največ $n$ različnih kompleksnih ničel.

### 51. Definicija funkcijske vrste

**Funkcijska vrsta** je izraz oblike: $$f_1(x) + f_2(x) + \dots = \sum_{n=1}^{\infty} f_n(x),$$ pri čemer so $f_1, f_2, \dots$ **realne funkcije**. Če za $x$ izberemo določeno vrednost $x_0$, ki je v skupnem definicijskem območju vseh funkcij v vrsti, dobimo **številsko vrsto** $\sum_{n=1}^{\infty} f_n(x_0)$. Množico vseh vrednosti $x$, za katere ta številska vrsta konvergira, imenujemo konvergenčno območje funkcijske vrste.



### 52. Konvergenca funkcijske vrste

Funkcijska vrsta $\sum_{n=1}^{\infty} f_n(x)$ je konvergentna v točki $x_0$, če konvergira številska vrsta $\sum_{n=1}^{\infty} f_n(x_0)$, ki jo dobimo z vstavitvijo te točke v funkcije. Če številska vrsta ne konvergira, pravimo, da je funkcijska vrsta v tej točki **divergentna**. Množico vseh realnih števil $x$, za katera vrsta konvergira, imenujemo **konvergenčno ali definicijsko območje** funkcijske vrste.

### 53. Definicija potenčne vrste

**Potenčna vrsta** je posebna oblika funkcijske vrste, ki jo zapišemo kot: $$\sum_{n=0}^{\infty} a_n (x - x_0)^n$$ Pri tem je **$x_0$ središče** vrste, števila $a_n$ pa so koeficienti vrste. Polinomi so pravzaprav posebni primeri potenčnih vrst, pri katerih so vsi koeficienti od določenega člena naprej enaki nič.

### 54. Konvergenčni polmer in konvergenčno območje potenčne vrste

- **Konvergenčni polmer (radij) $R$** izračunamo s pomočjo limite koeficientov: $R = \lim_{n \to \infty} \left| \frac{a_n}{a_{n+1}} \right|$.
- **Konvergenčno območje:**
    - Vrsta zagotovo konvergira na odprtem intervalu **$(x_0 - R, x_0 + R)$**.
    - Vrsta zagotovo divergira izven zaprtega intervala $[x_0 - R, x_0 + R]$.
    - V **robnih točkah** ($x = x_0 \pm R$) lahko vrsta konvergira ali divergira, zato je treba konvergenco tam preveriti posebej z uporabo kriterijev za številske vrste (npr. kvocientni, korenski, Leibnitzov kriterij).

### 55. Definicija Taylorjeve vrste funkcije

Če je realna funkcija $f$ v okolici točke $x_0$ neskončnokrat odvedljiva, jo lahko pod določenimi pogoji razvijemo v potenčno vrsto, imenovano **Taylorjeva vrsta**: $$f(x) = \sum_{k=0}^{\infty} \frac{f^{(k)}(x_0)}{k!}(x - x_0)^k$$ Kadar je središče razvoja točka **$x_0 = 0$**, to vrsto imenujemo tudi **MacLaurinova vrsta**.

### 56. Taylorjevi polinomi in ostanek Taylorjeve vrste

- **Taylorjev polinom stopnje $n$** je približek funkcije, ki ga dobimo, če zajamemo le končno število členov Taylorjeve vrste (do potence $x^n$): $f(x) \doteq \sum_{k=0}^{n} \frac{f^{(k)}(x_0)}{k!}(x - x_0)^k$.
- **Ostanek (ali napaka) $R_n(x)$** predstavlja razliko med dejansko vrednostjo funkcije in vrednostjo Taylorjevega polinoma stopnje $n$.
- Velja zveza: $f(x) = T_n(x) + R_n(x)$.
- Če ostanek $R_n(x)$ konvergira proti 0, ko gre $n$ proti neskončnosti, pravimo, da je funkcija **analitična**, saj je v tisti točki enaka svoji Taylorjevi vrsti.


### 57. Taylorjeva vrsta eksponentne funkcije

Eksponentno funkcijo $e^x$ razvijemo v vrsto, ki vključuje vse potence $x$. Razvoj je: **$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots = \sum_{n=0}^{\infty} \frac{x^n}{n!}$$** Ta vrsta konvergira za vsak **$x \in \mathbb{R}$**.

### 58. Taylorjeva vrsta sinusne funkcije

Sinusna funkcija je liha, zato njen razvoj vsebuje le **lihe potence** spremenljivke $x$ z alternirajočimi predznaki: **$$\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \dots = \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n+1}}{(2n+1)!}$$** Vrsta konvergira za vsak **$x \in \mathbb{R}$**.

### 59. Taylorjeva vrsta kosinusne funkcije

Kosinusna funkcija je soda, zato njen razvoj vsebuje le **sode potence** spremenljivke $x$ z alternirajočimi predznaki: **$$\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \dots = \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!}$$** Vrsta konvergira za vsak **$x \in \mathbb{R}$**.

### 60. Taylorjeva vrsta logaritemske funkcije

Za logaritemsko funkcijo je podan razvoj za $\ln(x+1)$, ki se glasi: **$$\ln(x+1) = x - \frac{x^2}{2} + \frac{x^3}{3} - \frac{x^4}{4} + \dots = \sum_{n=1}^{\infty} (-1)^{n+1} \frac{x^n}{n}$$** Konvergenčno območje te vrste je polodprti interval **$x \in (-1, 1]$**.

### 61. Geometrijska Taylorjeva vrsta

Geometrijska vrsta predstavlja razvoj funkcije $\frac{1}{1-x}$: **$$\frac{1}{1-x} = 1 + x + x^2 + x^3 + \dots = \sum_{n=0}^{\infty} x^n$$** Vrsta konvergira na odprtem intervalu **$x \in (-1, 1)$**.

### 62. Binomska Taylorjeva vrsta

Binomska vrsta je razvoj potenčne funkcije $(1+x)^\alpha$ za poljuben $\alpha \in \mathbb{R} \setminus {0}$: **$$(1+x)^\alpha = 1 + \binom{\alpha}{1}x + \binom{\alpha}{2}x^2 + \binom{\alpha}{3}x^3 + \dots = \sum_{n=0}^{\infty} \binom{\alpha}{n}x^n$$** Koeficienti $\binom{\alpha}{n}$ so binomski simboli. Vrsta konvergira na odprtem intervalu **$x \in (-1, 1)$**.

### 63. Taylorjeva vrsta korenske funkcije

Korensko funkcijo $\sqrt{1+x}$ obravnavamo kot poseben primer **binomsko-potenčne vrste** $(1+x)^\alpha$, kjer je **$\alpha = 1/2$**. Splošna oblika te Taylorjeve vrste je: $$(1+x)^\alpha = 1 + \binom{\alpha}{1}x + \binom{\alpha}{2}x^2 + \dots = \sum_{n=0}^{\infty} \binom{\alpha}{n}x^n$$ Vrednosti $\binom{\alpha}{n}$ so **binomski simboli**. Vrsta konvergira na odprtem intervalu **$x \in (-1, 1)$**.

### 64. Periodična funkcija

Realna funkcija $f$ je **periodična**, če obstaja takšno realno število $p \neq 0$, da za vsak $x$ velja **$f(x+p) = f(x)$**.

- Število $p$ imenujemo **perioda**; če je $p$ perioda, so periode tudi vsi njeni večkratniki $np$.
- Najmanjšo pozitivno periodo imenujemo **osnovna perioda**.
- Funkcija je v celoti določena, če poznamo njene vrednosti na katerem koli intervalu dolžine $p$.

### 65. Fourierjeva vrsta funkcije s periodo $2\pi$

Če je periodična funkcija $f$ s periodo **$2\pi$** odsekoma zvezna in ima v vsaki točki levi in desni odvod, jo lahko zapišemo s **Fourierjevo vrsto**: $$F(x) = a_0 + \sum_{n=1}^{\infty} (a_n \cos(nx) + b_n \sin(nx))$$ **Fourierjevi koeficienti** so določeni z integrali:

- $a_0 = \frac{1}{2\pi} \int_{-\pi}^{\pi} f(x) , dx$
- $a_n = \frac{1}{\pi} \int_{-\pi}^{\pi} f(x) \cos(nx) , dx$
- $b_n = \frac{1}{\pi} \int_{-\pi}^{\pi} f(x) \sin(nx) , dx$

### 66. Konvergenca Fourierjeve vrste

Fourierjeva vrsta konvergira pod pogojem, da je funkcija **odsekoma zvezna** in da v vsaki točki obstajata **levi in desni odvod**. Glede na točko $x$ ločimo dve stanji konvergence:

1. **V točkah zveznosti:** Vsota vrste $F(x)$ je enaka dejanski vrednosti funkcije, torej **$F(x) = f(x)$**.
2. **V točkah nezveznosti ($x_0$):** Vsota Fourierjeve vrste je enaka **aritmetični sredini** leve in desne limite funkcije v tej točki: $F(x_0) = \frac{1}{2} (\lim_{x \uparrow x_0} f(x) + \lim_{x \downarrow x_0} f(x))$.

### 67. Fourierjeva vrsta funkcije s poljubno periodo $T$

Za funkcijo s poljubno periodo $T_0$ (in frekvenco $f = 1/T_0$) je Fourierjeva vrsta sestavljena iz **harmonikov**: $$a_0 + \sum_{n=1}^{\infty} (a_n \cos(n\omega_0 x) + b_n \sin(n\omega_0 x))$$ Pri tem je **$\omega_0 = \frac{2\pi}{T_0}$** osnovna kotna frekvenca. Koeficienti so izraženi kot:

- $a_0 = \frac{1}{T_0} \int_{-\frac{T_0}{2}}^{\frac{T_0}{2}} f(x) , dx$
- $a_n = \frac{2}{T_0} \int_{-\frac{T_0}{2}}^{\frac{T_0}{2}} f(x) \cos(n\omega_0 x) , dx$
- $b_n = \frac{2}{T_0} \int_{-\frac{T_0}{2}}^{\frac{T_0}{2}} f(x) \sin(n\omega_0 x) , dx$


### 68. Osnovna perioda in osnovna krožna frekvenca funkcije

- **Osnovna perioda ($T_0$):** To je **najmanjša pozitivna perioda** $p$, za katero velja $f(x+p) = f(x)$ za vsak $x$. Funkcija je v celoti določena z vrednostmi na katerem koli intervalu dolžine te periode.
- **Osnovna krožna (kotna) frekvenca ($\omega_0$):** Določena je z zvezo **$\omega_0 = \frac{2\pi}{T_0} = 2\pi f$**, kjer je $f = 1/T_0$ frekvenca funkcije. Kotno frekvenco $n$-tega člena v vrsti ($n\omega_0$) imenujemo $n$-ta harmonska frekvenca.

### 69. Fourierjeva vrsta funkcije na intervalu $[a, b]$

Čeprav viri primarno obravnavajo periodične funkcije, se funkcijo, določeno na intervalu $[a, b]$, razvije tako, da se interval dolžine $T = b - a$ obravnava kot ena perioda. Splošna oblika te vrste je: **$$a_0 + \sum_{n=1}^{\infty} (a_n \cos(n\omega_0 x) + b_n \sin(n\omega_0 x))$$** kjer so koeficienti izračunani z integracijo preko intervala $[a, b]$ (oziroma ustrezno zamaknjenega intervala dolžine $T_0$).

### 70. Sodo in liho nadaljevanje funkcije

Če je funkcija prvotno definirana le na intervalu $[0, T/2]$, jo lahko razširimo na interval $[-T/2, T/2]$ na dva načina:

- **Sodo nadaljevanje:** Funkcijo razširimo tako, da velja $f(-x) = f(x)$. Takšen razvoj v Fourierovo vrsto nam da **kosinusno vrsto**.
- **Liho nadaljevanje:** Funkcijo razširimo tako, da velja $f(-x) = -f(x)$. Takšen razvoj nam da **sinusno vrsto**.

### 71. Kosinusna Fourierjeva vrsta

Kosinusna Fourierjeva vrsta se uporablja za **sode periodične funkcije**. V takšnem razvoju so vsi koeficienti $b_n$ enaki 0, zato vrsta vsebuje le konstantni člen in kosinusne člene: **$$F(x) = a_0 + \sum_{n=1}^{\infty} a_n \cos(n\omega_0 x)$$**

### 72. Sinusna Fourierjeva vrsta

Sinusna Fourierjeva vrsta se uporablja za **lihe periodične funkcije**. V takšnem razvoju so vsi koeficienti $a_n$ (vključno z $a_0$) enaki 0, zato vrsta vsebuje le sinusne člene: **$$F(x) = \sum_{n=1}^{\infty} b_n \sin(n\omega_0 x)$$**

### 73. Primerjava Taylorjeve vrste in Fourierjeve vrste

Viri izpostavljajo tri ključne razlike med obema vrstama:

1. **Pogoji za razvoj:** Za Taylorjevo vrsto mora biti funkcija **neskončnokrat odvedljiva**, za Fourierovo pa zadošča, da je **odsekoma zvezna** z obstoječimi levimi in desnimi odvodi.
2. **Način izračuna:** Koeficiente Taylorjeve vrste računamo z **odvodi** v točki, koeficiente Fourierove vrste pa z **integrali** čez celo periodo.
3. **Kakovost aproksimacije:** Taylorjeva vrsta najbolje aproksimira funkcijo **v bližini specifične točke**, Fourierjeva vrsta pa zagotavlja dobro aproksimacijo na **celotnem območju periode**.


### 74. Definicija realne funkcije dveh in več spremenljivk

- **Funkcija dveh spremenljivk** je preslikava $f$, ki vsaki točki $(x, y)$ iz definicijskega območja $D \subseteq \mathbb{R}^2$ priredi natanko eno realno število $z = f(x, y)$.
- **Funkcija $n$ spremenljivk** je preslikava, ki vsaki točki $(x_1, \dots, x_n)$ iz $D \subseteq \mathbb{R}^n$ priredi realno število $z = f(x_1, \dots, x_n)$.

### 75. Graf realne funkcije dveh spremenljivk

Graf funkcije dveh spremenljivk je množica točk v tridimenzionalnem prostoru, definirana kot **$\Gamma(f) = {(x, y, f(x, y)) : (x, y) \in D} \subseteq \mathbb{R}^3$**. Geometrijsko ta množica točk običajno predstavlja **ploskev** v prostoru.

### 76. Nivojnice oz. izočrte funkcije dveh spremenljivk

Čeprav so nivojnice navedene kot tema v seznamu vprašanj za izpit, v priloženih vsebinskih virih **ni eksplicitne definicije** tega pojma. V splošnem (izven virov) nivojnice predstavljajo krivulje v ravnini $xy$, na katerih funkcija zavzame konstantno vrednost ($f(x, y) = c$), kar se pogosto uporablja za vizualizacijo ploskev.

### 77. Parcialni odvodi funkcije več spremenljivk

Parcialni odvodi so definirani kot **limite parcialnih diferenčnih kvocientov**, pri katerih spreminjamo le eno spremenljivko, ostale pa obravnavamo kot konstante. Za funkcijo dveh spremenljivk sta definirana kot:

- $f_x(x, y) = \lim_{h \to 0} \frac{f(x + h, y) - f(x, y)}{h}$
- $f_y(x, y) = \lim_{h \to 0} \frac{f(x, y + h) - f(x, y)}{h}$

### 78. Geometrijski pomen parcialnih odvodov funkcije dveh spremenljivk

Viri ne navajajo neposredne geometrijske razlage parcialnih odvodov kot nagibov tangentnih premic v smeri koordinatnih osi, vendar pojasnjujejo, da parcialna odvoda $f_x$ in $f_y$ v točki $(x_0, y_0)$ določata **koeficiente tangentne ravnine** na graf funkcije, če je funkcija v tej točki diferenciabilna.

### 79. Totalni diferencial funkcije dveh spremenljivk in računanje približne vrednosti

- **Totalni diferencial $df$** funkcije $f$ v točki $(x_0, y_0)$ je definiran z izrazom: **$df = f_x(x_0, y_0)dx + f_y(x_0, y_0)dy$**.
- Uporablja se za **računanje približnih vrednosti** funkcije v okolici točke $(x_0, y_0)$ po formuli: **$f(x_0 + \Delta x, y_0 + \Delta y) \doteq f(x_0, y_0) + df$**.

### 80. Tangentna ravnina na graf funkcije dveh spremenljivk

Tangentna ravnina je ravnina, ki se v točki $(x_0, y_0)$ najbolje prilega grafu funkcije in predstavlja njegov **lokalni linearni približek** (približek s totalnim diferencialom). Njena enačba izhaja iz totalnega diferenciala in se glasi: **$$z = f(x_0, y_0) + f_x(x_0, y_0)(x - x_0) + f_y(x_0, y_0)(y - y_0)$$**

### 81. Verižno pravilo za parcialni odvod

Verižno pravilo uporabimo, ko je funkcija $z = f(x, y)$ **posredno odvisna** od novih spremenljivk $u$ in $v$ preko vmesnih spremenljivk $x(u, v)$ in $y(u, v)$. Če so vse vpletene funkcije diferenciabilne, izračunamo parcialna odvoda po novih spremenljivkah po naslednjih formulah:

- **$z_u = z_x \cdot x_u + z_y \cdot y_u$**
- **$z_v = z_x \cdot x_v + z_y \cdot y_v$**

### 82. Višji parcialni odvodi

Višji parcialni odvodi (npr. 2. reda) so **odvodi že izračunanih parcialnih odvodov**. Pri funkciji dveh spremenljivk poznamo štiri odvode drugega reda: $f_{xx}$, $f_{yy}$ ter mešana odvoda $f_{xy}$ in $f_{yx}$. Velja pomemben **izrek (Izrek 6.5)**: če sta mešana parcialna odvoda zvezni funkciji, sta med seboj **enaka** ($f_{xy} = f_{yx}$), kar pomeni, da vrstni red odvajanja ni pomemben.

### 83. Hessejeva matrika funkcije in njena uporaba

**Hessejeva matrika $H_f$** je kvadratna matrika vseh **drugih parcialnih odvodov** funkcije $f$. Če so vsi drugi parcialni odvodi zvezni, je ta matrika **simetrična**. **Uporaba:**

- **Aproksimacija:** Uporablja se za Taylorjeve razvoje višjih redov, ki omogočajo boljšo lokalno aproksimacijo funkcije kot le prvi odvodi.
- **Klasifikacija ekstremov:** Njena determinanta ($\det H_f$) je ključna pri določanju narave stacionarnih točk (ali gre za minimum, maksimum ali sedlo).

### 84. Definicija lokalnih ekstremov funkcije več spremenljivk

Funkcija $f$ ima v točki $(a, b)$ **lokalni ekstrem**, če v neki majhni okolici (odprtem krogu s polmerom $\epsilon$) te točke velja:

- **Lokalni minimum:** če za vsako točko $(x, y)$ v okolici velja $f(x, y) \ge f(a, b)$.
- **Lokalni maksimum:** če za vsako točko $(x, y)$ v okolici velja $f(x, y) \le f(a, b)$. Pri funkcijah $n$ spremenljivk je definicija analogna, le da je okolica $n$-dimenzionalna odprta krogla.

### 85. Stacionarne točke funkcije dveh spremenljivk in tipi stacionarnih točk

Točka $(a, b)$ je **stacionarna (ali kritična) točka**, če so v njej **vsi parcialni odvodi prvega reda enaki 0** ($f_x = 0$ in $f_y = 0$). Tipi stacionarnih točk se določijo s pomočjo determinante Hessejeve matrike ($\det H_f$):

1. **Lokalni ekstrem:** nastopi, če je **$\det H_f(a, b) > 0$**.
    - Gre za **lokalni minimum**, če je hkrati $f_{xx}(a, b) > 0$.
    - Gre za **lokalni maksimum**, če je hkrati $f_{xx}(a, b) < 0$.
2. **Sedlo:** nastopi, če je **$\det H_f(a, b) < 0$** (v tej točki ni lokalnega ekstrema).
3. **Neodločen primer:** če je $\det H_f(a, b) = 0$, s pomočjo drugih odvodov tipa točke ne moremo določiti.




### 86. Določanje tipa stacionarne točke s pomočjo Hessejeve matrike

Za dvakrat zvezno parcialno odvedljivo funkcijo dveh spremenljivk določimo naravo stacionarne točke $(a, b)$ s pomočjo **determinante Hessejeve matrike** (označene kot $\det H_f(a, b)$ ali $\det \text{Hess}_f(a, b)$). Postopek je naslednji:

- **Lokalni ekstrem:** Če je **$\det H_f(a, b) > 0$**, v točki $(a, b)$ nastopi lokalni ekstrem. Njegov tip določimo s predznakom drugega parcialnega odvoda po $x$:
    - **Lokalni minimum:** Če je $f_{xx}(a, b) > 0$.
    - **Lokalni maksimum:** Če je $f_{xx}(a, b) < 0$.
- **Sedlo:** Če je **$\det H_f(a, b) < 0$**, v točki $(a, b)$ ni lokalnega ekstrema, temveč se tam nahaja sedlo.
- **Neodločen primer:** Če je **$\det H_f(a, b) = 0$**, s pomočjo drugih parcialnih odvodov narave točke ne moremo ugotoviti.

Hessejeva matrika je sicer matrika vseh drugih parcialnih odvodov funkcije, ki je simetrična, če so ti odvodi zvezni.

### 87. Globalni ekstremi funkcije več spremenljivk

**Globalni ekstremi** so največje in najmanjše vrednosti, ki jih funkcija zavzame na celotnem definicijskem območju. Pri iskanju teh ekstremov moramo preveriti tri skupine kandidatov:

1. **Stacionarne točke:** Točke znotraj definicijskega območja, kjer so vsi parcialni odvodi prvega reda enaki nič ($f_{x_1} = f_{x_2} = \dots = f_{x_n} = 0$).
2. **Točke neodvedljivosti:** Točke, v katerih funkcija ni parcialno odvedljiva.
3. **Robne točke:** Točke, ki ležijo na robu definicijskega območja funkcije.

Za iskanje kandidatov na robu oziroma ob upoštevanju določenih pogojev (vezi) se pogosto uporablja metoda **Lagrangeovih multiplikatorjev**, kjer iščemo stacionarne točke pomožne Lagrangeove funkcije.


### 88. Vezani ekstremi funkcije več spremenljivk

**Vezani ekstremi** so posebna vrsta ekstremov parcialno odvedljive funkcije $n$ spremenljivk $f(x_1, \ldots, x_n)$, kjer iščemo **največje in najmanjše vrednosti** funkcije na določeni podmnožici definicijskega območja. Ta podmnožica je določena z dodatnimi pogoji, ki jih imenujemo **vezi**. Običajno gre za $k$ pogojev (kjer je $k < n$) v obliki enačb: $$g_1(x_1, \ldots, x_n) = 0, \ldots, g_k(x_1, \ldots, x_n) = 0$$

### 89. Lagrangejeva funkcija in njene stacionarne točke

Za iskanje kandidatov za vezane ekstreme uporabimo **Lagrangeovo funkcijo** $F$. Ta funkcija združi prvotno funkcijo $f$ in vse pogoje $g_i$ s pomočjo dodatnih parametrov $\lambda_i$, ki jih imenujemo **Lagrangeovi multiplikatorji** ali množitelji.

- **Zapis Lagrangeove funkcije:** $$F(x_1, \ldots, x_n; \lambda_1, \ldots, \lambda_k) = f(x_1, \ldots, x_n) + \lambda_1 g_1(x_1, \ldots, x_n) + \cdots + \lambda_k g_k(x_1, \ldots, x_n)$$.
- **Stacionarne točke:** Kandidati za vezane ekstreme so **stacionarne točke** te nove funkcije $F$. Poiščemo jih tako, da rešimo sistem enačb, kjer so vsi parcialni odvodi funkcije $F$ (tako po prvotnih spremenljivkah $x_i$ kot po multiplikatorjih $\lambda_i$) enaki nič:
    - $F_{x_1} = 0, \ldots, F_{x_n} = 0$
    - $F_{\lambda_1} = 0, \ldots, F_{\lambda_k} = 0$.

Zadnjih $k$ enačb ($F_{\lambda_i} = 0$) dejansko predstavlja prvotne pogoje oziroma vezi $g_i = 0$.


### 90. Definicija diferencialne enačbe (navadne in parcialne)

**Diferencialna enačba** je enačba, ki vsebuje **neznano funkcijo** ene ali več spremenljivk ter njene **odvode**. Ločimo dve glavni vrsti:

- **Navadne diferencialne enačbe (NDE):** V enačbi nastopa neznana funkcija ene spremenljivke (npr. $y = y(x)$), njeni odvodi ($y', y'', \dots$) ter neodvisna spremenljivka $x$.
- **Parcialne diferencialne enačbe (PDE):** V enačbi nastopa neznana funkcija **več spremenljivk**, njeni **parcialni odvodi** ter neodvisne spremenljivke.

### 91. Red diferencialne enačbe

**Red** diferencialne enačbe je določen s **stopnjo najvišjega odvoda**, ki se pojavi v enačbi. Na primer, če je najvišji odvod v enačbi drugi odvod ($y''$), pravimo, da je enačba drugega reda.

### 92. Splošna in partikularna rešitev diferencialne enačbe

Rešitev diferencialne enačbe je vsaka odvedljiva funkcija, ki enačbi zadošča.

- **Splošna rešitev:** Zapis, ki združuje vse možne rešitve enačbe in vsebuje **nedoločene parametre (konstante)**. Število teh konstant je običajno enako redu diferencialne enačbe.
- **Partikularna rešitev:** To je natanko **ena določena rešitev**, ki jo dobimo, če v splošni rešitvi izberemo konkretne vrednosti za parametre.

### 93. Začetni in robni pogoji

Partikularno rešitev pogosto določimo s predpisovanjem dodatnih pogojev:

- **Začetni pogoji:** To so vrednosti neznane funkcije in njenih odvodov ob **začetku opazovanja** (običajno, ko je neodvisna spremenljivka čas $t$). Diferencialno enačbo skupaj z začetnimi pogoji imenujemo **začetni problem** ali **Cauchyjeva naloga**.
- **Robni pogoji:** To so vrednosti neznane funkcije in njenih odvodov v **robnih točkah** definicijskega območja funkcije.

### 94. Diferencialne enačbe 1. reda

Splošna oblika diferencialne enačbe 1. reda je **$F(x, y, y') = 0$**. V teh enačbah nastopa najvišje prvi odvod neznane funkcije. Viri podrobneje obravnavajo dve vrsti teh enačb:

- **Diferencialna enačba z ločljivima spremenljivkama:** Oblike $y' = g(x) \cdot f(y)$, kjer lahko spremenljivki $x$ in $y$ ločimo na različni strani enačbe in integriramo.
- **Linearna diferencialna enačba 1. reda:** Oblike $a(x)y' + b(x)y = c(x)$. Njena splošna rešitev je vsota splošne rešitve homogene enačbe ($y_h$) in partikularne rešitve nehomogene enačbe ($y_p$).

### 95. Diferencialna enačba z ločljivima spremenljivkama

Diferencialna enačba z ločljivima spremenljivkama je enačba oblike **$y' = g(x) \cdot f(y)$** oziroma **$g(x) dx = h(y) dy$**, kjer so $f$, $g$ in $h$ poljubne funkcije ene spremenljivke. Postopek reševanja vključuje tri korake:

1. V enačbo vstavimo **$y' = \frac{dy}{dx}$**.
2. Spremenljivki $x$ in $y$ **ločimo** tako, da je vsaka na svoji strani enačaja.
3. Obe strani enačbe **integriramo**.

### 96. Linearna diferencialna enačba 1. reda

To je diferencialna enačba oblike **$a(x)y' + b(x)y = c(x)$**, kjer so $a$, $b$ in $c$ funkcije neodvisne spremenljivke $x$. Njena splošna rešitev je vedno sestavljena iz dveh delov: **$y(x) = y_h(x) + y_p(x)$**, kjer je $y_h$ splošna rešitev homogene enačbe, $y_p$ ali pa katera koli partikularna rešitev nehomogene enačbe. V splošni rešitvi nastopa natanko ena splošna konstanta.

### 97. Homogena linearna diferencialna enačba 1. reda

Linearna diferencialna enačba prvega reda je **homogena**, če je funkcija na desni strani enaka nič (**$c(x) = 0$**), torej ima obliko **$a(x)y' + b(x)y = 0$**. Takšno enačbo rešujemo kot diferencialno enačbo z ločljivima spremenljivkama. Njena splošna rešitev $y_h$ vsebuje eno konstanto $C$ in jo običajno zapišemo kot $y_h(x) = C \cdot h(x)$.

### 98. Nehomogena linearna diferencialna enačba 1. reda

Enačba je **nehomogena**, če funkcija na desni strani **ni enaka nič** (**$c(x) \neq 0$**). Postopek reševanja takšne enačbe zahteva, da najprej poiščemo splošno rešitev pripadajoče homogene enačbe ($y_h$), nato pa še poljubno partikularno rešitev nehomogene enačbe ($y_p$).

### 99. Metoda variacije konstante

**Metoda variacije konstante** je postopek za iskanje partikularne rešitve $y_p$ nehomogene linearne diferencialne enačbe. Pri tej metodi vzamemo obliko splošne rešitve homogene enačbe ($y_h(x) = C \cdot h(x)$) in **konstanto $C$ zamenjamo z neznano funkcijo $C(x)$**. Nastavek za partikularno rešitev je torej: **$$y_p(x) = C(x) \cdot h(x)$$** Neznano funkcijo $C(x)$ določimo tako, da ta nastavek vstavimo v prvotno nehomogeno diferencialno enačbo in zahtevamo, da ji ustreza.


### 100. Eksaktna diferencialna enačba

Čeprav je **eksaktna diferencialna enačba** navedena kot ena izmed izpitnih tem, v priloženih vsebinskih virih **ni podane njene eksplicitne definicije ali postopka reševanja**. V okviru poglavja o funkcijah več spremenljivk viri sicer definirajo **totalni diferencial** ($df = f_x dx + f_y dy$), ki je matematična osnova za eksaktne enačbe, vendar same povezave z diferencialnimi enačbami v teh odlomkih ne izpeljejo.

### 101. Diferencialna oblika enačbe 1. reda

Viri omenjajo diferencialno obliko v kontekstu **diferencialnih enačb z ločljivima spremenljivkama**, kjer enačbo zapišemo kot: **$$g(x) dx = h(y) dy$$** To obliko dobimo tako, da v prvotno enačbo vstavimo $y' = \frac{dy}{dx}$ in nato ločimo spremenljivki $x$ in $y$ na različni strani enačaja, kar omogoča neposredno integracijo.

### 102. Znižanje reda diferencialne enačbe

Red diferencialne enačbe lahko znižamo z **vpeljavo primerne nove spremenljivke** (bodisi odvisne bodisi neodvisne). Ta postopek določene enačbe višjega reda prevede na obliko, ki jo znamo rešiti z metodami za enačbe nižjega reda.

### 103. Homogena linearna diferencialna enačba reda $n$ s konstantnimi koeficienti

To je enačba oblike **$a_n y^{(n)}(x) + \dots + a_1 y'(x) + a_0 y(x) = 0$**, kjer so $a_0, \dots, a_n$ realne konstante.

- Rešitev iščemo z nastavkom **$y(x) = e^{\lambda x}$**.
- V splošni rešitvi nastopa natanko **$n$ splošnih konstant** (parametrov).
- Splošna rešitev je vsota delnih rešitev, ki so odvisne od narave ničel karakteristične enačbe.

### 104. Karakteristična enačba

**Karakteristična enačba** nastane, ko nastavek $y(x) = e^{\lambda x}$ vstavimo v homogeno linearno diferencialno enačbo s konstantnimi koeficienti. Ima obliko polinomske enačbe: **$$a_n \lambda^n + \dots + a_1 \lambda + a_0 = 0$$** Ta enačba ima največ $n$ različnih rešitev $\lambda_i$. Oblika splošne rešitve $y_h$ je odvisna od večkratnosti teh ničel:

- **Enojna ničla:** prispeva člen $C_i e^{\lambda_i x}$.
- **Dvojna ničla:** prispeva $C_{i1} e^{\lambda_i x} + C_{i2} x e^{\lambda_i x}$.
- **Trojna ničla:** prispeva $C_{i1} e^{\lambda_i x} + C_{i2} x e^{\lambda_i x} + C_{i3} x^2 e^{\lambda_i x}$.

### 105. Nehomogena linearna diferencialna enačba reda $n$ s konstantnimi koeficienti

To je enačba oblike **$a_n y^{(n)}(x) + \dots + a_1 y'(x) + a_0 y(x) = r(x)$**, kjer desna stran $r(x)$ ni enaka nič.

- **Splošna rešitev** je sestavljena iz dveh delov: **$y(x) = y_h(x) + y_p(x)$**.
- $y_h$ je splošna rešitev pripadajoče homogene enačbe (z $n$ konstantami).
- $y_p$ je katera koli partikularna rešitev nehomogene enačbe, ki jo pogosto poiščemo z **metodo nedoločenih koeficientov** oziroma "inteligentnega ugibanja". Pri tej metodi za določene oblike funkcije $r(x)$ (polinomi, eksponentne funkcije, sinus/kosinus) izberemo ustrezen nastavek za $y_p$.

### 106. Metoda nedoločenih koeficientov

**Metoda nedoločenih koeficientov** (ali metoda inteligentnega ugibanja) se uporablja za iskanje **partikularne rešitve $y_p$** nehomogene linearne diferencialne enačbe s konstantnimi koeficienti. Ta metoda je učinkovita, kadar je funkcija na desni strani $r(x)$ takšne oblike, da so njeni odvodi v isti družini funkcij kot ona sama (npr. polinomi, eksponentne ali trigonometrične funkcije).

- **Postopek:** Za določeno obliko $r(x)$ izberemo vnaprej določen **nastavek za $y_p$** (npr. če je $r(x)$ polinom stopnje $n$, je nastavek $x^s \cdot (\text{polinom stopnje } n)$).
- **Določitev koeficientov:** Nastavek vstavimo v diferencialno enačbo in določimo neznane koeficiente (npr. $A, B, \dots$) tako, da enačba drži.
- **Resonanca:** Eksponent $s$ v nastavku je najmanjše nenegativno celo število, ki zagotavlja, da $y_p$ reši enačbo (običajno povezano s tem, ali je del desne strani že v splošni rešitvi homogene enačbe).

### 107. Eulerjeva diferencialna enačba (homogena in nehomogena)

**Homogena Eulerjeva diferencialna enačba** ima obliko $a_n x^n y^{(n)}(x) + \dots + a_1 x y'(x) + a_0 y(x) = 0$, kjer so $a_i$ konstante.

- **Reševanje homogene:** Uporabimo nastavek **$y(x) = x^\lambda$**, ki nas pripelje do karakteristične enačbe. Oblika splošne rešitve je odvisna od ničel $\lambda_i$: enojna ničla prispeva $C_i x^{\lambda_i}$, dvojna pa $C_{i1} x^{\lambda_i} + C_{i2} \ln x \cdot x^{\lambda_i}$.
- **Nehomogena Eulerjeva enačba:** Viri ne vsebujejo eksplicitnih navodil za reševanje nehomogene oblike (kjer je na desni strani funkcija $r(x) \neq 0$), vendar se v teoriji običajno rešuje z variacijo konstant ali s prevebo na enačbo s konstantnimi koeficienti s substitucijo $x = e^t$ (ta informacija ni v vaših virih).



### 108. Definicija sistemov diferencialnih enačb

Sistem diferencialnih enačb je množica dveh ali več enačb, v katerih nastopajo **odvodi več neznanih funkcij** iste neodvisne spremenljivke (običajno časa $t$). Rešitev sistema je n-terica funkcij, ki hkrati zadoščajo vsem enačbam.

### 109. Sistem $n$ linearnih diferencialnih enačb 1. reda s konstantnimi koeficienti

To je sistem oblike $\vec{x}' = A\vec{x} + \vec{b}(t)$, kjer je $A$ matrika konstantnih koeficientov. Homogeni del rešujemo s pomočjo **lastnih vrednosti in lastnih vektorjev** matrike $A$ (kar je povezano s snovjo o matrikah iz vaših virov).

### 110. Začetni pogoji za sisteme diferencialnih enačb

Pri sistemih moramo za enolično določitev partikularne rešitve podati **začetne vrednosti za vsako neznano funkcijo** posebej v isti začetni točki $t_0$.

### 111. Prevedba sistema dveh diferencialnih enačb 1. reda na eno diferencialno enačbo 2. reda (metoda eliminacije)

Sistem dveh enačb prvega reda (npr. za $x(t)$ in $y(t)$) rešimo tako, da iz ene enačbe izrazimo eno spremenljivko (npr. $y$), jo odvajamo in vstavimo v drugo enačbo. Tako dobimo **eno linearno diferencialno enačbo drugega reda** za eno neznano funkcijo ($x$), ki jo nato rešimo z običajnimi metodami.

