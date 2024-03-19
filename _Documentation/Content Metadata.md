---
Title: Content Metadata
Date: 2024-03-12
Modified: 2024-03-12
Type: docs
Slug: documentation/metadata
Authors: 
Lang: en
Translation: false
---

# Content Metadata

Here we look at the different metadata items that characterize each content item.

## Common metadata

For all types of content.

- **Title**: The title for the page. This will appear as the title within the web page, and also as the title in the tabs and in the browser bar.
- **Date**: Creation timestamp. Should be set when applying a template.
- **Modified**: Modification timestamp. It should not need to be edited by hand, there is a tool in the toolbar to insert timestamps.
- **Type**: The type of the content item. Can be one of page, person, news, blog, event, project, or service. This should not need to be edited by hand.
- **Slug**: This is the path under which the content will be shown in the site, without the leading slash. So for example if we want to publish a page at `https://sunet.se/om-sunet/some-page`, the Slug should be `om-sunet/some-page`. Slugs can only be composed of lower case letters, numbers, dashes and slashes.
- **Status**: One of `draft`, `published`, or `hidden`.
- **Authors**: the authors of the page. Not much used at the moment (the authors in the wordpress content did not exist in the people feed).
- **Lang**: The language of the page.
- **Translation**: Whether the page is the translation of another page.

## Event metadata

Content items of type event may have:

- **DisplayDate**: The date(s) of the event, to be shown in the event page, as free text.
- **StartDate**: The date the event starts with format YYYY-MM-DD.
- **EndDate**: The date the event ends with format YYYY-MM-DD.

 There is a tool in the toolbar to insert dates in this format.

## Page metadata

Metadata for pages.

- **TabTitle**: If you need the title in the web page and the title for the tabs and browser to be dfferent, set here the title to appear on the tabs and the browser. Optional.

## service and project metadata

- **Subtitle**: Short text that will appear in the cards in the listings of services and projects.
- **Category**: The Title of the corresponding project or service category, as set in `navigation/projekt-categories` and `navigation/service-categories`.
- **Contact**: The slug of the contact person as set in their entry at `people/`, see below.

## People metadata

Metadata for people.

- **Visa**: Whether the person should be listed at `kontakt/medarbetatare`.
- **Email**: Email of the person
- **Phone**: The phone number of the person
- **Role_sv**: Role of the person in Sunet, in Swedish.
- **Role_en**: Role of the person in Sunet, in English.