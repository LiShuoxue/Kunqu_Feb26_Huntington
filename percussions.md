# Instructions of Peking Opera Percussions

## Basic Notations

| Shorthand       | Description                                              |
| --------------- | -------------------------------------------------------- |
| `x`             | Downbeat                                                 |
| `,`             | Upbeat                                                   |
| `.`             | dotted note                                              |
| `..` `...`      | Stop the stroke, the number of dots shows the time scale |
| `{` `}`         | Separate a stroke label if there is ambiguity            |
| `${}`           | Quote a set of drum notation                             |
| `[1]` `[2]`     | Single and double stroke                                 |
| `L` `R` `l` `r` | Left/right stroke                                        |
| `D` `d`         | [1] stroke; [2] Double stroke at the center              |
| `B` `b`         | Stroke at the drum edge                                  |
| `D~` `d~`       | Roll stroke. Number of `~` shows the time scale          |
| `Y` `Z` `y` `z` | Stroke of the cascanet                                   |


The shorthands below should be used after a stroke label to indicate

| Shorthand       | Description                                                         |
| --------------- | ------------------------------------------------------------------- |
| `>`             | The drumstick moves from center towards somewhere                   |
| `<`             | The drumstick moves from somewhere towards the center               |
| `l` `r` `u` `d` | Four directions on the drum surface                                 |
| `H` `h`         | Above the drum surface                                              |
| `S` `s`         | Pressing on the drum surface                                        |
| `P` `p`         | Pointing on the drum surface, upper/lower case indicate the degree. |
| `M`             | Mute stroke but still hit the drum surface                          |
| `m`             | Mute stroke without hitting the drum surface.                       |

The additional notes:

1. About `><`:
   1. If `><` are used after capitalized strokes, it indicates that we first hit the drum surface, then move the drumstick accordingly.
   2. If `><` are used after lower-case strokes, it indicates that we do not hit the drum surface but only move the drumstck.
   3. If `><` is not used between stroke label and the direction label, it indicates that we just hit the drum surface at the specified direction.
2. About the pointing label `Pp`: If a direction label occurs, `Pp` should be after it. If `>` occurs, it means that we first move the stick to the direction, then point on that direction; if not, we just move the stick end to that direction, but still point on the center.

Here we show how to denote the pattern before the *Precludio*:

```
,R{rr-} LxR D~xr>hR LxR- LxR- xR.R
```


## Common Patterns


### g1
```
[2] xr ,r xr>l-         # (41.1)
[1] xZ ,d xd>l-         # (41.1)

[1] xdr   xD            # (42.1.1)
[1] xd{d} xD            # (42.1.2)
[1] xDY   xD            # (42.1.3)

[1] xDxD.. xDDxY xD # (47.1)-(47.3)
[1] xZ xZ xD-           # (48.1)

[1] ${G1}S xdM xdM xdM...  # (50)
```

### G1 
```
xdd RxL-          # (41.2)
xdd xD{r>l}       # (41.2)
xD>h xR>h xD      # (42.2.1)
LxR,dbP xD        # (42.2.3)
xD~R xD           # (42.2.4)
xD>bS xD          # (42.2.5)

xD~~S xD          # (43.1)
xD~~p R xD        # (43.2)
xD~~xRRRR xD      # (43.3)

xD~~LxR,RR xr>l   # (44)

[1] xZh xZ xD     # (48.2)
```

### 2
```
[1g]  xdr,y xp,   xD # (52.1.1)
             l     T
[1g]     ,p xD, D xD # (52.1.2)
             T     T
[2G] xRrLl, xd,   xD # (52.2)
          T  q     C
[1G] xYdr,Y xFx xDx  # (52.2)
```

### G3
```
[2] xRL,rp xR xR xR
[2p] ,R{rr} xD xR xD
```

### G4
```
R{d>bs} xD,>d xD,RL xRL,R xD-
```

### G4[p]
```
xD   xRL  xR xL xR xD   # (57.2.1)
xD>h xRD~ xR xL xR xD   # (57.2.2)
```

### G5
```
R{rr-} xr,R xr,R LxR-
```

### Ablativo (Abl)
```
xd,d,DD,DD xDD,DD,DD,D xD,dr,D-
```

### Cappello (Cap)
```
[g] p-xDxDxD xDDxDDxD0yDxD
			 T T T  T  T  T    T
[G] rrP- xR,R xR,R.R xRR>r- xR-
      T   C c  C c    qC-    C-
```

