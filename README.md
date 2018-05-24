# Kezdő programozás

A kurzus célja, hogy a résztvevők betekintést nyerjenek a programozás világába.
Megismerkedünk az programozói gondolkodásmóddal és áttekintjük az alapvető
programozási eszközöket. A tanfolyam **nem** igényel semmiféle előismeretet, a
tananyag ennek tükrében került összeállításra, sok-sok gyakorló példán mélyítjük
el az új ismereteket. Törekszünk arra -szem előtt tartva, hogy ez egy új világ
lesz számodra-, hogy a bemutatott megtanult dolgok, a lehető legkevésbé legyenek
bármiféle programozási nyelvhez kötve, azt csupán mint eszközt használjuk a
tanult dolgok bemutatására, kipróbálására.

A kurzus kezdetben a Python nyelvet használja, de hamarosan bővítjük a palettát,
hogy a számodra legszimpatikusabb nyelvvel vághass bele ebbe az új, izgalmas
kalandba. A későbbi új nyelvek megjelenése a kínálatban, nem jelenti a tudásanyag
differenciálódását. Fontosnak tartjuk, bármelyik nyelvet választod a későbbiekben
a tanulás elkezdéséhez, az elsajátított tudásanyag nem függ a kiválasztott nyelvtől.

### Tematika:

1.  Adatok típusai, változók, I/O
2.  Logikai típus, elágazás
3.  Ciklusok
4.  Függvények, eljárások
5.  Összetett típusok(OOP)
6.  Összetett típusok(OOP) + modularizáció
7.  File-hibakezelés
8.  Projekt
9.  Projekt
10. Projekt

### Projekt

A kurzus folyamán megszerzett tudást arra fogjuk használni, hogy megvalósítsunk
egy képkonvertáló alkalmazást az "asciify"-t. A projekt elkészítéséhez minden
tudásunkra szükség lesz (itt-ott picit többre is), de nagyon hasznos megtapasztalni
az utat egy komplettebb program tervezésétől kezdve a megvalósításon át egészen
a használatának öröméig.

### asciify

