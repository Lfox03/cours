---
title: Bases de données
description: des fonctions et définitions de base pour la NSI.
---

# 1. Bases de données

Une section mémo pour les fonctions et définitions de base en NSI

## 1. Définitions

!!! note "intégrité de domaine"
    Les **valeurs** doivent appartenir au **domaine fixé** pour chaque attribut

!!! note "intégrité de relation _(ou contrainte d'unicité)_"
    **Chaque tuple est unique** et doit être identifié par une clé primaire qui ne peut pas être nulle.

    Par conséquent, une valeur de clé primaire ne peut apparaître qu'une fois dans la relation.

!!! note "intégrité de référence _(ou intégrité référencielle)_"
    Entre deux relations: toute **clé étrangère** doit faire **référence** à une **clé primaire** d'une autre table.

    Par conséquent, la valeur d'une clé étrangère doit toujours être également une des valeurs de la clé référencée.

```sql linenums="1"
SELECT * FROM Jaja
WHERE id_jaja > 5
```