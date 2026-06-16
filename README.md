# JT ArticleX PRO Module

**JT ArticleX PRO** is a Bootstrap-native advanced article showcase module for **Joomla 6**.

It helps you display Joomla articles in modern layouts such as Carousel, Grid, Compact List, Media List, Featured + List and Magazine without loading unnecessary external CSS or JavaScript libraries.

Built by **JoomTheme**
Website: https://joomtheme.com
Support: [support@joomtheme.com](mailto:support@joomtheme.com)

---

## ✨ Features

* Joomla 6.1.1 compatible
* Modern Joomla MVC / namespaced module structure
* Bootstrap-native output
* No external carousel library
* No unnecessary CSS framework dependency
* Clean Cassiopeia-friendly markup
* Multiple article display layouts
* Responsive design
* Category link support
* Featured badge support
* Configurable article info position
* Turkish and English language files
* Joomla update server support
* JED Checker friendly GPL license headers

---

## 🎨 Available Layouts

### Carousel

A modern article carousel using Bootstrap carousel behavior.

Features:

* Premium bottom carousel controls
* Previous / next arrow buttons
* Line or dot indicators
* Configurable autoplay
* Configurable interval
* Responsive article columns
* No overlay conflict with title or read more links

---

### Grid

A clean Bootstrap card grid layout for blogs, news pages and landing pages.

Best for:

* Blog listings
* News blocks
* Homepage article sections
* Category previews

---

### Compact List

A tight article list layout with small images.

Best for:

* Sidebar modules
* Latest news lists
* Small content areas
* Announcement blocks

---

### Media List

A wider list layout with larger article images.

Best for:

* Blog index pages
* News listing pages
* Main content article lists

---

### Featured + List

Displays one large featured article with a compact list of additional articles.

Best for:

* Homepage highlights
* News portal sections
* Featured content blocks

---

### Magazine

A magazine-style layout with one large featured article and multiple compact story cards.

Best for:

* News portals
* Magazine websites
* Editorial homepages
* Joomla content showcases

---

## 🧩 Main Options

JT ArticleX PRO includes useful but simple options designed not to overwhelm users.

### Content Options

* Select categories
* Include subcategories
* Filter featured articles
* Set article count
* Set ordering
* Hide current article
* Show only articles with images

### Display Options

* Show / hide article image
* Show / hide category
* Link category
* Show / hide date
* Show / hide author
* Show / hide intro text
* Show / hide read more
* Configure intro text length
* Configure title length

### Carousel Options

* Enable carousel
* Autoplay
* Interval
* Show controls
* Controls position
* Show indicators
* Indicator style: Lines or Dots

### Featured Badge Options

* Show badge on featured image
* Badge type:

  * Category
  * Featured
  * Custom Text
* Badge style:

  * Primary
  * Secondary
  * Success
  * Danger
  * Warning
  * Info
  * Dark
  * Light

### Info Position

Choose where article info appears:

* Above title
* Below title

Example:

```text
Title
Category · Date
Intro text
Read more
```

or:

```text
Category · Date
Title
Intro text
Read more
```

---

## 🚀 Installation

1. Download the latest ZIP package from the GitHub Releases page.
2. Go to your Joomla administrator panel.
3. Navigate to:

```text
System → Install → Extensions
```

4. Upload the ZIP package.
5. After installation, go to:

```text
Content → Site Modules
```

6. Create or edit **JT ArticleX PRO**.
7. Select a module position.
8. Choose your layout.
9. Publish the module.

---

## 🔄 Update Server

JT ArticleX PRO includes Joomla update server metadata.

Update XML files are stored in:

```text
/updates
```

Recommended structure:

```text
updates/
├── update.xml
└── changelog.xml
```

The module manifest includes update server and changelog definitions so Joomla can detect future updates.

---

## 📁 Package Structure

```text
mod_jtarticlexpro/
├── mod_jtarticlexpro.xml
├── services/
│   └── provider.php
├── src/
│   ├── Dispatcher/
│   │   └── Dispatcher.php
│   └── Helper/
│       └── ArticleXProHelper.php
├── tmpl/
│   ├── default.php
│   ├── carousel.php
│   ├── grid.php
│   ├── compact.php
│   ├── media.php
│   ├── featured.php
│   └── magazine.php
├── language/
│   ├── en-GB/
│   │   ├── mod_jtarticlexpro.ini
│   │   └── mod_jtarticlexpro.sys.ini
│   └── tr-TR/
│       ├── mod_jtarticlexpro.ini
│       └── mod_jtarticlexpro.sys.ini
└── README.md
```

---

## 🧱 Technical Notes

JT ArticleX PRO follows the modern Joomla module structure.

* Uses `services/provider.php`
* Uses namespaced PHP classes
* Uses Joomla module dispatcher structure
* Uses Joomla helper class structure
* Uses Joomla language files
* Uses Joomla manifest XML
* Uses Bootstrap-native markup
* Avoids unnecessary custom CSS
* Avoids external slider libraries

---

## 🌍 Languages

Included languages:

* English `en-GB`
* Turkish `tr-TR`

Language files:

```text
mod_jtarticlexpro.ini
mod_jtarticlexpro.sys.ini
```

---

## ✅ Compatibility

| Platform                         | Status    |
| -------------------------------- | --------- |
| Joomla 6.1.1                     | Supported |
| Bootstrap-based Joomla templates | Supported |
| Cassiopeia                       | Supported |
| PHP 8.x                          | Supported |

---

## 📸 Screenshots

Add your screenshots to the repository and reference them here.

Example:

```markdown
![Magazine Layout](screenshots/magazine-layout.png)
![Carousel Layout](screenshots/carousel-layout.png)
![Featured List Layout](screenshots/featured-list-layout.png)
```

Recommended screenshot folder:

```text
screenshots/
├── carousel-layout.png
├── grid-layout.png
├── compact-list-layout.png
├── featured-list-layout.png
└── magazine-layout.png
```

---

## 📝 Changelog

### v1.0.11

* Added GPL-compatible license headers to PHP files
* Added update server metadata
* Added changelog URL support
* Improved JED Checker compatibility
* Joomla manifest updated
* Package cleanup

### v1.0.10

* Fixed featured badge display inside Bootstrap ratio containers
* Badge now appears correctly on top-left of featured images

### v1.0.9

* Added featured image badge support
* Added badge type options
* Added badge style options
* Added info position option

### v1.0.8

* Improved Magazine layout
* Added better 4-column magazine behavior
* Improved featured and compact story card balance

### v1.0.7

* Changed current article hide behavior
* Improved option naming

### v1.0.6

* Removed unused preset option
* Added mini images to Featured + List side articles

### v1.0.5

* Added Media List layout
* Improved Compact List layout
* Added category link option

### v1.0.4

* Added premium bottom carousel controls
* Improved carousel arrow button style
* Added controls position option

### v1.0.3

* Improved carousel indicator color handling
* Added custom indicator class

### v1.0.2

* Added indicator style options
* Improved arrow button styling

### v1.0.1

* Moved carousel controls outside content area
* Fixed blocked title and read more links

### v1.0.0

* Initial development release

---

## 📜 License

GNU General Public License version 2 or later.

See `LICENSE.txt` for details.

---

## 👨‍💻 Author

**JoomTheme**

Website: https://joomtheme.com
Support: [support@joomtheme.com](mailto:support@joomtheme.com)

---

## 💬 Support

For support, updates and documentation, visit:

https://joomtheme.com
