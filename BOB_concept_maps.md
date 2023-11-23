<!--
author:   Dr. Mark Jacob
email: mark.jacob@iuz.tu-freiberg.de
version:  0.0.1
language: en
narrator: UK English Female
comment: Content of week 3 WS 2023/2024
icon: https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/TUBAF_Logo.svg/800px-TUBAF_Logo.svg.png
script:   https://cdn.jsdelivr.net/npm/mermaid@10.5.0/dist/mermaid.min.js
import: https://raw.githubusercontent.com/liaScript/mermaid_template/master/README.md
-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://github.com/TUBAF-IUZ-LiaScript/EF_BOB_23/blob/main/BOB_concept_maps.md)

# Concept maps

## sample map

```mermaid @mermaid
flowchart TB
    classDef someclass fill:#f96;
    A[Concrete] --> B
    A:::someclass --> C
    C[Language] --> V[Words]
    C --> W[Interaction]
    V --> I[Etymology]
    I --> AD[com lat. = together]
    AD:::someclass --> AK
    I --> AE(cretus lat. = grown)
    AE:::someclass --> AK[grown together]
    AK:::someclass
    
    V --> J[Collocations]
    J --> I
    J --> reinforced:::someclass 
    P --> R[Processes]
    R --> AK
    R --> AP[Inputs & Outputs]
    W --> P[Describing]
    J --> P
    W --> Q[Discussing]
    Q --> AG[Argumentation]
    AG --> AP
    AP --> S[Presentations]
    AP --> AQ[Texts]
    AQ <--> AR[Concept maps]
    S --> AI
    S <--> AR
    
    B[Subject] --> D[Composition]
    D --> N[Aggregate]:::someclass 
    D --> O[Cement]:::someclass 
    B --> E[Production]
    E --> L[Mixing]:::someclass 
    E --> M[Curing]:::someclass 
    B --> F[Structure]
    F --> AA[Homogeneity]:::someclass 
    F --> AB[Porosity]:::someclass 
    B --> G[Properties]
    G --> X[high compressive strength]:::someclass 
    G --> Y[Water resistant]:::someclass 
    B --> H[Applications]
    H --> Z[Dams]:::someclass 
    H --> AC[Furnaces]:::someclass 
    D --> E
    E --> F
    F --> G
    G --> H
    B --> AH
    H --> AH[Impacts]
    AH --> AJ[Economic]:::someclass    
    AH --> AI[Environmental]:::someclass 
    X --> Z
    Y --> Z
```

## Concept map RK

```mermaid @mermaid
flowchart TD
    A[new space telescope Euclid] 
    A-->|European Space Agency ESA| B(launch an 1 July)
    A-->C(designed to help solve mysteries of)
    C---D(dark energy) 
    C---E(dark matter)
    D---|therefor has|F(two scientific instruments)
    E---|therefore has|F
    F---G(visible light camera)
    F---H(near-infrared detector)
    A---I(intended to observe a huge swathe of space)
```

## Concept map SH

```mermaid @mermaid
flowchart 
    A[Quantum Computing >QC<] 
    A-->B[successful research progress at Google]
    A-->C[Problem: Qubits in QC interference and create errors]
    B-->D(Google research demonstrated possible scaling of quantum error correction)
    C-->D
    D-->E(logical Qubits can be build bigger)
    D-->F(error interference can be reduced)
    D-->G(Google researchers believe in useful QC within years)
    E-->I[Problem: scaling up to bigger logical Qubits will 
    require a big step forward in hardware]
    F-->H[small improvement but in theory scaling up is possible]
    G-->J[>>There is palable confidence that a commercially useful 
    device will be created<< -Hartmud Neven at Google]
    H-->K(CONCLUSION: overall confidence in scalable quantum error correction in the future is pretty high)
    I-->K
    J-->K
```

## Concept map OL

```mermaid @mermaid
flowchart TD
    Z2[raising global wealth, less poverty] --> A
    Z[more eduction for woman] --> A[people having fewer children]
    Z1[access to contraception] --> A 
    A -->B(global population growth comes to an stop)
    B -->C(estimations were reduced further for the peak of the global population)
    C -->D[estimated peak at 2040 at 8.5 billion 
    according to Earth4All Modell created by the Club of Rome ]
    D -->E[fall of the population to 6 billion until the end of the century]
    C -->F[consequences]
    F -->G[decressing of active working people]
    F -->H[will not help to fix the climate]
    H -->H1[important tipping points will be reached to fast]
    G --> G1[more difficulties to keep healthcare systems working]
    H --> H2[a faster population decline would be needed 
    for a more positive impact on the climate]
```

## Concept map BP

