# [httpcod.es][5]

[httpcod.es][5] is an easy to reference database of HTTP Status Codes with their definitions and helpful code references, each code is at `httpstatuses.com/code`. All standard codes are included, as are some non-standard codes that have significant presence in the wild.

This is a for of [rmaake1/httpstatuses][6], after `httpstatuses.com` went offline.

## Contributing

All contributions are welcome! If you have an idea to improve the website please submit a pull request or [create an issue][1], or provide your thoughts on [open issues][1].

Each status code lives in a Markdown file at [contents/codes](contents/codes), the easiest way to submit changes is via the GitHub editor. When contributing changes to the status codes please be mindful of the following:

* Markdown links should be used as [references instead of inline][2]
* If an RFC or external document is referenced, make the reference a link
* Source information on a status code from the most recent standards available (Status Code standards directory is available on [iana.org][3])
* The opening paragraph of a status code should describe the meaning, following paragraphs can describe implementation
* Don't edit the meaning of descriptions, but formatting and structural changes are a-okay
* [Don't double-space after a period][4], and remove any examples of it
* If the description references a section in the current RFC, always add the RFC identifier. For example "Section 6.6" should become "RFC1234 Section 6.6"

### Running locally

To build and run you'll need Zola. You can [get Zola from the official website][7].

To run the site locally, and have it live update when changes are made to files run `zola serve`.

To generate the static files, and have them output to the directory `public`, run `zola build`.


[1]: <https://github.com/jonstodle/httpcodes/issues>
[2]: <https://daringfireball.net/projects/markdown/syntax#link>
[3]: <http://www.iana.org/assignments/http-status-codes/http-status-codes.xhtml>
[4]: <http://www.slate.com/articles/technology/technology/2011/01/space_invaders.html>
[5]: <https://httpcod.es>
[6]: <https://github.com/rmaake1/httpstatuses>
[7]: <https://www.getzola.org/documentation/getting-started/installation/>
