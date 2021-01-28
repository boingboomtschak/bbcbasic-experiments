#### BBC BASIC code

```basic
MODE1:VDU19,1,4,0,0,0,0:VDU19,2,6,0,0,0,0
dr=64:st=16:f=20
DIMDx%(dr):DIMDy%(dr)
FORi=0TOdr
Dx%(i)=RND(1280)
Dy%(i)=RND(1024)
NEXT

GCOL0,3:PROC_R
GCOL0,2:PROC_R
GCOL0,1:f=f*2:PROC_R
GCOL0,0:MOVE280,512:PLOT101,1024,684
GCOL0,3:VDU28,10,20,30,12:VDU23,8202,0,0,0
PRINT"         is it really"
PRINT"so hard to believe?.."
END

DEF PROC_R
FORd=0TOdr
MOVEDx%(d),Dy%(d)
PLOT5,Dx%(d),Dy%(d)-f
Dy%(d)=Dy%(d)-f
NEXT
ENDPROC
```

[Source code in Owlet Editor](https://bbcmic.ro/#%7B%22v%22%3A1%2C%22program%22%3A%2210%C3%AB1%3A%C3%AF19%2C1%2C4%2C0%2C0%2C0%2C0%3A%C3%AF19%2C2%2C6%2C0%2C0%2C0%2C0%5Cn20dr%3D64%3Ast%3D16%3Af%3D20%5Cn30%C3%9EDx%25%28dr%29%3A%C3%9EDy%25%28dr%29%5Cn40%C3%A3i%3D0%C2%B8dr%5Cn50Dx%25%28i%29%3D%C2%B3%281280%29%5Cn60Dy%25%28i%29%3D%C2%B3%281024%29%5Cn70%C3%AD%5Cn90%C3%A60%2C3%3A%C3%B2_R%5Cn100%C3%A60%2C2%3A%C3%B2_R%5Cn110%C3%A60%2C1%3Af%3Df*2%3A%C3%B2_R%5Cn120%C3%A60%2C0%3A%C3%AC280%2C512%3A%C3%B0101%2C1024%2C684%5Cn130%C3%A60%2C3%3A%C3%AF28%2C10%2C20%2C30%2C12%3A%C3%AF23%2C8202%2C0%2C0%2C0%5Cn140%C3%B1%5C%22%20%20%20%20%20%20%20%20%20is%20it%20really%5C%22%5Cn150%C3%B1%5C%22so%20hard%20to%20believe%3F..%5C%22%5Cn160%C3%A0%5Cn180%C3%9D%20%C3%B2_R%5Cn190%C3%A3d%3D0%C2%B8dr%5Cn200%C3%ACDx%25%28d%29%2CDy%25%28d%29%5Cn210%C3%B05%2CDx%25%28d%29%2CDy%25%28d%29-f%5Cn220Dy%25%28d%29%3DDy%25%28d%29-f%5Cn230%C3%AD%5Cn240%C3%A1%22%2C%22author%22%3A%22%40boingb00mtschak%22%2C%22date%22%3A1611643241142%2C%22id%22%3A%221353955917209849856%22%7D)

##### base2048 encoded

```
Нࡐಹݬ༲ষଛΝеپƋٯసɊదكНಠƗןڈɚଛqДپSڕwѤཏಇѯবƱڅڏЬཏӶƄচєࡤߩॡधӕѲ༫ʌԚࡈѤਯӼЛɴՃٽࡈѤο੮ӋనԘദऽൽਓΤњߡҺ۱gҊ३ƜςສಥڅXɪਯӿЛڴऋڀڊɊ೦ن٣छࢴٱƨɚଛԂ༬ဏࠀڅȤݖతࡇѯУרնͼއ߁ҰНथѨٯసʅଛԀДٿԪڕଉɞథΝНߣࢻןڎɪοΥЛРƋڥଈখෂࡇДپࢲןЬɊ౬Ԃ໐थಮܤͲɢଛqДپSڅҾނࡡeʛGđҨOкೞƜݟaঘశಉҊࡗӷоࡒԌร༪еࡄԬʝਨಕ౬גкॴೠҟܬࡡȽȵɝߘӷњࡍԉฒནm౭ΡจʩԩܧԁmಛuປͽœՏҺॷǥΖμʤҺڕȤݾഹࡡݿσɢե౨Ҋ३ƗςۍࠀڕͲʫฑ੦ړԗՑ༬էФਸૐƄथಸආਦɪౙ1
```

Exactly 280 characters, so you'll have to reply to a tweet at the bot and remove the direct @ mention.

#### GIF

<img src="https://raw.githubusercontent.com/d-mckee/bbcbasic-experiments/main/02-so-hard-to-believe/so-hard-to-believe.gif" width="640">

