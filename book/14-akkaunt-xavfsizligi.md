[← Mundarijaga](../README.md)

# 14. Akkaunt va axborot xavfsizligi

Oʻlchov: pul va shaxsiy maʼlumot. Akkauntingizni boshqa birov qoʻlga kiritsa, siz pulingizni, telefon kitobingizdagi odamlarni va oʻz shaxsingizni yoʻqotasiz.

### 1. Pochta, toʻlov va ijtimoiy tarmoq akkauntlarida ikki bosqichli tasdiqni yoqing — avval telefondagi push-tasdiq, undan keyingina SMS-kod
<!-- teglar: pul=0 vaqt=kam iroda=yoq qaytim=katta olcham=pul -->
- Sarf: 0 soʻm; har akkaunt uchun bir marta, ikki-uch daqiqa
- Oddiy tilda: telefoningizga chiqadigan push-tasdiq fishing orqali qilinadigan oʻgʻirlik urinishlarining toʻqson foizidan koʻpini va avtomatlashtirilgan barcha urinishlarni toʻxtatadi; "oxirgi marta qayerdan kirgansiz", "zaxira pochta" kabi savol-javobga tayangan tasdiq esa fishing oʻgʻirligining atigi oʻndan birini toʻxtatadi. Bir marta sozlaysiz, bir necha daqiqa.
- Qaytimi: Google 350 000 ta haqiqiy egallab olish urinishini baholaganda: qurilma turidagi tasdiq (telefondagi push-tasdiq, xavfsizlik kaliti) "fishingga asoslangan urinishlarning 94% dan koʻpini va avtomatlashtirilgan urinishlarning 100% ini" toʻxtatgan; bilimga asoslangan tasdiq (oxirgi kirish joyi, zaxira pochta kabi savollar) esa "fishing urinishlarining bor-yoʻgʻi 10% ini va avtomatlashtirilgan urinishlarning 73% ini" toʻxtatgan
- Dalil darajasi: A
- Manba: Doerfler P, Thomas K, Marincenko M, et al. (2019). Evaluating Login Challenges as a Defense Against Account Takeover. The World Wide Web Conference (WWW '19). <https://doi.org/10.1145/3308558.3313481>
- Izoh: shu tadqiqot tasdiq oddiy foydalanuvchini ham toʻxtatib qoʻyishini aniqlagan: qonuniy foydalanuvchilarning 52% i birinchi urinishda kira olmagan, ammo 97% i oxir-oqibat kirgan. Avval pochtangizni himoyalang, chunki qolgan barcha akkauntni pochta orqali tiklash mumkin

### 2. Pochta paroli alohida boʻlsin — hech bir saytda takrorlanmasin
<!-- teglar: pul=0 vaqt=kam iroda=biroz qaytim=katta olcham=pul -->
- Sarf: 0 soʻm; parol menejeridan foydalansangiz, yod olish shart emas
- Oddiy tilda: boshqa saytdan sizib chiqqan parol toʻgʻridan-toʻgʻri sizning pochtangizga kirishda ishlatiladi. Pochtaga kirib olishsa, oʻsha pochta orqali parol tiklanadigan barcha akkaunt ham qoʻldan ketadi.
- Qaytimi: parol takrorlash eng oson hujum yoʻli — boshqa joydan sizgan parol toʻppa-toʻgʻri pochtaga urinib koʻriladi; pochta qoʻldan ketsa, uning orqali tiklanadigan hamma akkaunt birga ketadi
- Dalil darajasi: C
- Manba: muallif tajribasi, bevosita manba yoʻq
- Izoh: yod ololmasangiz, brauzerning oʻz parol menejeridan foydalaning — bu bitta parolni takrorlashdan ancha yaxshi. Parollarni messenjer "saqlanganlari" yoki eslatmalar ilovasida saqlamang

### 3. Telefonga ekran qulfini, SIM-kartaga PIN-kodni qoʻying
<!-- teglar: pul=0 vaqt=kam iroda=yoq qaytim=katta olcham=pul -->
- Sarf: 0 soʻm; bir marta sozlaysiz
- Oddiy tilda: telefon yoʻqolsa, topib olgan odamning eng tez qiladigan ishi — SIM-kartani boshqa telefonga solib, tasdiq kodlarini qabul qilish va akkauntlaringizni birma-bir tiklab olishdir. SIM-kartaga PIN qoʻyilgan boʻlsa, boshqa telefonda yoqishda parol soʻraladi va bu yoʻl yopiladi.
- Qaytimi: telefon yoʻqolgandan keyin eng tez hujum yoʻli — SIM-kartani boshqa telefonga solib SMS-kodlarni olish, soʻng akkauntlarni birma-bir tiklash. SIM-kartada PIN boʻlsa, almashtirilganda yoqishda parol soʻraladi va bu yoʻl uziladi
- Dalil darajasi: C
- Manba: muallif tajribasi, bevosita manba yoʻq
- Izoh: PIN telefonning "SIM-karta qulfi" boʻlimida sozlanadi; standart boshlangʻich kod odatda 1234 yoki 0000; uch marta xato tersangiz PUK-kod bilan ochish kerak boʻladi, shuning uchun sozlagach darrov yozib qoʻying

### 4. Telefon yoʻqolsa shu tartibda ish tuting: SIM-kartani bloklatish, masofadan qulflash, parollarni oʻzgartirish, politsiyaga xabar, bank kartasini muzlatish
<!-- teglar: pul=0 vaqt=kam iroda=yoq qaytim=katta olcham=pul -->
- Sarf: 0 soʻm; oʻn-oʻn besh daqiqa
- Oddiy tilda: tartib tezlikdan muhimroq: avval SIM-kartani bloklatib, tasdiq kodlari degan tomirni uzing; soʻng telefonni masofadan qulflab, maʼlumotni oʻchiring; keyin kompyuterdan pochta va toʻlov parollarini oʻzgartiring; soʻng politsiyaga xabar berib dalolatnoma oling; oxirida zarur boʻlsa bank kartangizni muzlating. Bloklatishni boshqa odamning telefonidan operator qoʻllab-quvvatlash markaziga qoʻngʻiroq qilib ham amalga oshirish mumkin.
- Qaytimi: tartib tezlikdan muhim — avval SIM-ni bloklatish tasdiq kodlari tomirini uzadi, soʻng qurilmani masofadan qulflash va tozalash, soʻng kompyuterdan pochta va toʻlov parollari, keyin politsiyaga xabar va dalolatnoma, oxirida zaruratga qarab bank kartasi
- Dalil darajasi: C
- Manba: muallif tajribasi, bevosita manba yoʻq; yoʻqolgan pasport yoki ID-kartani tiklash boʻyicha tegishli boʻlimga qarang
- Izoh: mobil operatoringiz qoʻllab-quvvatlash raqamlarini (Uzmobile, Beeline, Ucell, Mobiuz) va oʻz raqamingizni oldindan bilib qoʻying. Favqulodda holatda 112 yagona raqamiga ham murojaat qilsa boʻladi. Boshqa odamning telefonidan ham operatorga qoʻngʻiroq qilib SIM-ni bloklatish mumkin

### 5. Kartadan ruxsatsiz pul yechilsa — avval bloklatib muzlating, keyin politsiyaga xabar bering va bankka yozma ariza toping
<!-- teglar: pul=0 vaqt=kam iroda=biroz qaytim=katta olcham=pul -->
- Sarf: 0 soʻm; gʻayritabiiy harakatni sezgan zahoti kartani bloklating yoki muzlating, politsiya dalolatnomasini, bloklash va tranzaksiya bildirishnomalarini saqlab qoʻying; karta oʻzingizda boʻlsa, yaqin joydan kichik bir amaliyot (balans soʻrash yoki pul yechish/toʻlash) qilib "haqiqiy karta shu yerda" ekanini qayd etib qoʻying
- Oddiy tilda: kartadan ruxsatsiz pul yechilsa, avval karta-emitent bankka (mobil ilova, call-markaz yoki rasmiy sayt orqali) darrov murojaat qilib kartani bloklating; soʻng 102 ga yoki politsiyaga xabar berib dalolatnoma oling; keyin bankka yozma ariza topshirib, tranzaksiyaga eʼtiroz bildiring va tekshirishni talab qiling; bank javob bermasa yoki rad etsa, Markaziy bankka murojaat qiling. Parol va tasdiq kodini birovga aytgan boʻlsangiz, zararning bir qismi oʻzingizga tushishi mumkin — shuning uchun kod va parol hech kimga berilmaydi.
- Qaytimi: bank kartalari va toʻlov tizimlari ishtirokchilari bank kartalaridan noqonuniy foydalanishning oldini olish choralarini koʻrishi va karta egasi maʼlumotlarini himoya qilishi shart. Ruxsatsiz operatsiya sezilsa kartani bloklash — tan olingan birinchi qadam; bank-emitent yoki toʻlov tizimi operatoriga (call-markaz, mobil ilova, rasmiy sayt) darrov murojaat qilinadi
- Dalil darajasi: B
- Manba: "Toʻlovlar va toʻlov tizimlari toʻgʻrisida"gi Qonun (OʻRQ-578-son, 01.11.2019). <https://lex.uz/docs/-4575786> ; Oʻzbekiston Respublikasi hududida bank kartalarining chiqarilishi va muomalada boʻlishi qoidalari toʻgʻrisidagi nizom (roʻyxat raqami 3294, 03.04.2021). <https://lex.uz/docs/-5355601>
- Izoh: Oʻzbekiston qonunchiligi bank kartasidan oʻgʻirlik uchun javobgarlikni kuchaytirmoqda (bank, toʻlov tashkilotlari va provayderlar masʼuliyati oshirilmoqda), ammo Xitoy sudi qoidasidagi "pulni oʻzingiz yechganini isbotlash yuki bankda" degan aniq norma Oʻzbekiston birlamchi manbasida hozircha tasdiqlanmadi — bu daʼvoni mustaqil tekshiring. Amaliy qoida universal: darrov bloklash va dalolatnoma har qanday holatda birinchi qadamdir. Karta, parol va tasdiq kodini ehtiyotsiz saqlashdan kelib chiqqan zararga oʻzingiz javob berishingiz mumkin, shuning uchun kodni uzatmang (1-bandga qarang)

### 6. Vaqti-vaqti bilan akkauntingizdagi kirgan qurilmalar va ruxsat berilgan ilovalarni koʻrib chiqing, keraksizini oʻchiring
<!-- teglar: pul=0 vaqt=kam iroda=biroz qaytim=orta olcham=pul -->
- Sarf: 0 soʻm; har safar bir necha daqiqa
- Oddiy tilda: akkaunt oʻgʻirlagan odam koʻpincha darrov harakat qilmaydi, bir muddat pusib turadi. Kirgan qurilmalar roʻyxatidagi notanish qurilma, ruxsat berilgan ilovalar roʻyxatidagi allaqachon keraksiz boʻlgan uchinchi tomon ilovasi — oddiy odam oʻzi koʻra oladigan iz. Koʻrsa, "hamma joydan chiqish"ni bosib, parolni oʻzgartiring.
- Qaytimi: akkaunt oʻgʻirligi koʻpincha oʻsha zahoti sodir boʻlmaydi, hujumchi avval pusib turadi. Kirgan qurilmalar roʻyxatidagi notanish qurilma va ruxsat berilgan ilovalar roʻyxatidagi eskirgan uchinchi tomon — eng oson topiladigan iz
- Dalil darajasi: C
- Manba: muallif tajribasi, bevosita manba yoʻq
- Izoh: pochta, ijtimoiy tarmoqlar, toʻlov ilovalari, Apple va Android akkauntlarida shu boʻlim bor. Notanish qurilma koʻrsa, "hamma joydan chiqish"ni bosib, parolni oʻzgartiring

### 7. Ilovadan foydalanish uchun "hammasiga roziman"ni bosmang: xizmat uchun zarur boʻlmagan maʼlumotga rozilik bermasangiz ham, sizga xizmat koʻrsatishdan bosh torta olmaydi
<!-- teglar: pul=0 vaqt=kam iroda=biroz qaytim=orta olcham=erkinlik -->
- Sarf: 0 soʻm; "hammasiga roziman"ni bosmay sabr qilish kifoya
- Oddiy tilda: shaxsga doir maʼlumotga ishlov berish, qoida tariqasida, subyektning roziligi bilan amalga oshiriladi; maʼlumot faqat qonuniy asos bilan yigʻilishi kerak. Xarita ilovasiga joylashuv zarur, lekin fonar ilovasiga telefon kitobi kerak emas — bunday keraksiz ruxsatlarni bermang.
- Qaytimi: qonunga koʻra shaxsga doir maʼlumotga ishlov berish subyektning roziligi yoki boshqa qonuniy asos boʻlganda amalga oshiriladi; rozilik istalgan vaqtda qaytarib olinishi mumkin
- Dalil darajasi: B
- Manba: "Shaxsga doir maʼlumotlar toʻgʻrisida"gi Qonun (OʻRQ-547-son, 02.07.2019). <https://lex.uz/docs/-4396419> ; Shaxsga doir maʼlumotlarga ishlov berishning namunaviy tartibi (3478-son, 15.11.2023). <https://lex.uz/uz/docs/-6663967>
- Izoh: Oʻzbekiston qonunchiligi shaxsga doir maʼlumotga ishlov berishni rozilik asosiga quradi va rozilikni istalgan vaqtda qaytarib olish huquqini beradi. Xitoy qonunidagi "rozilik bermaganingiz uchun xizmat koʻrsatishdan bosh torta olmaydi" degan aynan oʻsha norma Oʻzbekiston birlamchi manbasida alohida band bilan tasdiqlanmadi — mezon amalda: "bu maʼlumot shu xizmat uchun haqiqatan zarurmi". Ilovani oʻrnatgan zahoti tizim ruxsatlar boʻlimidan keraksizini oʻchirib qoʻying, kerak boʻlganda bir martalik ruxsat bering

### 8. Oʻz shaxsga doir maʼlumotingizni koʻrish, koʻchirib olish, tuzatish va oʻchirish huquqingiz bor — rad etilsa, murojaat qilish va sudga berish mumkin
<!-- teglar: pul=0 vaqt=kam iroda=biroz qaytim=orta olcham=erkinlik -->
- Sarf: 0 soʻm; faqat tashkilot ishni paysalga solsa, murojaat yoki daʼvo kerak boʻladi; sudga borish bir necha oylik ish, shuning uchun avval vakolatli davlat organiga murojaat qilgan arzonroq
- Oddiy tilda: tashkilotdan oʻz maʼlumotingizni koʻrsatish, koʻchirib berish, tuzatish va oʻchirishni talab qilish huquqingiz bor; xizmat toʻxtagan, saqlash muddati tugagan yoki rozilik qaytarib olingan hollarda maʼlumot oʻz vaqtida oʻchirilishi kerak. Rad etgan taqdirda sababini tushuntirishi shart, oʻchirmasa — talab qila olasiz.
- Qaytimi: subyekt mulkdor va operatordan oʻz shaxsga doir maʼlumotini talab qila oladi; maʼlumot qonunga xilof yigʻilgan yoki saqlangan boʻlsa, oʻchirib tashlashni talab qilish mumkin; huquqlar buzilsa vakolatli davlat organi (pd.gov.uz) va sudga murojaat qilinadi
- Dalil darajasi: B
- Manba: "Shaxsga doir maʼlumotlar toʻgʻrisida"gi Qonun (OʻRQ-547-son, 02.07.2019), subyekt huquqlari — 30-modda. <https://lex.uz/docs/-4396419> ; Shaxsga doir maʼlumotlarni himoya qilish davlat organi. <https://pd.gov.uz>
- Izoh: akkauntni oʻchirish (yopish) va shaxsga doir maʼlumotni oʻchirish — ikki xil ish; yopgandan keyin maʼlumotni oʻchirishni alohida talab qiling. Yangi telefon olishdan yoki eskisini sotishdan oldin eski telefonda barcha akkauntdan chiqib, ulanishlarni uzib, soʻng zavod sozlamalariga qaytaring — qonun keyingi oʻchirish huquqini beradi, ammo allaqachon sizib chiqqan narsani qaytarib ola olmaydi. 30-moddaning aynan soʻzlashuvi va oʻchirish tartibi boʻyicha lex.uz dagi amaldagi tahrirni tekshirib oling

### 9. Yuzni skaner qildirish majburiy emas: biometrik maʼlumot maxsus himoyalangan toifa — rozilik shart va uni qaytarib olish mumkin
<!-- teglar: pul=0 vaqt=kam iroda=biroz qaytim=orta olcham=pul -->
- Sarf: 0 soʻm; yuz skaneri talab qilinganda "boshqa tasdiqlash usuli bormi" deb soʻrang
- Oddiy tilda: yuz tasviri (biometrik maʼlumot) — erkin foydalanilmaydigan, maxsus himoyalangan toifa; unga ishlov berish uchun subyektning roziligi shart va bu rozilik istalgan vaqtda qaytarib olinadi. Yuz va parolning eng katta farqi — yuz sizib chiqsa, uni oʻzgartirib boʻlmaydi, shuning uchun undan ehtiyotroq boʻling.
- Qaytimi: biometrik maʼlumot — hamma foydalana olmaydigan (cheklangan) toifaga kiradi; unga ishlov berish subyektning roziligi bilan amalga oshiriladi, rozilik istalgan vaqtda qaytarib olinadi; biometrik va genetik maʼlumot Oʻzbekiston hududida saqlanishi shart (2026-yilgi oʻzgartirish)
- Dalil darajasi: B
- Manba: Shaxsga doir maʼlumotlarga ishlov berishning namunaviy tartibi (3478-son, 15.11.2023). <https://lex.uz/uz/docs/-6663967> ; "Shaxsga doir maʼlumotlar toʻgʻrisida"gi Qonun (OʻRQ-547-son, 02.07.2019). <https://lex.uz/docs/-4396419>
- Izoh: koʻpincha turar-joy majmuasi kirishi, ijara platformasi, sport zali yoki mehmonxona yuz roʻyxatga olishni soʻraydi. Oʻzbekiston qonunida biometrik maʼlumot cheklangan toifa boʻlib, rozilik talab qiladi va uni qaytarib olish mumkin. Ammo Xitoy qoidasidagi "boshqa usul boʻlsa, yuz skaneri yagona usul boʻlmaydi; xususiy joylarda kamera oʻrnatish taqiqlanadi" degan aynan normalar Oʻzbekiston birlamchi manbasida tasdiqlanmadi — bu aniq daʼvolarni mustaqil tekshiring. Amaliy maslahat: alternativ usul (karta, parol, ID) soʻrang, rad etilsa vakolatli organga (pd.gov.uz) murojaat qiling. Oʻz maʼlumotingizni koʻrish/tuzatish/oʻchirish huquqi boʻyicha 8-bandga qarang
