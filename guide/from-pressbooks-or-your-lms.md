# From Pressbooks or Your LMS

<small>Part 4</small>

Start from your own book or course, or an open one to adapt, with two free converters (both in beta)[^1] – no Grav installation needed to see what carries over:

- **[Pressbooks Converter](https://grav-pressbooks-converter.hibbittsdesign.org/)** – upload a Pressbooks XHTML export, and download an Open Publishing Space guide, ready to review and publish
- **[Common Cartridge Converter](https://grav-common-cartridge-converter.hibbittsdesign.org/)** – export a course from Canvas, Moodle, Brightspace or Blackboard as a [Common Cartridge](/guide/glossary.md?id=glossary-common-cartridge "A standard file format for moving a course between learning management systems – Canvas, Moodle, Brightspace and Blackboard can all export one.") file, and download its modules, ready for Open Course Space

**Already sharing Markdown with Docsify-This?** The free [Grav Docsify Bridge](https://grav-docsify-bridge.hibbittsdesign.org/) moves it into either starter, and back again.

Table: What carries over from a Pressbooks book

| Content | In the converted guide |
|---|---|
| Text, headings, figures and captions | Carried over |
| Exercises and other callouts | Carried over as callout boxes |
| Footnotes | Carried over |
| H5P activities and videos | H5P activities embedded (an option) or linked; other media linked back to the book |
| Tables inserted with a Pressbooks [shortcode](/guide/glossary.md?id=glossary-shortcode "A short tag in square brackets that Grav turns into a box, an embed or another feature when it shows a page.") | Shown as text, to replace with a Markdown table |

![A chapter of an openly licensed Pressbooks book, beside the same chapter after conversion to an Open Publishing Space guide, with its heading, text and image carried over, and a sidebar with a search box and the book's modules and chapters](pressbooks-to-open-publishing-space.webp)

*The same chapter in Pressbooks and in Open Publishing Space, with no revisions – from [Universal Design for Learning (UDL) for Inclusion, Diversity, Equity, and Accessibility (IDEA)](https://ecampusontario.pressbooks.pub/universaldesign2/), [CC BY 4.0](/guide/glossary.md?id=glossary-cc-by-4-0 "A Creative Commons licence that lets anyone share and adapt a work, for any purpose, as long as they give credit.")*

![A converted module intro page on a phone, twice: at the top with the module title, authors and three icons, and scrolled down to a Learning Objectives box listing four outcomes, both with a Previous and Next bar at the bottom of the screen](pressbooks-to-open-publishing-space-phone.webp)

*A module's intro page on a phone: its text and images, then its Learning Outcomes as a Learning Objectives box*

Examples (raw conversions, with no revisions or fine-tuning): [four openly licensed Pressbooks books in Open Publishing Space](https://demo.hibbittsdesign.org/variants/grav-open-publishing-quark2-pressbooks-books/) · [LMS course content in Open Course Space](https://demo.hibbittsdesign.org/variants/grav-open-course-space-common-cartridge-it2dda/)

**No web server needed:** choose Docsify-This or a Starter Kit as the converter's destination, and the book becomes plain Markdown you can adapt, reuse and publish as a website for free. It's readable right in its GitHub or Codeberg repository, and ready to move to Grav whenever you want – [see the same four books on Docsify-This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-open-publishing-pressbooks-books-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&pagination=true&searchbox=true&collapsibleSidebarGroups=true&collapseSidebarGroups=true&dark-mode=auto&name=Books%20from%20Pressbooks&edit-link=https://raw.githubusercontent.com/paulhibbitts/docsify-open-publishing-pressbooks-books-site/main/home.md&edit-link-text=This%20page%20as%20Markdown&edit-link-emoji=:page_facing_up:) · [on GitHub](https://github.com/paulhibbitts/docsify-open-publishing-pressbooks-books-site)

[^1]: Beta means they handle many books and courses well, but a converted guide or course may need some tidying – tables inserted with a Pressbooks shortcode, for example, need replacing with Markdown tables.

> [!NOTE]
> **See four converted books** – [in Open Publishing Space](https://demo.hibbittsdesign.org/variants/grav-open-publishing-quark2-pressbooks-books/), with one search box for all of them, and [the same books on Docsify-This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-open-publishing-pressbooks-books-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&pagination=true&searchbox=true&collapsibleSidebarGroups=true&collapseSidebarGroups=true&dark-mode=auto&name=Books%20from%20Pressbooks&edit-link=https://raw.githubusercontent.com/paulhibbitts/docsify-open-publishing-pressbooks-books-site/main/home.md&edit-link-text=This%20page%20as%20Markdown&edit-link-emoji=:page_facing_up:), with no web server needed.
>
> **Compare one yourself** – the [original Pressbooks book](https://ecampusontario.pressbooks.pub/universaldesign2/) and the [same book in Open Publishing Space](https://demo.hibbittsdesign.org/variants/grav-open-publishing-quark2-pressbooks-udl/) or [on Docsify-This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-open-publishing-pressbooks-udl-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&pagination=true&searchbox=true&collapsibleSidebarGroups=true&collapseSidebarGroups=true&dark-mode=auto&name=Universal%20Design%20for%20Learning%20%28UDL%29&edit-link=https://raw.githubusercontent.com/paulhibbitts/docsify-open-publishing-pressbooks-udl-site/main/home.md&edit-link-text=This%20page%20as%20Markdown&edit-link-emoji=:page_facing_up:), converted with no revisions.
>
> *Thanks to the authors for making these books open!*
>
> **See a converted course** – [an LMS course in Open Course Space](https://demo.hibbittsdesign.org/variants/grav-open-course-space-common-cartridge-it2dda/), converted with no revisions.
