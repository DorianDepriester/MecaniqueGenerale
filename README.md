# MecaniqueGenerale
Cours de Mécanique du Solide Indéformable

## Compilation
Le compilateur makeglossaries est nécessaire à la création de la liste des symboles

Le schéma complet de compilation est donc le suivant :
```bash
pfdlatex MecaniqueGenerale
makeglossaries MecaniqueGenerale
pfdlatex MecaniqueGenerale
pfdlatex MecaniqueGenerale
```
