# Comment fonctionnent les LLM — Une exploration visuelle

**🌐 [Voir la page en ligne](https://uneiaparjour.github.io/how-llms-work/)**

---

## À propos

Ce dépôt contient l' **adaptation et la traduction française** de la page interactive originale
[How LLMs Work](https://github.com/ynarwal/how-llms-work) créée par **[ynarwal](https://github.com/ynarwal)**.

La traduction a été réalisée par **Bertrand Formet** pour [uneIAparjour.fr](https://uneiaparjour.fr),
avec l'aide de **Claude** (Anthropic).  

---

## La source

La page originale est une exploration visuelle et interactive du fonctionnement des grands modèles de langage (LLM), basée sur la conférence d'**Andrej Karpathy** :

> *« Intro to Large Language Models »*  
> [▶ Voir sur YouTube](https://www.youtube.com/watch?v=zjkBMFhNj_g)

Elle couvre l'ensemble des étapes de construction d'un LLM :
collecte des données, tokenisation, pré-entraînement, inférence,
modèle de base, post-entraînement (SFT + RLHF), psychologie des LLM, RAG.

---

## La démarche de traduction

### Pourquoi traduire cette page ?

La page de ynarwal est une très bonne introduction visuelle aux LLM disponible en ligne — pédagogiquement solide, interactive, accessible à un public non technique. La rendre disponible en français peut répondre à un besoin pour les publics francophones, notamment dans les contextes éducatifs et de formation professionnelle.

### Comment la traduction a été produite

La traduction a été réalisée avec **Claude Sonnet** (Anthropic), dans l'interface claude.ai.

Le processus s'est déroulé en plusieurs étapes :

1. **Traduction complète** du HTML — textes, attributs d'accessibilité (`aria-label`, `aria-describedby`), navigation, boutons
2. **Adaptation des démos interactives** — la séquence de génération de tokens utilise une phrase en français (« Le ciel apparaît bleu ») avec des tokens candidats adaptés ; le canvas animé de l'intro utilise des fragments en français
3. **Adaptation du diagramme BPE** — l'exemple illustre la tokenisation du mot « tokenisation » en français
4. **Ajout du bandeau d'attribution** dans l'introduction, indiquant l'auteur original, le traducteur et l'outil utilisé
5. **Vérification** de la cohérence terminologique (termes techniques maintenus en anglais mais expliqués quand c'est l'usage : token, embedding, RLHF, SFT, etc.)

### Ce qui n'a pas été modifié

- La structure HTML et le CSS
- Le JavaScript (logique des animations, démos interactives)
- Les chiffres et statistiques (avec une note précisant qu'ils sont représentatifs de l'ère 2024)
- Le design visuel

### Note sur la vérification

Le contenu traduit a été relu, il est aligné avec ce qui est décrit dans la conférence de Karpathy. Pour toute inexactitude, ouvrir une issue.

---

## Crédits

| Rôle | Personne / Outil |
|---|---|
| Page originale | [ynarwal](https://github.com/ynarwal/how-llms-work) |
| Conférence source | [Andrej Karpathy](https://www.youtube.com/watch?v=zjkBMFhNj_g) |
| Traduction et adaptation| [Bertrand Formet](https://uneiaparjour.fr) |
| Aide à la traduction | [Claude](https://claude.ai) (Anthropic) |

---

## Licence

La licence de l'œuvre originale s'applique.  
Adaptation et traduction partagées dans le même esprit — libre d'utilisation pour tout usage pédagogique et non commercial, avec attribution.
