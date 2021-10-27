# Plan and actions

## Strategy and ideas

### Frá fyrsta fundi
- Gögn: Fréttir og Alþingi
	- merkja hluta
- Flokkari fyrir náttúruvernd / loftslag
	- Tekur tíma að þjálfa
	- Gensim
	- LDA etc.
	- Orðalista
	- **Strax hér tölfræði um náttúruvernd**
	- Undirflokkar og sentiment
- NER
	- Fólk (einræða í nefnifall)
	- Stjórnmálaflokkar (bara fyrir fréttir)
	- **Athuga mun á Alþingi og fréttum.**
- Tölfræði
	- Hver talar um náttúruvernd?
	- Hversu mikið?
	- Ath. mun á flokkum, aldri og kyni
	- jákvætt/neikvætt
	- Eftir tíma árs

### Frá Vésteini
0. Takið góðan hluta af gögnunum til hliðar sem prófunargögn, amk 10%, eftir að hafa raðað þeim slembið.

1. Búið til einhverskonar flokkara sem getur merkt inn fréttir um náttúruvernd. Getið notað einhverskonar orðalista til að veiða út fréttir til að byrja með. En reynið að handmerkja eitthvað af gögnum, einhverja tugi frétta amk. Þá getið þið notað þau gögn til að þjálfa flokkara, t.d. naive bayes með sklearn eða flokkara ofaná icebert.   

2. Skrapið vef alþingis til að tengja nöfn við stjórnmálaflokka. Sjáið hvort þið getið tekið með aldur, kyn og eittvað fleira. Gætuð viljað skoða bæjarstjórnir líka.  

3. Notið sérnafnamarkara (NER) til að finna fólk í fréttum sem tengjast náttúruvernd, ath. að varpa í nefnifall til að einræða.  

4. Skoðið tölfræði í kringum hvernig fólk birtist í fréttunum.

5. Notið sentiment tól ([https://huggingface.co/vesteinn/XLMR-ENIS-finetuned-sst2](https://eur02.safelinks.protection.outlook.com/?url=https%3A%2F%2Fhuggingface.co%2Fvesteinn%2FXLMR-ENIS-finetuned-sst2&data=04%7C01%7Cebe19%40hi.is%7Cbb8aeab6ceba4613f33308d992214ee7%7C09fa5f0e211846568529677ed8fdbe78%7C0%7C0%7C637701494022316438%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=X%2B2rwdu89q7S2dPPc0dgv%2BpX4GR0NS9TVMYHqUUH95g%3D&reserved=0 "Upprunaleg vefslóð: https://huggingface.co/vesteinn/XLMR-ENIS-finetuned-sst2. Smelltu eða pikkaðu ef þú treystir þessum tengli.")) á setningar í fréttunum, reiknið sentiment nálægt því þar sem nafn kemur fyrir. Takið saman tölfræði út frá nöfnum.  

6. Reiknið líka sentiment fyrir fréttir í heild og takið saman tölfræði.

7. Skoðuð mögulega undirflokka í fréttum um náttúruvernd og reiknið tölfræði út frá undirflokkum svipað og að ofan, getið notað t.d. LDA sbr skjal í canvas.




## Hvað við höfum gert:

