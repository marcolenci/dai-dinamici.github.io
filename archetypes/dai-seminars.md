+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"
categories = ["dai-seminar"]
outputs = ["HTML", "Calendar"]
title = "" # In the form "Author (Affiliation)"
speaker = ""
seminar = "" # Seminar title
affiliation = ""
# The three " are for multiline parts. Omitted abstract and date will produce TBA in the page
abstract = """

"""
location = "" # Empty until we have the link, then "[Zoom Room](URL HERE)"
start = "" # Use https://dencode.com/date/iso8601, Europe/Rome time zone, format ISO8601 Date
end = ""  # As above
draft = true # Delete this line if you want the event to be published
+++

<!-- By omitting 'speaker', you can omit also 'affiliation', 'abstract', 'start', 'end' but you need to write manually the text below, after 
deleting the irrelevant parts, the <!-- and the --> 

<!-- Use Markdown syntax: https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf 
See also: https://www.markdownguide.org/basic-syntax/
(for a new line without breaking a paragraph simply end the line with two or more spaces)

The following shortcodes for videos or images are available: https://gohugo.io/content-management/shortcodes/
{{< center >}}To center text, use the center shortcode{{< /center >}}

We can create more if needed, just let me know.

You cannot add html content, if you need that, I can make it possible, so, in case, let me know.
-->

<!--
*Speaker:* **NAME**  (AFFILIATION)

*Title:* ***TITLE***

*Abstract:* ABSTRACT

**NOTE:** *The seminar will be streamed live on our [YouTube
channel](https://www.youtube.com/channel/UCyNNg155G3iLS7l-qZjboyg) then
saved there. If you ask questions,  with your video feed on or off, you
agree to the use of your image/spoken words for said purpose.*
-->
