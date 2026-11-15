# Calculateur d'IMC — Vue 3 + Vite

Application qui calcule l'indice de masse corporelle (poids en kg, taille en cm) et affiche la catégorie.

## Lancer le projet
```bash
npm install
npm run dev
```
Puis ouvrir http://localhost:5173

## Rôles
- `ref` : données réactives (`poids`, `taille`, `afficherResultat`)
- `computed` : `imc`, `categorie`, `explication` recalculés automatiquement
- `v-model` : liaison dans les deux sens entre les champs et les `ref`
- Extension : couleur différente selon la catégorie (classe CSS dynamique)

## Tests
| Poids | Taille | IMC | Catégorie |
|---|---|---|---|
| 70 kg | 175 cm | 22,9 | Corpulence normale |
| 50 kg | 170 cm | 17,3 | Insuffisance pondérale |
| 80 kg | 170 cm | 27,7 | Surpoids |
| 100 kg | 170 cm | 34,6 | Obésité |
