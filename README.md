# JocPoliticInfo - Data Repository

🇷🇴 [Română](#română) | 🇬🇧 [English](#english)

---

## 🇷🇴 Română

### 📊 Despre acest repository

Acest repository conține datele pentru jocul de memorie politică găzduit la [jocpolitic.info](https://jocpolitic.info).

Jocul este o versiune digitală a clasicului joc de memorie, folosind imagini ale politicienilor moldoveni. Scopul este educativ și distractiv - să ajute cetățenii să recunoască figurile politice din Moldova.

### 🤝 Cum să contribui

Apreciem contribuțiile comunității! Iată cum poți ajuta:

1. **Fork** acest repository
2. **Modifică** fișierul `people.json` pentru a:
   - Adăuga politicieni noi
   - Actualiza informații existente
   - Corecta greșeli
3. **Trimite** un Pull Request cu modificările tale
4. **Așteaptă** aprobarea de la moderatori

### 📋 Structura datelor

Fiecare politician trebuie să urmeze această structură:

```json
{
  "id": 123,
  "name": "Nume Prenume",
  "team": "PARTIDUL",
  "imageUrl": "https://link-către-imagine.jpg"
}
```

**Câmpuri obligatorii:**
- `id`: Număr unic (nu duplica ID-uri existente!)
- `name`: Numele complet al politicianului
- `team`: Abrevierea partidului (ex: PAS, PSRM, PPPDA, PN, BCS, PPDA, etc.)
- `imageUrl`: Link direct către o imagine publică

### 📸 Cerințe pentru imagini

- Format: JPG sau PNG
- Dimensiune recomandată: minim 250x250 pixeli
- Imagine clară, profesională, preferabil portret
- Hosting public accesibil (ex: Wikipedia Commons, site-uri oficiale)
- ⚠️ **NU încărcați imagini direct în acest repository!**

### 📝 Exemple de partide

- `PAS` - Partidul Acțiune și Solidaritate
- `PSRM` - Partidul Socialiștilor din Republica Moldova
- `PPPDA` - Platforma DA
- `PN` - Partidul Nostru
- `BCS` - Blocul Comuniștilor și Socialiștilor
- `PDM` - Partidul Democrat din Moldova
- `PPDA` - Partidul Platforma Demnitate și Adevăr

### ✅ Reguli de contribuție

- Verifică că persoana este o figură politică publică activă
- Folosește nume oficiale complete
- Asigură-te că imaginea este de bună calitate
- Păstrează formatarea JSON validă
- Un politician per Pull Request pentru review mai ușor

---

## 🇬🇧 English

### 📊 About this repository

This repository contains the data for the political memory game hosted at [jocpolitic.info](https://jocpolitic.info).

The game is a digital version of the classic memory game, using images of Moldovan politicians. The purpose is educational and entertaining - to help citizens recognize political figures from Moldova.

### 🤝 How to contribute

We appreciate community contributions! Here's how you can help:

1. **Fork** this repository
2. **Modify** the `people.json` file to:
   - Add new politicians
   - Update existing information
   - Fix errors
3. **Submit** a Pull Request with your changes
4. **Wait** for approval from moderators

### 📋 Data structure

Each politician must follow this structure:

```json
{
  "id": 123,
  "name": "First Last",
  "team": "PARTY",
  "imageUrl": "https://link-to-image.jpg"
}
```

**Required fields:**
- `id`: Unique number (don't duplicate existing IDs!)
- `name`: Full name of the politician
- `team`: Party abbreviation (e.g., PAS, PSRM, PPPDA, PN, BCS, PPDA, etc.)
- `imageUrl`: Direct link to a public image

### 📸 Image requirements

- Format: JPG or PNG
- Recommended size: minimum 250x250 pixels
- Clear, professional image, preferably portrait
- Publicly accessible hosting (e.g., Wikipedia Commons, official websites)
- ⚠️ **DO NOT upload images directly to this repository!**

### 📝 Party examples

- `PAS` - Party of Action and Solidarity
- `PSRM` - Party of Socialists of Republic of Moldova
- `PPPDA` - Platform DA
- `PN` - Our Party
- `BCS` - Bloc of Communists and Socialists
- `PDM` - Democratic Party of Moldova
- `PPDA` - Dignity and Truth Platform Party

### ✅ Contribution rules

- Verify the person is an active public political figure
- Use complete official names
- Ensure the image is good quality
- Keep valid JSON formatting
- One politician per Pull Request for easier review

---

## 🔗 Links / Legături

- 🎮 **Game / Joc**: [jocpolitic.info](https://jocpolitic.info)
- 💻 **Source Code / Cod Sursă**: [github.com/victorantos/FaceMemoryGame](https://github.com/victorantos/FaceMemoryGame)
- 🐛 **Issues / Probleme**: [Report here / Raportează aici](https://github.com/victorantos/JocPoliticInfo/issues)

---

## 📄 License / Licență

This data is provided for educational purposes. All images are publicly available and belong to their respective owners.

Aceste date sunt furnizate în scopuri educaționale. Toate imaginile sunt disponibile public și aparțin proprietarilor respectivi.