# Réponses TP 2

**Auteur:** *Lucas Gosteli*

## Exercice 1

### b)

Quelles étapes (steps) sont réalisées par cette action ?

> - uses: actions/checkout@v3
> - name: Set up Python 3.10
> - name: Install dependencies
> - name: Lint with flake8
> - name: Test with pytest

Une étape est définie au minimum par 2 éléments, lesquels sont-ils et à quoi servent-ils ?

> name : donne le noms de l'étape
> run : qui execute des commandes

La première étape contient le mot-clé ‘with’, a quoi sert-il  ?

> Il sert à passer des arguments à l'étape qui va être lancé

## Exercice 2: Qualité de code

### a)

Sur l’onglet Summary d’une analyse de code, SonarCloud fournit 4 indicateurs. Quels sont-ils et quelles sont leurs utilités ?

À quoi sert l’indicateur Quality Gate ?

### b)

Quelle est la différence entre les sections New code et Overall Code dans l’onglet Summary ?

Y a-t-il des Code Smells ? Si oui, combien et pour quelle(s) raisons(s) ?

Y a-t-il des Security Hotspots ? Si oui, combien et pour quelle(s) raison(s) ?

## Exercice 3: Gitlab CI/CD

### a)

1. Que fait le job pytest ?
2. Que fait le job image-creation ?
3. Que fait le job package-creation ?
4. Les jobs s’exécutent-ils dans le même ordre que défini dans le fichier ? Sinon, pourquoi ?
5. Le stage 2 génère une image Docker. Où est-elle stockée et comment pouvez-vous la retrouver ?
6. Le stage 3 génère un wheel Python. Où est-il stocké et comment pouvez-vous le retrouver ?
