### Stockage de vos fichiers téléchargés

Pour faciliter le processus d'installation et le premier accès, Tiki enregistre par défaut dans sa base de données vos fichiers téléchargés (documents bureautiques, images, pdf, etc. attachés à des pages wiki, des messages de forum, des éléments de suivi, des galeries de fichiers...) Cela fonctionne parfaitement dans la plupart des cas, mais ce n'est pas la configuration recommandée si vous devez enregistrer plusieurs milliers de fichiers ou plus.

Dans ce cas, envisagez de passer de "Store to database" à "Store to directory", que vous trouverez dans l'assistant de configuration. Veuillez utiliser ce répertoire de chemin prédéfini : `__DATA_DIR__`. Vous pourrez migrer vos fichiers actuellement téléchargés de l'un à l'autre.
