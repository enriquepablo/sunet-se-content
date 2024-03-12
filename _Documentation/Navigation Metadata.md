---
Title: Navigation Metadata
Date: 2024-03-12
Modified: 2024-03-12
Slug: documentation/navigation-metadata
Authors: 
Lang: en
Translation: false
---

# Navigation metadata

Metadata kept at `navigation/`.

## footer

Metadata to build the footer of the site.

- **address-sv** and **address-meta-sv**: This is used for the line and subline, with the address of Sunet, that appear in the bottom right corner of all pages. For the English site, substitute `-sv` with `-en`.
- **om-webbplatsen-sv**: This is for the first set of links in the bottom right of all pages, under the tile of "Om Webbplatsen".  For the English site, substitute `-sv` with `-en`.
    - **Title**: title of the dropdown, "Om Webbplatsen" by default.
    - **Order**: For the order in which the sets of links ("Om Webbplatsen", "Kontakt/Support") appear.
    - **Links**: List of links to be shown under the title. Each link consists on the text for the link and the target for the link, separated by a colon.

## menus

Metadata for the different menus in the site. Each menu corresponds with a file, and each is composed of a list of links, where each link consists on the text for the link and the target for the link, separated by a colon. As always, for the English site substitute `-sv` with `-en`.

- **global-menu-sv**: This is the horizontal menu that appears in the top right of every page.
- **main-menu-sv**: This is the horizontal menu that appears in the top center of every page.
- **kontakt-sv**: This is the vertical menu that appears to the left of the content in all pages under the path (in the website) `/kontakt/`.
- **om-sunet-sv**: This is the vertical menu that appears to the left of the content in all pages under the path (in the website) `/om-sunet/`.

## Categories

Categories for services (under `navigation/service-categories`) and projects (under `navigation/projekt-categories`).

Each category is characterized by:

- **Title_sv** The displayable name of the category, in Swedish. For the English name use **title_en**.
- **Slug**: the slug for the category (with no slashes, no path: just the title in the main language (Swedish), all in lower case, with no spaces, and all ASCII).
- **Order**: This is to order the categories when they are listed.