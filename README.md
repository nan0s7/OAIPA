# OAIPA
An open source IPA (International Phonetic Alphabet) for the ASCII character set

Pulmonic Consonants | Bilabial | Labiodental | Dental | Alveolar | Postalveolar | Retroflex | Palatal | Velar | Uvular | Pharyngeal | Glottal
---             | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---:
Plosive         | p  b  |       |       | t  d  |       | D  D` | c  -  | k  g  | q  G  |       | ?
Nasal           |    m  |    mg |       |    n  |       |    nn |    nj |    ng |    N  |       |
Trill           |    B  |       |       |    r  |       |       |       |       |    R  |       |
Tap, flap       |       |    v` |       |    P  |       |    [  |       |       |       |       |
Fricative       | F  V  | f  v  | T  T` | s  z  | S  Z  | $  2  | -  -  | x  -  | X  K  | h` ?? | h  H
Lateral fric.   |       |       |       | 1  1` |       |       |       |       |       |       |
Approximate     |       |    u` |       |    J  |       |    {  |    j  |    uq |       |       |
Lateral approx. |       |       |       |    l  |       |    -  |    -  |    L  |       |       |

Vowels | Front | Fr. Cen. | Central | Cen. Bk. | Back
---            | :---: | :---: | :---: | :---: | :---:
Close          | i  y  |       | i- u- |       | uu u
Half close-mid |       | I  Y  |       |    U  |
Close-mid      | e  0  |       | 9  -  |       | -  o
Half open-mid  |       |       |    -  |       |
Open-mid       | E  oe |       | 3  -  |       | ^  O
Half open      |    ae |       | 6     |       |
Open           | a  OE |       |       |       | A  A`

#### Diacritics
In situations where information is clear and uncluttered, the closing parenthesis is not mandatory.
Description | Example | Description | Example | Description | Example
--- | :---: | --- | :---: | --- | :---:
Voiceless       | n(v), d(v) | Breathy voiced              | b(,,), a(,V) | Dental             | t(d), d(D)
Voiced          | s(V), t(V) | Creaky voiced               | b(~~), a(~V) | Apical             | t(a), d(A)
Aspirated       | t(h), d(h) | Linguolabial                | t(m),  d(M)  | Laminal            | t(L), d(L)
More rounded    |            | Labialised                  | t(w),  d(W)  | Nasalised          | e~
Less rounded    |            | Palatalised                 | t(j),  d(J)  | Nasal release      | d(n), d(N)
Advanced        | u(+)       | Velarised                   | t(y),  d(Y)  | Lateral release    | d(l)
Retracted       |            | Pharyngealised              | t(?),  d(?)  | No audible release | d(-)
Centralised     | e(..)      | Velarised or pharyngealised | l(~)         |
Mid-centralised | e(x)       | Raised                      | e(T)         |
Syllabic        | n(.)       | Lowered                     | e(t)         |
Non-syllabic    | e(n)       | Advanced tongue root        | e(<)         |
Rhoticity       | a(s)       | Retracted tongue root       | e(>)         |

### Unchanged from IPA
- a, e, i, o, u, y
- b, c, d, f, g, h, j, k, l, m, n, p, q, r, s, t, v, x, z
- w
- //  //, /  /, [  ], <  >

### Unchanged besides size and or font
- I, Y
- B, G, N, L, R

### Changed based on the sound of their Latin alphabet counterparts
- F (bilabial fricative)
- V (voiced bilabial fricative)
- ng (voiced velar nasal)

### Changed based on the sound in the IPA and the existing letter in OAIPA
#### Pulmonic consonants
- nn (voiced retroflex nasal)
- nj (voiced palatal nasal)
#### Other sounds/symbols
- hw (voiceless labial-velar fricative)

### Changed based on the appearance of the Latin alphabet counterparts
#### Vowels
- 0 [zero] (front close-mid rounded vowel)
- E (front open-mid)
- oe (rounded front open-mid)
- ae (front half open)
- OE (rounded front open)
- i- (central close)
- u- (rounded central close)
- 9 (central close-mid)
- (central half open-mid)
- 3 (central open-mid)
- 6 (central half open)
- uu (back close)
- U (near-back near-close)
- ^ (back open-mid)
- O [capital o] (rounded back open-mid)
- A (back open)
- A` (rounded back open)
#### Pulmonic consonants
- mg (voiced labiodental nasal)
- v` (voiced labiodental tap/flap)
- u` (voiced labiodental approximant)
- T (dental fricative)
- T` (voiced dental fricative)
- P (voiced alveolar tap/flap)
- 1 (alveolar lateral fricative)
- 1` (voiced alveolar lateral fricative)
- S (postalveolar fricative)
- Z (voiced postalveolar fricative)
- J (voiced alveolar approximant)
- D (retroflex plosive)
- D` (voiced retroflex plosive)
- [ (voiced retroflex tap/flap)
- $ (retroflex fricative)
- 2 (voiced retroflex fricative)
- { (voiced retroflex approximant)
- uq (voiced velar approximant)
- X (uvular fricative)
- K (voiced uvular fricative)
- h` (pharyngeal fricative)
- ?? (voiced pharyngeal fricative)
- ? (glottal stop/plosive)
- H (voiced glottal fricative)
#### Other sounds/symbols
- HH (voiceless epiglottal fricative)
- ] (voiced alveolar lateral flap)
- ) (affricate or double articulation marker, placed after two sounds)
#### Suprasegmentals
- ' (primary stress)
- , (secondary stress)
- : (long vowel)
- ; (half-long vowel)
- = (extra short vowel)
- | (minor foot break)
- || (major intonation break)
- . (syllable break)
- _ (linking without a break)
#### Diacritics
- (h) (aspirated)
- (w) (labialised)
- (?) (pharyngealised)
- (~) (velarised or pharyngealised)
- (T) (raised)
- (t) (lowered)
- ~ (nasalised)
#### Tone levels
- '' (top level tone)
- ' (high level tone)
- "-" [without quotes; a single dash] (mid level tone)
- , (low level tone)
- ,, (bottom level tone)
- ^| (upstep) or? |'
- v| (downstep) or? |,
#### Tone contours
- v (rising contour tone)
- ^ (falling contour tone)
- -' (high rising contour tone)
- '- (low rising contour tone)
- ~ (rising-falling contour tone)
- ">/" or "/>" [without quotes or spaces] (global rise) or? /'
- ">\ or \ >" [without quotes or spaces] (global fall) or? \ ,
