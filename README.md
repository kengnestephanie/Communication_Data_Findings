## Table des matières
- [Motivation du projet](#mo)
- [Aperçu du projet](#po)
- [Détails du projet](#dp)
  - [Choix du jeu de données](#choix)
  - [Exploration des données](#explorer)
  - [Documentation](#ds)
- [Jeu de données](#data)
- [Informations clés pour la présentation](#cle)
- [Pourquoi ce projet?](#p) 


## Motivation du projet <a name="mo"></a>

Nous nous sommes intéressés à utiliser les données sur les prêts prospères pour mieux comprendre : </br>
- Exploration univariée :
   - Statut du prêt
   - Statut d'emploi
   - Revenu mensuel déclaré
- Exploration bivariée :
   - Statut et note de prospérité
   - Début de Crédit avec la catégorie d'inscription
   - Statut du prêt et montant du prêt
   - Note de prospérité et statut d'emploi
- Exploration multivariée :
   - Notation, montant du prêt et statut du prêt
   - Relations entre la catégorie de crédit, la cote de crédit et le résultat du crédit
   - Relations entre Montant de prêt, catégorie de prêt et statut du prêt 
  
## Aperçu du projet <a name="ap"></a>

Ce projet comporte deux parties qui démontrent l'importance et la valeur des techniques de visualisation des données dans le processus d'analyse des données. Dans la première partie, vous utiliserez les bibliothèques de visualisation Python pour explorer systématiquement un ensemble de données sélectionné, en partant de tracés de variables uniques et en passant à des tracés de plusieurs variables. Dans la deuxième partie, vous produirez une courte présentation illustrant les propriétés, les tendances et les relations intéressantes que vous avez découvertes dans l'ensemble de données sélectionné. La principale méthode de transmission de vos découvertes consistera à transformer vos visualisations exploratoires de la première partie en visualisations explicatives raffinées.


## Détails du projet <a name="dp"></a>

Ce projet est divisé en deux grandes parties. Dans la première partie, vous effectuerez une analyse exploratoire des données sur un ensemble de données de votre choix. Vous utiliserez les bibliothèques Python de science des données et de visualisation de données pour explorer les variables de l'ensemble de données et comprendre la structure, les bizarreries, les modèles et les relations des données. L'analyse dans cette partie doit être structurée, allant des relations univariées simples aux relations multivariées, mais elle n'a pas besoin d'être nette ou parfaite. Il n'y a pas de réponse unique qui doit sortir d'un ensemble de données donné. Cette partie du projet est votre opportunité de poser des questions sur les données et de faire vos propres découvertes. Il est important de garder à l'esprit que parfois l'exploration peut mener à des impasses, et qu'il peut prendre plusieurs étapes pour creuser jusqu'à ce que vous recherchez vraiment.

Dans la deuxième partie, vous tirerez les principales conclusions de votre exploration et les transmettrez aux autres par le biais d'une analyse explicative. À cette fin, vous allez créer un jeu de diapositives qui s'appuie sur des visualisations claires et explicatives pour communiquer vos résultats. Cette partie du projet devrait faire un usage intensif de la première partie du projet.

### Etape 1.1: Choix du jeu de données<a name="choix"></a>

Tout d'abord, vous choisirez un jeu de données dans les options d'ensemble de données.

Téléchargez le fichier Options de jeu de données pour obtenir des détails complets.

### Etape 1.2: Exploration des données <a name="explorer"></a>

Il est temps d'aborder les parties intéressantes. Explorez vos données et documentez vos résultats dans un rapport. Le rapport doit présenter brièvement l'ensemble de données, puis passer systématiquement en revue les points d'exploration que vous avez menés. Vous devriez avoir des en-têtes et du texte qui organisent vos pensées et vos conclusions. Les visualisations dans cette partie du projet n'ont pas besoin d'être complètement peaufinées : il ne s'agit que de votre propre exploration à ce stade. Cependant, vous devez toujours vous assurer que vous respectez les principes d'utilisation de types de tracés et d'encodages appropriés afin que des conclusions précises puissent être tirées, et que vous ayez suffisamment de commentaires et d'étiquetage pour que lorsque vous reprenez votre travail, vous puissiez saisir rapidement votre analyse. pas.

### Etape 2.1: Documentation  <a name="ds"></a>

À la fin de votre exploration, vous avez probablement un tas de choses que vous avez découvertes. Il est maintenant temps d'organiser vos découvertes et de sélectionner une histoire que vous transmettrez aux autres. Dans votre document, vous devez résumer vos principales conclusions et réfléchir aux étapes que vous avez suivies dans votre exploration des données. Vous devez également présenter les informations clés que vous souhaitez transmettre dans votre rapport explicatif ainsi que toute modification apportée aux visualisations, ou noter les nouvelles visualisations qui seront créées pour faire le pont entre vos informations.

### Etape 2.2: Création de la diaporama <a name="sd"></a>

Suivez les plans que vous avez établis à l'étape précédente et créez un jeu de diapositives avec des visualisations de données explicatives pour raconter une histoire sur les données que vous avez explorées. Vous pouvez commencer avec le code que vous avez utilisé dans votre exploration, mais vous devez vous assurer que le code est révisé afin que vos tracés soient peaufinés. Assurez-vous de prêter également attention aux aspects de l'intégrité de la conception dans vos révisions.


## Jeu de données <a name="data"></a>

Cet ensemble de données contient 113937 prêts avec 81 variables sur chaque prêt, pour les besoins de cette enquête, nous avons considérés les variables suivantes : Term, LoanStatus, BorrowerRate, ProsperRating (Alpha), ListingCategory (numeric), EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans , LoanOriginalAmount, LoanOriginationDate, Recommandations, Investisseurs.


## Informations clés pour la présentation<a name="cle"></a>

Nous avons choisi des tracés clés avec un rapport données/encre élevé pour la présentation. Les graphiques que nous avons choisis montrent la distribution des principales variables, l'état du prêt, le revenu mensuel déclaré, la note de prospérité et nous avons essayé de raconter une histoire, quels sont les principaux prédicteurs de statut du prêt et des variables de la note de prospérité.
   
### Pourquoi ce projet? <a name="p"></a>

La visualisation des données est une compétence importante qui est utilisée dans de nombreuses parties du processus d'analyse des données. La visualisation **exploratoire** des données se produit généralement pendant et après le processus de traitement des données. Il s'agit de la principale méthode que nous utiliserons pour comprendre les modèles et les relations présents dans nos données. Cette compréhension nous aidera à aborder toutes les analyses statistiques et nous aidera à tirer des conclusions et des constatations. Ce processus peut également éclairer les tâches de nettoyage de données supplémentaires à effectuer. Des techniques de visualisation de données **explicatives** sont utilisées après la génération de nos résultats et sont utilisées pour aider à communiquer vos résultats à d'autres. Comprendre les considérations de conception nous assurera que notre message est clair et efficace. En plus d'être un bon producteur de visualisations, passer par ce projet nous aidera également à être un bon consommateur de visualisations qui nous sont présentées par d'autres.

