**Description des variables globales** :

*config* - dictionnaire stockant les paramètres de l'application.

*dictRu* - dictionnaire, stockage de la traduction de l'interface utilisateur en russe.

*dictEn* - dictionnaire stockant la traduction de l'interface utilisateur en anglais.

*dictDe* - dictionnaire stockant la traduction de l'interface utilisateur en allemand.

*dictEs* - dictionnaire stockant la traduction de l'interface utilisateur en espagnol.

*dictFr* - dictionnaire stockant la traduction de l'interface utilisateur en français.

*allDicts* - dictionnaire, stockant les dictionnaires pour l'ensemble des langues.

*valueInput* - élément de l'interface utilisateur, où la valeur saisie par l'utilisateur est stockée.

*resultInput* - élément de l'interface utilisateur, qui stocke la valeur du résultat du calcul de la racine carrée.

*precisionInput* - élément de l'interface utilisateur, qui stocke la valeur des chiffres significatifs.

*precisionSlider* - élément d'interface utilisateur associé au curseur permettant de modifier la valeur des chiffres significatifs.

*digitsAfterPointInput* - l'élément d'interface utilisateur qui stocke la valeur des chiffres après le point décimal.

*digitsAfterPointSlider* - l'élément d'interface utilisateur lié au curseur permettant de modifier la valeur des chiffres après la virgule.

*languageSelect* - élément de l'interface utilisateur, qui enregistre la langue actuellement sélectionnée.

**Description de la fonction** :

*clampDigits*

- Description : coupe le nombre de chiffres après la virgule pour la sortie sur le serveur spécifié.
- Paramètres d'entrée :
  - *valeur* - nombre pour lequel le nombre de décimales est défini

*clamp*

- Description : limite le nombre de chiffres dans la plage spécifiée
- Paramètres d'entrée :
  - *précision* - nombre
  - *min* - valeur minimale
  - *max* - valeur maximale

*setPrecision

- Description : définit la valeur de précision pour le nombre résultant 
- Paramètres d'entrée :
  - *précision* - valeur de la précision

*setDigitsAfterPoint*

- Description : détermine la valeur du nombre de décimales pour le nombre de résultats. 
- Paramètres d'entrée :
  - *digits* - valeur du nombre de décimales

*setPrecisionSupported*

- Description : définit le support de la précision, en fonction de la valeur de l'indicateur. 
- Paramètres d'entrée :
  - *valeur* - la valeur logique du drapeau

*updateResult*

- Description : calcule la valeur de la racine carrée et met à jour la valeur de la variable de sortie

*mise à jour de la langue

- Description : met à jour la description textuelle des éléments de l'interface utilisateur lorsque la langue est modifiée.