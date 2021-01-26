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

##### base2048 encoded

```
Нࡐಹݬ༲ষଛΝеپƋٯసɊదكНಠƗןڈɚଛqДپSڕwѤཏಇѯবƱڅڏЬཏӶƄচєࡤߩॡधӕѲ༫ʌԚࡈѤਯӼЛɴՃٽࡈѤο੮ӋనԘദऽൽਓΤњߡҺ۱gҊ३ƜςສಥڅXɪਯӿЛڴऋڀڊɊ೦ن٣छࢴٱƨɚଛԂ༬ဏࠀڅȤݖతࡇѯУרնͼއ߁ҰНथѨٯసʅଛԀДٿԪڕଉɞథΝНߣࢻןڎɪοΥЛРƋڥଈখෂࡇДپࢲןЬɊ౬Ԃ໐थಮܤͲɢଛqДپSڅҾނࡡeʛGđҨOкೞƜݟaঘశಉҊࡗӷоࡒԌร༪еࡄԬʝਨಕ౬גкॴೠҟܬࡡȽȵɝߘӷњࡍԉฒནm౭ΡจʩԩܧԁmಛuປͽœՏҺॷǥΖμʤҺڕȤݾഹࡡݿσɢե౨Ҋ३ƗςۍࠀڕͲʫฑ੦ړԗՑ༬էФਸૐƄथಸආਦɪౙ1
```

Exactly 280 characters, so you'll have to reply to a tweet at the bot and remove the direct @ mention.

#### GIF

<img src="https://raw.githubusercontent.com/d-mckee/bbcbasic-experiments/main/02-so-hard-to-believe/so-hard-to-believe.gif" width="640">

