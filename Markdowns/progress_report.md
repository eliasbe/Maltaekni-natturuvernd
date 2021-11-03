# Áfangaskil - Náttúruvernd í fréttum og á þingi

## Inngangur

Markmið þessa verkefnis má skipta niður í skref. Í upphafi viljum við skapa máltækniflokkara sem getur greint umræðu um náttúruvernd og loftslagsmál í fréttatextum og alþingisskjölum ásamt öðrum gögnum að einhverju leyti. Því næst viljum við geta greint afstöðu þess texta, það má bæði skilja sem jákvæðni textans eða afstöðu hans til loftslagsbreytinga af mannavöldum. Í þriðja lagi viljum við geta greint hver sé höfundur textans og hvort viðkomandi sé að tala fyrir hönd stjórnmálaflokks. Að endingu, ef ofangreint gengur upp, viljum við geta gefið fullyrðingum einkunnir á skala Sólarinnar þegar kemur aðmarkmiðum tengdum náttúruvernd, loftslagsbreytingum og hringrásarhagkerfinu. Í því tilfelli myndum við nota einkunnir Sólarinnar sem viðmið.

## Gögn

Gögnin sem nú er unnið með eru safn rúmlega 600.000 frétta af íslenskum miðlum, fengnar frá Vésteini. Þeim hefur verið skipt upp í þjálfunarsafn og prófunarsafn, unnið er að leiðum til að merkja hluta þeirra í fréttir tengdar náttúruvernd og fréttir ótengdar þeim málaflokki. 

Prófað hefur verið að keyra LDA flokkara á hluta fréttanna sem skiptir þeim í 10 hópa og hefur það gengið vel. Með því væri hægt að plokka út undirsöfn sem annað hvort þykir líklegt að tengist málaflokknum eða þá að tengjast greinilega ekki flokknum. Til stendur að þjálfa stærra líkan sem vinnur með öll þjálfunargögnin. 

Önnur gögn sem til stendur að nálgast og vinna með eru annars vegar gögn frá Alþingi og bæjarstjórnum sem og gögn sem Sólin notaði til að setja saman einkunnatöfluna sína. Gögn frá Alþingi og bæjarstjórum væru notuð til að tengja Alþingismenn við flokka og greina orð þeirra úr pontunni og frumvörpum. Gögnin frá Sólinni yrðu notuð til að grundvalla einkunnargjöf líkansins. 

## Árangur

Hingað til hefur vinnan miðast að því að lesa inn gögnin og fá yfirlit yfir þau, leita í þeim að náttúruverndartengingum og flokka þau með viðgjafarlausri hópun (e. unsupervised clustering) með LDA aðferðum. Hugmyndin er að merkja hluta gagnanna, senda gögnin án merkinga í slíka hópun og skoða svo í hvaða hópa jákvætt merktu og neikvætt merktu gögnin lenda. Til þess að slíkt sé marktækt þarf að merkja hluta gagnanna sem prófunar- eða þróunarsafn og athuga hvort aðferðin flokkar þau gögn rétt.


Við höfum einnig eytt tíma í samskipti við Unga Umhverfissinna til að nálgast gögn Sólarinnar. 

Þar að auki höfum við litið til þess að nota flokkara ofan á ICEbert líkan til þess að flokka texta í flokka sem tengjast náttúruvernd og þeir sem ekki tengjast því.  
