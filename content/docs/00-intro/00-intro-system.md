# 00 — SYSTEM

Je suis informaticien.

Je préfère vous prévenir tout de suite.

Ça expliquera beaucoup de choses dans les pages qui suivent.

J'ai une légère tendance à considérer qu'un problème incompréhensible doit forcément avoir des logs quelque part, qu'un comportement étrange mérite qu'on regarde les processus en cours et que, si vraiment plus rien ne fonctionne, il reste toujours la possibilité de redémarrer.

Déformation professionnelle.

Devant un problème, certaines personnes parlent à leurs amis. D'autres consultent un psy.

Moi, je tape mentalement :

```text
$ tail -f /var/log/life.log
```

Chacun sa méthode.

Je suis aussi un enfant des années 80.

Ce qui n'arrange rien.

J'ai grandi à une époque où un ordinateur était encore un objet légèrement mystérieux, où un téléphone servait essentiellement à téléphoner et où Internet, lorsqu'il a fini par arriver dans nos maisons, produisait avant chaque connexion le cri d'agonie caractéristique d'un modem 56K.

Une partie non négligeable de mon système d'exploitation a aussi été compilée à partir de *Retour vers le futur*, *WarGames*, *SOS Fantômes*, *Indiana Jones*, *Terminator* et de quelques centaines d'heures de culture parfaitement inutile.

Mon cerveau est donc capable de retrouver instantanément une réplique de film vieille de trente ans.

En revanche, pourquoi je suis entré dans la cuisine ?

```text
SYSTEM:

Long-term pop-culture storage ....... 98%
Useful short-term memory ............ 12%

Status: NORMAL FOR AGE
```

Merci.

C'est probablement pour ça que, lorsque j'ai décidé de raconter une histoire vieille de plus de dix ans, mon cerveau l'a traitée comme il traite à peu près tout le reste.

Comme un système à analyser.

J'avais des souvenirs, des fichiers, des messages, des textes, des dates, des traces numériques.

Autrement dit :

des logs.

Et lorsqu'un informaticien trouve des logs, il fait rarement ce qu'il devrait raisonnablement faire.

Les laisser tranquilles.

```text
$ grep -R "WTF" ./past/

WARNING:
Too many results.
```

Ça aurait dû être mon premier indice.

Il restait cependant un problème.

Je suis informaticien.

Pas écrivain.

Dans ma tête, certaines scènes existaient encore parfaitement. Les transformer en livre était une autre histoire.

Construire un chapitre. Trouver un rythme. Couper. Déplacer. Réécrire. Remettre ce qu'on venait de supprimer. Puis découvrir le lendemain que le passage écrit à deux heures quarante-sept du matin et considéré comme absolument génial était, en réalité, une grosse merde.

**Écrivain, c'est un putain de métier.**

Et ce n'était pas le mien.

Il me fallait de l'aide.

Nous sommes en 2026.

Je suis informaticien.

J'ai grandi avec *Terminator*.

J'ai donc pris la seule décision logique possible.

J'ai confié le problème à une intelligence artificielle.

Oui.

`Skynet`

Je sais.

```text
SYSTEM EVENT

1984:
Human watches Terminator.

Conclusion:
Never trust artificial intelligence.

2026:
Same human gives AI access to manuscript.

Conclusion:
Lessons learned ............ 0
```

Quelques centaines d'heures plus tard, une chose était claire : l'IA pouvait m'aider à structurer, challenger, couper, reformuler ou supporter la cent-quarante-septième version du même paragraphe.

Mais elle ne pouvait pas inventer ce qui comptait vraiment.

Les logs.

---

Cette histoire est inspirée de faits réels.

Et pour une fois, cette phrase signifie exactement ce qu'elle dit.

Une partie des traces existe encore : textes, messages, dates, archives.

Mais vous ne les aurez pas toutes.

Une histoire réelle appartient d'abord aux personnes qui l'ont vécue. Certains éléments permettent de la raconter. D'autres n'ont aucune raison de sortir des archives.

Je ne suis pas en train de publier un dump de production.

```text
$ pg_dump life > public.sql

ERROR:
Are you completely fucking insane?
```

Excellente question.

Le réel sera donc notre point de départ.

Pas notre prison.

Et lorsque nous aurons atteint la limite de ce qui doit être raconté, nous changerons simplement de branche.

