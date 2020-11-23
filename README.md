# Project 3: From Portland to Portland


**Intro**

This is a project about traveling across the US. We discuss the following areas:

1. Maine
2. New Hampshire
3. Pennsylvania
4. New York
5. Ohio


**Figma**

* [Link to the project on Figma](https://www.figma.com/file/xM9rNsdK4iNcFJmDZho3Aw/Sprint-3%3A-From-Portland-to-Portland-%2F-desktop-%2B-mobile?node-id=500%3A0)


**Technology used:**

1. CSS 
2. HTML

**Suggestions for improvement**

1. Use decimals for line-height
2. Improve responsive layout for the interval `425px-768px`
3. Remove stray font properties (if any)
4. Travel to the destinations mentioned on the page 😉


**BEM Structure**

```
blocks
├── content
│   └── content.css
├── cover
│   ├── __link
│   │   └── cover__link.css
│   ├── __subtitle
│   │   └── cover__subtitle.css
│   ├── __title
│   │   └── cover__title.css
│   └── cover.css
├── footer
│   ├── __copyright
│   │   └── footer__copyright.css
│   ├── __link
│   │   └── footer__link.css
│   ├── __links
│   │   └── footer__links.css
│   └── footer.css
├── header
│   ├── __lang-link
│   │   ├── _active
│   │   │   └── header__lang-link_active.css
│   │   └── header__lang-link.css
│   ├── __links
│   │   └── header__links.css
│   └── header.css
├── intro
│   ├── __list
│   │   └── intro__list.css
│   ├── __list-item
│   │   └── intro__list-item.css
│   ├── __span-accent
│   │   └── intro__span-accent.css
│   ├── __subtitle
│   │   └── intro__subtitle.css
│   ├── __text
│   │   └── intro__text.css
│   ├── __title
│   │   └── intro__title.css
│   └── intro.css
├── lead
│   ├── __caption
│   │   └── lead__caption.css
│   ├── __figure
│   │   └── lead__figure.css
│   ├── __image
│   │   └── lead__image.css
│   ├── __subtitle
│   │   └── lead__subtitle.css
│   ├── __title
│   │   └── lead__title.css
│   └── lead.css
├── link
│   └── link.css
├── logo
│   └── logo.css
├── page
│   ├── __container
│   │   └── page__container.css
│   └── page.css
├── photo-grid
│   ├── __image
│   │   └── photo-grid__image.css
│   ├── __item
│   │   └── photo-grid__item.css
│   └── photo-grid.css
├── place
│   ├── __image
│   │   └── place__image.css
│   ├── __image-item
│   │   └── place__image-item.css
│   ├── __link
│   │   └── place__link.css
│   ├── __paragraph
│   │   └── place__paragraph.css
│   ├── __summary
│   │   └── place__summary.css
│   ├── __title
│   │   └── place__title.css
│   ├── __url-heading
│   │   └── place__url-heading.css
│   ├── __website
│   │   └── place__website.css
│   └── place.css
└── places
    └── places.css

```