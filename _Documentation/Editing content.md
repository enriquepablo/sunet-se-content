---
Title: Editing content
Created: 2024-03-12
Modified: 2024-03-12
Slug: documentation/editing-content
Authors: 
Lang: en
Translation: false
---

# Editing content

The content for the sunet.se site is created and edited as markdown, so some familiarity with markdown is advised. It is not necessary to know it by heart though since the toolbar should have helpers for all the format that may be needed.

There is a markdown [cheat-sheet here](https://www.markdownguide.org/basic-syntax/) that may be handy.

## Adding content

First we need to decide where we want to place the content item in obsidian. If it is a blog post, event or content item, we'll place them under `articles/`, for any other type of page we'll look under `pages/`.

Once we've chosen the directory, we right-click on it and choose "new note", and then we give it a name (that can have spaces and non-ascii characters), and press enter.

Then we apply a template, clicking on ![](templates-icon.png) (in the left top corner) that will add the necessary metadata to the page. We edit the metadata according to [Content Metadata](_Documentation/Content%20Metadata.md).

And then we can start editing the actual content.

## Editing

As has been mentioned, the content of the site is edited as markdown. Obsidian only shown the markdown when the cursor is on top of specially formatted text; so if you mark a word as bold, Obsidian will show it in bold, and if you place the cursor on top of it, it will show the `**` characters that mark it as bold.

The usual formatting (headings, paragraphs, links, lists, etc.) is accessible through the toolbar and referenced in the cheat-sheet linked above so I won't repeat it here. The toolbar has tools to:

- Undo and redo changes;
- apply headings;
- word styles: bold, cursive, strike-through, highlighted, superscript, subscript, quoted text;
- Links;
- Numbered and unnumbered lists;
- justification of paragraphs;
- Insert timestamps and dates;
- Change the background and foreground color;
- Publish changes to staging;
- See changes that would be pushed to staging;
- Undo all changes, either in current file or the whole site;
- Revert the last change that has been pushed to staging;
- full-screen.

A more detailed look at some of the tools:

## Links

In markdown the links are represented by placing the link text in square brakets immediately followed by the linked address in parenthesis, like: `[link text](https://google.com)`. (To be able to show the format here, I have made it a code block, wrapping it in backticks.

For external links, the address placed in parenthesis is the full address of the link.

For internal links, we don't put the protocol (http or https) or the hostname of the link, just the path. So a link to a page within the sunet.se site will just consist on the slug of the linked page, prepended with a slash, like: `/om-sunet/aktuellt`.

It is also possible to insert links through the contextual menu, right-clicking with the mouse on top of some selected text. In this case, we should choose "add external link" rather that "add link", even if we are adding an internal link.

## Tables

We can insert a table anywhere using the contextual menu, right-clicking with the mouse, and choosing "insert table". To edit the table, we can use "advanced tables toolbar", accessible in the left sidebar by clicking on ![](tables-icon.png) .

In the website, tables will always occupy the width of the page.

## Images

Images are kept under `wp-content/uploads`. To display an image in a page, the markdown is almost identical to that of a link, with the only difference that to display the image rather than just linking it, you prepend the link with a `!`, like: `![alt text for the image](/wp-content/uploads/some-image.png)`. 

The images under `wp-content/uploads` should have the size that we want them to show in the site.

There are basically 3 ways to insert an image in a page.

- **manually**: Just drop the image in some directory under `wp-content/uploads`, using your operative system tools, and then manually add the markdown to embed it as explained above.
- **Drag and drop**: You can drag an image from your system's file explore and drop it in a markdown page. In this case the image will be placed directly at `wp-content/uploads/images`. You will need to manually add the alt text for the image. Also, at the moment the link is formed without the leading slash, so that has to be fixed: `![](wp-content/uploads/my-image.png`) -> `![some alt text](/wp-content/uploads/my-image.png`)
- **Pasting it**: You can paste an image from your clipboard. When you paste an image, obsidian will ask you for a name for it, and will place it at `wp-content/uploads/images`. The same caveats apply as when drag and dropping: No alt text, no leading slash in the link.

The main problem to fix with non-manual methods is the inability to put different files in different directories.

## Attachments

To add attachments such as PDFs, first we place them somewhere under `wp-content/uploads`, using your operative system's facilities, and then in a page add a normal internal link to it.
