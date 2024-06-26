# Glossaire (plus ou moins exhaustif) des différents termes de la cybersécurité ! 🔒

## 🛡️ ~~Sécurité Offensive~~
La sécurité offensive est une approche proactive de la cybersécurité qui vise à identifier et corriger les vulnérabilités des systèmes informatiques avant qu'elles ne soient exploitées par les attaquants.

Exemple : Réalisation de tests de pénétration (pentests) pour évaluer la sécurité d'un réseau.

## 🎯 Surface d’attaque
Ensemble des points d’entrée possibles par lesquels un attaquant peut tenter de pénétrer un système.

Exemple : Ports ouverts sur un serveur, interfaces de connexion.

## 💥 Exploitation
Processus d'utilisation de vulnérabilités dans un système pour en prendre le contrôle ou en extraire des données.

Exemple : Utilisation d'un exploit pour obtenir un accès non autorisé à un système.

## ⛓️ Kill Chain
Modèle décrivant les différentes étapes suivies par un attaquant lors d'une intrusion informatique. Ces phases incluent :

- **Reconnaissance** : Rassembler des informations sur la cible.
- **Scannage** : Identifier les vulnérabilités de la cible.
- **Gain d'accès** : Exploiter les vulnérabilités pour accéder à la cible.
- **Maintien de l'accès** : Conserver l'accès à la cible et masquer sa présence.
- **Dissimulation des traces** : Supprimer les preuves de l'intrusion.

L'idée derrière la kill chain est que si vous pouvez identifier et perturber une ou plusieurs de ces phases, vous pouvez arrêter l'attaque avant qu'elle ne réussisse.

Par exemple, vous pouvez mettre en place des contrôles de sécurité pour empêcher la reconnaissance, ou déployer des systèmes de détection d'intrusion pour identifier et bloquer les tentatives d'accès non autorisé.

## 🎯 Pentest

### Black Box
Test de pénétration où l'attaquant n'a aucune information préalable sur l'infrastructure cible.

Exemple : Une entreprise engage un pentesteur pour simuler une attaque externe sans fournir de détails sur son réseau.

### Grey Box
Test de pénétration où l'attaquant dispose de certaines informations limitées sur l'infrastructure cible.

Exemple : Le pentesteur reçoit des informations sur le réseau interne de l'entreprise, mais pas les détails complets.

### White Box
Test de pénétration où l'attaquant a un accès complet aux informations sur l'infrastructure cible.

Exemple : Le pentesteur a accès aux schémas de réseau, aux configurations des serveurs, et au code source des applications.

## 🌐 Social Engineering

### Tailgating / Piggybacking
Technique où un attaquant suit une personne autorisée pour accéder à une zone sécurisée sans avoir de badge ou d'identification.

Exemple : Un intrus suit un employé dans un bâtiment sécurisé en maintenant la porte ouverte.

### Quid Pro Quo
Technique où l'attaquant offre un service ou un avantage en échange d'informations ou d'accès.

Exemple : Un attaquant se fait passer pour un technicien informatique offrant une aide en échange de mots de passe.

### OSINT (Open Source Intelligence)
Collecte d’informations disponibles publiquement pour effectuer des attaques ciblées.

Exemple : Utilisation des réseaux sociaux pour obtenir des informations sur les employés d'une entreprise.

### Red Team
Équipe de sécurité offensive simulant des attaques réelles pour tester la défense d'une organisation.

Exemple : Une Red Team réalise une campagne de phishing pour évaluer la réaction des employés.

### Dumpster Diving
Recherche de données sensibles dans les poubelles ou les zones de déchets.

Exemple : Un attaquant fouille les poubelles d'une entreprise pour trouver des documents jetés contenant des informations confidentielles.

### Impersonation
Technique où l'attaquant se fait passer pour une personne de confiance pour obtenir des informations ou accéder à des ressources.

Exemple : Un attaquant se fait passer pour un employé de la maintenance pour accéder à des zones sécurisées.


## 🛠️ Techniques d’Exploitation🔒

### Buffer Overflow
Vulnérabilité où un programme écrit plus de données dans un tampon que ce qu'il peut contenir, permettant l'exécution de code malveillant.

Exemple : Un attaquant envoie des données excessives à un programme pour exécuter un code arbitraire.

### Privilege Escalation
Technique permettant à un attaquant d'obtenir des niveaux d'accès plus élevés que ceux initialement obtenus.

Exemple : Utilisation d'une vulnérabilité pour passer d'un utilisateur régulier à un administrateur.

### Remote Code Execution (RCE)
Vulnérabilité permettant à un attaquant d'exécuter du code à distance sur un système cible.

Exemple : Exploitation d'une faille dans une application web pour exécuter des commandes sur le serveur.

## 🎯 Phases d’attaque

