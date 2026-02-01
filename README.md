# wp-lemon Snippets

wp-lemon Snippets is a Visual Studio Code extension that provides snippets for the wp-lemon stack based on WordPress, Timber, Twig, JavaScript and SCSS.

you can find the extension on the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=StudioLemon.wp-lemon-snippets).

## Features

This extension provides snippets for the following languages:

- PHP
- Twig
- JavaScript
- SCSS

## Available Snippets

### JavaScript Snippets

#### Swiper function

**Prefix:** `wp-lemon-swiper`, `swiper`  
**Description:** Swiper/Carousel function with Swiper.js integration  
Creates a complete Swiper carousel implementation with navigation, pagination, and autoplay modules.

---

### PHP File Templates

#### acfBuilder Configuration

**Prefix:** `acfbuilder`, `wp-lemon-acfbuilder`  
**Scope:** php, html  
**Description:** Complete ACF Builder configuration file  
Generates a full ACF Builder fields configuration file for custom post types.

#### Block Pattern for Post Type

**Prefix:** `block-pattern-for-post-type`, `wp-lemon-block-pattern-for-post-type`  
**Scope:** php, html  
**Description:** Create a block pattern for a specific post type  
Generates a complete block pattern template with proper headers and post type assignment.

#### Extended Timber Post Class

**Prefix:** `timberPostObject`, `wp-lemon-timberPostObject`  
**Scope:** php  
**Description:** Create an extended Timber Post class  
Sets up an extended post query class with custom methods and properties.

#### Customizer File

**Prefix:** `wp-lemon-customizer-file`, `custimzer-file`  
**Description:** Complete customizer configuration file  
Generates a full customizer file with section registration.

#### Page Template

**Prefix:** `page-template`, `wp-lemon-page-template`  
**Description:** WordPress page template  
Creates a complete page template file with Timber integration.

---

### PHP Code Snippets

#### Define Home and Site URL

**Prefix:** `home-url`, `site-url`, `wp-lemon-define-home-url`, `wp-lemon-define-site-url`  
**Scope:** php  
**Description:** Define WordPress home and site URLs  
Adds WP_HOME and WP_SITEURL constants for local development.

#### Timber Post Classmap

**Prefix:** `timberPostClassmap`, `wp-lemon-timberPostClassmap`  
**Scope:** php  
**Description:** Add a Timber classmap filter  
Registers custom post type classes with Timber's classmap system.

#### Render Action Hook

**Prefix:** `render-action`, `wp-lemon-render-action`  
**Scope:** php  
**Description:** Add a hook to render a Twig file  
Creates a function that renders a Twig template via WordPress action hook.

#### Block Fields Repeater

**Prefix:** `wp-lemon-block-fields-repeater`  
**Scope:** php  
**Description:** ACF Builder repeater field for blocks  
Adds a repeater field with image subfield to block fields.

#### Customizer Field

**Prefix:** `wp-lemon-customizer-field`, `customizer-field`  
**Scope:** php  
**Description:** Add customizer setting and control  
Generates both add_setting and add_control calls for a customizer field.

---

### SCSS Snippets

#### Bootstrap Media Query - Up

**Prefix:** `media-query-up`, `wp-lemon-media-query-up`  
**Scope:** scss  
**Description:** Bootstrap mobile-first media query  
Creates a media-breakpoint-up include for responsive styles.

#### Bootstrap Media Query - Down

**Prefix:** `media-query-down`, `wp-lemon-media-query-down`  
**Scope:** scss  
**Description:** Bootstrap desktop-first media query  
Creates a media-breakpoint-down include for responsive styles.

#### CSS Comment

**Prefix:** `comment`, `wp-lemon-comment`  
**Scope:** scss  
**Description:** Formatted CSS comment block  
Generates a styled comment separator for organizing stylesheets.

---

### Timber/Twig Snippets

#### Single Post Template

**Prefix:** `single-template`, `wp-lemon-single-template`  
**Scope:** twig  
**Description:** Create a single post template  
Generates a complete single post template with action hooks.

#### Picture Element

**Prefix:** `picture`  
**Scope:** twig  
**Description:** Responsive picture element with macro  
Imports and uses the media.picture macro for responsive images.

#### TODO Helper

**Prefix:** `todo`, `wp-lemon-todo`  
**Scope:** twig  
**Description:** TODO marker in templates  
Adds a TODO helper for marking incomplete sections.

#### Translation

**Prefix:** `__`, `wp-lemon-__`, `translate`, `wp-lemon-translate`  
**Scope:** twig  
**Description:** WordPress translation function  
Wraps text in the WordPress translation function.

#### Animation Helper

**Prefix:** `animation`, `wp-lemon-animation`, `aos-animation`, `wp-lemon-aos-animation`  
**Scope:** twig  
**Description:** AOS animation helper  
Adds animation attributes using the helpers.animation macro.

---

### Standard Twig Snippets

#### Autoescape

**Prefix:** `autoescape`, `wp-lemon-autoescape`  
**Scope:** text.html.twig  
**Description:** Autoescape block

#### Block

**Prefix:** `block`, `wp-lemon-block`  
**Scope:** text.html.twig  
**Description:** Template block definition

#### Ceil

**Prefix:** `ceil`, `wp-lemon-ceil`  
**Scope:** text.html.twig  
**Description:** Ceiling function

#### Replace

**Prefix:** `replace`, `wp-lemon-replace`  
**Description:** String replacement filter

#### Replace Regex

