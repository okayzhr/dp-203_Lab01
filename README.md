## 📊 Azure Synapse Analytics - Gegevensanalyseproject

Dit project is een verkennende oefening met **Azure Synapse Analytics**, waarin we verschillende mogelijkheden van het platform demonstreren: van data-inname tot analyse met SQL en Spark.

### 🚀 Overzicht

In deze oefening heb je:

- Een Azure Synapse Analytics-werkruimte ingericht via een PowerShell-script en een ARM-template
- Gegevens geïmporteerd vanuit een externe bron naar een Data Lake
- Serverless SQL gebruikt om CSV-data te analyseren
- Apache Spark gebruikt met PySpark-notebooks voor gegevensverkenning
- Een dedicated SQL pool gebruikt voor het uitvoeren van datawarehouse-query's
- Visualisaties gemaakt in Synapse Studio
- Het project opgeruimd door de resource group te verwijderen


### 🛠️ Benodigdheden

- Een actieve Azure-abonnement met beheerdersrechten
- Toegang tot de Azure Portal: https://portal.azure.com
- Enige ervaring met PowerShell, SQL en Python is een pluspunt

### 📁 Projectstructuur

```plaintext
dp-203/
├── Allfiles/
│   └── labs/
│       └── 01/
│           ├── setup.ps1
│           └── andere labbestanden
├── README.md (dit bestand)
```

### ⚙️ Installatie en Uitvoering

1. Clone de repository:
   ```powershell
   git clone https://github.com/MicrosoftLearning/dp-203-azure-data-engineer dp-203
   cd dp-203/Allfiles/labs/01
   ./setup.ps1
   ```

2. Volg de stappen in [deze oefening](https://learn.microsoft.com/en-us/training/modules/explore-synapse-studio/), of de uitgebreide handleiding in dit bestand, om:

   - Data te importeren naar Azure Data Lake Storage
   - SQL scripts en notebooks te bouwen in Synapse Studio
   - Pipelines te maken en te monitoren
   - Analyses en visualisaties uit te voeren

3. Verwijder de resource group aan het eind om kosten te vermijden.

### 🧠 Belangrijke concepten

- **Synapse Studio**: Webinterface voor het beheren en analyseren van data
- **Serverless SQL Pool**: Gebruik SQL zonder infrastructuur te beheren
- **Apache Spark Pool**: Schaalbare analyse met Python, Scala en meer
- **Pipelines**: Geautomatiseerde workflows voor dataverwerking
- **Dedicated SQL Pool**: Klassieke datawarehouse-oplossing

### 📌 Opmerking

> Vergeet niet je resource group te verwijderen na gebruik:
> 
> - Ga naar *Resource groups* in de Azure Portal
> - Selecteer `dp203-xxxxxxx`
> - Klik op **Delete resource group**

![Schermafbeelding 2025-04-03 210945](https://github.com/user-attachments/assets/9ed25c72-ed6d-496f-adfa-4ab618a99035)
![Schermafbeelding 2025-04-03 211804](https://github.com/user-attachments/assets/a2ed5cf9-3455-4d8b-ab96-fb6f1db526be)
![Schermafbeelding 2025-04-03 212906](https://github.com/user-attachments/assets/87eb58e9-de64-4b30-825d-14a591cceeeb)
![Schermafbeelding 2025-04-03 213858](https://github.com/user-attachments/assets/75434a5d-26c3-484c-8bfc-7d7777adc2fb)
![Schermafbeelding 2025-04-04 103056](https://github.com/user-attachments/assets/a1589690-a36e-4eeb-8741-86d73cc97b08)
![Schermafbeelding 2025-04-04 110318](https://github.com/user-attachments/assets/1d659ed9-1486-4911-855a-85f451f3768f)
![Schermafbeelding 2025-04-04 115420](https://github.com/user-attachments/assets/349ede65-52e5-4618-84a4-f6ad0a89a7e9)
![Schermafbeelding 2025-04-04 115806](https://github.com/user-attachments/assets/7453ce98-e8f2-4a84-8a09-9158be8cb1e2)
![Schermafbeelding 2025-04-04 125650](https://github.com/user-attachments/assets/bf2bc3be-dd0f-4b54-9144-70bd41d23646)
![Schermafbeelding 2025-04-04 130652](https://github.com/user-attachments/assets/0b4ed918-ec48-46c4-8f65-7aa2e25db618)
![Schermafbeelding 2025-04-04 132809](https://github.com/user-attachments/assets/35c76bef-62a4-4108-a4c1-92e7b4da9f75)