![Phases d’attaque](https://github.com/kalvin-net/Glossaire-des-termes-de-la-cybers-curit-/assets/172443217/62b7fc29-add5-4dea-81b8-89912d5d687e)

### Reconnaissance
Collecte d'informations sur la cible pour identifier les vulnérabilités potentielles.

Exemple : Scanner les adresses IP d'une entreprise pour trouver les services exposés.

### Scanning
Utilisation d'outils pour détecter les ouvertures et les vulnérabilités sur la cible.

Exemple : Utilisation de Nmap pour identifier les ports ouverts sur un réseau.

### Gaining Access
Exploitation des vulnérabilités identifiées pour pénétrer le système cible.

Exemple : Utilisation d'un exploit pour obtenir un accès à distance à un serveur.

### Maintaining Access
Actions entreprises pour conserver l'accès au système compromis.

Exemple : Installation d'une porte dérobée pour un accès futur.

### Covering Tracks
Effacement des traces de l'attaque pour éviter la détection.

Exemple : Suppression des journaux système pour masquer les activités malveillantes.

## 🧑‍💻 Concepts 🔒

### Hacker
Individu qui utilise ses compétences techniques pour accéder aux systèmes informatiques. Il peut être éthique (White Hat) ou malveillant (Black Hat).

Exemple : Un White Hat effectue un pentest pour aider une entreprise à sécuriser son réseau.

### Bug Bounty
Programme où les entreprises offrent des récompenses financières aux individus découvrant et signalant des vulnérabilités dans leurs systèmes.

Exemple : Google propose des récompenses pour les bugs trouvés dans Chrome.

### Hacktiviste
Hacker qui utilise ses compétences pour promouvoir une cause politique ou sociale.

Exemple : Anonymous lance des attaques DDoS contre des sites gouvernementaux pour protester contre des politiques.

### Backdoor
Accès secret installé dans un système par un attaquant pour permettre un retour ultérieur.

Exemple : Un pirate installe un logiciel malveillant sur un serveur pour un accès futur non détecté.

### Botnet
Réseau de machines compromises contrôlées par un attaquant pour effectuer des actions coordonnées.

Exemple : Utilisation d'un botnet pour lancer une attaque DDoS contre un site web.

### Command and Control (C&C)
Serveur utilisé par un attaquant pour envoyer des commandes aux machines compromises dans un botnet.

Exemple : Un C&C envoie des instructions aux bots pour voler des informations ou lancer des attaques.

### Pivoting
Technique où un attaquant utilise un système compromis comme point d'ancrage pour accéder à d'autres parties du réseau.

Exemple : Compromettre un poste de travail pour accéder ensuite aux serveurs internes.

### Exploit Kit
Ensemble d'outils permettant de trouver et d'exploiter des vulnérabilités dans des systèmes.

Exemple : Un exploit kit peut être utilisé pour compromettre des navigateurs web avec des vulnérabilités non corrigées.

### Payload
Code malveillant livré et exécuté par un exploit.

Exemple : Un payload peut être un ransomware qui chiffre les fichiers d'une victime.

### Shellcode
Code écrit pour être exécuté dans le contexte d'une shell ou d'un autre environnement d'exécution.

Exemple : Utilisation de shellcode pour ouvrir une porte dérobée sur un système compromis.

## 🛡️ Sécurité Défensive 🔒

### Sécurité Systèmes / Endpoint / Hôtes

#### Patch Management
Processus de gestion et d'application des correctifs logiciels pour corriger les vulnérabilités.

Exemple : Application régulière des mises à jour de sécurité Windows.

#### EDR (Endpoint Detection and Response)
Solutions de sécurité conçues pour détecter et répondre aux menaces sur les terminaux.

Exemple : Utilisation d'un EDR pour surveiller et analyser les activités suspectes sur les postes de travail.

#### EPP (Endpoint Protection Platform)
Solution de sécurité combinant antivirus, antimalware et autres fonctionnalités pour protéger les terminaux.

Exemple : Utilisation d'un EPP pour prévenir les infections par des logiciels malveillants.

#### XDR (Extended Detection and Response)
Solution de sécurité intégrant la détection et la réponse sur plusieurs vecteurs (terminaux, réseaux, cloud).

Exemple : Utilisation d'un XDR pour corréler les événements de sécurité entre les terminaux et le réseau.

#### HIDS (Host-based Intrusion Detection System)
Système de détection des intrusions basé sur l'hôte qui surveille et analyse les activités sur un système individuel.

Exemple : Utilisation d'un HIDS pour détecter des modifications non autorisées de fichiers système.

#### Incident de sécurité
Événement ou série d'événements compromettant la confidentialité, l'intégrité ou la disponibilité d'un système d'information.

Exemple : Détection et réponse à une attaque de phishing qui a compromis des comptes utilisateur.

#### Honeypot
Système leurre conçu pour attirer et analyser les activités des attaquants.

Exemple : Déploiement d'un honeypot pour observer les tentatives de piratage et collecter des informations sur les méthodes d'attaque.

#### Sandboxing
Technique d'exécution de programmes dans un environnement isolé pour prévenir les dommages au système hôte.

Exemple : Analyse d'un fichier suspect dans une sandbox pour détecter les comportements malveillants.

### 🎯 Sécurité réseau

#### Intrusion Detection Systems (IDS)
Systèmes qui surveillent le réseau pour détecter les activités suspectes ou malveillantes.

Exemple : Utilisation de Snort pour identifier les tentatives d'intrusion sur le réseau.

#### Intrusion Prevention Systems (IPS)
Systèmes qui non seulement détectent, mais aussi préviennent les activités malveillantes sur le réseau.

Exemple : Utilisation d'un IPS pour bloquer automatiquement les tentatives de scan de ports.

#### Firewall
Dispositif ou logiciel qui contrôle le trafic réseau entrant et sortant basé sur des règles de sécurité prédéfinies.

Exemple : Utilisation d'un pare-feu pour bloquer l'accès non autorisé à certains services réseau.

#### Segmentation Réseau
Technique de division d'un réseau en segments plus petits pour améliorer la sécurité et la gestion.

Exemple : Séparer le réseau d'administration du réseau utilisateur pour limiter les accès.

#### NDR (Network Detection and Response)
Solutions de sécurité centrées sur la détection et la réponse aux menaces dans le trafic réseau.

Exemple : Utilisation d'un NDR pour analyser le trafic réseau et détecter des anomalies.

#### DMZ (Demilitarized Zone)
Zone réseau où sont placés les services accessibles depuis l'extérieur, tout en étant isolés du réseau interne.

Exemple : Héberger des serveurs web dans une DMZ pour protéger le réseau interne contre les attaques directes.

## 🔐 Sécurité des applications

### Secure Software Development Lifecycle (SDLC)
Intégration de pratiques de sécurité tout au long du cycle de développement logiciel.

Exemple : Réalisation de revues de code et de tests de sécurité à chaque étape du développement d'une application.

### Application Security Testing
Ensemble de techniques et d'outils pour identifier les vulnérabilités dans les applications.

Exemple : Utilisation de tests statiques (SAST) et dynamiques (DAST) pour identifier les failles de sécurité dans une application web.

### Code review
Processus d'examen du code source par des développeurs pour identifier et corriger les erreurs et les vulnérabilités.

Exemple : Réalisation de revues de code par des pairs pour s'assurer que les pratiques de sécurité sont respectées.

## 🛡️ Sécurité des données

### Cryptographie
Technique de protection des informations par le chiffrement pour garantir confidentialité, intégrité et authenticité.

Exemple : Utilisation du chiffrement AES pour protéger les données sensibles en transit et au repos.

### Identity & Access Management (IAM)
Gestion des identités et des accès pour garantir que seules les personnes autorisées peuvent accéder aux ressources.

Exemple : Mise en place de l'authentification multifactorielle (MFA) pour renforcer la sécurité des accès.

### Data Loss Prevention (DLP)
Technologies et stratégies pour prévenir la perte ou le vol de données sensibles.

Exemple : Utilisation d'un DLP pour empêcher l'envoi non autorisé de données confidentielles par e-mail.

### Chiffrement des données (Transit et Repos)
Processus de chiffrement des données lorsqu'elles sont transférées (en transit) et lorsqu'elles sont stockées (au repos).

Exemple : Utilisation de TLS pour sécuriser les communications et de chiffrement disque pour protéger les données stockées.

### Data Protection Officer (DPO)
Responsable de la protection des données au sein d'une organisation, garantissant la conformité avec les réglementations de protection des données.

Exemple : Un DPO veille à ce que l'entreprise respecte le RGPD et protège les données personnelles des clients.

## ☁️ Sécurité Cloud

### Cloud Access Security Brokers (CASB)
Solutions de sécurité placées entre les utilisateurs et les services cloud pour appliquer les politiques de sécurité de l'entreprise.

Exemple : Utilisation d'un CASB pour surveiller et contrôler l'accès aux applications SaaS afin de prévenir les fuites de données.

### Identity & Access Management (IAM)
Gestion des identités et des autorisations pour contrôler qui peut accéder à quelles ressources dans un environnement cloud.

Exemple : Utilisation d'AWS IAM pour définir des rôles et des politiques de sécurité sur les services AWS.

### Conformité et Gouvernance dans le cloud
Processus et outils pour garantir que l'utilisation du cloud respecte les réglementations et les politiques de l'organisation.

Exemple : Mise en place de Cloud Security Posture Management (CSPM) pour surveiller la conformité avec le RGPD dans un environnement multi-cloud.

### Sécurité des conteneurs et des microservices
Pratiques et outils pour sécuriser les environnements de conteneurs et les architectures de microservices.

Exemple : Utilisation de solutions comme Kubernetes et Docker pour gérer la sécurité des conteneurs, et implémentation de politiques réseau avec des outils comme Istio.

## 📱 Sécurité Mobile

### Mobile Device Management (MDM)
Solutions pour gérer et sécuriser les appareils mobiles utilisés dans une organisation.

Exemple : Utilisation de Microsoft Intune pour déployer des politiques de sécurité sur les smartphones des employés.

### Détection et réponse aux menaces mobiles (MTD)
Solutions de sécurité pour détecter et répondre aux menaces sur les appareils mobiles.

Exemple : Utilisation de Lookout pour surveiller les menaces et les vulnérabilités sur les appareils mobiles.

### Sécurité des applications mobiles
Pratiques et outils pour sécuriser les applications mobiles contre les vulnérabilités et les attaques.

Exemple : Utilisation de tests d'intrusion mobile et de l'analyse du code source pour détecter et corriger les vulnérabilités dans une application mobile.

### Chiffrement des données mobiles
Processus de chiffrement des données stockées et transmises par les appareils mobiles pour garantir leur confidentialité et leur intégrité.

Exemple : Utilisation de chiffrement de bout en bout pour les messages envoyés via une application de messagerie mobile.

## 🎯 Sécurité des identités et des accès (IAM) 🔒

### Authentification / Autorisation
Processus de vérification de l'identité d'un utilisateur (authentification) et de détermination de ses droits d'accès (autorisation).

Exemple : Utilisation de OAuth 2.0 pour l'authentification et l'autorisation des utilisateurs dans une application web.

### Single Sign-On (SSO)
Solution permettant aux utilisateurs de se connecter une seule fois pour accéder à plusieurs applications ou systèmes.

Exemple : Utilisation de Okta pour permettre aux employés de se connecter une fois et accéder à toutes les applications d'entreprise.

### Multi Factor Authentication (MFA)
Ajout d'une couche de sécurité supplémentaire en exigeant plusieurs méthodes d'authentification.

Exemple : Utilisation d'un mot de passe et d'un code envoyé par SMS pour se connecter à un compte bancaire en ligne.

### Gestion des privilèges
Contrôle des droits d'accès des utilisateurs pour garantir qu'ils ont uniquement les permissions nécessaires pour leurs tâches.

Exemple : Utilisation de solutions comme CyberArk pour gérer et contrôler les accès privilégiés dans une organisation.

## 🎯 Sécurité Opérationnelle 🔒

### Surveillance et Journalisation des Activités
Processus de suivi et d'enregistrement des activités des utilisateurs et des systèmes pour détecter des comportements anormaux ou suspects.

Exemple : Utilisation de Splunk pour collecter et analyser les journaux système afin d'identifier des tentatives d'accès non autorisées.

### Incident response
Ensemble des actions entreprises pour gérer et atténuer les impacts d'un incident de sécurité.

Exemple : Mise en place d'un plan d'intervention pour isoler un serveur compromis et restaurer les données à partir de sauvegardes.

### Threat Hunting
Recherche proactive de menaces et d'activités malveillantes dans les systèmes et réseaux.

Exemple : Utilisation d'outils comme Elastic Stack pour analyser les anomalies et détecter des comportements potentiellement malveillants.

### Security Information and Event Management (SIEM)
Solutions permettant de collecter, analyser et corréler les événements de sécurité à partir de différentes sources pour identifier et répondre aux menaces.

Exemple : Utilisation de SIEM comme IBM QRadar pour centraliser les journaux et détecter les incidents de sécurité en temps réel.

### Computer Expert Response Team (CERT)
Équipe spécialisée dans la gestion et la réponse aux incidents de sécurité informatique, souvent au niveau national ou sectoriel.

Exemple : Le CERT-FR qui fournit des alertes et des conseils de sécurité aux organisations françaises.

### Computer Security Incident Response Team (CSIRT)
Équipe responsable de la gestion des incidents de sécurité au sein d'une organisation spécifique.

Exemple : Le CSIRT d'une entreprise qui intervient en cas de compromission de données ou d'attaques de ransomware.

### False Negative
Événement où un système de sécurité ne parvient pas à identifier une menace réelle.

Exemple : Un antivirus qui ne détecte pas un nouveau type de malware.

### False Positive
Événement où un système de sécurité identifie à tort une activité légitime comme étant une menace.

Exemple : Un IDS qui alerte sur une connexion réseau normale comme étant une tentative d'intrusion.

### Forensic
Enquête et analyse post-incident pour déterminer comment une intrusion s'est produite et quelles données ont été compromises.

Exemple : Analyse des disques durs et des journaux système pour retracer les actions d'un attaquant après une intrusion.

### Reverse Engineering
Processus de déconstruction d'un logiciel ou d'un matériel pour comprendre son fonctionnement interne, souvent utilisé pour analyser des logiciels malveillants.

Exemple : Utilisation d'outils comme IDA Pro pour disséquer un virus informatique et comprendre son mode de fonctionnement.

## 🎯 Sécurité des Infrastructures critiques 🔒

### Supervisory Control and Data Acquisition (SCADA)
Systèmes de contrôle utilisés pour superviser et gérer des infrastructures industrielles critiques comme les réseaux électriques et les usines de traitement de l'eau.

Exemple : Un système SCADA gérant les opérations d'une centrale électrique.

### Industrial Control Systems (ICS)
Systèmes de contrôle utilisés dans les industries pour gérer et automatiser les processus industriels.

Exemple : Utilisation d'un ICS pour contrôler les processus de fabrication dans une usine.

### Protection contre les cyberattaques sur les infrastructures publiques
Mesures et stratégies mises en place pour sécuriser les infrastructures publiques critiques contre les cyberattaques.

Exemple : Mise en place de pare-feu et de systèmes de détection d'intrusion pour protéger un réseau de distribution d'eau contre des attaques cybernétiques.

## 🎯Sécurité des opérations de sécurité - SecOps

### Automatisation et Orchestration de la sécurité (SOAR)
Solutions intégrées permettant d'automatiser et d'orchestrer les réponses aux incidents de sécurité.

Exemple : Utilisation de SOAR comme Palo Alto Cortex XSOAR pour automatiser les réponses aux alertes de sécurité.

### DevSecOps
Intégration de la sécurité dans chaque étape du cycle de développement logiciel, en combinant les pratiques DevOps avec des mesures de sécurité.

Exemple : Mise en place de pipelines CI/CD sécurisés où les tests de sécurité automatisés sont effectués à chaque étape du développement.

### Gestion des vulnérabilités
Processus d'identification, d'évaluation et de traitement des vulnérabilités dans les systèmes et applications.

Exemple : Utilisation de scanners de vulnérabilités comme Nessus pour identifier et corriger les failles de sécurité sur les serveurs et les applications.

### Security Operation Center (SOC)
Centre dédié à la surveillance et à la gestion continue des incidents de sécurité dans une organisation.

Exemple : Un SOC surveillant 24/7 les activités réseau et les journaux de sécurité pour détecter et répondre rapidement aux menaces.

## 🎯 Gestion des risques 🔒

### Gestion des risques
Processus d'identification, d'évaluation et de traitement des risques pour minimiser leur impact sur l'organisation.

Exemple : Utilisation d'un cadre comme ISO 31000 pour structurer l'approche de gestion des risques.

### Conformité / Compliance
Adhésion aux lois, règlements et standards de l'industrie pour garantir que les opérations d'une organisation respectent les exigences légales et réglementaires.

Exemple : Assurer la conformité avec le RGPD pour protéger les données personnelles des utilisateurs.

### DSI (Directeur des Systèmes d'Information)
Responsable de la gestion des technologies de l'information et des systèmes informatiques au sein d'une organisation.

Exemple : Un DSI supervise l'implémentation d'une nouvelle infrastructure cloud pour l'entreprise.

### RSSI (Responsable de la Sécurité des Systèmes d'Information)
Responsable de la sécurité des systèmes d'information, chargé de protéger les actifs numériques de l'organisation.

Exemple : Un RSSI met en place une politique de sécurité pour protéger les données sensibles de l'entreprise.

### PSSI (Politique de Sécurité des Systèmes d'Information)
Document définissant les directives, règles et procédures pour protéger les systèmes d'information d'une organisation.

Exemple : La PSSI d'une entreprise stipule que tous les employés doivent utiliser l'authentification à deux facteurs pour accéder aux systèmes critiques.

### Threat Intelligence
Collecte et analyse d'informations sur les menaces pour anticiper et prévenir les cyberattaques.

Exemple : Utilisation de sources de threat intelligence pour détecter des indicateurs de compromission (IoC) et se protéger contre de nouvelles menaces.

### Risk Management Framework
Cadre structurant l'approche de gestion des risques, intégrant l'identification, l'évaluation et la réduction des risques.

Exemple : Utilisation du NIST RMF pour structurer la gestion des risques dans une organisation gouvernementale.

### Politiques et procédures de Sécurité
Ensemble de directives et de procédures visant à protéger les actifs informationnels d'une organisation.

Exemple : Une politique de sécurité peut inclure des procédures de sauvegarde régulière et des contrôles d'accès stricts.

### GDPR (General Data Protection Regulation)
Règlement européen sur la protection des données personnelles des citoyens de l'UE.

Exemple : Mise en œuvre de politiques de protection des données pour se conformer aux exigences du GDPR.

### HIPAA (Health Insurance Portability and Accountability Act)
Loi américaine régissant la protection des informations de santé sensibles.

Exemple : Les hôpitaux doivent chiffrer les dossiers médicaux électroniques pour se conformer à la HIPAA.

### ISO 27001
Norme internationale de gestion de la sécurité de l'information, spécifiant les exigences pour établir, mettre en œuvre et améliorer un système de gestion de la sécurité de l'information (SMSI).

Exemple : Une entreprise de technologie obtient la certification ISO 27001 pour démontrer son engagement envers la sécurité de l'information.

### PCA (Plan de Continuité d'Activité)
Planification et préparation pour assurer la continuité des opérations pendant et après un incident perturbateur.

Exemple : Un PCA peut inclure des stratégies de reprise après sinistre pour les systèmes informatiques critiques.

### PRA (Plan de Reprise d'Activité)
Stratégie pour restaurer les systèmes et les opérations après un incident, souvent une composante du PCA.

Exemple : Un PRA détaille les étapes pour restaurer les services informatiques après une cyberattaque.

## 🎯 Concepts 🔒

### Hardening
Processus de sécurisation d'un système en réduisant sa surface d'attaque et en éliminant les vulnérabilités.

Exemple : Désactiver les services non essentiels et appliquer les correctifs de sécurité pour durcir un serveur.

### Allow list / Deny list
Liste de contrôle permettant ou bloquant l'accès à des ressources spécifiques.

Exemple : Une allow list autorise uniquement certains IP à accéder à une application, tandis qu'une deny list bloque les IP non autorisées.

### ACL (Access Control List)
Liste spécifiant les permissions d'accès des utilisateurs ou des groupes à des ressources particulières.

Exemple : Une ACL sur un routeur peut définir quels utilisateurs peuvent accéder à certains segments du réseau.

### IoT Security
Pratiques et technologies pour protéger les dispositifs connectés à Internet (Internet of Things) contre les cybermenaces.

Exemple : Utilisation de protocoles sécurisés et de mises à jour régulières pour protéger les dispositifs IoT dans une maison intelligente.

### Surface d’attaque
Ensemble des points de vulnérabilité qu'un attaquant peut exploiter pour accéder à un système.

Exemple : La surface d'attaque d'une application web inclut les formulaires d'entrée, les API et les ports réseau ouverts.

### Posture de sécurité
État global de préparation d'une organisation à se défendre contre les cybermenaces.

Exemple : Une évaluation de la posture de sécurité peut révéler des faiblesses dans les contrôles d'accès et les politiques de mise à jour.

### Moindre privilège
Principe de sécurité selon lequel les utilisateurs ne reçoivent que les permissions nécessaires pour accomplir leurs tâches.

Exemple : Un employé du service financier n'a accès qu'aux systèmes comptables et non aux systèmes RH.

### Assume breach
Approche de sécurité qui part du principe qu'une compromission s'est déjà produite et se concentre sur la détection rapide et la réponse.

Exemple : Une entreprise adopte une stratégie assume breach et déploie des systèmes de détection des intrusions et de surveillance continue.

### Chiffrement de bout en bout
Méthode de cryptographie où les données sont chiffrées sur l'appareil de l'expéditeur et déchiffrées uniquement sur l'appareil du destinataire.

Exemple : Les applications de messagerie comme WhatsApp utilisent le chiffrement de bout en bout pour sécuriser les communications.

### Zero Trust
Modèle de sécurité qui ne fait confiance à aucun utilisateur ou appareil par défaut, même s'ils sont à l'intérieur du réseau.

Exemple : Implémentation de Zero Trust en exigeant une vérification stricte des identités et des autorisations pour chaque accès au réseau.

### Veille
Activité de surveillance continue pour détecter et analyser les nouvelles menaces, vulnérabilités et tendances en cybersécurité.

Exemple : Une équipe de sécurité effectue une veille quotidienne en consultant des sources de threat intelligence et des forums de sécurité.

## 🎯 Cyberattaques 🔒

### Attaques basées sur les logiciels malveillants

#### Virus
Programme malveillant qui se propage en s'attachant à des fichiers exécutables et se réplique lorsqu'il est exécuté.

Exemple : Un virus informatique infectant un fichier Word et se propageant à d'autres fichiers sur le même ordinateur.

#### Ver
Logiciel malveillant capable de se propager de manière autonome à travers les réseaux sans avoir besoin de s'attacher à un programme hôte.

Exemple : Le ver Conficker qui a infecté des millions de systèmes en exploitant une vulnérabilité de Windows.

#### Trojan / Cheval de Troie
Logiciel malveillant déguisé en programme légitime pour tromper les utilisateurs et les inciter à l'installer.

Exemple : Un faux lecteur multimédia téléchargeable qui, une fois installé, donne accès à distance à un attaquant.

#### Ransomware
Malware qui chiffre les données d'une victime et demande une rançon en échange de la clé de déchiffrement.

Exemple : Le ransomware WannaCry qui a paralysé des milliers d'ordinateurs en chiffrant leurs données et exigeant un paiement en Bitcoin pour les déchiffrer.

#### Spyware
Logiciel malveillant conçu pour espionner les activités d'un utilisateur sans son consentement, collectant des informations sensibles.

Exemple : Un spyware qui enregistre les frappes de clavier pour voler des informations de connexion.

#### Adware
Logiciel malveillant qui affiche des publicités non désirées sur l'ordinateur d'un utilisateur, souvent intégré à des logiciels gratuits.

Exemple : Un adware qui affiche des publicités pop-up chaque fois qu'un utilisateur ouvre un navigateur web.

#### Rootkit
Ensemble de logiciels malveillants qui permettent un accès non autorisé à un ordinateur tout en dissimulant leur présence.

Exemple : Un rootkit qui se cache dans le système d'exploitation pour éviter la détection par les logiciels de sécurité.

### 🎯Attaques de Phishing et d'ingénierie Sociale🔒

#### Phishing
Technique de fraude visant à obtenir des informations sensibles en se faisant passer pour une entité de confiance via des emails ou des sites web.

Exemple : Un email prétendant venir d'une banque demandant de vérifier des informations de compte via un lien frauduleux.

#### Spear Phishing
Variante de phishing ciblée où l'attaquant personnalise le message en fonction de la victime spécifique.

Exemple : Un email de spear phishing envoyé à un cadre supérieur, incluant des détails personnels pour le rendre plus crédible.

#### Whaling
Forme de spear phishing ciblant des individus de haut rang dans une organisation, comme les PDG ou les CFO.

Exemple : Un email frauduleux envoyé au PDG d'une entreprise, prétendant venir d'un partenaire commercial et demandant un transfert d'argent urgent.

#### Vishing
Phishing par téléphone, où les attaquants appellent les victimes en se faisant passer pour des entités légitimes pour obtenir des informations sensibles.

Exemple : Un appel prétendant venir de la sécurité bancaire demandant des informations sur la carte de crédit.

#### Smishing
Phishing par SMS, où les attaquants envoient des messages texte pour inciter les victimes à fournir des informations sensibles ou à télécharger des logiciels malveillants.

Exemple : Un SMS prétendant venir d'un service de livraison demandant de cliquer sur un lien pour reprogrammer une livraison.

#### Sock puppet
Compte en ligne fictif créé pour tromper et manipuler les autres utilisateurs sur les réseaux sociaux ou les forums.

Exemple : Un attaquant utilisant plusieurs faux profils pour influencer une discussion en ligne en faveur de ses intérêts.

#### Pretexting
Technique de manipulation où l'attaquant invente un scénario plausible pour inciter la victime à divulguer des informations sensibles.

Exemple : Un appel prétendant venir du service des ressources humaines demandant des informations de sécurité sociale pour une mise à jour de dossier.

#### Baiting
Technique d'ingénierie sociale où l'attaquant attire la victime avec une offre alléchante pour obtenir des informations ou infecter son système.

Exemple : Laisser une clé USB infectée avec une étiquette « Confidentiel » dans un lieu public pour inciter quelqu'un à la brancher à son ordinateur.

#### Doxxing
Publication en ligne d'informations personnelles privées d'une personne sans son consentement, souvent dans le but de nuire ou de harceler.

Exemple : La divulgation des informations personnelles d'un journaliste en ligne en représailles à un article critique.

#### Sybil Attack
Attaque où un individu ou une organisation crée plusieurs identités fausses pour influencer ou perturber un réseau.

Exemple : Un attaquant créant plusieurs faux nœuds dans un réseau peer-to-peer pour manipuler les votes ou les décisions du réseau.

#### Astroturfing
Technique de manipulation où une entreprise ou une organisation crée de faux mouvements de base pour donner l'impression d'un soutien populaire.

Exemple : Une entreprise créant de faux comptes de réseaux sociaux pour promouvoir positivement ses produits et services.

### 🎯 Attaques par le réseau 🔒

#### Man in the Middle / MitM
Attaque où l'attaquant intercepte et éventuellement modifie les communications entre deux parties sans leur connaissance.

Exemple : Intercepter les communications entre un utilisateur et un site web pour voler des informations de connexion.

#### Sniffing
Technique de capture du trafic réseau pour écouter et analyser les données échangées.

Exemple : Utiliser un logiciel comme Wireshark pour capturer les paquets réseau et lire les informations sensibles.

#### Spoofing
Technique où l'attaquant falsifie son identité pour tromper un système ou un utilisateur.

##### IP Spoofing
Falsification de l'adresse IP source pour masquer l'identité de l'attaquant.

Exemple : Envoyer des paquets avec une adresse IP falsifiée pour contourner les règles de sécurité réseau.

##### DNS Spoofing
Corruption des réponses DNS pour rediriger le trafic vers des sites malveillants.

Exemple : Manipuler une réponse DNS pour rediriger les utilisateurs vers un site de phishing.

##### ARP Spoofing
Falsification des messages ARP pour associer l'adresse MAC de l'attaquant à l'adresse IP d'une autre machine.

Exemple : Intercepter le trafic réseau en envoyant de fausses réponses ARP pour rediriger les données vers la machine de l'attaquant.

#### Denial of Service / DoS
Attaque visant à rendre un service ou un réseau indisponible en le submergeant de requêtes.

Exemple : Envoyer une grande quantité de requêtes à un serveur web pour le surcharger et le rendre indisponible.

#### Distributed Denial of Service / DDoS
Variante de l'attaque DoS où plusieurs machines sont utilisées pour submerger la cible.

Exemple : Utiliser un botnet pour lancer une attaque massive sur un serveur.

#### Wi-Fi Cracking
Technique visant à casser les mécanismes de sécurité des réseaux Wi-Fi pour accéder au réseau sans autorisation.

Exemple : Utiliser des outils comme Aircrack-ng pour casser une clé de cryptage Wi-Fi.

#### NAC Bypassing
Technique pour contourner les contrôles d'accès réseau (Network Access Control) qui restreignent l'accès au réseau.

Exemple : Utiliser une adresse MAC autorisée pour obtenir un accès réseau non autorisé.

### 🎯 Attaques sur les applications Web 🔒

#### SQL Injection
Attaque où des commandes SQL malveillantes sont insérées dans les entrées d'une application pour manipuler la base de données.

Exemple : Insérer `' OR '1'='1' --` dans un champ de formulaire pour accéder à des données non autorisées.

#### XPath Injection
Attaque similaire à l'injection SQL, mais visant les requêtes XPath pour manipuler les données XML.

Exemple : Insérer des expressions XPath malveillantes pour accéder à des données XML sensibles.

#### Path Traversal
Attaque où l'attaquant accède à des fichiers sensibles en manipulant les chemins de fichier.

Exemple : Utiliser `../../../etc/passwd` dans une URL pour accéder à des fichiers système critiques.

#### CSP Bypass
Technique pour contourner la politique de sécurité de contenu (Content Security Policy) d'un site web, permettant l'exécution de scripts malveillants.

Exemple : Exploiter des failles dans les directives CSP pour exécuter du code JavaScript malveillant.

#### Local File Inclusion (LFI)
Attaque où l'attaquant inclut des fichiers locaux sur le serveur via des entrées malveillantes.

Exemple : Inclure `/etc/passwd` dans une URL pour afficher le contenu de ce fichier sur une page web.

#### Cross-Site Scripting (XSS)
Attaque où des scripts malveillants sont injectés dans des pages web vues par d'autres utilisateurs.

Exemple : Insérer du JavaScript malveillant dans un champ de commentaire pour voler les cookies des utilisateurs.

#### Cross-Site Request Forgery (CSRF)
Attaque où l'utilisateur authentifié est trompé pour exécuter des actions non désirées sur un site web.

Exemple : Envoyer un lien piégé à un utilisateur connecté pour changer son mot de passe sans son consentement.

#### Remote File Inclusion (RFI)
Attaque où l'attaquant inclut des fichiers distants via des entrées malveillantes.

Exemple : Inclure un fichier hébergé sur un serveur distant pour exécuter du code malveillant sur le serveur cible.

#### Clickjacking
Technique où des éléments invisibles ou déguisés sont placés sur une page web pour inciter les utilisateurs à cliquer sur des liens ou boutons à leur insu.

Exemple : Masquer un bouton de confirmation de transaction sous un bouton apparemment inoffensif.

#### Insecure Direct Object References (IDOR)
Attaque où l'attaquant accède à des objets (fichiers, données) sans autorisation en modifiant les références directes.

Exemple : Modifier l'URL de `/profile?id=123` à `/profile?id=124` pour accéder au profil d'un autre utilisateur.

### 🎯 Attaques sur les Systèmes 🔒

#### Brute Force
Attaque où l'attaquant essaie toutes les combinaisons possibles de mots de passe jusqu'à trouver le bon.

Exemple : Utiliser un outil comme Hydra pour essayer tous les mots de passe possibles sur un compte.

#### Dictionary Attack
Variante de l'attaque par force brute où l'attaquant utilise une liste de mots de passe courants.

Exemple : Utiliser une liste de mots de passe communs pour tenter de se connecter à un compte utilisateur.

#### Credential Stuffing
Utilisation de combinaisons de noms d'utilisateur et de mots de passe volés pour accéder à plusieurs comptes.

Exemple : Utiliser des identifiants volés dans une fuite de données pour se connecter à d'autres services.

#### Privilege Escalation
Technique permettant à un attaquant d'obtenir des privilèges plus élevés que ceux initialement accordés.

Exemple : Exploiter une vulnérabilité pour passer d'un accès utilisateur normal à un accès administrateur.

#### Buffer Overflow
Technique d'exploitation où un programme écrit plus de données que prévu dans un espace mémoire, ce qui peut permettre l'exécution de code malveillant.

Exemple : Exploiter une application mal sécurisée pour exécuter un code arbitraire.

#### Zero Day
Vulnérabilité inconnue des développeurs du logiciel et non corrigée, exploitée par des attaquants.

Exemple : Utiliser une vulnérabilité non divulguée dans un logiciel populaire pour lancer une attaque.

#### Cryptojacking
Utilisation non autorisée des ressources informatiques d'un utilisateur pour miner des cryptomonnaies.

Exemple : Injecter un script de minage de cryptomonnaie dans un site web pour utiliser les ressources des visiteurs.

#### Defacing
Attaque où l'attaquant modifie le contenu visuel d'un site web pour afficher des messages ou des images.

Exemple : Remplacer la page d'accueil d'un site web par un message politique ou de revendication.

### 🎯 Attaques physiques / Attaques sur le matériel 🔒

#### Tampering
Manipulation physique ou modification d'un appareil pour compromettre sa sécurité.

Exemple : Installer un keylogger matériel sur un clavier pour capturer les frappes de l'utilisateur.

#### Side Channel Attacks
Attaques basées sur des informations indirectes (comme la consommation d'énergie ou les émissions électromagnétiques) pour extraire des données sensibles.

Exemple : Analyser les fluctuations de consommation électrique d'un dispositif pour extraire des clés cryptographiques.

#### Cold Boot Attack
Technique où un attaquant extrait des données sensibles de la mémoire vive (RAM) après un redémarrage à froid.

Exemple : Redémarrer un ordinateur et accéder à la mémoire RAM avant qu'elle ne soit effacée pour récupérer des clés de chiffrement.

#### Evil Maid Attack
Attaque où un attaquant ayant un accès physique à un appareil non surveillé installe des logiciels malveillants ou vole des données.

Exemple : Installer un logiciel espion sur un ordinateur portable laissé sans surveillance dans une chambre d'hôtel.

Exemple : Infecter un logiciel fourni par un tiers de confiance pour accéder aux systèmes des clients qui l'installent.

## 🎯Attaques avancées et persistantes

### Advanced Persistent Threat (APT)
Attaque prolongée et ciblée par un groupe sophistiqué visant à s'infiltrer dans un réseau pour collecter des données sensibles ou causer des dommages sur une longue période.

Exemple : Le groupe APT28 (Fancy Bear) a mené des cyberespionnages contre des gouvernements et des organisations internationales.

### Watering Hole Attack
Attaque où l'attaquant compromet un site web légitime fréquemment visité par les cibles pour les infecter avec des logiciels malveillants.

Exemple : Compromettre un site web professionnel visité par les employés d'une entreprise pour infecter leurs ordinateurs avec un malware.

### Supply Chain Attack
Attaque où l'attaquant compromet un fournisseur ou un partenaire pour atteindre sa cible finale.

Exemple : Infection d'un logiciel de mise à jour d'un fournisseur de logiciels, comme l'attaque sur SolarWinds Orion, qui a conduit à la compromission de nombreuses entreprises et agences gouvernementales.

## 🎯 Les réseaux 🌐

### Darknet
Partie d'internet non indexée par les moteurs de recherche traditionnels, nécessitant des logiciels spécifiques pour y accéder.

Exemple : Utiliser TOR pour accéder à des forums cachés sur le Darknet.

### Deep Web
Partie d'internet non indexée par les moteurs de recherche, incluant des bases de données et intranets.

Exemple : Accéder à une base de données universitaire protégée par un mot de passe.

### TOR (The Onion Router)
Réseau anonyme pour naviguer sur internet sans révéler son adresse IP via des nœuds chiffrés.

Exemple : Utiliser TOR pour protéger son anonymat en ligne.

### I2P (Invisible Internet Project)
Réseau anonyme pour créer des services en ligne cachés et communiquer de manière sécurisée.

Exemple : Héberger un site web anonyme sur le réseau I2P.

### Freenet
Réseau décentralisé pour partager des fichiers et publier du contenu de manière anonyme et résistante à la censure.

Exemple : Utiliser Freenet pour publier un blog anonyme sur des sujets sensibles.

### Tails (The Amnesic Incognito Live System)
Système d'exploitation portable basé sur Linux pour naviguer anonymement en effaçant toutes les traces à l'arrêt.

Exemple : Utiliser Tails depuis une clé USB pour une navigation anonyme.

### Monero / Bitcoin
Cryptomonnaies, Monero se distinguant par son anonymat et la confidentialité des transactions.

Exemple : Utiliser Monero pour des transactions anonymes sur des marchés du Darknet.

## 🎯 Types de Hackers 🎩

### Black / Grey / White Hats
Catégorisation des hackers selon leurs intentions :

- **Black Hats** : Hackers malveillants pour gains personnels.
  
  Exemple : Vente de données de cartes de crédit volées.

- **Grey Hats** : Hackers qui enfreignent les lois pour démontrer des vulnérabilités.

  Exemple : Rapport de failles après démonstration.

- **White Hats** : Hackers éthiques pour sécuriser les systèmes.

  Exemple : Tests d'intrusion pour identifier les vulnérabilités.

## Cybercriminalité et Fraudes 💻

### Cybercriminalité
Activités criminelles via des ordinateurs et réseaux informatiques.

Exemple : Vol d'identité en ligne.

### Darknet Markets
Marchés en ligne sur le Darknet pour des produits et services illégaux.

Exemple : Acheter des informations de cartes de crédit volées.

### Hacking Services
Services malveillants offerts par des hackers.

Exemple : Piratage de comptes réseaux sociaux.

### Carding Sites
Sites vendant des informations de cartes de crédit volées et services de fraude.

Exemple : Achat de numéros de cartes de crédit volées.

### Ransomware as a Service (RaaS)
Modèle où des développeurs vendent ou louent des logiciels de ransomware.

Exemple : Lancer une attaque de ransomware via un service RaaS.

### Bulletproof Hosting
Services d'hébergement ignorants les demandes de retrait de contenu.

Exemple : Héberger un site de phishing sur un serveur bulletproof.

### Exit Scamming
Disparition soudaine des administrateurs d'un marché du Darknet avec les fonds des utilisateurs.

Exemple : Fermeture inattendue d'un marché de drogues sur le Darknet.

# 🎯 OSINT (Open Source Intelligence)🌐

### OSINT (Open Source Intelligence)
Collecte et analyse d'informations provenant de sources accessibles au public pour des fins de renseignement.

Exemple : Utiliser les réseaux sociaux, les forums et les bases de données en ligne pour recueillir des informations sur une cible.

### HUMINT (Human Intelligence)
Renseignement obtenu par des moyens humains, tels que des interactions directes avec des sources humaines.

Exemple : Interroger une personne ayant des informations internes sur une organisation.

### SIGINT (Signals Intelligence)
Collecte et analyse de signaux électroniques et de communications pour obtenir des renseignements.

Exemple : Intercepter et analyser des communications téléphoniques ou des messages radio.

### IMINT (Imagery Intelligence)
Renseignement obtenu à partir d'images, généralement capturées par des satellites ou des drones.

Exemple : Utiliser des images satellite pour surveiller les mouvements de troupes militaires.

### GEOINT (Geospatial Intelligence)
Analyse et interprétation de données géospatiales pour obtenir des renseignements.

Exemple : Analyser des cartes et des images géospatiales pour planifier des opérations militaires ou de secours en cas de catastrophe.

## 🎯 Techniques et Outils 🔍

### Scraping
Technique d'extraction automatisée de données à partir de sites web.

Exemple : Utiliser un script pour extraire des informations de prix sur plusieurs sites de commerce électronique.

### Web Crawling
Technique automatisée de navigation sur le web pour indexer des contenus.

Exemple : Utiliser un crawler pour créer un index de contenu de différents sites web pour un moteur de recherche.

### Social Media Monitoring
Surveillance et analyse des activités et des mentions sur les réseaux sociaux.

Exemple : Utiliser des outils pour suivre les mentions d'une marque ou d'un produit sur Twitter et Facebook.

### Footprinting
Collecte d'informations préliminaires sur une cible pour planifier une attaque.

Exemple : Utiliser des outils comme WHOIS pour obtenir des informations sur les domaines et les adresses IP d'une entreprise.

### Metadonnées
Données décrivant d'autres données, souvent trouvées dans les fichiers et les communications.

Exemple : Analyser les métadonnées d'une photo pour obtenir des informations sur l'appareil photo utilisé et la date de prise de vue.

### Geotagging
Ajout de données géographiques (latitude et longitude) à des fichiers multimédias, comme des photos.

Exemple : Une photo prise avec un smartphone inclut automatiquement les coordonnées GPS du lieu où elle a été prise.

# 🎯 Les Outils de Cybersécurité 🔒🛠️

### Nmap
Outil de balayage de réseau et de sécurité pour découvrir des hôtes et des services sur un réseau informatique.

Exemple : Utiliser Nmap pour scanner un réseau et identifier les ports ouverts sur les machines.

### Burp Suite
Plateforme de test de sécurité des applications web.

Exemple : Utiliser Burp Suite pour intercepter et modifier les requêtes HTTP entre un navigateur et un serveur web pour tester les vulnérabilités.

### Nessus
Scanner de vulnérabilités permettant d’identifier les failles de sécurité dans les systèmes.

Exemple : Utiliser Nessus pour effectuer un scan de sécurité sur un réseau d’entreprise et générer un rapport des vulnérabilités détectées.

### OpenVAS
Scanner de vulnérabilités open source qui aide à identifier les failles de sécurité dans les systèmes informatiques.

Exemple : Utiliser OpenVAS pour effectuer une analyse de vulnérabilité et générer un rapport détaillé.

### Shodan
Moteur de recherche pour les appareils connectés à internet.

Exemple : Utiliser Shodan pour trouver des caméras de surveillance ou des routeurs accessibles publiquement.

### Tenable
Fournisseur de solutions de gestion de la cybersécurité, connu pour ses outils comme Nessus.

Exemple : Utiliser Tenable.io pour surveiller en continu les vulnérabilités et gérer les risques de sécurité.

### Wireshark
Analyseur de paquets réseau qui capture et examine les données circulant sur un réseau.

Exemple : Utiliser Wireshark pour analyser le trafic réseau et détecter des anomalies ou des intrusions.

### TCPDUMP
Outil en ligne de commande pour capturer et analyser les paquets réseau.

Exemple : Utiliser TCPDUMP pour capturer les paquets sur une interface réseau et les enregistrer pour une analyse ultérieure.

### Maltego
Outil de visualisation et d’analyse de données pour la recherche d'informations et les enquêtes OSINT.

Exemple : Utiliser Maltego pour cartographier les relations entre différentes entités sur internet.

### John (John the Ripper)
Outil de craquage de mots de passe.

Exemple : Utiliser John the Ripper pour casser les mots de passe hashés dans un fichier volé.

### Metasploit
Cadre de développement d'exploits et de tests de pénétration.

Exemple : Utiliser Metasploit pour tester et exploiter des vulnérabilités sur un réseau cible.

### Kismet
Outil de détection de réseau sans fil et de détection d'intrusion.

Exemple : Utiliser Kismet pour surveiller les réseaux Wi-Fi et détecter les points d'accès et les clients.

### Crunch
Générateur de listes de mots pour des attaques par force brute.

Exemple : Utiliser Crunch pour créer une liste de mots de passe potentiels à utiliser avec des outils de craquage.

### Hashcat
Outil avancé de craquage de mots de passe.

Exemple : Utiliser Hashcat pour casser des mots de passe hashés en utilisant la puissance de calcul des GPU.

### Hydra
Outil de craquage de mots de passe en ligne.

Exemple : Utiliser Hydra pour tester de multiples combinaisons de mots de passe sur un service en ligne tel que SSH ou FTP.

### SpiderFoot
Outil de collecte de renseignements automatisé pour OSINT.

Exemple : Utiliser SpiderFoot pour automatiser la collecte d'informations sur une cible, y compris les adresses IP, les noms de domaine et les e-mails.

### SQLmap
Outil d'automatisation des tests d'injection SQL.

Exemple : Utiliser SQLmap pour identifier et exploiter des vulnérabilités d'injection SQL dans une application web.

### Hping
Outil de forgeage de paquets TCP/IP pour tester la sécurité des réseaux.

Exemple : Utiliser Hping pour envoyer des paquets personnalisés afin de tester les règles de pare-feu et de détecter des systèmes sur un réseau.

### Ffuf
Outil de fuzzing et de brute forcing pour les répertoires et les fichiers sur les serveurs web.

Exemple : Utiliser Ffuf pour découvrir des répertoires et des fichiers cachés sur un serveur web.

### DirBuster
Outil de brute forcing pour découvrir des répertoires et des fichiers cachés sur des serveurs web.

Exemple : Utiliser DirBuster pour identifier des répertoires non répertoriés sur un site web.

### Aircrack-ng
Suite d'outils pour auditer les réseaux Wi-Fi.

Exemple : Utiliser Aircrack-ng pour casser la clé de cryptage d'un réseau Wi-Fi.

### Ghidra
Suite d'outils d'analyse de logiciels reverse engineering développée par la NSA.

Exemple : Utiliser Ghidra pour analyser et décompiler des fichiers exécutables pour identifier des vulnérabilités.

### BloodHound
Outil pour cartographier les relations et les permissions dans les environnements Active Directory.

Exemple : Utiliser BloodHound pour visualiser les chemins d'escalade de privilèges dans un domaine Active Directory.

### Cewl
Générateur de listes de mots basé sur le contenu d'un site web.

Exemple : Utiliser Cewl pour générer une liste de mots de passe potentiels à partir des mots trouvés sur un site web cible.

### LinPEAS
Script d'audit de sécurité pour Linux, utilisé pour l'énumération post-exploitation.

Exemple : Utiliser LinPEAS pour rechercher des vulnérabilités et des informations sensibles sur un système Linux compromis.

### Evil-WinRM
Outil pour accéder à Windows Remote Management (WinRM) et effectuer des tâches d'administration à distance.

Exemple : Utiliser Evil-WinRM pour accéder à distance à un serveur Windows et exécuter des commandes.

### Mimikatz
Outil pour extraire les informations d'identification de la mémoire sur les systèmes Windows.

Exemple : Utiliser Mimikatz pour récupérer des mots de passe en clair et des hashes de la mémoire d'un système Windows.

### Ettercap
Outil pour les attaques de type Man-in-the-Middle (MitM) et l'analyse de réseau.

Exemple : Utiliser Ettercap pour intercepter et modifier les communications entre deux systèmes sur un réseau.

### The Harvester
Outil pour la collecte d'adresses e-mail, de sous-domaines et de noms d'employés via des sources publiques.

Exemple : Utiliser The Harvester pour collecter des informations sur une entreprise cible à partir de moteurs de recherche et de réseaux sociaux.

### Netcat
Outil de mise en réseau polyvalent pour lire et écrire des données sur des connexions réseau en utilisant les protocoles TCP ou UDP.

Exemple : Utiliser Netcat pour établir une connexion de reverse shell avec un serveur compromis.


[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/kalin-net)  

![GitHub stats](https://github-readme-stats.vercel.app/api?username=kalvin-net&show_icons=true)  

