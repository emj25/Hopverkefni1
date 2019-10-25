# Upplýsingar um hvernig keyra skuli verkefnið:
Clone-a verkefnið niður af github (eða sækja það hvernig sem þú vilt)
Install NodeJS ef þú er ekki með það. NodeJS má sækja hér: https://nodejs.org/en/
Keyra NPM INSTALL
Keyra NPM RUN DEV eða NPM RUN SASS
Vista eitthvað *.scss skjal til þýða scss skrár í css skrá

Lýsingu á uppsetningu verkefnis, hvernig því er skipt í möppur, hvernig CSS er skipulagt og fleira sem á við

# Lýsing á uppsetningu verkefnis og skipulag CSS:
Aðalskráin index.html er í rót og stýrir forsíðunni.  Aðrar html-skrár eru vistaðar í sér möppu og allar myndir sem eru notaðar eru einnig í sér möppu.

Öllu útliti á síðunum er stýrt með scss-skrám.  Ellefu scss-skrár eru í möppu merktum þeim og er skipt eftir því sem þær stýra.  Sumar eiga við eina html-síðu en aðrar eru notaðar víðar.  Styles.scss sækir upplýsingar í þessar skrár með import-skipun.  Loks er sú skrá þýdd yfir í styles.css skrána með sass. Í styles.css sækja html-skrárnar allar upplýsingar um útlit.
	
# Skipulag á möppum og skrám
Mappa [efni]
- inniheldur textaskrár fyrir síður

Mappa [img]
- inniheldur myndefni fyrir síður

Mappa [pages]
- html undirsíður

Mappa [scss]
- scss skrár sem eru notaðar til að búa til styles scss í sass keyrslu

index.html
- forsíða heimasíðu

styles.css
- css skrá sem verður til þýðingu á styles.scss

styles.scss
- safn allra skilgreininga í öðrum scss skrám

package-lock.json
- inniheldur upplýsingar fyrir NodyJS til að setja upp öll JavaScript modules sem við notum til hagræðingar við vinnslu verkefnisins.

package.json
- "lint-css": lintar css skjalið
- "lint-scss": linta scss skjöl (athugar bara skjöl sem styles.scss improtar)
- "dev":  Keyrir Browser Sync og Sass,
- "browser-sync": Fylgist með breytingum á css og html skrám svo ekki þurfi að refresha broser
- "sass": fylgist með breytingum á scss skrám og uppfærir css skjál þegar þær eru gerðar (og scss skrár vistaðar.



# Þeir sum unnu verkefnið eru:
Bóas Guðjónsson
Dæmahópur: 3
kt: 070392-2839
bog26@hi.is

Einar Már Júlíusson
Dæmahópur:  2
kt: 271066-8649
emj25@hi.is

Ósvaldur Knudsen
Dæmahópur: 1
kt: 030174-3999
okk3@hi.is 


> Útgáfa 0.1
