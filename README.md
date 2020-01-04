# OAIPA
An open source IPA (International Phonetic Alphabet) for the ASCII character set.
Version 0.4.

Main goals:
- doesn't look overly cluttered (compared to other ASCII IPA assignments)
- covers most if not all of the IPA
- shouldn't have a need to learn the sounds of arbitrary symbols like @, #, etc.

Pulmonic Consonants | Bilabial | Labiodental | Dental | Alveolar | Postalveolar | Retroflex | Palatal | Velar | Uvular | Pharyngeal | Glottal
---             | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---:
Plosive         | p  b  |       |       | t  d  |       | T  D  | c  gj | k  g  | q  G  |       | ?
Nasal           |    m  |    M  |       |    n  |       |    nn |    nj |    ng |    N  |       |
Trill           |    B  |       |       |    rr |       |       |       |       |    rX |       |
Tap, flap       |       |    v" |       |    r  |       |    RL |       |       |       |       |
Fricative       | F  V  | f  v  | th tH | s  z  | S  Z  | S" Z" | SJ ZJ | x  x" | X  X" | h- ?? | h  H
Lateral fric.   |       |       |       | hL HL |       |       |       |       |       |       |
Approximate     |       |    w" |       |    R  |       |    R" |    j  |    W" |       |       |
Lateral approx. |       |       |       |    l  |       |    l" |    J  |    L  |       |       |

#### Non-pulmonic consonants
table here

Vowels | Front | Fr. Cen. | Central | Cen. Bk. | Back
---            | :---: | :---: | :---: | :---: | :---:
Close          | i  y  |       | i- u- |       | uu u
Half close-mid |       | i" Y  |       |    U  |
Close-mid      | e  ee |       | y" o- |       | UU o
Half open-mid  |       |       |    e" |       |
Open-mid       | E  oe |       | AE YY |       | AA O
Half open      |    ae |       |    a" |       |
Open           | a  OE |       |       |       | A  A"

#### Other symbols
- hw (voiceless labial-velar fricative)
- w (voiced labial-velar approximant)
- (voiced labial-palatal approximant)
- HH (voiceless epiglottal fricative) [to be changed]
- (voiced epiglottal fricative)
- (epiglottal plosive)
- (alveolo-palatal fricatives)
- (voiced alveolar lateral flap)
- (simultaneous S and X)
- ) (afficate and double articulation marker)

#### Diacritics
In situations where information is clear and uncluttered, the closing parenthesis is not mandatory.

Description | Example | Description | Example | Description | Example
--- | :---: | --- | :---: | --- | :---:
Voiceless       | n(v), d(v) | Breathy voiced              | b(,,), a(,V) | Dental             | t(d), d(D)
Voiced          | s(V), t(V) | Creaky voiced               | b(~~), a(~V) | Apical             | t(a), d(A)
Aspirated       | t(h), d(h) | Linguolabial                | t(m),  d(M)  | Laminal            | t(L), d(L)
More rounded    | O(R)       | Labialised                  | t(w),  d(W)  | Nasalised          | e~
Less rounded    | O(r)       | Palatalised                 | t(j),  d(J)  | Nasal release      | d(n), d(N)
Advanced        | u(+)       | Velarised                   | t(y),  d(Y)  | Lateral release    | d(l)
Retracted       | e(_)       | Pharyngealised              | t(?),  d(?)  | No audible release | d(-)
Centralised     | e(..)      | Velarised or pharyngealised | l(~)         | Not a diagraph     | t*H
Mid-centralised | e(x)       | Raised                      | e(T)         |                    |
Syllabic        | n(.)       | Lowered                     | e(t)         |                    |
Non-syllabic    | e(n)       | Advanced tongue root        | e(<)         |                    |
Rhoticity       | a(s)       | Retracted tongue root       | e(>)         |                    |

#### Suprasegmentals
- ' (primary stress)
- , (secondary stress)
- : (long)
- ; (half-long)
- = (extra short)
- | (minor foot break)
- || (major intonation break)
- . (syllable break)
- _ (linking without a break)
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
