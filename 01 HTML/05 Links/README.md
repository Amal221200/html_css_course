# Links / Hyperlinks

The `<a>` HTML element (or anchor element), with its **href** attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.

Content within each `<a>` should indicate the link's destination. If the href attribute is present, pressing the enter key while focused on the `<a>` element will activate it.

```
    <a href="https://www.google.com" target="_blank"></a>
```

## Attributes

- **`target`**: Where to display the linked URL, as the name for a browsing context (a tab, window, or `<iframe>`). The following keywords have special meanings for where to load the URL:

  - \_self: the current browsing context. (Default)
  - \_blank: usually a new tab, but users can configure browsers to open a new window instead.
  - \_parent: the parent browsing context of the current one. If no parent, behaves as \_self.
  - \_top: the topmost browsing context (the "highest" context that's an ancestor of the current one). If no ancestors, behaves as \_self.

- **`href`**: The URL that the hyperlink points to. Links are not restricted to HTTP-based URLs — they can use any URL scheme supported by browsers:

  - Sections of a page with document fragments
  - Specific text portions with text fragments
  - Pieces of media files with media fragments
  - Telephone numbers with `tel:` URLs
  - Email addresses with `mailto`: URLs
  - SMS text messages with `sms:` URLs
  - While web browsers may not support other URL schemes, websites can with registerProtocolHandler()

- **`download`**: Causes the browser to treat the linked URL as a download. Can be used with or without a filename value:

  Without a value, the browser will suggest a filename/extension, generated from various sources:

  - The Content-Disposition HTTP header
  - The final segment in the URL path
  - The media type (from the Content-Type header, the start of a data: URL, or Blob.type for a blob: URL)

- **`filename`**: defining a value suggests it as the filename. / and \ characters are converted to underscores (\_). Filesystems may forbid other characters in filenames, so browsers will adjust the suggested name if necessary.
