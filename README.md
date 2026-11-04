# Tähemets – Androidi rakenduse projekt

Valmis projekt, millest saab APK kahel viisil.

## A) Ilma arvutitarkvarata (GitHub)
1. Tee tasuta konto aadressil github.com ja loo uus repo.
2. Lae selle kausta KÕIK failid (sh peidetud kaust .github) repo-sse üles.
3. Ava repo lehel Actions -> Build APK -> Run workflow.
4. Kui töö on roheline (3-5 min), ava see ja lae alla Tahemets-apk (zip). Sees on app-debug.apk.
5. Kopeeri APK telefoni ja ava. Telefon küsib luba "tundmatutest allikatest" - luba.

## B) Android Studio
1. Ava Android Studio -> Open -> vali see kaust. Oota, kuni sünkroniseerimine lõpeb.
2. Menüü Build -> Build APK(s). Valmis fail: app/build/outputs/apk/debug/app-debug.apk

## Hääl
Rakendus kasutab telefoni enda kõnesünteesi (eesti keel). Kui eesti häält pole, ava rakenduses
Avaleht -> "Ei kuule eesti keelt?" -> "Lae eesti hääl alla".

Rakenduse sisu on failis app/src/main/assets/index.html
