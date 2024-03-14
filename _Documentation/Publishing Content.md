---
Title: Publishing Content
Date: 2024-03-12
Modified: 2024-03-12
Slug: documentation/publishing-content
Authors: 
Lang: en
Translation: false
---

# Publishing content.

In principle there is no need to save any changes locally; as soon as any the content changes, it is saved to disk, with a delay of a couple of seconds. If we want to make fully sure, we can hit `Ctrl-S`.

In addition, there are a few facilities to save the changes to github and publish them in staging from there, and to undo some publication, and to check and discard the changes that would be pushed to github and published at staging.

- In the toolbar, under the anchor icon, there is a double arrow icon, and if we push it, it will show the changes that are present locally but have not been published to github & staging.
- Also under the anchor icon, there is an icon of an arrow pointing upwards and rightwards. Clicking on it will push all the local changes to github, and publish it at staging.
- Under the warning icon in the toolbar, there are 3 actions that are not recoverable, so use with caution.
    - The leftwards pointing arrow will discard all non-published changes to the current file.
    - The encircled leftwards pointing arrow will discard all non-published changes to all the files.
    - The downwards and leftwards pointing arrow will remove the last published changes from all places: from the local filesystem, from github, and from staging. So it will allow us to undo the last pubication.