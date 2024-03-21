Démarrer avec Gemini API🚀
=========================

L'API Gemini LLM Multimodal est un outil puissant pour intégrer des fonctionnalités multimodales dans vos applications. Il fournit une interface transparente pour accéder et contrôler différents modes de transport, tels que les voitures, les vélos et les transports en commun, le tout au sein d'une seule API.

- **Première étape: accéder à ce repo `<https://github.com/omvriio/gemini_api>` **
    - Installer Git bash si vous ne l'avez pas déjà :
        windows: `https://git-scm.com/download/win`
        mac: `https://git-scm.com/download/mac`
        linux: `https://git-scm.com/download/linux`
    - Sur VSCode : 
        - Utiliser le raccourci `Ctrl + Shift + P`
        - Chercher Git: Cloner ou Git: Clone (en anglais)
        - Coller le lien du repo `https://github.com/omvriio/gemini_api` dans la barre de recherche
        - Choisir un dossier de destination pour le repository
- **Deuxième étape: obtenir une clé API**
    - Allez sur : `https://aistudio.google.com/app/apikey`
    - Cliquez sur "Créer une clé API"
    - Copier la clé API et Coller la dans le fichier .env sans les guillemets

- **Troisième étape: installer les dépendances**
    - Ouvrer le terminal dans le dossier du projet et taper `pip install -r requirements.txt`

- **Quatrième étape: lancer l'application streamlit localement**
    - Ouvrer le terminal dans le dossier du projet
    - Taper :
        - `streamlit run chat_api.py --server.enableXsrfProtection false`: pour essayer gemini en mode chat
        - `streamlit run vision_api.py --server.enableXsrfProtection false`: pour essayer le model de vision
