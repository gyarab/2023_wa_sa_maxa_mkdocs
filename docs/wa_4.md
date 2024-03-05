# Krátký záznam z hodiny webových aplikací dne *23.2* 
![Fotka tabule](/docs/TabuleZHhodinyWA.png)

## Krátké shrnutí
- Připomněli jsme si naši oblíbenou zkratku **D.R.Y** _("Do NOT repeat yourself!")_ 
- Vytvořili jsme statickou webovou stránku pomocí [**MkDocs**](https://www.mkdocs.org/)
- **MkDocs** je generátor statických stránek určený pro projektovou dokumentaci stavby. Je napsán v jazyce Python.
- V poslední řadě jsme naši webovou aplikaci postli do repozitáře na github

### How to MkDocs
- Instalace knihovny  
`py -3 -m venv venv`
- Aktivujeme knihovnu, abychom mohli instalovat mkdocs.  
`source ./venv/Script/activate `
- Instalace MkDocs  
`pip install mkdocs`  
`python -m mkdocs`

### How to "postnout webovou aplikaci na github"
Prvně musíme vytvořit soubor .gitignore, do kterého napíšeme to, co **necheme** pushnout (venv/)  
- `$ git init`  
- `$ git add .`  
- `$ git commit -m "My first commit"`  
- `$ git branch -M main`  
- `$ git remote add origin link_to_your_repo`  
- `$ git push -u origin main`  
