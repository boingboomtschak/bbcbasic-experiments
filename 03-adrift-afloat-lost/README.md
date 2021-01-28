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

[Source code in Owlet Editor](https://bbcmic.ro/#%7B%22v%22%3A1%2C%22program%22%3A%22%C3%AB1%3Ac%3D1%3As%3D64%3Ax%3D1280%2Fs%3Ay%3D1024%2Fs%5Cn%C3%A3i%3D0%C2%B8s%5Cn%C3%A60%2Cc%5Cn%C3%AC0%2Ci*y%3A%C3%B05%2Ci*x%2C1024%5Cn%C3%AC0%2Ci*y%3A%C3%B05%2C%28s-i%29*x%2C0%5Cn%C3%AC1280%2C%28s-i%29*y%3A%C3%B05%2C%28s-i%29*x%2C0%5Cn%C3%AC1280%2C%28s-i%29*y%3A%C3%B05%2Ci*x%2C1024%5Cn%C3%A7c%3C3%C2%8Cc%3Dc%2B1%C2%8Bc%3D1%5Cn%C3%AD%5Cn%C3%AF31%2C17%2C10%5Cn%C3%BB3%5Cn%C3%B1%5C%22..adrift..%5C%22%5Cn%C3%AF31%2C14%2C14%5Cn%C3%BB2%5Cn%C3%B1%5C%22..afloat..%5C%22%5Cn%C3%AF31%2C10%2C18%5Cn%C3%BB1%5Cn%C3%B1%5C%22..lost.%5C%22%5Cn%C3%AF5%5Cn%C3%B5%5Cn%C3%A7c%3D1%C2%8C%C3%B1%5C%22%5Cu0013%5Cu0001%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0013%5Cu0002%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0013%5Cu0003%5Cu0002%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5C%22%5Cn%C3%A7c%3D2%C2%8C%C3%B1%5C%22%5Cu0013%5Cu0001%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0013%5Cu0002%5Cu0002%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0013%5Cu0003%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5C%22%5Cn%C3%A7c%3D3%C2%8C%C3%B1%5C%22%5Cu0013%5Cu0001%5Cu0002%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0013%5Cu0002%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0013%5Cu0003%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5Cu0000%5C%22%5Cn%C3%A7c%3C3%C2%8Cc%3Dc%2B1%C2%8Bc%3D1%5Cnz%3D%C2%A6%28100%29%5Cn%C3%BD%C2%A3%22%2C%22author%22%3A%22%40boingb00mtschak%22%2C%22date%22%3A1611713852895%2C%22id%22%3A%221354252115279974401%22%7D)

##### base2048 encoded

```
ຈࢠঔޑȷѨཏಇѯయԪڕࠄɗ೦ՂҏࡩƗڴཥࡁआζИౙవಽUРϢࡆϨԒ৭ݭYॷਸՁϦࡩƗڲଇɚଢΛއ൬ƝמࡏॻਸΛݿپT൳ȥɺతࠔݗێԚպहݾഹࠔݗێԚպࠂɚϢࡇХబƋՐЪୠਸՂѳߤԠദઌɊ౬wдו൶ށѢРབڝРثഌڂଇࡁ௱ڣϦࡪಮڅD߃ಸمʫܬঌಜΦଯങ౼ʪחೡڄసঞଛΦƊൽࠁ෮ͱɓࡂ೫ܜƐƏصʟݺೡΝНߢƕܡଐঐϣΓϽݙɸฤҽƿϢยƊઔமಆബಆ౪ҹG888Hߟ888Cథe88CҰศɩԭɩǷŧe888keʚ88RW888Pp১گаڮԌΡƸ888ȤƷ888ŧƓ888ĸɈݯ৫ೱࢶґɤಽɐвঐψԅ੯ҲԨٯञߍघ
```

Only 255 characters encoded, so you can @bbcmicrobot and paste the base2048 encoded version.

#### GIF

<img src="https://raw.githubusercontent.com/d-mckee/bbcbasic-experiments/main/03-adrift-afloat-lost/adrift-afloat-lost.gif" width="640">
