# digitallife（数字人生）

[English](README.md) · [简体中文](README.zh.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · **Français** · [Deutsch](README.de.md) · [Español](README.es.md) · [Português](README.pt.md)

> Un moniteur d'activité macOS natif —— **toutes vos données restent sur votre propre Mac.**

digitallife enregistre discrètement ce qui se passe sur votre Mac au quotidien : quelles applications vous utilisez et pendant combien de temps, la consommation réseau et batterie/énergie, les modifications de fichiers, les applications installées et désinstallées… puis présente le tout dans une élégante application native de barre de menus sous forme de rapports quotidiens / hebdomadaires / mensuels clairs. Pas de cloud, pas de compte, rien n'est téléversé.

---

## ✨ Ce que vous pouvez voir

- **Temps d'utilisation des applications** et classements quotidiens (avec icônes)
- **Tendances de batterie et d'énergie**, classement énergétique par application (optionnel)
- **Trafic réseau** par application
- **Activité des fichiers** : créés / supprimés / modifiés —— dossier, type et application d'origine
- Palmarès **CPU / mémoire**
- **Titres de fenêtres et temps d'inactivité**, applications de la barre de menus / résidentes en arrière-plan
- Historique d'**installation / désinstallation** des applications
- **Analyse de l'espace disque** (localisation des gros dossiers / fichiers) et **nettoyage des fichiers inutiles**
- **Rapports quotidiens / hebdomadaires / mensuels**, temps d'écran comparé à la période précédente
- Les données peuvent être effacées par jour / catégorie, avec **export JSON / CSV**

---

## 💻 Configuration requise

- **macOS 13 (Ventura) ou ultérieur**
- **Apple Silicon** (puce série M)

---

## ⬇️ Téléchargement et installation

1. Téléchargez le dernier `DigitalLife-<version>.dmg` depuis **[Releases](https://github.com/Link-X/digitallife-releases/releases/latest)**
2. Ouvrez le DMG et **glissez « 数字人生 » dans « Applications »**
3. **Double-cliquez pour lancer** —— l'application est **notariée par Apple**, il n'y a donc aucun blocage « endommagé » / « développeur non vérifié », et pas besoin de « clic droit → Ouvrir »
4. Au premier lancement, ouvrez « 权限设置… » (Autorisations) depuis la barre de menus et accordez les autorisations système comme indiqué

### Autorisations (à accorder selon les besoins ; si l'une manque, seule la fonction concernée est limitée, rien d'autre)

| Autorisation | Utilisation |
|------|------|
| Accès complet au disque | Historique du navigateur, etc. |
| Accessibilité | Identifier l'application au premier plan |
| Enregistrement de l'écran | Lire les titres de fenêtres (**aucune capture d'écran**) |
| Automatisation (Événements système) | Application / fenêtre au premier plan |

---

## 🔒 Confidentialité

C'est ce à quoi digitallife tient le plus :

- **100 % de vos données restent en local**, écrites dans une base de données sur votre propre Mac, **sans aucune transmission réseau**
- **La seule requête réseau** se produit lorsque vous **cliquez manuellement sur « Vérifier les mises à jour »** —— elle récupère uniquement un numéro de version et n'envoie aucune de vos données ; sinon l'application est entièrement hors ligne
- Pour une protection renforcée, vous pouvez **activer le chiffrement de la base de données** dans les réglages (la clé est stockée dans le trousseau du système)

---

## 🔄 Vérifier les mises à jour

Menu de l'application **« 关于数字人生 » (À propos) → « 检查更新 » (Vérifier les mises à jour)** : cliquez une fois manuellement ; s'il existe une version plus récente, vous serez averti avec un lien de téléchargement. Aucune interrogation en arrière-plan, aucun téléchargement automatique.

---

## 📄 Licence

**Logiciel propriétaire · Tous droits réservés (All Rights Reserved)** — Copyright © 2026 许道斌 (Daobin Xu).

- **Le code source est fermé** : à l'exception de l'auteur, aucune utilisation, copie, modification, ingénierie inverse ou distribution du code source n'est autorisée sans autorisation écrite préalable. **« Visible » ne signifie pas « utilisable ».**
- **Application officielle gratuite pour un usage non commercial** : les particuliers (étude / recherche / loisir), les organisations à but non lucratif, les établissements d'enseignement et de recherche et les organismes gouvernementaux peuvent **utiliser gratuitement** l'application signée et notariée, non modifiée, officiellement publiée dans ce dépôt.
- **Canal officiel, usage personnel uniquement** : téléchargez depuis les [Releases](https://github.com/Link-X/digitallife-releases/releases/latest) de ce dépôt pour votre propre usage ; **la redistribution, le transfert, la copie, la modification et l'ingénierie inverse sont interdits.**
- **L'usage commercial nécessite une autorisation** : tout usage commercial —— **y compris l'utilisation par une organisation à but lucratif (entreprise / société) dans le cadre de son activité, même à usage strictement interne par ses employés** —— nécessite une autorisation écrite préalable.

> « Non commercial » désigne un usage qui n'est pas principalement destiné à un avantage commercial ou à une rémunération monétaire : usage personnel, organisations à but non lucratif, établissements d'enseignement et de recherche, et organismes gouvernementaux dans le cadre de leurs fonctions non lucratives / publiques.

Pour toute demande de licence, contactez **许道斌 (Daobin Xu)** (<15555537368xu@gmail.com>). Les conditions bilingues complètes figurent dans [LICENSE](LICENSE).