### Cessazione (Ces)
```
[2G] R{rr-} xD ,R xD-
[1G] D{dr-} xD ,D.D xD-
```

### Martello (Mart)
```
[S] Z~~ ,DZdrp xD>r,Z~~ xD>r,Z~~ ... xD>rh,D>rh.. xD,Dd,dd,D xDD,DD,DDD0 xD-
[L] ,p0 xDZ,DZxDZ,DZ... xD,DDxDD,D xDDDD,DD00 xDz00,Z
[P] D.D xy,y xDz,DzxDz,Dz... x0D,Zd xDD,D xDD,DDxDD,D
              C7 T7 C7 T7...  C7 T   q  C  C  lC yT C
[P]                      ... xDD,Z xD
                              C7 T  C
[P]                      ... x00,p xd,d, xD,dd,dd xdd,dd,dd xD
                              C7 T  q c   C lc yT  C  lc yT  C
```

### Estrazione (Estr)
```
xDD,DD xyD,yDDD xD,DDxDD,DD... 
      ... xDD,DD xy D,y  xdd,0d xD-
                          lT yl  T-
      ... xDD,DD xy D,y  xdr,D-
                          l  T
      ... xDD,DD xdmD,dM xD-
                          T
```

### Fenice (Fen)
```
[1] xD.DxDD xdmDxdmD xYxY xdxD xDDxDD xDDxD +[A/R]
[1] x0D,Ydrp xD,z0dd xDD,D xDD,xDD xD ,D +[S]
[2] RL- xD,D~,RLRL xRL,R-RL,0R xD-  +[S]
      T  C    C T   C  T C   T  C
```

### Sfregatura (Freg)
```
xDD,DD xYD>r,YDD xYD>r,YDD xYD>r,YDD xDD,DD xDD,DD ... xYD,Y xD-
[g]               lT        lT        TT TT  TT TT ...  TT T  T-
[cym]         T   lc    T   lc    T   cT cT  cT cT ...  c7 T  c-
[G]           T   qC    c   qC    c   Cc Cc  Cc Cc ...  Cc C  C-
```

### Gong di uno Martello (G1M)
```
D~R R R rrd- xb>Uh.. LxR..     ( D~~~~~~~~~~~~~~~~~~...)
        T-    Ccccc..  Tcccc.. (xCccc,TcccxCccc,Tccc...)
```

### Nostalgia (Nost)
```
[2] xR xRR xLRxD xLxRxLxR...xLRxLR xRxR..[1]..xDxD xD.DxYxY xD.DxDxD
         T  C  c  C c C c... Cc Cc  C C        C C  C   C C  C.c C C
```

### Ploro (Plr)
```
xdb,0D~ xdbp,0D~ xdbp,0D~ xR,L xRL,db xD-
```

### Precludio (Pre)
```
[g] ,ddxD,DxD.D,DDxDDD0,D-
[G] R{rr-} LxR D~xr>hR LxR- LxR- RR
```

### Processione (Proc)
```
[G] xB L,R (xB L,R) xL L,R xL,R LxRR,LR xLR,LR... D- rr D-
     C   c ( C   c)  C   c  C c   Cc Tc  C  c ... C     C-
```

### Ritorno (Rit)
```
R{rr-} LxR D~xr>hR LxR- xD-
```

### Scattato (Scat)
```
[1] xd.d,yD,y0 xdrm,D xdrm,D ... xdrm,DDxDD,DD xD-
```

### Seta Ritorta (Tort)
```
[L] xd,d,LR0,>b D~xR,L,R,D x,RL,RL,RL.. xR,R,>b, D~xR,L,R,R LxR-
```

### Vento Prestissimo (VPP)
```
xD xDD~ xR xL xRxLxR xRLxR xRLxRLxR xD~xRLxR ...  xD,rr xD
```

### Vocativo (Voc)
```
[G] ,RL>lp- xdm,D xdM,dMxdM...
        T    q  C  T  T  T ...
```
Usage:
```
${G-Voc} 'Ah!' ${G5}|${G4[p]}
${G-Voc} 'Ah!' ${G-Voc} 'Ah!' ${G5}|${G3[p]}
${G-Voc} 'Ah!' ${G4[p]} 'Uh!' ${G3[p]} 'Ah..AHHHH!' ${G-Fret}|${G-Proc}|...
```
