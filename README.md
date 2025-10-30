# CleanMyWorkspace 🧼

Projet pédagogique en Go visant à illustrer la modularité, la gestion des dépendances locales, et le nettoyage d’un espace de travail en 2D.

## 📦 Structure

- `CleanMyWorkspaceFinal/` : projet principal
- `CleanMyWorkspace/` : module local importé via `replace`
- `Documents/puisance4.md` : ressource annexe
- `gunod` : fichier complémentaire

## 🚀 Exécution

```bash
cd CleanMyWorkspaceFinal
go mod tidy
go run main.go