.....................''''.'''.''...''''''''''''''''''.'''..........................
.....''.'...''..'..'''''''''.'''''..'.''''''''''''''''''...........................
.   ...'''.''..''''''''''''''''''''''.''''''''''''''''''''''''.........................
.       .''.''''''''''''''''''''''''''''''''''''''''''''''''''.''......................   
..      .'.'''.''''''''''''''''''''''''''''''''''`````''''''''''''.................       
...     .'.'''''''''''''''''''`''''''````````'^"!!>;>"----'`'''''''...'......             
...     .''''''''''''''''''''''''''-^----">;0iiijiii=>"-'''-`''''''''...                  
...    .'''''''''''''''''''''''`--''..   .'!=0===ji0ij="--^''''```''....  .               
...    .'''''''''''''''''''`''^^`'..  .'''''"=;=>!===00!"!-`----^^--'``'.....             
....   .''''''''''''''''''``""-'`'..'``''''-`;>>>!^=>;;"^^-^^---^""^^--^-''.......        
.'.   .''''''''''''''''`'`^;>!!!""^^'--!>!-''"^-"^';!>^'`'``'-'-^>;=;;!!"""-'....  ...    
.'..  .''...'.''''''''`-">;;;>>>;>;=;!-'">!^"^'``''!!!`''''"!"^^^">=0==00;;>!^`'........ .
''... .....'..''.''''^"!>>>!!!"---^"^"!^`-"-^''```-^!^-''^"!""^--^">=000iji==;!^`'........
''..  .....''.'''`'^""!>!"'`'''``'`'`'`^-'^""-'''^^"!!^"!"^-----^^"!>=00ijlj00=;!-`'......
'..' .........'`'^!"">>!!!""""""^'''''``--">;>^">;;;;>>>!"^-----^"^!;000ijltli0=;>"-`'....
'..' ...'..''``-^">>!^''```'-^^"^-``-!!!!>=iji0ijjjjii0=;!"^---''-^";=0iiiltclii0=;!^'`''.
'... ....'''`'^^"!"-'`'...  .'`''''^;itttlcoaaooofcctlji00=>!^--''`-">;=illtccliji0=>!-'''
'.. ...''''`''-^^^'''`'''.''..'`-"!;jcoaVV5e555Vaaoffclji0=;;>"-''''`^"";0jlcfcljjji0;!-``
'.. .....``''^"""'''`'.....''`-;0jllco5eebbbbbebe5Vaaffctli===;!"^'''''--";ijfffllljji;!-.
''....''``'`'!"^-^-`'.....`^!=jtfoaV55bbDppppDDDbbee55Vaaoftlji0;!"-`..'`'-==taoftlljji;"-
.'.''`````''!>"^!--`......'^0lcoV5eebDppgggggppppDDDbbbbeee5Vaafcj=!^`. ..'^=;oVoftlljl0>"
'`'`'''`'--!>;">"-''...   .>foVebDpgggggggggggpppppppDDDDDDDbbe5aftj="-'  .'>!=ofcctlljl=!
``.'''`'`'>;=;!!"^`''`..  .l5bppggggggggggggggggggggppppppppDDbb5afti=!''  .-;"ifccclljjj=
'..'''``-"0=i>"""'`'``''. 'fbpppgggggggggggggBBBggggggggggggpDDbe5afti;"''  `!>!ittttjiilj
'..'''`^!=;l0!""-'```'`''.'obDpppgggggggggggggggggggBBBBBBgggppDbe5Voci>^`. '^>!;0llljj0ij
`''''''";jjj=>>^-'```''``.'fDppppppppppgpppgggggggggggggggggBggpDbe5VVfj>'. .--">0iljij0ii
'.'`'-^!iili=0>"-'``'''''.'cbppppppppppDDDDDDDppDDDbbbbDDDDDDDDDDbb5VVocj;' .`'`^;0jjiij00
'.'''-!>illiij!"-'''''''''`cDpppDDDDDDDbbbbeeebe5aoctljtfooaVV55ee55VVacti>''.''`-;jliil0=
''`'``>>jttjjj;!^-''`'`'^''cDDDDbbbbbbbbe555Vot0>!!!;0jtccccffoooaoaaVafctj>`'``'`^illlll0
''''`^="jtllll;=!---'"'`!`"t5eeeeee5eee55Vaoi>"">;;>!^-'`''`'-!=jttcoaaoofti!`'`''^0llijtj
`'``'"";jllltl;0;^--^>"-='^>0i000ilca5eee5afl000=;"-'"-''...`..'"0jcaVVaaocl0^'`'`"0ttliil
`'`.';-0jjtlcl;=;!^-!=;^0-`-^"-````'!oDpgpeacji00=!^icl^`'--^^;lfa5ebbe5Vafti>`'`^!icctlil
'-. >"^0iitlcl===>^^>=;-=-'`.. .'..  'pmmBpefcfffl0jtcfcjijjtfVebDpppDbeVafli>'-^=0jffcjll
``.--';ii0jltji==>"-!;;">!'`'  `=>''"0mHHmgD5Vebeeb5VooffooVeDggBBBBgpDeVocl0!'^;cltffcjtl
```''!===i0jt=0=0>!^">;">;"!^-'`^;itoBHHHmBpDbDDpppDbeeebDpgBmmmmBBgpDb5afti;^-;lfttffcjct
`-'`^0;==j;ij===;0>"!>j=;i;;^!"";ilfbmHHHmBpDDDDpggBmmmmmmmHHHmmBBgpDb5afcj=!--jctllcctjcc
``'^>=>;0i=iii=;;;==>=li=j!=!^>;itabBHHHHmBgppDDpgBmmHHHHHHHHHmmBBgDbeaocli;"-!ltlijlcljcc
`'^>>;;00jilll=;;;;0>;i0;i""!-"=loeBHHHHHmBpDDDDDDgBmmHHHHHmmmBBggDb5Voctj0>"^=jliijltllct
^"!>>==;ljlcct0>>>;i!!==!=^---^=toDmHHHHmgpDDgggpebgBBBmmBBBggppDb5Vaoftlj=>";;lj00jjljttl
"^">;==jllfffcj>^!==!">!!!--'-^=loDBmmBgpDeebDDDbVapggggggppDDbe5Vaofcttlj0;;;=ji;0iijjtjj
^-!;;>ijtfffcli="">>>^"^"^^-'-->jca55eVocljjjjtcctaDggppDDbbe5Vaoofcctllli0=0!=00;000iiji0
"^>>!illcfctlli=>"!>!^^^-^-'-''^=lcaVajiii=00ijfVeDpggpDbee5Vaofcccttttlli==!>0jj>=00ii0i0
"""!illffccllli==;!!""^^-^---''-^0toVeb5accaeDDppggggppDDbeVaoffffccttttji0;=ltc=^;==00ij=
""!=itoofclltjiii=;!"""""^---'''-^itoepggggBBBggggppDbe555VVaoaaoofccctlii=ioao0!";==iijj>
^!;0jctct00jiiiii0;;"^"!!^^-^-'-^'^=iVbebgpeVVVeeee5acj00jfooaVaofccctli==0clii!>>;=ijll=!
^";0jll0;>==0iiji0;=>""!!^"^^^-^!`.^;ij>>;=!""!>>>>;=iltccfffoffcttllji=>;0>>=0!;;;=llll!>
-;=0ii;>!;=000ii00;;>!""""^"^^"!;-..`>jcfoaocfoooofffooaaaaaofctlljji0=>>;>;>0l=0;=jttt0;=
!;;==;>!>;===0jiii;;;>!!^""""">;0--. '"lccljiijjjtcfoaVVVVVVaoctljji0;!>""=00lflji0cccl;=0
!>;;;""!>;00=jiii0;>;;>!^""!!>=ii''-..'^o555555eeebbbDbbbe5Vaftjii=;!^!-!-0tlfoflijootj>0j
!>>>"^"!!;=iij0ij=>!;;>!""!!!;jii^`-' ..;eDggBBBBBBBggpDe5aftj0=;!"'`!--!"ifttccj0cooti!jj
"!!!^^!!>=ijii0i0;">!=>!"!>!>;lij!''"`...jbDpppgggggpDe5acli;!"^--'`"^'-;;iccljliicofliiti
""!"""!!;jljjiii=>!>!0>!>>;!>=ljj>^'`"'.. ;aee5eeee5aocl0>"---''``--!^`^>=jlljjlijfaclilji
^-"^""!;itlllj00;!>>;=>>;;=!;itlj!-`'`"'.   -!>>;;=;>!"-''''''`'``'"!'-">;0ijjljjtfctlilij
^^"^"!;0llltll0=;>>>=>;;=;;>0lll0>"''.-''       .'--'``````'''````->"-"!==0ijjjijlfltljiij
--^"=;0jljjjjj====>==;==;;;;itlj;;"^'``''.    '">-`'''`'''``''''-^"=>;=0ijjii0ijllficti=00
'^=00ijjjiiiii00i=0=;=ii!=;0ltji>=>-````''..`"!-'.''"!!!""^""""!"">0=;jjlji0=00jttojcti===
"=00illjljjji0ii0j0!;i0;!;=illi;";"-'''''''-^^'..'`-^!;000==>!"!>==jljjjji0;=i0lccolclj=00
"!;jlttjlljjjijil=!!=i0">;0ltj;!^!!-'^''.'--"'''`^>=0i0=;;>>!>0iijtfclllj=;=0i0tccfttji=00
=jlttccljiiiijti>!>"i=>">;jtj="-^^!'-!''.^`"'''!>"^^!>>^!!>;ijlltfttfcji0;=0iiitcfftt000=0
ijttllji=iijlj;>>!"=0!"";ilj=!-^'""'-'-''`^"'!>''--^^-^">>=iijtcctttlji0;>=0jiilfofcl000=0
lcclljiiijj0>!>>>!>0;"";ili0!"'-'!!'``----!^;"''-''---";;=00lctlttj0=ij;>;;=liitooccl0=iij
tctlttljii=;;;;=;>=;!!0jl0;;>--'-">'`'^"-;-="-^-'''-"!;>;;itljjlj0;>;=0i;>==tiifootctj0iii
tltcccli0i0ijii0>=0;>jji=>=;"''-"^!`-'^"!"=0"""!-'">>;>==jtjllji=>>>=0==0;==li0foocctjijjj
ttcfclijjttllj0=00=;lli0>;=!"^'--""---!"="ii0;>"">;;>;=jttllj0i;!>">>;;;===;li0foofcclljjj
ccctltcfftllii0i00=jlii!>==""!-''!"-^^!>;0==0="!;0=>;;lctli0=;0!">!>;!;>=;;;tjifofofclliij
ocllfooofcctjiiii0il00>";0!"^>!'^!""-^!>>0>0i>!i=>!!=cfcj;>=;=0""!!!=">>===0jijffcofflj00j
cljcooofcttllljjiili==!>0;!"-"!^>""^^^>=!0>l>=l0">;0cotj;^>0>j=!"!!>>^>>>;;;itjcfcfoftljjl
tjttcctlli;=;=0iijj0i;>==!"-'"">!^^^^^!;==i0=l=!>=0ccl0i""00=l=!"">;>-;;>;=;0lltccffottllt
ljljllji0;!>;=00ij0ii>>i>!>--!">^-"^^!!;i=jil"!===tjij=i">ii0ji!>!;=;>0i;>=;0ljtcffooccctl
liijllj;";=0iiiiji000!;=>>>"!"!!""""!>!>i0ct>";;ilj000=0>;ii0li=;>=0=;i0>;0==ijtcccffccctl
ljijlj0>>=jllijjji=0=>==;>!>"";!!!!!!>""0tc0;!=0il0=0i=0;;0jilj0=>==0ii=>=0=0=jttttfccctlt
ljjjjj;>;0ltliijj0i==>0=;>>;!=>>;;;>>!"!lo=0;ii>>l0i0000;=0jijc0i;=;jjj=0i000;jltttttctttt
lljjjl0==0jjljjjl0i0=;00==>=00=0===;>>!=cc;0j0!^>lij0=000=ij=0f0i0=0jtiijjii;0jjltljjtcttc
tclllfcljlllijjllij=>00i0==0i0=0i00=;;=jjlit=>"!>tji0==0iiii=0ft0i0ittilliji;0jijlljjtcfcf
tfcllffcl0jllljlllj=>i=0i000i00jjii0=;0l;jc0-=>>0jji0=0iiii000lfi0=jtltl0jli;ii0ijljitffoa
jootltfci0j0iiijjtlj==00iijjijjjjii0==j0;jf-`>0>=0ti0;iiiii=00itj00ttttj;lt00j0=ijtjitoaV5
llffctlji0j0i0;;ijlti0iijjjllljjiiii=ij=0cj>-!0;=0li===iiij=0=jlj00tttji0ltii0!0illjjfV5eb
tcccctlj00i0i=;>0jiltjljlltttljjjiii0ji=ii>i^";0=0ij=0=iiij000ilj=itcljiitlj0;;illjjca5ebD
ccoaftljiii00===iijjljllltctttjjii0i0ij=j>>"=^!i;00j0i00i0ii=00jj0ltcjj0jllli=0jjjlcoV5bbb
ofcfcfctjiji0=;=0=jltttctfccctljii000ii00!"^">";=00ji=0000i0===iiilttlijlllliijijltcfV5ebb
