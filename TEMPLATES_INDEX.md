# Index des Templates Disponibles

## 🔧 Code (templates/code/)

| Template | Usage | Tokens | Économie |
|----------|-------|--------|----------|
| `react_component.xml` | Créer composant React avec TDD | ~120 | 70% |
| `api_endpoint.xml` | Créer endpoint API REST | ~100 | 65% |
| `test_suite.xml` | Générer tests unitaires | ~60 | 75% |
| `refactor.xml` | Refactoring code | ~80 | 60% |
| `debug.xml` | Debugging et fix | ~90 | 55% |

## 📊 Analysis (templates/analysis/)

| Template | Usage | Tokens | Économie |
|----------|-------|--------|----------|
| `competitive_analysis.xml` | Analyse concurrentielle | ~250 | 60% |
| `data_analysis.xml` | EDA et statistiques | ~120 | 65% |
| `financial_analysis.xml` | Analyse financière | ~180 | 55% |

## ✍️ Content (templates/content/)

| Template | Usage | Tokens | Économie |
|----------|-------|--------|----------|
| `blog_post.xml` | Article de blog SEO | ~200 | 60% |
| `documentation.xml` | Doc technique | ~120 | 65% |
| `email.xml` | Emails professionnels | ~90 | 70% |

## 🎯 Orchestration (templates/orchestration/)

| Template | Usage | Tokens | Économie |
|----------|-------|--------|----------|
| `sub_agent.xml` | Architecture multi-agents | ~250 | 85-96% |
| `meta_chain.xml` | Chaîne de prompts | ~200 | 40-60% |

---

## Comment Utiliser

### Méthode 1 : Copier-Coller
```bash
cat templates/code/react_component.xml
# Copier → Personnaliser → Envoyer à Claude
```

### Méthode 2 : Référence Directe (si uploadé)
```xml
@templates/code/react_component.xml
<customization>
- component_name: UserProfile
- props: user, onEdit
</customization>
```

### Méthode 3 : Base pour Nouveau Template
```bash
cp templates/code/react_component.xml templates/code/my_custom.xml
# Éditer selon besoin
```

---

## Créer Votre Propre Template

### Structure Recommandée

```xml
<role>[Expert spécifique]</role>
<extended_thinking_budget>[0/512/1024/2048]</extended_thinking_budget>

<task>[Action claire]</task>

<context>
[Informations essentielles]
</context>

<requirements>
- Requirement 1
- Requirement 2
</requirements>

<output_format>
[Structure précise attendue]
</output_format>

<conventions>[PROJECT_NAME]_2024_STRICT</conventions>
```

### Checklist Qualité

- [ ] <300 tokens total
- [ ] Role spécifique (pas "expert généraliste")
- [ ] Output format précis
- [ ] Testé avec métriques
- [ ] Documenté (cas d'usage)

---

## Benchmarks Moyens

| Type | Tokens Standard | Tokens Optimisé | Économie |
|------|----------------|-----------------|----------|
| Simple | 400-800 | 80-150 | 70-80% |
| Moyen | 1500-3000 | 400-800 | 60-75% |
| Complexe | 5000-15000 | 1500-4000 | 60-70% |

---

## Contribution

Créé un super template ? Partagez-le !

1. Fork le repo
2. Ajoutez votre template dans le bon dossier
3. Testez-le avec métriques
4. Pull Request avec benchmark

**[Guide de contribution →](CONTRIBUTING.md)**
