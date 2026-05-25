# Sayniska Fasalka 8aad - Imtixaan MCQ

Kani waa codsi mareeg (web app) ah oo loogu talagalay ardayda Fasalka 8aad si ay u bartaan una tijaabiyaan aqoontooda maaddada **Sayniska** iyaga oo maraya imtixaanno su'aalo doorasho ah (MCQ). 

Codsigan wuxuu ka kooban yahay dhammaan cutubyada buugga Sayniska ee Fasalka 8aad (Cutubka 1aad ilaa 14aad) kuwaas oo loo qaybiyay 7 weji (Phases).

---

## 🌟 Tilmaamaha Muhiimka ah (Features)

- **Wejiyo iyo Cutubyo Go'an (Phase & Chapter Structure)**: Imtixaanku wuxuu u habaysan yahay 7 weji, mid walbana wuxuu isku darayaa labo cutub oo xiriira si ardayga uusan u wareerin.
- **Doorashooyin La Xiriira Su'aasha (Smart Distractors)**: Jawaabaha qaldan ee doorashada (A, B, C, D) waxaa si firfircoon looga soo xulaa isla cutubka ay su'aashu ku jirto, taas oo ka dhigaysa doorashooyinka kuwo macno leh oo la xiriira dulucda su'aasha.
- **Kaydinta Horumarka (LocalStorage Progress)**: Haddii ardaygu ka baxo mareegta ama uu refresh gareeyo, wuxuu ka sii wadan karaa halkii uu kaga tagay isaga oo riixaya badhanka **"Sii wad Imtixaanka"**.
- **Badhanka Dib-u-dejiye (Reset Option)**: Haddii ardaygu rabo inuu buriyo horumarkiisii hore oo uu weji cusub ama isla wejigii hore ka bilaabo eber, wuxuu isticmaali karaa badhanka **"Ka bilow bilow (Reset)"** oo ku yaal kaarka sii-wadista.
- **Naqshad Casri ah (Premium UI/UX)**: Wuxuu ku dhisanyahay qaabka *Glassmorphism* oo leh midabyo indhaha u roon, animations fudud, iyo la-qabsi buuxa oo loogu talagalay talefannada gacanta (Fully Responsive Mobile Design).

---

## 🛠️ Tiknoolajiyada La Isticmaalay (Tech Stack)

Codsigan wuxuu ku dhisanyahay si fudud oo aan u baahnayn wax adeege ah (serverless) ama dependency adag:
- **HTML5**: Dhismaha guud ee bogga iyo qaabaynta semantic-ga ah.
- **CSS3**: Naqshad dhalaalaysa, glassmorphic dark theme, animations, iyo responsive styling.
- **JavaScript (ES6+)**: Matoorka su'aalaha, dynamic rendering, Fisher-Yates Shuffling algorithm, iyo maareynta LocalStorage.

---

## 📂 Qaabdhismeedka Faylasha (File Structure)

- **`index.html`** - Dhismaha guud ee UI-ga iyo qaybaha kala duwan ee screens-ka (Phase selection, Quiz screen, Results screen).
- **`index.css`** - Habaynta midabada, layout-ka responsive-ka ah, iyo animations-ka.
- **`app.js`** - Sharciga shaqada ee quiz-ka, doorashada distractors-ka isla cutubka ah, kaydinta/sii-wadista imtixaanka ee LocalStorage.
- **`data.js`** - Keydka xogta su'aalaha iyo jawaabaha oo u habaysan wejiyo iyo cutubyo.
- **`favicon.png`** - Astaanta tab-ka ee browser-ka (Favicon) oo ah astaan Saynis oo qurxoon.

---

## 🚀 Sida Loo Adeegsado (How to Run)

Maadaama uu yahay codsi ku shaqeeya static files, uma baahnid inaad wax ku rakibto kumbuyuutarkaaga:
1. Soo degso dhammaan faylasha mashruuca.
2. Labo jeer guji faylka **`index.html`** si aad ugu furto browser kasta (Chrome, Edge, Safari, Firefox).
3. Dooro Phase-ka aad rabto inaad iska tijaabiso oo bilow!