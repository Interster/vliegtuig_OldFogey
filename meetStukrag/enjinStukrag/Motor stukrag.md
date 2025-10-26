# Meet stukrag van motor

Meet stukrag met die volgende opstelling.

Hier is die [[opsomming van stukrag video]].

Dit is nodig om te weet of die motor dalk te min krag gee om die Fogey gestadigd met reguitvlug kan laat vlieg.


Maak seker dat die skroef nie in grondeffek is nie.

Die skarnier moet ook toelaat om die massa van die krag wat oorkom moet word gemeet kan word.

![[1_meetStukrag.png]]

Meet die eie massa (oftewel moment) van die balk massa en die motor.  Met hierdie meting is die motor natuurlik af.

Hou rekening met $M_{RES}$ by die moment wat die stukrag genereer.  Dan kan $F_M$ uit die volgende vergelyking verkry word:
$$
F_S b + M_{RES} = F_M a \\
\therefore F_M = \frac{F_S b + M_{RES}}{a}
$$
waar $F_M$ die motor stukrag is en $F_S$ is die krag op die skaal.  $M_{RES}$ is die krag op die skaal wanneer net die motor (afgeskakel) en balk gemeet word maal met $a$.  Dit is die resultante moment met geen krag op nie.
$$
M_{RES} = m_{motor} \cdot a
$$
waar $m_{motor}$ die massa van die motor en weegbalk $a$ is.  Substitueer $M_{RES}$ in die massabalans hierbo:

$$
F_M = \frac{F_S b + m_{motor} \cdot a}{a} = \frac{F_S \cdot b}{a} + m_{motor}
$$


![[2_MeetMRES.png]]

Hier is die aanvanklike berekeningsblad:
![[20250810_143630.jpg]]

Hier is die opstelling van die meting.  Die skarnier is styf genoeg om sywaartse kragte van presessie en koppeleffekte te hanteer.

![[20250830_101824.jpg]]

![[20250830_103547.jpg]]Die rotor is nie in grondeffek nie, want dit is op die rant van die tafel.
![[20250830_103555.jpg]]

Hier is die meetresultate:

![[20250830_105522.jpg]]

Die motor is vir 'n verlengde tyd geloop om te toets hoe lank die battery hou.  Die massa van die motor en battery opstelling was 160 gram.

Berekeninge is in MassaBalansOldFogey.ods.

Die resultaat van die berekeninge is as volg.  Die grafiek van motor stukrag teenoor tyd is sigbaar in die volgende grafiek.  Dit is die verwerkte resultate.  Dit wys dat die stukrag ongeveer 270gram is.  Die motor loop ongeveer 4 minute op die battery.

![[MotorStukragTeenTyd.png]]

## Werksverrigting berekening

Die vraag wat beantwoord moet word is as volg:
Is die bestaande enjin sterk genoeg?

Die bestaande enjin genereer 2.5N krag betroubaar vir 'n lang genoeg periode om 'n vlug af te handel.  Die vraag is dus of 2.5N genoegsaam is.  Die Fogey gewig is 5.24N.  Gebruik die volgende kragtediagram om die werksverrigting te beoordeel:

![[KragteDiagram|500]]
Neem aan dat die Fogey 'n $\frac{L}{D}$ verhouding van 11 het.  Dit is soortgelyk an 'n Cessna 172.
Dan is die sleurkrag 5.24N/11 = 0.48N.  Die enjin lewer dus genoeg stukrag om die Fogey aan te dryf.
Die vraag bly dus waarom die Fogey nie genoeg werksverrigting het nie.  Die probleem mag dalk wees dat die Fogey oorgewig is en dat dit nie genoeg hefkrag kan genereer met die bestaande vlerkarea nie.  Die volgende aksies word voorgestel:

- Doen sweeftoetse met die Fogey om die L/D verhouding te bepaal.  Die berekende snelheid van die Fogey om sy massa te ondersteun met hefkrag is 7m/s.  Dit is dalk te vinnig en vereis heeltemal te veel lanseerkrag.  Die Fogey kom nie daarby uit met lansering nie en kan dus nie sy eie gewig met hefkrag ondersteun nie.  Meet spoed die Fogey met sweeftoetse en ook L/D.  Kyk of die 0.8 $C_L$ hefkragkoeffisient reg of optimisties is.

![[SweeftuigKragtediagram|700]]