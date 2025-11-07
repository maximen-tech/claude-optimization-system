# Exemple 1 : Feature Simple avec TDD

## Scénario
Créer une fonction de calcul de taxes pour e-commerce.

## AVANT (Sans optimisation) - 8000 tokens, 4 itérations

```
Salut, j'aimerais que tu crées une fonction pour calculer les taxes...
[Long texte descriptif de 400 tokens]
```

**Résultat** : 4 allers-retours, code sans tests, bugs.

## APRÈS (Avec template) - 1200 tokens, 1 itération

```xml
<task>TDD: Function calculateTax(price, region)</task>
<context>E-commerce. Tax: 5-20% by region.</context>
<stack>TypeScript strict</stack>
<workflow>1. Tests 2. Code 3. Refactor</workflow>
<o>Tests + Code. <100 lines.</o>
```

**Résultat** : 1 aller-retour, code testé, qualité production.

**Économie : 85%** 🎉
