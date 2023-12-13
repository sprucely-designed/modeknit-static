# Modeknit Static Website Repository

## Introduction

This repository, `sprucely-designed/modeknit-static`, preserves the legacy of Annie Modesitt through a static copy of the [ModeKnit website](https://www.modeknit.com). This site was a platform for Annie, a renowned knitwear designer, to share her insights and stories with the knitting community. The static site is a conversion of the original WordPress blog using WP2Static, ensuring the accessibility and preservation of the content as a tribute to Annie's enduring impact.

## About Annie Modesitt

Annie Modesitt, a self-taught knitter from Ohio, began her knitting journey at 25. Her career took off after moving from New York City to Texas, where she developed her unique approach to knitting. Known for her "Combination Method" of knitting, Annie believed there was no wrong way to knit. Her work appeared in prestigious publications such as Interweave Knits and Vogue Knitting. She authored several influential knitting books, including "Confessions of a Knitting Heretic" and "Knitting Millinery." Annie's inventive FLIP KNITS and her advocacy for knitting as an accessible craft made her a beloved figure in the knitting community. **Annie passed away October 1, 2020**

## Current Limitations

After converting the original WordPress blog to a static site, some features are no longer operational. These limitations include:

- **Site Search Inactivity**: The search functionality does not yield results due to the static nature of the site.
- **Non-Functional Forms**: Forms, including comment submission forms, return a 500 error as they are not connected to backend services for processing.
- **Twitter Embed Issues**: Embedded Twitter content may not display correctly due to changes in Twitter's platform and the static conversion.

These limitations are inherent to the transition from a dynamic WordPress site to a static format.

## Repository Structure

- Yearly folders (`2002` to `2020`): Contain posts and content from respective years.
- `author`, `catablog-items`, `category`, `donate`, `page`, `tag`, `thank-you`, `uh-oh`, `why_donate_button`: Various WordPress categories, tags, and pages.
- `wp-content`: WordPress themes and plugins.
- `wp-includes`: Standard WordPress core files.
- Root directory files: `index.html`, `robots.txt`, sitemaps, etc., for site structure.

## Contributing

Contributions that enhance accessibility, readability, and preservation of Annie's work, without altering the original text, are welcome. Significant changes should be discussed in an issue.

## License

Content is not licensed for reuse.

---

For inquiries or suggestions, please open an issue in this repository.
