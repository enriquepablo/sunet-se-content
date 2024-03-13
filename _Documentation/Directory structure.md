---
Title: Directory structure
Created: 2024-03-12
Modified: 2024-03-12
Slug: documentation/directory-structure
Authors: 
Lang: en
Translation: false
---
# Directory structure of the obsidian vault

Here we look at where the data and metadata that make up the site is kept in the directory tree within the obsidian vault.

## Documentation

Here we keep the end user's documentation.

## articles

Here we keep news items, blog posts and events, which are content types that are *dated* - this is, content items of this type have a publication date after which they are supposedly not edited, and possibly an expiration date (in the case of events) after which it no longer makes sense to keep them published.

## navigation

Here we keep metadata to build the navigational elements of the site. We'll get into the detail of these metadata in the metadata section. This info is parceled out in 4 subdirectories:

- **footer**: metadata to build the footer
- **menus**: metadata to build the menus, both horizontal in the top, and vertical in the left side of the content.
- **projekt-categories**: The different categories of projects.
- **service-categories**: The different categories of services.

## pages

Here we keep content items that are not dated (they have a creation and modification date, but these do not affect the publication process). As we'll see in the metadata section, the placement of content items in the final web site only depends on the value of their `Slug`, but here we'll propose a directory layout that reflects the structure of the site. So, if there is a page with title "Om Sunet" that is accessible in the website at `/om-sunet`, we'll place the markdown file at `pages/Om sunet`. If, in addition, there is a page with title "Anslutna organisationer" that is accessible in the site at `/om-sunet/anslutna-organisationer`, we'll place it in `pages/om-sunet/Anslutna organisationer`.

Apart from generic pages, there are 3 further types of content in this directory:

- The entry pages for the blog, the news and the events. These are located in `pages/om-sunet/aktuellt`, and just include the metadata and the headings for those pages. The events, news items and blog posts that are accessible from those pages are pulled from the **articles** directory mentioned above.
- The service and projekt pages. These are kept at `pages/tjanster/<service category/` and `pages/projekt/<projekt category/`, where `<service category>` and `<projekt category` are replaced by the service or projekt category `Slug`s (see the metadata section for an explanation of the `Slug`).

It is important that no `pages/arenden` directory is ever created. This directory is used to place the tickets pulled from JIRA during the build process (the process by which these markdown pages are transformed into HTML ready for the web). So any content placed in such directory will be wiped out during the build process.

## people

Here we keep metadata about Sunet people. This is not published as pages in the site, but different parts of the site pull info from here.

## templates

Templates for the different content types.

## wp-content

Here we keep the static files (images, PDFs, etc.) that are used in the site.