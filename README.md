# CSS Theme for Allmon3 - Dark Blue & Black Gray Styles

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-2.0-brightgreen.svg)

<img src="https://flagcdn.com/w20/us.png" width="20"/> **[English](#english)** | <img src="https://flagcdn.com/w20/fr.png" width="20"/> **[Français](#français)**

---

<a name="english"></a>
## <img src="https://flagcdn.com/w20/us.png" width="30"/> English

Custom CSS themes for Allmon3 created by **CN8VX**.

### 🎨 Available Themes

#### 1. Dark Blue Style
An elegant and modern theme using dark blue gradients, providing excellent readability and a pleasant user interface.

**Main Colors:**
- **Primary dark blue:** `#061d34`
- **Medium blue:** `#045791`
- **Accent blue:** `#0a2a4a`
- **Cyan accent:** `#00d4ff`

#### 2. Black & Gray Style
A sleek, modern monochrome theme with sophisticated black and gray tones for a professional look.

**Main Colors:**
- **Primary black:** `#1a1a1a`
- **Dark gray:** `#2d2d2d`
- **Medium gray:** `#252525`
- **Light gray accent:** `#909090`

### 🚀 Installation

#### Prerequisites
- Allmon3 installed and operational
- SSH access to the server
- Sudo privileges

#### Installation Procedure

**For Dark Blue Style:**
```bash
cd /etc/allmon3/
sudo wget https://raw.githubusercontent.com/CN8VX/CSS-theme-for-Allmon3/main/dark-blue-style.css
sudo mv custom.css custom.css.old
sudo mv dark-blue-style.css custom.css
sudo systemctl restart allmon3
```

**For Black & Gray Style:**
```bash
cd /etc/allmon3/
sudo wget https://raw.githubusercontent.com/CN8VX/CSS-theme-for-Allmon3/main/black-gray-style.css
sudo mv custom.css custom.css.old
sudo mv black-gray-style.css custom.css
sudo systemctl restart allmon3
```

**Refresh the web page:**
- Open your browser
- Access your Allmon3 interface
- Press `Ctrl + F5` (Windows/Linux) or `Cmd + Shift + R` (Mac) to force reload

### 🔄 Switch Between Themes

**To switch from Dark Blue to Black & Gray:**
```bash
cd /etc/allmon3/
sudo mv custom.css custom.css.dark-blue
sudo mv black-gray-style.css custom.css
sudo systemctl restart allmon3
```

**To switch from Black & Gray to Dark Blue:**
```bash
cd /etc/allmon3/
sudo mv custom.css custom.css.black-gray
sudo mv dark-blue-style.css custom.css
sudo systemctl restart allmon3
```

### 🔄 Restore Original Theme

If you want to revert to the original theme:
```bash
cd /etc/allmon3/
sudo mv custom.css custom.css.backup
sudo mv custom.css.old custom.css
sudo systemctl restart allmon3
```

Then refresh your browser with `Ctrl + F5`.

### ✨ Features

- ✅ Two distinct color schemes (Blue & Monochrome)
- ✅ Excellent readability on dark background
- ✅ Buttons with smooth transition effects
- ✅ Styled tables and modals
- ✅ Custom dropdowns
- ✅ Tooltips consistent with the theme
- ✅ Colored alerts (success, danger, etc.)
- ✅ Compatible with all Allmon3 features
- ✅ Modern gradient backgrounds
- ✅ Professional and clean design

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

*If you like these themes, don't hesitate to star ⭐ the repository!*

---
---

<a name="français"></a>
## <img src="https://flagcdn.com/w20/fr.png" width="30"/> Français

Thèmes CSS personnalisés pour Allmon3 créés par **CN8VX**.

### 🎨 Thèmes disponibles

#### 1. Style Bleu Foncé
Un thème élégant et moderne utilisant des dégradés de bleu foncé, offrant une excellente lisibilité et une interface utilisateur agréable.

**Couleurs principales:**
- **Bleu foncé primaire:** `#061d34`
- **Bleu moyen:** `#045791`
- **Bleu accentuation:** `#0a2a4a`
- **Cyan accent:** `#00d4ff`

#### 2. Style Noir & Gris
Un thème monochrome élégant et moderne avec des tons noirs et gris sophistiqués pour un look professionnel.

**Couleurs principales:**
- **Noir primaire:** `#1a1a1a`
- **Gris foncé:** `#2d2d2d`
- **Gris moyen:** `#252525`
- **Accent gris clair:** `#909090`

### 🚀 Installation

#### Prérequis
- Allmon3 installé et fonctionnel
- Accès SSH au serveur
- Privilèges sudo

#### Procédure d'installation

**Pour le style Bleu Foncé:**
```bash
cd /etc/allmon3/
sudo wget https://raw.githubusercontent.com/CN8VX/CSS-theme-for-Allmon3/main/dark-blue-style.css
sudo mv custom.css custom.css.old
sudo mv dark-blue-style.css custom.css
sudo systemctl restart allmon3
```

**Pour le style Noir & Gris:**
```bash
cd /etc/allmon3/
sudo wget https://raw.githubusercontent.com/CN8VX/CSS-theme-for-Allmon3/main/black-gray-style.css
sudo mv custom.css custom.css.old
sudo mv black-gray-style.css custom.css
sudo systemctl restart allmon3
```

**Rafraîchir la page web:**
- Ouvrez votre navigateur
- Accédez à votre interface Allmon3
- Appuyez sur `Ctrl + F5` (Windows/Linux) ou `Cmd + Shift + R` (Mac) pour forcer le rechargement

### 🔄 Basculer entre les thèmes

**Pour passer du Bleu Foncé au Noir & Gris:**
```bash
cd /etc/allmon3/
sudo mv custom.css custom.css.dark-blue
sudo mv black-gray-style.css custom.css
sudo systemctl restart allmon3
```

**Pour passer du Noir & Gris au Bleu Foncé:**
```bash
cd /etc/allmon3/
sudo mv custom.css custom.css.black-gray
sudo mv dark-blue-style.css custom.css
sudo systemctl restart allmon3
```

### 🔄 Restauration du thème original

Si vous souhaitez revenir au thème d'origine:
```bash
cd /etc/allmon3/
sudo mv custom.css custom.css.backup
sudo mv custom.css.old custom.css
sudo systemctl restart allmon3
```

Puis rafraîchissez votre navigateur avec `Ctrl + F5`.

### ✨ Caractéristiques

- ✅ Deux palettes de couleurs distinctes (Bleu & Monochrome)
- ✅ Excellente lisibilité sur fond sombre
- ✅ Boutons avec effets de transition fluides
- ✅ Tables et modales stylisées
- ✅ Dropdowns personnalisés
- ✅ Tooltips cohérents avec le thème
- ✅ Alertes colorées (succès, danger, etc.)
- ✅ Compatible avec toutes les fonctionnalités Allmon3
- ✅ Arrière-plans dégradés modernes
- ✅ Design professionnel et épuré

### 🐛 Dépannage

#### Le thème ne s'applique pas
1. Vérifiez que le fichier est bien nommé `custom.css`
2. Vérifiez les permissions: `sudo chmod 644 /etc/allmon3/custom.css`
3. Videz le cache du navigateur (`Ctrl + Shift + Delete`)
4. Redémarrez Allmon3: `sudo systemctl restart allmon3`

#### Certains éléments ne sont pas stylisés
- Faites un rechargement forcé: `Ctrl + F5`
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
- 📧 **Email**: [cn8vx.ma@gmail.com](mailto:cn8vx.ma@gmail.com)

### 🤝 Support et Suggestions

Toutes questions, problèmes ou suggestions sont les bienvenus! N'hésitez pas à:
- Signaler des bugs
- Proposer des améliorations
- Partager vos suggestions

### 📞 Support

Pour toute question ou problème:
- Consultez la [documentation Allmon3](https://github.com/AllStarLink/allmon3)
- 📧 **Email**: [cn8vx.ma@gmail.com](mailto:cn8vx.ma@gmail.com)

---

**73 de [CN8VX](https://www.qrz.com/db/CN8VX)** 📻

*Si vous aimez ces thèmes, n'hésitez pas à mettre une ⭐ sur le dépôt!*

---
<img width="1439" height="736" alt="dark-blue-allmon3_01" src="https://github.com/user-attachments/assets/9d0169e0-4b49-4b33-8963-fc008b055bd3" />
<img width="1441" height="738" alt="dark-blue-allmon3_02" src="https://github.com/user-attachments/assets/eaa3162f-da5d-409f-8c24-3a864ee6806b" />
