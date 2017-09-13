# cugir-help

Public-facing help and documentation for the CUGIR website: https://cul-it.github.io/cugir-help/

Help pages are written in markdown, and served via github-pages.  Each page should have a simple name and `.md` (markdown) extension, like `wms.md` and should begin with front matter like this:

```
---
title: WMS services
tags:
  - web services
  - another tag
status: public
---

# WMS services

WMS (Web Map Service) is a standard OGC protocol...
```

`title:` specifies the title as it will appear in the help index.

`tags:` can be used to assign subject tags to the page.

`status:` (`public` or `draft`) indicates whether the the page has been published.

`# WMS` is a heading for the page, and should match the `title:` for consistency.  Note that the filename `wms.md` should be as short as possible (yet still be unique within the help pages), whereas the full title should be more descriptive, and should also place the entry alphabetically in a place where it should be logically found.  (Thus, this example title is NOT "CUGIR WMS services".)


# Drafts

Unpublished drafts should say `status: draft` until they are ready to be made public.  You can view a list of any drafts at https://cul-it.github.io/cugir-help/blog/drafts.


