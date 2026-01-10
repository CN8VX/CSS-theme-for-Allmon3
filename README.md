# CSS Theme for Allmon3 - Dark Blue Style

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0-brightgreen.svg)

**[English](#english)** | **[Français](#français)**

---

<a name="english"></a>
## <img src="https://flagcdn.com/w20/us.png" width="30"/> English

Custom CSS theme for Allmon3 with a dark blue style created by **CN8VX**.

### 📸 Preview

An elegant and modern theme for Allmon3 using dark blue gradients, providing excellent readability and a pleasant user interface.

#### Main Colors
- **Primary dark blue:** `#061d34`
- **Medium blue:** `#045791`
- **Accent blue:** `#0a2a4a`
- **Cyan accent:** `#00d4ff`

### 🚀 Installation

#### Prerequisites
- Allmon3 installed and operational
- SSH access to the server
- Sudo privileges

#### Installation Procedure

1. **Download the CSS file via SSH**
   ```bash
   cd /etc/allmon3/
   sudo wget https://raw.githubusercontent.com/CN8VX/CSS-theme-for-Allmon3/main/dark-blue-style.css
   ```

2. **Backup the old CSS file**
   ```bash
   sudo mv custom.css custom.css.old
   ```

3. **Rename the new file**
   ```bash
   sudo mv dark-blue-style.css custom.css
   ```

4. **Restart Allmon3**
   ```bash
   sudo systemctl restart allmon3
   ```

5. **Refresh the web page**
   - Open your browser
   - Access your Allmon3 interface
   - Press `Ctrl + F5` (Windows/Linux) or `Cmd + Shift + R` (Mac) to force reload

### 🔄 Restore Original Theme

If you want to revert to the original theme:

```bash
cd /etc/allmon3/
sudo mv custom.css custom.css.dark-blue
sudo mv custom.css.old custom.css
sudo systemctl restart allmon3
```

Then refresh your browser with `Ctrl + F5`.

### ✨ Features

- ✅ Elegant dark blue gradients
- ✅ Excellent readability on dark background
- ✅ Buttons with transition effects
- ✅ Styled tables and modals
- ✅ Custom dropdowns
- ✅ Tooltips consistent with the theme
- ✅ Colored alerts (success, danger, etc.)
- ✅ Compatible with all Allmon3 features

### 🐛 Troubleshooting

#### Theme not applying
1. Verify the file is named `custom.css`
2. Check permissions: `sudo chmod 644 /etc/allmon3/custom.css`
3. Clear browser cache (`Ctrl + Shift + Delete`)
4. Restart Allmon3: `sudo systemctl restart allmon3`

#### Some elements are not styled
- Force reload: `Ctrl + F5`
- Check browser console for errors (F12)

### 📚 Resources

- [Allmon3 Documentation](https://github.com/AllStarLink/allmon3)
- [DMR Morocco Website](https://www.dmr-maroc.com/astuces_tips_asl3.php)
- [CN8VX GitHub](https://github.com/CN8VX)

### 📄 License

This project is developed by [CN8VX](https://www.qrz.com/db/CN8VX) under MIT license.

### 👤 Author

**CN8VX**
- Website: [dmr-maroc.com](https://www.dmr-maroc.com)
- GitHub: [@CN8VX](https://github.com/CN8VX)
- 📧 **Email**: [cn8vx.ma@gmail.com](mailto:cn8vx.ma@gmail.com)

### 🤝 Support and Suggestions

All questions, issues, or suggestions are welcome! Feel free to:
- Report bugs
- Propose improvements
- Share your suggestions

### 📞 Support

For any questions or issues:
- Check the [Allmon3 documentation](https://github.com/AllStarLink/allmon3)
- 📧 **Email**: [cn8vx.ma@gmail.com](mailto:cn8vx.ma@gmail.com)

---

**73 de [CN8VX](https://www.qrz.com/db/CN8VX)** 📻

*If you like this theme, don't hesitate to star ⭐ the repository!*

---
---

<a name="français"></a>
## <img src="https://flagcdn.com/w20/fr.png" width="30"/> Français

Thème CSS personnalisé pour Allmon3 avec un style bleu foncé créé par **CN8VX**.

### 📸 Aperçu

Un thème élégant et moderne pour Allmon3 utilisant des dégradés de bleu foncé, offrant une excellente lisibilité et une interface utilisateur agréable.

#### Couleurs principales
- **Bleu foncé primaire:** `#061d34`
- **Bleu moyen:** `#045791`
- **Bleu accentuation:** `#0a2a4a`
- **Cyan accent:** `#00d4ff`

### 🚀 Installation

#### Prérequis
- Allmon3 installé et fonctionnel
- Accès SSH au serveur
- Privilèges sudo

#### Procédure d'installation

1. **Télécharger le fichier CSS via SSH**
   ```bash
   cd /etc/allmon3/
   sudo wget https://raw.githubusercontent.com/CN8VX/CSS-theme-for-Allmon3/main/dark-blue-style.css
   ```

2. **Sauvegarder l'ancien fichier CSS**
   ```bash
   sudo mv custom.css custom.css.old
   ```

3. **Renommer le nouveau fichier**
   ```bash
   sudo mv dark-blue-style.css custom.css
   ```

4. **Redémarrer Allmon3**
   ```bash
   sudo systemctl restart allmon3
   ```

5. **Rafraîchir la page web**
   - Ouvrez votre navigateur
   - Accédez à votre interface Allmon3
   - Appuyez sur `Ctrl + F5` (Windows/Linux) ou `Cmd + Shift + R` (Mac) pour forcer le rechargement

### 🔄 Restauration du thème original

Si vous souhaitez revenir au thème d'origine :

```bash
cd /etc/allmon3/
sudo mv custom.css custom.css.dark-blue
sudo mv custom.css.old custom.css
sudo systemctl restart allmon3
```

Puis rafraîchissez votre navigateur avec `Ctrl + F5`.

### ✨ Caractéristiques

- ✅ Dégradés de bleu foncé élégants
- ✅ Excellente lisibilité sur fond sombre
- ✅ Boutons avec effets de transition
- ✅ Tables et modales stylisées
- ✅ Dropdowns personnalisés
- ✅ Tooltips cohérents avec le thème
- ✅ Alertes colorées (succès, danger, etc.)
- ✅ Compatible avec toutes les fonctionnalités Allmon3

### 🐛 Dépannage

#### Le thème ne s'applique pas
1. Vérifiez que le fichier est bien nommé `custom.css`
2. Vérifiez les permissions : `sudo chmod 644 /etc/allmon3/custom.css`
3. Videz le cache du navigateur (`Ctrl + Shift + Delete`)
4. Redémarrez Allmon3 : `sudo systemctl restart allmon3`

#### Certains éléments ne sont pas stylisés
- Faites un rechargement forcé : `Ctrl + F5`
- Vérifiez les erreurs dans la console du navigateur (F12)

### 📚 Ressources

- [Documentation Allmon3](https://github.com/AllStarLink/allmon3)
- [Site web DMR Maroc](https://www.dmr-maroc.com/astuces_tips_asl3.php)
- [GitHub CN8VX](https://github.com/CN8VX)

### 📄 Licence

Ce projet est développé par [CN8VX](https://www.qrz.com/db/CN8VX) sous licence MIT.

### 👤 Auteur

**CN8VX**
- Website: [dmr-maroc.com](https://www.dmr-maroc.com)
- GitHub: [@CN8VX](https://github.com/CN8VX)
- 📧 **Email** : [cn8vx.ma@gmail.com](mailto:cn8vx.ma@gmail.com)

### 🤝 Support et Suggestions

Toutes questions, problèmes ou suggestions sont les bienvenus ! N'hésitez pas à :
- Signaler des bugs
- Proposer des améliorations
- Partager vos suggestions

### 📞 Support

Pour toute question ou problème :
- Consultez la [documentation Allmon3](https://github.com/AllStarLink/allmon3)
- 📧 **Email** : [cn8vx.ma@gmail.com](mailto:cn8vx.ma@gmail.com)

---

**73 de [CN8VX](https://www.qrz.com/db/CN8VX)** 📻

*Si vous aimez ce thème, n'hésitez pas à mettre une ⭐ sur le dépôt !*

---
<img width="1439" height="736" alt="dark-blue-allmon3_01" src="https://github.com/user-attachments/assets/9d0169e0-4b49-4b33-8963-fc008b055bd3" />
<img width="1441" height="738" alt="dark-blue-allmon3_02" src="https://github.com/user-attachments/assets/eaa3162f-da5d-409f-8c24-3a864ee6806b" />






