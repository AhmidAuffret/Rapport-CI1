# Stratégie d’utilisation des sous-agents Codex

## Objectif

Les sous-agents sont utilisés pour améliorer la qualité du rapport CI1 Leroux grâce à des relectures spécialisées.

Ils ne doivent pas remplacer l’agent principal.

L’agent principal reste responsable :

* de la cohérence globale ;
* de la décision finale ;
* des modifications dans les fichiers ;
* du respect du style de l’étudiant ;
* du respect des consignes IMT ;
* de l’absence d’invention.

## Règle principale

Un seul agent doit modifier les fichiers du rapport.

Les sous-agents doivent produire :

* des constats ;
* des risques ;
* des recommandations ;
* des corrections proposées.

Ils ne doivent pas modifier directement les fichiers, sauf demande explicite de l’agent principal.

## Quand utiliser des sous-agents

Utiliser des sous-agents pour :

1. Relire une partie complète du rapport.
2. Vérifier une mission technique sensible.
3. Contrôler la conformité avec la grille IMT.
4. Vérifier que le style reste proche de celui de l’étudiant.
5. Vérifier la confidentialité et l’anonymisation.
6. Comparer une section avec le plan détaillé.
7. Préparer une relecture finale avant export.

Ne pas utiliser de sous-agents pour :

1. Une petite correction orthographique.
2. Une modification très localisée.
3. Une simple mise à jour de statut.
4. Une tâche déjà claire et courte.
5. Une action Git simple.

## Sous-agents recommandés

### Sous-agent 1 — Relecteur IMT

Rôle :
Vérifier que la section respecte les consignes IMT et couvre les critères de la grille.

À vérifier :

* présentation du contexte ;
* missions ;
* méthodes et outils ;
* étapes ;
* moyens et ressources ;
* difficultés ;
* solutions ;
* résultats ;
* perspectives ;
* clarté ;
* illustrations.

Sortie attendue :

* critères couverts ;
* critères faibles ;
* corrections recommandées ;
* priorité : haute / moyenne / faible.

Modèle recommandé :

* tâche simple ou checklist : modèle rapide possible ;
* analyse d’une grande partie : modèle fort recommandé.

### Sous-agent 2 — Relecteur style étudiant

Rôle :
Vérifier que le texte reste proche du style d’écriture de l’étudiant, à partir de `06_style_ecriture.md` et `10_audit_style_anciens_rapports.md`.

À vérifier :

* écriture progressive ;
* ton personnel ;
* première personne utilisée quand nécessaire ;
* explications accessibles ;
* absence de style trop académique ;
* absence de style trop générique ou artificiel.

Sortie attendue :

* passages qui sonnent trop IA ;
* passages trop soutenus ;
* formulations à simplifier ;
* recommandations de reformulation.

Modèle recommandé :

* modèle fort si la section est longue ou importante ;
* modèle rapide possible pour une relecture courte.

### Sous-agent 3 — Relecteur technique

Rôle :
Vérifier la cohérence technique des missions :

* Intune / Android Enterprise ;
* Power Apps / SharePoint / Power Automate ;
* AD / Microsoft 365 ;
* Docker uniquement si utilisé.

À vérifier :

* absence d’erreur technique ;
* absence d’invention ;
* cohérence des outils ;
* niveau adapté à un rapport CI1 ;
* distinction entre ce qui est fait, observé, supposé ou à vérifier.

Sortie attendue :

* risques techniques ;
* affirmations à vérifier ;
* passages à nuancer ;
* éléments à compléter.

Modèle recommandé :

* modèle fort recommandé.

### Sous-agent 4 — Relecteur confidentialité

Rôle :
Vérifier que le texte ne contient pas d’informations sensibles.

À vérifier :

* mots de passe ;
* secrets ;
* IP internes ;
* noms de comptes ;
* noms de serveurs ;
* logs bruts ;
* données personnelles ;
* captures non anonymisées.

Sortie attendue :

* éléments sensibles trouvés ;
* remplacement recommandé par `[REDACTED]` ;
* niveau de risque.

Modèle recommandé :

* modèle rapide possible pour scan simple ;
* modèle fort si la section contient des logs ou incidents sécurité.

### Sous-agent 5 — Relecteur clarté et structure

Rôle :
Vérifier que la section est lisible, bien structurée et compréhensible par un lecteur non spécialiste.

À vérifier :

* ordre logique ;
* transitions ;
* répétitions ;
* phrases trop longues ;
* paragraphes trop denses ;
* clarté des objectifs et résultats.

Sortie attendue :

* problèmes de structure ;
* simplifications proposées ;
* paragraphes à déplacer ;
* répétitions à supprimer.

Modèle recommandé :

* modèle rapide possible ;
* modèle fort si la partie est longue.

## Choix du modèle selon la complexité

Lorsqu’il invoque un sous-agent, l’agent principal doit choisir un modèle adapté à la complexité de la tâche, si l’environnement Codex le permet.

Règle générale :

* tâche simple, courte, checklist, scan ciblé : modèle rapide ou économique ;
* tâche longue, technique, ambiguë, critique ou structurante : modèle fort ;
* rédaction ou relecture d’une partie majeure : modèle fort ;
* contrôle final du rapport : modèle fort.

Si l’environnement ne permet pas de choisir explicitement le modèle du sous-agent, l’agent principal doit indiquer dans sa consigne le niveau de complexité attendu :

* `complexité faible`
* `complexité moyenne`
* `complexité forte`

## Format de demande à un sous-agent

Quand un sous-agent est utilisé, l’agent principal doit lui donner :

1. Son rôle exact.
2. Les fichiers à lire.
3. Ce qu’il doit vérifier.
4. Ce qu’il ne doit pas faire.
5. Le format de sortie attendu.
6. Le niveau de complexité.
7. Le modèle recommandé si disponible.

## Format de sortie obligatoire des sous-agents

Chaque sous-agent doit répondre avec :

1. Verdict court.
2. Points conformes.
3. Problèmes détectés.
4. Corrections recommandées.
5. Priorité des corrections.
6. Éléments à vérifier humainement.
7. Limites de son analyse.

## Utilisation dans le workflow de rédaction

Pour chaque grande section du rapport :

1. L’agent principal rédige un brouillon.
2. L’agent principal lance les sous-agents nécessaires.
3. Les sous-agents rendent leurs analyses.
4. L’agent principal consolide les retours.
5. L’agent principal applique uniquement les corrections utiles.
6. L’agent principal fait un commit.
7. L’étudiant valide humainement.

## Règle anti-surcorrection

Les sous-agents ne doivent pas transformer le texte en style trop parfait, trop académique ou trop impersonnel.

Le rapport doit rester personnel et crédible comme rapport d’étudiant alternant.