```mermaid @mermaid
flowchart TB
A[Tiny metal robot]
A-->B[material]  
A-->C[use]
B-->D[galium, neodymium, iron and boron]
C-->E[unnormal stuff]
F-->G[can jump]
F-->H[carry over 30x of own mass]
E-->I[can melt and go through minimalistic spaces]
A-->J[how]
J-->K[magnetic field change]
```


## Concept map TR

```mermaid @mermaid
flowchart LR
D[src: doi.org/j6tw]
A[Zebra finches]
A-->|male|E[unique songs, >1000]
E-->B[learned in first 90 days]
E-->C[attract females, reproduction]
A-->R[having break from crooning]
R-->w[result: lower pitch, shorter length]
R-->S[experiment: stopped 16 from singing]
S-->z[weight on neck]
w-->t[reason: lack of muscle use]
F[Suspection]-->k[other birds need practise daily too]
```

## Concept map FG

```mermaid @mermaid
flowchart TD
    A[Splitting of humans from common ancestor] --> B(Neanderthals and Denisovian)
    B --> |Moving north| C[effect on sleep-wake cycles]
    B -->|interbreeding| D[inheritence of genoms]
    D --> E(Modified cycles in Europeans)
    F --> E 
    H --> F[Survival Benefit]
    E --> G(Morning people)
    C --> H(faster adptation to changes in day night cycle)
```

## Concept map HG

```mermaid @mermaid
flowchart TD
     C{frozen flower in amber}
    C --> D[size]
    D --> H[worlds largest flower in amber
        three times as large as other flower fossils ]
    D --> I[28 millimeters in diameter]
    D --> L[five-petalled flower]
    C --> E[origin]
    E --> J[discovered and described in 1872]
    E --> K[around 33.9 to 38 million yeras old]
    E -->G[was found in a mine in russia]
    C -->F[analys]
    F -->|focus on its pollen| M[s]
    C --> |the first descirbtion| N[categorised as coming from evergeen
            plant called stewartina kowalewskii ]
    N -->  |wrong| M[similarities with pollen from the modern flower Symplocos]
    M --> O[renamed the fossil to Symplocos kowalewskii]      


```

## Concept map NW

```mermaid @mermaid
 
```

## Concept map YH

```mermaid @mermaid
flowchart TD
    A[grwon up orca female ] -->|give birth | B(orca calf )
    B --> C(female orca )
    B-->D(male orca)
    C -->|feed| F(orca grows up)
    F --> |feed themselfs| F
    F --> |cycle repeats| A
    D --> |feed| G(Orca grows up)
    G --> |feed themselfs| G
    A--> H(keeps feeding)
    H -->G
    G --> |isn´t able bear another healty calf|A
    H --> |don´t feed another younger calf| C
    H --> |don´t feed another younger calf| D

```

## Concept map MB

```mermaid @mermaid
flowchart TD     
A[Real life on mars] --> B{building a city}-->b(problems)     
b-->C(Energy)-->c(huge solar fields)     
b-->D(Radiation)-->d(Building underground)     
b-->E(Resources)-->e(mining)    
c-->F{Money and Science}     
d-->F     
e-->F              
```

## Concept map BM

```mermaid @mermaid
flowchart TD
    A[plant alga] -->|grow for 50 years|B(become a conglomeration of one independent organisms)
    B --> C{what is inside?}
    C -->D[bacteria]
    C -->E[viruses within bacteria]
    D --> F[strange]
    E --> F 
    F --> J[symbiosis is not unusual, in plant cells] --> |however|O[Algae is not a plant cell]
    F -->|lets look| G[sequence all the DNA]
    G -->K[Symbiosis, but how?]
    K-->|don´t know|N[There must be a balance]
```

## Concept map NS

```mermaid @mermaid

```

## Concept map KS

```mermaid @mermaid

```

## Concept map LT

```mermaid @mermaid
flowchart TD
    X{$2billion}-->|invested in|A
    A[[Lab-grown meat]]-->|does|B[produce 4-25 times more CO2]
    A[[Lab-grown meat]]-->|could|C(be greener than regular beef)
    C-->|coming with|D(lesser/no slaugther of livestock fa:fa-cow)
    C-->|coming with|E(no need for farming facilities)
    E-->F(less land needed)
    B-->|because of|G[production components]
    G-->H[nutrients]
    G-->J[vitamins and medication]
    
```

## Concept map CR

```mermaid @mermaid

mindmap
  root((Digital Playtime))
    Negative Mindset
        parent concerns
          addiction
         too much time spend
     no time to deal with topic
        dont have time to waste mindset?
    Positive Mindset
      fond chilhood memories
      share video game journey of kids with parents, instead of fighting against it
     improved competence, social connection
     also experience violent part of world

```

## Concept map EN

```mermaid @mermaid

```