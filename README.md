# Databázový systém zamestnancov

- Projekt je pripravený pre Eclipse ako Java konzolová aplikácia.

# Spustenie:
- 1. Eclipse -> File -> Import -> Existing Projects into Workspace.
- 2. Vyber priečinok Databaza_Projekt_Petrik_Gazovic.
- 3. Spusti triedu app.Main.
  
# Splnené požiadavky:
- OOP: dedičnosť, abstraktná trieda Employee, polymorfizmus.
- Abstraktná trieda: model.Employee.
- Rozhranie: service.SkillExecutable.
- Dynamická dátová štruktúra: ArrayList, HashMap.
- Dve skupiny zamestnancov: DataAnalyst, SecuritySpecialist.
- Zamestnanec má ID, meno, priezvisko, rok narodenia.
- Zamestnanec eviduje spolupracovníkov a úroveň spolupráce.
- Pridanie/odobranie zamestnanca, pridanie spolupráce, vyhľadanie podľa ID.
- Spustenie dovednosti podľa skupiny.
- Abecedný výpis podľa priezviska v skupinách.
- Štatistiky: prevažujúca kvalita spolupráce, zamestnanec s najviac väzbami.
- Výpis počtu zamestnancov v skupinách.
- Uloženie/načítanie zamestnanca do/zo súboru.
- SQL záloha: implementovaný DatabaseManager pre SQLite cez JDBC.