**Prefix:** `replacex`, `wp-lemon-replacex`  
**Description:** Regex replacement filter

#### Split

**Prefix:** `split`, `wp-lemon-split`  
**Description:** Split string into array

#### Dump

**Prefix:** `dump`, `wp-lemon-dump`  
**Scope:** text.html.twig  
**Description:** Debug output with dump()

#### Else

**Prefix:** `else`, `wp-lemon-else`  
**Scope:** text.html.twig  
**Description:** Else statement

#### Endblock

**Prefix:** `endblock`, `wp-lemon-endblock`  
**Scope:** text.html.twig  
**Description:** Close block tag

#### Endfilter

**Prefix:** `endfilter`, `wp-lemon-endfilter`  
**Scope:** text.html.twig  
**Description:** Close filter tag

#### Endfor

**Prefix:** `endfor`, `wp-lemon-endfor`  
**Scope:** text.html.twig  
**Description:** Close for loop

#### Endif

**Prefix:** `endif`, `wp-lemon-endif`  
**Scope:** text.html.twig  
**Description:** Close if statement

#### Endmacro

**Prefix:** `endmacro`, `wp-lemon-endmacro`  
**Scope:** text.html.twig  
**Description:** Close macro definition

#### Endset

**Prefix:** `endset`, `wp-lemon-endset`  
**Scope:** text.html.twig  
**Description:** Close set block

#### Endspaceless

**Prefix:** `endspaceless`, `wp-lemon-endspaceless`  
**Scope:** text.html.twig  
**Description:** Close spaceless block

#### Extends

**Prefix:** `extends`, `wp-lemon-extends`  
**Scope:** text.html.twig  
**Description:** Template inheritance

#### Filter Block

**Prefix:** `filterb`, `wp-lemon-filterb`  
**Scope:** text.html.twig  
**Description:** Filter block (multi-line)

#### Filter

**Prefix:** `filter`, `wp-lemon-filter`  
**Scope:** text.html.twig  
**Description:** Filter statement

#### Floor

**Prefix:** `floor`, `wp-lemon-floor`  
**Scope:** text.html.twig  
**Description:** Floor function

#### For...Else

**Prefix:** `fore`, `wp-lemon-fore`  
**Scope:** text.html.twig  
**Description:** For loop with else clause

#### For

**Prefix:** `for`, `wp-lemon-for`  
**Scope:** text.html.twig  
**Description:** For loop

#### If (inline)

**Prefix:** `if`, `wp-lemon-if`  
**Scope:** text.html.twig  
**Description:** Inline if statement

#### If Block

**Prefix:** `ifb`, `wp-lemon-ifb`  
**Scope:** text.html.twig  
**Description:** If block (multi-line)

#### If...Else

**Prefix:** `ife`, `wp-lemon-ife`  
**Scope:** text.html.twig  
**Description:** If statement with else clause

#### If (single line)

**Prefix:** `if1`, `wp-lemon-if1`  
**Scope:** text.html.twig  
**Description:** Single-line if statement

#### Import

**Prefix:** `import`, `wp-lemon-import`  
**Scope:** text.html.twig  
**Description:** Import macro file

#### Import Self

**Prefix:** `importself`, `wp-lemon-importself`  
**Scope:** text.html.twig  
**Description:** Import macros from current file

#### Include with Key/Value

**Prefix:** `inckv`, `wp-lemon-inckv`  
**Scope:** text.html.twig  
**Description:** Include template with key/value parameters

#### Include

**Prefix:** `inc`, `wp-lemon-inc`, `include`, `wp-lemon-include`  
**Scope:** text.html.twig  
**Description:** Include template

#### Include with Parameters

**Prefix:** `incp`, `wp-lemon-incp`  
**Scope:** text.html.twig  
**Description:** Include template with parameters

#### Macro

**Prefix:** `macro`, `wp-lemon-macro`  
**Scope:** text.html.twig  
**Description:** Macro definition

#### Max

**Prefix:** `max`, `wp-lemon-max`  
**Scope:** text.html.twig  
**Description:** Maximum value function

#### Min

**Prefix:** `min`, `wp-lemon-min`  
**Scope:** text.html.twig  
**Description:** Minimum value function

#### Round

**Prefix:** `round`, `wp-lemon-round`  
**Scope:** text.html.twig  
**Description:** Round number with floor method

#### Set Block

**Prefix:** `setb`, `wp-lemon-setb`  
**Scope:** text.html.twig  
**Description:** Set variable block (multi-line)

#### Set

**Prefix:** `set`, `wp-lemon-set`  
**Scope:** text.html.twig  
**Description:** Set variable

#### Shuffle

**Prefix:** `shuffle`, `wp-lemon-shuffle`  
**Scope:** text.html.twig  
**Description:** Shuffle array

#### Random

**Prefix:** `random`, `wp-lemon-random`  
**Scope:** text.html.twig  
**Description:** Random value function

#### Spaceless

**Prefix:** `spaceless`, `wp-lemon-spaceless`  
**Scope:** text.html.twig  
**Description:** Remove whitespace between HTML tags

#### Use

**Prefix:** `use`, `wp-lemon-use`  
**Scope:** text.html.twig  
**Description:** Horizontal template reuse

---

## Usage

To use a snippet, start typing one of the prefix keywords listed above in the appropriate file type, and VS Code will suggest the snippet. Press `Tab` or `Enter` to insert the snippet, then use `Tab` to navigate between the placeholders.

All snippets have the `wp-lemon-` prefix variant for easy discovery when typing `wp-lemon-` in your editor.
