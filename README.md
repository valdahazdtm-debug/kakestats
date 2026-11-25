# KakeStats veebileht – avaldamise juhend

Failid: index.html, terms.html, privacy.html, style.css, .nojekyll. Veebileht on staatiline, mobiilisõbralik ja ei sisalda jälgimisskripte. Ava index.html brauseris.

## Enne avaldamist
- Asenda kõik nurksulgudes kohatäited (terms.html ja privacy.html): vastutava isiku/ettevõtte ametlik nimi, kontaktmeil, riik, avaldamise kuupäev, tegelik hostingu piirkond ja rahvusvaheliste andmeedastuste kaitsemeetmed, edastatud DM-ide ja eksporditud logide säilitamiskord, krüpteerimine ja turvameetmed. KakeStats Development on projekti nimi, mitte kinnitatud juriidiline isik.
- Eemalda mõlema dokumendi ülaosas olev Draft for review märkus alles siis, kui tekst on üle kontrollitud ja vastab tegelikele praktikatele.
- Praegune Python-kood säilitab keele- ja serveriseadeid ilma automaatse kustutamiseta; logide 30 päeva ei kehti DM-idele ega eksporditud failidele. Kehtesta kustutamise kord, sealhulgas andmete päringu korral ja kui andmeid enam ei vajata. Lisa avalik kontakt, kuhu kasutajad saavad päriselt kirjutada.
- Enne avalikku kasutust soovitan lülitada automaatse DM-edastuse välja või asendada selle selge, vabatahtliku tugiprotsessiga; kui muudad koodi, uuenda poliitikat vastavalt. Piira isikustatud logimist hädavajaliku diagnostikaga ja kasuta analüütikas anonüümseid koondandmeid. Kontrolli andmete krüpteerimist kettal (Discord nõuab seda), teenusepakkujate andmetöötlustingimusi ja GDPR õiguslikke aluseid. Käesolev mustand ei kinnita nende meetmete täitmist.
- Lisa privaatsuspoliitika ja kasutustingimuste lingid boti /help vastusesse või muusse hõlpsasti leitavasse botisisesesse vaatesse. Käesolev pakett ei muuda boti koodi.

## GitHub Pages
1. Logi sisse https://github.com ja loo avalik repository nimega kakestats.
2. Paki ZIP lahti. Laadi viis veebifaili repository juurkausta (mitte botikoodi, .env faili, andmebaasi ega logisid).
3. Settings → Pages → Build and deployment → Source: Deploy from a branch → main → / (root) → Save.
4. Kui avaldamine õnnestub, vaata tegelikku URL-i Pages lehelt. Tavaliselt on see https://KASUTAJANIMI.github.io/kakestats/ .
5. Lisa Developer Portal → KakeStats → General Information lehele kaks URL-i: https://KASUTAJANIMI.github.io/kakestats/terms.html ja https://KASUTAJANIMI.github.io/kakestats/privacy.html . Kontrolli mõlema avalikku ligipääsu inkognito aknas.

## Aluseks võetud materjal
- main_kakestats_setup_languages.py (viimane koodiversioon, üle vaadatud 25.11.2026).
- Discord Developer Terms of Service, §5: https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service
- Discord Developer Policy: https://support-dev.discord.com/hc/en-us/articles/8563934450327-Discord-Developer-Policy
- GDPR, eriti artiklid 5, 6, 12–14, 15–22, 28, 32 ja 44–49: https://eur-lex.europa.eu/eli/reg/2016/679/oj
- GitHub Pages: https://docs.github.com/en/pages/quickstart

Dokumendid on ingliskeelsed mustandid, mitte kinnitus õigusliku vastavuse või Discordi verifitseerimise kohta. Kontrolli tegelikke andmetöötluse korraldusi enne avaldamist.
