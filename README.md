# ChatGPT
Présentation (in French) des dernières évolutions de l'IA. IA Génératives. ChatGPT et al... webotheque

Sommaire
* Historique

ChatGPT fait parti du champ de l'Intelligence Artificielle dans le sous-ensemble Deep Learning :

![IA vue ensembliste](img/DeepLearning2IA.png "Vue ensembliste des categories d'IA").

* Classification des approches

Voici les évolutions des modèles de Deep Learing depuis 10 ans. A chaque case cela represente un ou deux papiers originaux , puis des centaines de papiers de recherche et application ( site Arxiv)

![10 ans de Deep Learning](img/10yOfAI.png "Dix ans de Deep Learning").
 * ChatGPT

Crée par Open AI en 2022. C'est une application de type Chatbot qui a surpassée l'attente des utilisateurs avec de nombreuses incompréhensions. Record de vitesse d'adoption battu, quelques millions d'utilisateurs en quelques jours. Multi-taches, Multi-langues. Absolument sans garde-fou et garantie :-)

 * Profusion de modèles concurrents

Voir le papier " A survey of LLM figure 1"

 * Le fine tuning

Voir le slide d'Andrew Karpathy

![GPT Pipeline d'entrainement](img/GPT-TrainingPipelines.PNG "GPT Pipeline d'entrainement").

* LangChain

  un LLM est associé au monde exterieur ( moteur de recherche, calculatrice , calendrier etc ..) via differents connecteurs voir les workflow suivants

![GPT et LangChain](img/LangChain.png "GPT et LangChain").

 * Emerging-LLM-App-Stack

   Graphique détaillé des modules en jeu lors d'un déploiement LLM , voir une vision épurée avec RAG

![LLM stack ](img/Emerging-LLM-App-Stack.png "GPT et LLM new stack").

* Retrieval Augmented Generation , RAG
  
  Ce pattern permet de préciser le contexte à placer dans le prompt. Il force un prompt engineering sur et permet par exemple d'ajouter des références dans la réponse pour des requetes sur ses propres données qui ont été "embeddés" dans une base de données "Vecteur". Embedding ou plongement est l'espace abstrait (multimodal eventuellement) qui transforme une requete ou un texte dans un vecteur. Voir par exemple Word2Vec pour l'apparition de cette notion

![RAG fwk ](img/RAG.png "RAG Framework").  

Une autre vue , par weights and bias ( wandb.ai )

![RAG fwk ](img/wandb-course.png "RAG Framework 2").  

Dans le rapport de la commission de l'IA , 13 mars 2024

![Cercle Vertueux de l'IA !](img/LeCercleVertueuxDel'IA.png)

  

 
# Webotheque 

folder doc et mooc et/ou fichiers links
 
