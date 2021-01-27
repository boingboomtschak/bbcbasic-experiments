#### BBC BASIC code

```basic
MODE 1:c=1:s=64
FORi=0TOs
GCOL0,c
MOVE0,i*(1024/s):PLOT5,i*(1280/s),1024
MOVE0,i*(1024/s):PLOT5,(s-i)*(1280/s),0
MOVE1280,(s-i)*(1024/s):PLOT5,(s-i)*(1280/s),0
MOVE1280,(s-i)*(1024/s):PLOT5,i*(1280/s),1024
IFc<3THENc=c+1ELSEc=1
NEXT
V.31,17,10
C.3
P."..adrift.."
V.31,14,14
C.2
P."..afloat.."
C.1
V.31,10,18
P."..lost."
V.5
REPEAT
IFc=1THENPRINT"ēāĀĀĀĀĀēĂĀĀĀĀĀēăĂĀĀĀĀ"
IFc=2THENPRINT"ēāĀĀĀĀĀēĂĂĀĀĀĀēăĀĀĀĀĀ"
IFc=3THENPRINT"ēāĂĀĀĀĀēĂĀĀĀĀĀēăĀĀĀĀĀ"
IFc<3THENc=c+1ELSEc=1
z=INKEY(65)
UNTIL FALSE
```

##### base2048 encoded

```
ຈࢠঔޑȷѨཏಇѯయԪڕࠄɗ೦ՂҏࡩƗڴཥࡁआζИౙవಽUРϢࡆϨԒ৭ݭYॷਸՁϦࡩƗڲଇɚଢΛއ൬ƝמࡏॻਸΛݿپT൳ȥɺతࠔݗێԚպहݾഹࠔݗێԚպࠂɚϢࡇХబƋՐЪୠਸՂѳߤԠദઌɊ౬wдו൶ށѢРབڝРثഌڂଇࡁ௱ڣϦࡪಮڅD߃ಸمʫܬঌಜΦଯങ౼ʪחೡڄసঞଛΦƊൽࠁ෮ͱɓࡂ೫ܜƐƏصʟݺೡΝНߢƕܡଐঐϣΓϽݙɸฤҽƿϢยƊઔமಆബಆ౪ҹG888Hߟ888Cథe88CҰศɩԭɩǷŧe888keʚ88RW888Pp১گаڮԌΡƸ888ȤƷ888ŧƓ888ĸɈݯ৫ೱࢶґɤಽɐвঐψԅ੯ҲԨٯञߍघ
```

Only 255 characters encoded, so you can @bbcmicrobot and paste the base2048 encoded version.

#### GIF

<img src="https://raw.githubusercontent.com/d-mckee/bbcbasic-experiments/main/03-adrift-afloat-lost/adrift-afloat-lost.gif" width="640">
