# Cheating Sheet

## 标记说明

- `x`与`,`为板眼标记；`..|...`表示鼓键停止，任由下手击打
- `L|l`左键，`R|r`右键，`D|d`双键 `B|b`双键交边, `D~|d~`双键轮击，大小写标记轻重
- `T`为（一般用于起式）的小锣点
- 锣鼓标记的第二个字母及之后表示方位
  - 若无，则表示击打鼓键中心
  - `l|r|u|d`为鼓面的左右上下，与鼓键标记连用表示击打部位。若表示鼓键不击打，只是位移到该方位，则在鼓键标记和方位标记之间加上`>`
  - `H|h`为鼓面以上，大小写表示高的程度，`S|s`为压住鼓键，与鼓键标记连用表示此时最终停留的状态
  - 为消除歧义起见，可以在一次鼓键操作前后加上括号`{}`分隔，例如念作“多多大”则记作`xr{r},R`。

## 重点底鼓

五击头的使用：
1. 貂蝉初次上场
2. 院子和翠环拌嘴完之后下场
3. 王允去议事下场
4. 貂蝉吕布歌舞毕饮酒
5. 吕布两次“请转”之前的出门

```sh
alias xCc.. = "xB>Uh.."
alias DT_trans = "xl>luxxR{rr-}"
```

吕布出场的成套底鼓打法（回头圆场-四击头-回头长尖-归位）

```python
D~R R R rrd-  xCc.. LxR.. # 回头s
xB L,R xB L,R xL L,R xL,R LxRR,LRxLRLR... # 圆场
DT_trans xD, xD,RLxRL,Rr- # 四击头
xDD~~~~R R R rrd-  xCc.. # 回头
xD,D~... # 长尖
DT_trans xD D~xR>HR LxR- xrr xD- # 归位
```

不同的一锣：
```python
D~S H xD        # 嘟～仓
D~ xDh xRh xD   # 嘟～崩登仓
```

唢呐尾声转圆场打下：
```python
xLR, xL,R xLR,LR xr{r},R xLR,LR x,  R{rr-} xCc.. <G-proc/>
```