---
created: 
template_destination_folder: 05 🗓 Journalier
---



Tag : #daily

***
## 🌱 Tache Journalières
- [ ] Sport 
- [ ] Lecturesssssssssss

## Synthèse journée 


<%* 
// Définir le chemin du fichier cible 
const targetPath = `05 🗓 Journalier/${tp.file.title}-add.md`;
// Vérifier si le fichier existe 
if (await app.vault.adapter.exists(targetPath)) 
{ %>  ![[<% targetPath %>]]  <%* } 
else 
{ %>   <%* } 

%>