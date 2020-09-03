# Projet de développement logiciel (PDL), 2020-2021


Ce module se déroule à l'Université de Rennes 1, ISTIC, en Master 1 (MIAGE).
L'objectif de PDL est de mener à bien un projet logiciel avec des technologies et données ouvertes. De nombreux défis sont à relever, nécessitant des compétences en gestion de projet, en modélisation, et en programmation.

Cette mise en situation doit permettre de mieux comprendre et appréhender la difficulté de développer du logiciel dans un contexte extrêmement concret. Des techniques et outils (git, github, Maven, JUnit, etc.) de développement logiciel, bien connus de l’industrie, seront utilisés. Des choix technologiques devront également être effectués. Il est attendu de la part de chaque étudiant de PDL de démontrer qu’elle ou il est capable :
 * de comprendre l’existant (exigences, spécificité des technologies et du domaine d’application, architecture, format des données, etc.) 
 * de contribuer très concrètement à un projet à la fois au niveau du code (cas de tests, ajouts de fonctionnalités, refactoring, etc.), de la documentation, ou de la mise en œuvre de l’intégration continue
 * de maîtriser un ensemble de technologies (Java et son écosystème, CSV, JSON, JUnit, API Web, etc.) et de techniques (e.g., test) importantes 
 * de s’adapter à l’évolution d’un projet et de ses exigences
 * de travailler collectivement 
 * de tenir les dates de rendu 
 * de valider de manière continue les exigences et l’implémentation
 
Les objectifs et l'organisation de PDL sont décrits dans ce document: https://annuel2.framapad.org/p/projetpdl2021-9iqv
 
## Projet: Polyglot Wikipedia Matrix Extractor 

L'objectif du projet PDL 2020-2021 est d’extraire des tableaux au format CSV à partir de pages Wikipedia. 
C'est la suite du projet 2018-2020: http://blog.mathieuacher.com/WikipediaMatrixChallenge/ 
L'originalité cette année est quadruple:
 * on veut écrire des extracteurs dans d'autres langages que Java (e.g., en Python ou JavaScript) -- c'est une approche multi-langage, *polyglote* 
 * on veut *tester* ces extracteurs écrits dans différents langages
 * on veut établir des *vérités terrains* (i.e., les résultats CSV attendus) en construisant un outil et en se servant des extracteurs
 * (option) on veut proposer un *service en ligne* pour faciliter l'extraction par un utilisateur lambda
 
Pour initier le projet, chaque groupe s'appuiera sur des implémentations existantes d'extracteur, en Java, et réalisés par les promotions précédentes. 

Le projet est décrit dans YYYY

La composition des groupes est à remplir en ligne avant le XXX:
https://lite.framacalc.org/9iqv-projetpdl2021-groupes 

Le projet que vous aurez à maintenir et faire évoluer vous sera donné mercredi 25 septembre à 10h: *cf la feuille Google sheet et les assignations*

Pour chaque projet à reprendre, effectuez un *fork* du repository Github (un seul par groupe): ce sera votre repository jusqu'à la fin du projet. Indiquer l'URL de votre repository Github sur la feuille Google sheet

**Du println() aux test automatiques et à l'intégration continue**: slides en ligne, cf `CM-validation-1920.pdf`! Un des objectifs de votre projet est de mettre en oeuvre des tests automatiques et de l'intégration continue pour valider et continuellement améliorer vos extracteurs. 

## Dates de rendu

 * EX : 7 octobre 2020 (23h59)  
 * SP1 : 7 novembre 2020 (23h59)
 * SP2 : 1er décembre 2020 (23h59)
 * PR : 6 décembre 2020  


## Années précédentes 
 
Matériel des années précédentes: https://github.com/acherm/PDL1920/ https://github.com/acherm/PDL1819/ http://mathieuacher.com/teaching/PDL/
 
Les projets ont été très variés et changent chaque année (analyse de données issues d'OpenFoodFacts, Wikipedia, Wikidata, d'échecs, de l'impression 3D, contributions à un projet comme FAMILIAR ou opencompare, etc.) mais l'objectif pédagogique reste le même. 


