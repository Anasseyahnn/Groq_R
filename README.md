# 🚀 GroqR • _The Blazing-Fast Groq API Client for R_  

![image](https://github.com/user-attachments/assets/2ac737e7-9bc8-40e5-b793-3707b1b9a8e9)



[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![CRAN Status](https://www.r-pkg.org/badges/version/GroqR)](https://cran.r-project.org/package=GroqR)  

**Interagissez avec l’API Groq en R** pour des réponses **ultra-rapides** en NLP, grâce aux **LPU (Language Processing Units)** de Groq. Idéal pour le traitement de texte, la génération de contenu et l'analyse de données.  

---

## ✨ **Pourquoi GroqR ?**  
- ⚡ **Vitesse inégalée** : Réponses en **millisecondes** avec les modèles Llama 3, Mixtral, Gemma, etc.  
- 📊 **Intégration transparente** : Fonctionne nativement dans vos scripts R.  
- 🔧 **Simple mais puissant** : De la requête basique aux conversations complexes.  

```r
library(groqR)
response <- groq_chat("Explique-moi le machine learning comme si j'avais 5 ans.")
cat(response$choices[[1]]$message$content)
```

🔧 Installation

Depuis GitHub (version dev)
```r
if (!require("remotes")) install.packages("remotes")
remotes::install_github("Anasseyahanan/GroqR")
```

Depuis CRAN (soon)
```r
install.packages("GroqR")
```

💡 Utilisation de base  

Configuration de la clé API    
Obtenez une clé API gratuite sur [Groq Cloud](https://console.groq.com/keys) et configurez-la     

 
📊 Fonctionnalités    
    
✅ Support des principaux modèles Groq (Llama 3, Mixtral, Gemma, etc.)    
✅ Gestion des conversations multi-tours (chat complet avec historique)    
✅ Personnalisation des paramètres (temperature, max_tokens, etc.)    
✅ Gestion des erreurs et timeouts configurables    


📂 Structure du projet    

test_ai_R/               
│___ main.R             # Fonctions principales  
│___.Renviron           # Variable d'envirionnement   
└── README.md           # Ce fichier  


🔗 Liens utiles
Site officiel Groq
Documentation Groq API
