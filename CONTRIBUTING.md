# Contributing Guidelines / Ghid pentru Contribuții

🇷🇴 [Română](#română) | 🇬🇧 [English](#english)

---

## 🇷🇴 Română

### 🎯 Înainte să contribui

1. **Verifică** dacă politicianul nu există deja în `people.json`
2. **Asigură-te** că persoana este o figură politică publică din Moldova
3. **Citește** regulile de mai jos cu atenție

### 📝 Cum să faci un Pull Request

1. **Fork** repository-ul
2. **Creează** un branch nou: `git checkout -b add-politician-nume`
3. **Editează** `people.json`
4. **Commit** cu mesaj descriptiv: `git commit -m "Add politician: Nume Prenume (PARTID)"`
5. **Push** la fork-ul tău: `git push origin add-politician-nume`
6. **Deschide** un Pull Request

### ✏️ Format JSON corect

```json
{
  "id": 999,
  "name": "Ion Popescu",
  "team": "PAS",
  "imageUrl": "https://example.com/image.jpg"
}
```

**Atenție la:**
- Virgulă după fiecare obiect (exceptând ultimul)
- Ghilimele duble pentru string-uri
- ID unic (verifică ultimul ID folosit)
- URL-uri complete cu `https://`

### 🖼️ Surse recomandate pentru imagini

1. **Wikipedia Commons** - Preferată pentru imagini cu licență liberă
2. **Site-uri oficiale** ale partidelor sau parlamentului
3. **Profiluri oficiale** de social media (publice)

**Nu folosiți:**
- Imagini private sau protejate de copyright
- Screenshot-uri de calitate slabă
- Imagini editate sau modificate
- Meme-uri sau caricaturi

### ⚠️ Reguli importante

- **Un singur politician** per Pull Request
- **Verifică** validitatea JSON (poți folosi [jsonlint.com](https://jsonlint.com))
- **Păstrează** ordinea alfabetică după partid, apoi după nume
- **Nu șterge** sau modifica politicieni existenți fără motiv valid
- **Folosește** numele oficial complet (nu porecle)

### 📋 Checklist înainte de submit

- [ ] ID-ul este unic
- [ ] Numele este complet și corect scris
- [ ] Partidul folosește abrevierea standard
- [ ] URL-ul imaginii funcționează
- [ ] Imaginea este clară și profesională
- [ ] JSON-ul este valid
- [ ] Commit message-ul este descriptiv

---

## 🇬🇧 English

### 🎯 Before contributing

1. **Check** if the politician doesn't already exist in `people.json`
2. **Ensure** the person is a public political figure from Moldova
3. **Read** the rules below carefully

### 📝 How to make a Pull Request

1. **Fork** the repository
2. **Create** a new branch: `git checkout -b add-politician-name`
3. **Edit** `people.json`
4. **Commit** with descriptive message: `git commit -m "Add politician: First Last (PARTY)"`
5. **Push** to your fork: `git push origin add-politician-name`
6. **Open** a Pull Request

### ✏️ Correct JSON format

```json
{
  "id": 999,
  "name": "John Smith",
  "team": "PAS",
  "imageUrl": "https://example.com/image.jpg"
}
```

**Pay attention to:**
- Comma after each object (except the last one)
- Double quotes for strings
- Unique ID (check the last ID used)
- Complete URLs with `https://`

### 🖼️ Recommended image sources

1. **Wikipedia Commons** - Preferred for freely licensed images
2. **Official websites** of parties or parliament
3. **Official social media** profiles (public)

**Don't use:**
- Private or copyrighted images
- Low quality screenshots
- Edited or modified images
- Memes or caricatures

### ⚠️ Important rules

- **One politician** per Pull Request
- **Verify** JSON validity (you can use [jsonlint.com](https://jsonlint.com))
- **Maintain** alphabetical order by party, then by name
- **Don't delete** or modify existing politicians without valid reason
- **Use** complete official names (no nicknames)

### 📋 Checklist before submitting

- [ ] ID is unique
- [ ] Name is complete and correctly spelled
- [ ] Party uses standard abbreviation
- [ ] Image URL works
- [ ] Image is clear and professional
- [ ] JSON is valid
- [ ] Commit message is descriptive

---

## 📧 Contact / Contact

For questions or issues / Pentru întrebări sau probleme:
- Open an issue / Deschide un issue: [GitHub Issues](https://github.com/victorantos/JocPoliticInfo/issues)
- Game website / Site-ul jocului: [jocpolitic.info](https://jocpolitic.info)