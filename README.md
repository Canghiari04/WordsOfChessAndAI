# WordOfChessAndAI
Progetto per Tesi Triennale Informatica per il Management (8014) Anno Accademico (2023/2024)

## Informazioni
L'obiettivo della tesi prevede di sviluppare un sistema capace di estrarre tutti i metadati principali da una lista di articoli scientifici in formato PDF, in questo caso focalizzati sull'evoluzione del rapporto tra `Intelligenza Artificiale` e `Computer Chess`, e adeguare una serie di tecniche di machine learning affinché il contenuto recuperato possa essere classificato secondo delle liste predefinite di etichette. È bene precisare che il sistema è stato realizzato in maniera tale che possa operare indipendentemente dall'archivio di documenti accademici scelti e dalle liste di categorie predeterminate.

## Pre-requisiti
Prima di eseguire i differenti `Notebook`, è necessario aver già installato:
- Python 3.10 o versioni più recenti
- La lista di dipendenze richieste

## Installazione
1. Clona la repository localmente.
```bash
git clone https://github.com/Canghiari04/WordsOfChessAndAI.git
```
2. Crea un ambiente virtuale.
```bash
python3 -m venv .venv
source .venv/bin/activate
```
3. Installa le dipendenze.
```bash
cd pip
pip install -r requirements.txt
```