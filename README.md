# OAIPA
An open source IPA (International Phonetic Alphabet) for the ASCII character set.
Version 0.3

Pulmonic Consonants | Bilabial | Labiodental | Dental | Alveolar | Postalveolar | Retroflex | Palatal | Velar | Uvular | Pharyngeal | Glottal
---             | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---:
Plosive         | p  b  |       |       | t  d  |       | D  D" | c  j- | k  g  | q  G  |       | ?
Nasal           |    m  |    M  |       |    n  |       |    nn |    nj |    ng |    N  |       |
Trill           |    b" |       |       |    r  |       |       |       |       |    rX |       |
Tap, flap       |       |    v" |       |    R  |       |    [  |       |       |       |       |
Fricative       | F  V  | f  v  | T  T" | s  z  | S  Z  | S" Z" | -  -  | x  x" | X  K  | h- ?? | h  H
Lateral fric.   |       |       |       | hL HL |       |       |       |       |       |       |
Approximate     |       |    w" |       |    J  |       |    {  |    j  |    W" |       |       |
Lateral approx. |       |       |       |    l  |       |    l" |    j" |    L  |       |       |

Vowels | Front | Fr. Cen. | Central | Cen. Bk. | Back
---            | :---: | :---: | :---: | :---: | :---:
Close          | i  y  |       | i- u- |       | uu u
Half close-mid |       | i" y" |       |    U  |
Close-mid      | e  0  |       | 9  -  |       | -  o
Half open-mid  |       |       |    -  |       |
Open-mid       | E  oe |       | 3  3" |       | ^  O
Half open      |    ae |       | 6     |       |
Open           | a  OE |       |       |       | A  A"

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
Centralised     | e(..)      | Velarised or pharyngealised | l(~)         |                    |
Mid-centralised | e(x)       | Raised                      | e(T)         |                    |
Syllabic        | n(.)       | Lowered                     | e(t)         |                    |
Non-syllabic    | e(n)       | Advanced tongue root        | e(<)         |                    |
Rhoticity       | a(s)       | Retracted tongue root       | e(>)         |                    |

### Unchanged from IPA
- a, e, i, o, u, y
- b, c, d, f, g, h, j, k, l, m, n, p, q, r, s, t, v, x, z
- w
- //  //, /  /, [  ], <  >

### Unchanged besides size and or font
- G, N, L

### Changed based on the sound of their Latin alphabet counterparts
- M (voiced labiodental nasal)
- F (bilabial fricative)
- V (voiced bilabial fricative)
- ng (voiced velar nasal)

### Changed based on the sound in the IPA and the existing letter in OAIPA
#### Pulmonic consonants
- b" (voiced bilabial trill)
- W" (voiced labiodental approximant)
- T" (voiced dental fricative)
- hL (alveolar lateral fricative)
- HL (voiced alveolar lateral fricative)
- nn (voiced retroflex nasal)
- l" (voiced retroflex lateral approximant)
- nj (voiced palatal nasal)
- j" (voiced palatal lateral approximant)
- x" (voiced velar fricative)
- W" (voiced velar approximant)
- rX (voiced uvular trill)
#### Vowels
- i" (front-central half close)
- y" (rounded front-central half close)
- 3" (rounded central open-mid)
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
- A" (rounded back open)
#### Pulmonic consonants
- v" (voiced labiodental tap/flap)
- T (dental fricative)
- R (voiced alveolar tap/flap)
- S (postalveolar fricative)
- Z (voiced postalveolar fricative)
- J (voiced alveolar approximant)
- D (retroflex plosive)
- D" (voiced retroflex plosive)
- [ (voiced retroflex tap/flap)
- S" (retroflex fricative)
- Z" (voiced retroflex fricative)
- { (voiced retroflex approximant)
- j- (voiced palatal plosive)
- X (uvular fricative)
- K (voiced uvular fricative)
- h- (pharyngeal fricative)
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