Mais nous n'en sommes pas encore là.

Il reste un dernier détail à régler.

Mon cerveau.

---

Vous avez vu *Vice-Versa* ?

Plusieurs émotions installées derrière une console et chargées de piloter un cerveau.

Chez moi aussi, il y a une console.

Sauf que Pixar avait Joie, Tristesse, Peur, Colère et Dégoût.

Mon cerveau a manifestement téléchargé ses dépendances sur un dépôt beaucoup moins recommandable.

J'ai récupéré le casting d'`American Pie`

J'ai récupéré quatre processus.

**Stifler. Oz. Kevin. Finch.**

Et moi au milieu.

Théoriquement root.

```text
$ whoami
jim

$ sudo systemctl status brain

WARNING:
Multiple unmanaged processes detected.
```

Présentation des services.

## STIFLER

![Stifler — stifler.exe](/images/stifler.jpg)

Stifler est la pulsion, le sexe, l'ego et le chaos.

C'est le processus qui transforme une pensée parfaitement respectable en quelque chose qu'il serait généralement préférable de ne pas prononcer à voix haute.

Il n'a aucun filtre.

Aucune notion du moment approprié.

Et des droits administrateur qu'il n'aurait jamais dû obtenir.

Mais Stifler possède aussi une fonction importante : c'est une soupape de sécurité.

Quand la charge émotionnelle devient trop forte, il trouve généralement le moyen de la faire redescendre.

Rarement avec délicatesse.

Jamais avec dignité.

```text
stifler.exe

filter .............. NOT FOUND
dignity ............. NOT FOUND
libido .............. RUNNING
admin_rights ......... inexplicably YES
```

## OZ

![Oz — oz.exe](/images/oz.jpg)

Oz, c'est le cœur.

Le romantique.

La partie du système qui considère que les émotions constituent parfaitement une donnée exploitable, même lorsqu'elles ne rentrent dans aucune colonne d'un tableur.

Il conserve des détails que personne ne lui a demandé de sauvegarder.

Très longtemps.

Beaucoup trop longtemps.

```text
oz.exe

logic ............... OPTIONAL
emotional_cache ..... UNLIMITED
delete_old_memories . DISABLED
```

## KEVIN

![Kevin — kevin.exe](/images/kevin.jpg)

Kevin représente la raison, les faits et la cohérence.

C'est notre administrateur sécurité.

Il refuse tout par défaut.

Kevin vérifie les dates, confronte les souvenirs aux faits et pose généralement la question que personne n'avait envie d'entendre.

Il est prudent.

Méthodique.

Souvent pénible.

Et malheureusement souvent utile.

```text
kevin.exe

firewall ............ ENABLED
risk_tolerance ...... LOW
fact_check .......... ENABLED
fun .................. BLOCKED BY POLICY
```

## FINCH

![Finch — finch.exe](/images/finch.jpg)

Finch analyse.

**Tout.**

Une phrase, une date, un fichier, une incohérence : donnez-lui trois lignes de logs et il voudra immédiatement les trois gigaoctets précédents.

Il corrèle.

Il compare.

Il reconstruit.

Et il considère manifestement que « c'est vieux, on s'en fout » n'est pas une hypothèse de travail acceptable.

```text
finch.exe

analysis ............ RUNNING
pattern_detection ... RUNNING
log_retention ....... FOREVER
overthinking ........ CRITICAL
```

## JIM

![Jim — processus principal, normalement](/images/jim.jpg)

Jim, c'est moi.

Enfin...

C'est censé être moi.

Le processus principal.

Celui qui possède théoriquement la console, les droits root et le dernier mot.

```text
jim.exe

role ................ narrator
root_access ......... YES
actual_control ...... DEBATABLE
```

Voilà.

Vous connaissez l'architecture.

Le reste viendra quand il devra venir.

```text
SYSTEM BOOT

project ............. LEGACY CODE

source:
  real_logs ......... AVAILABLE
  privacy_filter .... ENABLED

internal processes:
  stifler.exe ....... RUNNING
  oz.exe ............ RUNNING
  kevin.exe ......... RUNNING
  finch.exe ......... RUNNING

jim.control ......... nominal

SYSTEM:
Narrative environment ready.

$ _
```

Bon.

Maintenant, on peut commencer.
