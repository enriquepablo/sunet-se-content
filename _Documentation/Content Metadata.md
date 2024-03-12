Title: Content Metadata
Date: 2024-03-12
Modified: 2024-03-12
Slug: documentation/metadata
Authors: 
Lang: en
Translation: false

# Content Metadata

Here we look at the different metadata items that characterize each content item.

## Generic metadata

For all types of content.

- **Title**: The title for the page. This will appear as the title within the web page, and also as the title in the tabs and in the browser bar.
- **Date**: Creation date. Should be set when applying a template.
- **Modified**: Modification date. It should not need to be edited by hand, there is a plugin that updates it automatically.
- **Slug**: This is the path under which the content will be shown in the site, without the leading slash. So for example if we want to publish a page at `https://sunet.se/om-sunet/some-page`, the Slug should be `om-sunet/some-page`. Slugs can only be composed of lower case letters, numbers, dashes and slashes.
- **Status**: One of `draft`, `published`, or `hidden`.
- **Authors**: the authors of the page. Not much used at the moment.
- **Lang**: The language of the page.
- **Translation**: Whether the page is the translation of another page.

## Article metadata

For news items, blog posts, and events.

- **Category**: One of `blogg`, `nyheter`, or `evenemang`.

In addition, events may have:

- **DisplayDate**: The date(s) of the event, to be shown in the event page.
- **StartDate**: The date the event starts.
- **EndDate**: The date the event ends.

## Page metadata

Metadata for pages.

- **TabTitle**: If you need the title in the web page and the title for the tabs and browser to be dfferent, set here the title to appear on the tabs and the browser.

Metadata for services and projects.

- **Subtitle**: Short text that will appear in the cards in the listings of services and projects.
- **Category**: The Title of the corresponding project or service category, as set at `navigation/projekt-categories` and `navigation/service-categories`.
- **Contact**: The slug of the contact person as set in their entry at `people/`, see below.

## People metadata

Metadata for people.

- **Visa**: Whether the person should be listed at `kontakt/medarbetatare`.
- **Email**: Email of the person
- **Phone**: The phone number of the person
- **Role_sv**: Role of the person in Sunet, in Swedish.
- **Role_en**: Role of the person in Sunet, in English.