Configurer l'intégration avec les sources d'authentification externes
=====================================================================

Les paramètres généraux de l'intégration avec des sources externes
d'authentification se configurent dans le menu Configuration \>
Authentification \> Configuration Authentification .

Les sources d'authentification externes prises en charges par GLPI sont
les suivantes :

-   annuaire LDAP ; voir [Authentifier des utilisateurs à partir
    d'annuaires
    LDAP](config_auth_ldap.html "L'interface de GLPI avec les annuaires LDAP se configure depuis le menu Configuration > Authentification > Annuaire LDAP.");
-   serveur de messagerie ; voir [Authentifier des utilisateurs à partir
    de serveurs de
    messagerie](config_auth_imap.html "L'interfaçage de GLPI avec des serveurs de messagerie comme source d'authentification se configure depuis le menu Configuration > Authentification > IMAP/POP.");
-   serveur CAS ; voir [Configurer les autres méthodes
    d'authentification
    externe](config_auth_other.html "L'interfaçage de GLPI à des systèmes permettant de faire de l'authentification unique se configure depuis le menu Configuration > Authentification > Autre méthode d'authentification.");
-   certificat x509 ; voir [Configurer les autres méthodes
    d'authentification
    externe](config_auth_other.html "L'interfaçage de GLPI à des systèmes permettant de faire de l'authentification unique se configure depuis le menu Configuration > Authentification > Autre méthode d'authentification.");
-   authentification déléguée au serveur web; voir [Configurer les
    autres méthodes d'authentification
    externe](config_auth_other.html "L'interfaçage de GLPI à des systèmes permettant de faire de l'authentification unique se configure depuis le menu Configuration > Authentification > Autre méthode d'authentification.");

Afin de pouvoir utiliser ces sources externes d'authentification, il
faut au préalable activer les extensions correspondantes dans la
configuration de PHP. Il n'y a pas de limite quant au nombre de sources
externes configurées dans l'application.

Pour utiliser la capacité de GLPI de créer à la volée des utilisateurs
présents dans les sources externes d'authentification, il faut l'activer
dans le menu Configuration \> Authentification \> Configuration
Authentification . Les annuaires LDAP permettent en outre de refuser la
création des utilisateurs ne possédant pas d'habilitations. La
suppression d'un utilisateur de l'annuaire peut aussi entraîner une
action telle que la mise à la corbeille de l'utilisateur, la suppression
de ses habilitations ou sa désactivation.

**Parent topic:** [Configurer la gestion
d'identité](../glpi/config_auth.html "La manière dont GLPI gère l'authentification et les informations personnelles des utilisateurs se configure depuis le menu Configuration > Authentification.")
