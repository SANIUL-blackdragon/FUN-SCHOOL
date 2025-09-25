# **CSS Specification: Complete Mastery with Detailed Guidance**

### **Unit 1: CSS Fundamentals and Syntax**  
**Description:** Introduction to CSS, its purpose, and how it integrates with HTML. Students will learn fundamental syntax and apply basic styling to web pages.  

#### **Topic 1: CSS Introduction and Integration**  
Students will be assessed on their ability to:  
1. **Understand the purpose and role of CSS in web development.**  
   *Guidance:* Students should be able to explain that CSS (Cascading Style Sheets) is used to control the presentation, formatting, and layout of HTML documents. They should understand that CSS separates content (HTML) from presentation (CSS), enabling consistent styling across multiple pages and easier maintenance.  

2. **Differentiate between HTML, CSS, and JavaScript in web development.**  
   *Guidance:* Students should recognize that HTML provides structure and content, CSS controls visual presentation and layout, while JavaScript adds interactivity and dynamic behavior. They should be able to give examples of what each technology is responsible for in a webpage.  

3. **Apply CSS using inline, internal, and external methods.**  
   *Guidance:* Students should be able to write inline styles using the style attribute directly in HTML elements, create internal stylesheets using the `<style>` tag in the HTML head section, and link external CSS files using the `<link>` tag. They should understand the advantages and disadvantages of each method, including when to use each approach.  

4. **Understand the concept of cascading and inheritance in CSS.**  
   *Guidance:* Students should explain that cascading refers to the process of combining style sheets and resolving conflicts when multiple rules target the same element. They should understand that inheritance means some properties applied to parent elements are inherited by their children, and be able to identify which properties are inherited (e.g., font-family, color) and which are not (e.g., border, margin).  

5. **Use the CSS comment syntax correctly.**  
   *Guidance:* Students should be able to write single-line and multi-line comments using `/* comment */` syntax. They should understand that comments are ignored by browsers and are used for documentation and to temporarily disable CSS rules.  

#### **Topic 2: CSS Syntax and Structure**  
Students will be assessed on their ability to:  
1. **Write CSS rules with correct syntax.**  
   *Guidance:* Students should be able to construct CSS rules consisting of selectors and declaration blocks. They should understand that selectors target HTML elements, and declaration blocks contain one or more declarations, each consisting of a property and a value separated by a colon and ending with a semicolon.  

2. **Identify and use different types of CSS selectors.**  
   *Guidance:* Students should be able to use element selectors (e.g., `p`), class selectors (e.g., `.container`), ID selectors (e.g., `#header`), and the universal selector (`*`). They should understand when to use each type and the specificity differences between them.  

3. **Apply multiple declarations to a single selector.**  
   *Guidance:* Students should be able to write multiple property-value pairs within a single declaration block, separated by semicolons. They should understand that the order of declarations can matter when properties affect each other.  

4. **Group multiple selectors with the same declarations.**  
   *Guidance:* Students should be able to group selectors by separating them with commas (e.g., `h1, h2, h3 { color: blue; }`). They should understand that this is a technique for applying the same styles to multiple elements efficiently.  

5. **Understand and apply the concept of CSS specificity.**  
   *Guidance:* Students should understand that specificity determines which CSS rule is applied when multiple rules target the same element. They should be able to explain the basic specificity hierarchy (ID > class > element) and how to calculate specificity for simple selectors.  

---

### **Unit 2: The Box Model and Layout Fundamentals**  
**Description:** Understanding the CSS box model and how it controls layout, spacing, and sizing of elements.  

#### **Topic 1: Box Model Components**  
Students will be assessed on their ability to:  
1. **Define and explain the components of the CSS box model.**  
   *Guidance:* Students should be able to identify and describe the four components of the box model: content (the actual content of the element), padding (space between content and border), border (the edge surrounding the padding), and margin (space outside the border). They should understand how these components work together to determine the total space an element occupies.  

2. **Manipulate padding properties in CSS.**  
   *Guidance:* Students should be able to use `padding-top`, `padding-right`, `padding-bottom`, `padding-left`, and the shorthand `padding` property. They should understand how padding affects the size of an element and how it interacts with the background color/image.  

3. **Manipulate margin properties in CSS.**  
   *Guidance:* Students should be able to use `margin-top`, `margin-right`, `margin-bottom`, `margin-left`, and the shorthand `margin` property. They should understand how margins create space around elements and how vertical margins can collapse (margin collapse).  

4. **Apply and explain the difference between `box-sizing: border-box` and `box-sizing: content-box`.**  
   *Guidance:* Students should understand that `content-box` (the default) calculates width and height based only on the content area, not including padding and border. They should explain that `border-box` calculates width and height to include padding and border, making layout calculations more intuitive. They should be able to demonstrate practical applications of both models.  

5. **Calculate the total width and height of an element including all box model components.**  
   *Guidance:* Students should be able to calculate the total space an element occupies by adding content width/height, padding, border, and margin. They should understand how these calculations change based on the box-sizing property and be able to predict how changes to one component affect the overall layout.  

#### **Topic 2: Borders and Outlines**  
Students will be assessed on their ability to:  
1. **Style borders using CSS border properties.**  
   *Guidance:* Students should be able to use `border-width`, `border-style`, `border-color`, and the shorthand `border` property. They should understand different border styles (solid, dashed, dotted, double, etc.) and how to apply them to specific sides of an element.  

2. **Create rounded corners using the border-radius property.**  
   *Guidance:* Students should be able to use `border-radius` to create rounded corners on elements. They should understand how to apply different radius values to each corner using the shorthand notation or individual properties (`border-top-left-radius`, etc.). They should be able to create circular elements by setting border-radius to 50% or appropriate values.  

3. **Apply border images to elements.**  
   *Guidance:* Students should be able to use `border-image-source`, `border-image-slice`, `border-image-width`, `border-image-outset`, `border-image-repeat`, and the shorthand `border-image` property. They should understand how to use images as borders and control how those images are sliced and repeated around the element.  

4. **Differentiate between borders and outlines in CSS.**  
   *Guidance:* Students should understand that borders are part of the box model and affect layout, while outlines (`outline`) are drawn outside the border and do not take up space. They should be able to use outline properties (`outline-width`, `outline-style`, `outline-color`, `outline-offset`) and explain when outlines are useful (e.g., for accessibility focus indicators).  

5. **Apply box shadows to elements.**  
   *Guidance:* Students should be able to use the `box-shadow` property with its various parameters: horizontal offset, vertical offset, blur radius, spread radius, color, and inset. They should understand how to create multiple shadows and how to use shadows for depth and emphasis in design.  

---

### **Unit 3: Text and Typography**  
**Description:** Advanced control over text appearance, spacing, and readability.  

#### **Topic 1: Font Properties**  
Students will be assessed on their ability to:  
1. **Apply and control font families in CSS.**  
   *Guidance:* Students should be able to use the `font-family` property to specify preferred fonts and fallback font stacks. They should understand the difference between generic font families (serif, sans-serif, monospace, cursive, fantasy) and web fonts, and how to implement web fonts using `@font-face`.  

2. **Control font size and scaling.**  
   *Guidance:* Students should be able to use `font-size` with various units (px, em, rem, %, vw). They should understand the differences between absolute and relative units and how to create responsive typography. They should also be able to use `font-size-adjust` to maintain readability when web fonts are unavailable.  

3. **Manipulate font weight, style, and variant.**  
   *Guidance:* Students should be able to use `font-weight` (normal, bold, numeric values), `font-style` (normal, italic, oblique), and `font-variant` (normal, small-caps). They should understand the differences between italic and oblique and how to use these properties for emphasis and hierarchy.  

4. **Implement web fonts using @font-face.**  
   *Guidance:* Students should be able to use the `@font-face` rule to include custom fonts on web pages. They should understand the syntax, including `font-family`, `src`, `font-weight`, `font-style`, and `unicode-range` descriptors. They should also understand different font formats (WOFF2, WOFF, TTF, EOT) and when to use each.  

5. **Control font stretching, synthesis, and other advanced font properties.**  
   *Guidance:* Students should be able to use `font-stretch` (condensed, normal, expanded), `font-synthesis` (weight, style, none), and other advanced properties like `font-feature-settings` and `font-variant-ligatures`. They should understand how these properties affect text rendering and readability.  

#### **Topic 2: Text Properties**  
Students will be assessed on their ability to:  
1. **Control text alignment and justification.**  
   *Guidance:* Students should be able to use `text-align` (left, right, center, justify), `text-align-last` (auto, left, right, center, justify), and `text-justify` (auto, inter-word, inter-character, none). They should understand how alignment affects readability and appearance, and when to use justification versus other alignment options.  

2. **Adjust text spacing and indentation.**  
   *Guidance:* Students should be able to use `letter-spacing`, `word-spacing`, `line-height`, and `text-indent`. They should understand how these properties affect readability and visual hierarchy, and how to use them effectively in different contexts (e.g., headings, paragraphs, captions).  

3. **Apply text decoration and transformation.**  
   *Guidance:* Students should be able to use `text-decoration` (line, color, style), `text-decoration-line` (none, underline, overline, line-through), `text-decoration-color`, `text-decoration-style` (solid, double, dotted, dashed, wavy), and `text-transform` (none, capitalize, uppercase, lowercase). They should understand how to use these properties for emphasis and visual consistency.  

4. **Control text overflow and wrapping.**  
   *Guidance:* Students should be able to use `text-overflow` (clip, ellipsis), `overflow-wrap` (normal, break-word), `word-break` (normal, break-all, keep-all), `white-space` (normal, nowrap, pre, pre-line, pre-wrap), and `hyphens` (none, manual, auto). They should understand how these properties control how text behaves when it exceeds its container's boundaries.  

5. **Apply text shadows and other text effects.**  
   *Guidance:* Students should be able to use `text-shadow` with its parameters (horizontal offset, vertical offset, blur radius, color). They should understand how to create multiple text shadows and how to use them for readability and visual effects. They should also be able to use `text-emphasis`, `text-emphasis-color`, `text-emphasis-position`, and `text-rendering` for advanced text effects.  

---

### **Unit 4: Colors and Backgrounds**  
**Description:** Mastery of color systems and advanced background styling.  

#### **Topic 1: Color Systems**  
Students will be assessed on their ability to:  
1. **Use and convert between different color formats in CSS.**  
   *Guidance:* Students should be able to use named colors (e.g., red, blue), HEX (e.g., #FF0000), RGB (e.g., rgb(255, 0, 0)), RGBA (e.g., rgba(255, 0, 0, 0.5)), HSL (e.g., hsl(0, 100%, 50%)), and HSLA (e.g., hsla(0, 100%, 50%, 0.5)). They should understand the differences between these formats and when to use each one.  

2. **Apply opacity and transparency to elements.**  
   *Guidance:* Students should be able to use the `opacity` property (values from 0 to 1) and RGBA/HSLA color values to create transparency effects. They should understand the difference between element opacity and color transparency, and how opacity affects child elements.  

3. **Create and apply color gradients.**  
   *Guidance:* Students should be able to use `linear-gradient()` and `radial-gradient()` functions to create gradients. They should understand how to control gradient direction, color stops, and position. They should also be able to create complex gradients with multiple color stops and transparency.  

4. **Use the currentColor keyword and CSS color variables.**  
   *Guidance:* Students should be able to use the `currentColor` keyword to inherit the text color value for other properties. They should also be able to use CSS custom properties (variables) to define and reuse colors throughout a stylesheet (e.g., `--primary-color: #FF0000;`).  

5. **Apply advanced color functions and adjust colors.**  
   *Guidance:* Students should be able to use modern color functions like `color-mix()` to mix colors, `color-contrast()` to ensure text has sufficient contrast against backgrounds, and relative color syntax to modify existing colors. They should understand how these functions can be used for theming and accessibility.  

#### **Topic 2: Backgrounds**  
Students will be assessed on their ability to:  
1. **Apply solid color backgrounds to elements.**  
   *Guidance:* Students should be able to use the `background-color` property to set solid color backgrounds. They should understand how this property interacts with other background properties and how it affects the element's box model.  

2. **Use background images and control their display.**  
   *Guidance:* Students should be able to use the `background-image` property to apply images as backgrounds. They should understand how to control image display using `background-repeat` (repeat, repeat-x, repeat-y, no-repeat), `background-position` (keywords, percentages, length values), and `background-attachment` (scroll, fixed, local).  

3. **Control background size and origin.**  
   *Guidance:* Students should be able to use `background-size` (auto, cover, contain, length/percentage values) to control how background images are sized. They should also be able to use `background-origin` (padding-box, border-box, content-box) to determine the positioning area of background images.  

4. **Apply multiple backgrounds to a single element.**  
   *Guidance:* Students should be able to specify multiple background images, separated by commas, in a single `background` shorthand property or individual background properties. They should understand how the order of images affects their stacking and how to control the properties of each image individually.  

5. **Create advanced background effects.**  
   *Guidance:* Students should be able to use `background-blend-mode` to control how background images blend with each other and with the background color. They should also be able to use `mask-image`, `mask-mode`, `mask-size`, `mask-position`, and other mask properties to create complex masking effects.  

---

### **Unit 5: Advanced Selectors**  
**Description:** Precision targeting of elements using complex selectors.  

#### **Topic 1: Selector Types**  
Students will be assessed on their ability to:  
1. **Use and differentiate between basic selectors.**  
   *Guidance:* Students should be able to use element selectors (e.g., `div`), class selectors (e.g., `.class`), ID selectors (e.g., `#id`), and the universal selector (`*`). They should understand the specificity differences between these selectors and when to use each type.  

2. **Apply attribute selectors to target elements based on their attributes.**  
   *Guidance:* Students should be able to use attribute selectors like `[attr]` (presence), `[attr=value]` (exact match), `[attr~=value]` (contains word), `[attr|=value]` (starts with), `[attr^=value]` (starts with), `[attr$=value]` (ends with), and `[attr*=value]` (contains). They should understand how to use these selectors for form elements, links, and other elements with specific attributes.  

3. **Use pseudo-classes to target elements based on their state.**  
   *Guidance:* Students should be able to use link pseudo-classes (`:link`, `:visited`), user action pseudo-classes (`:hover`, `:active`, `:focus`), form pseudo-classes (`:checked`, `:disabled`, `:valid`, `:invalid`), structural pseudo-classes (`:first-child`, `:last-child`, `:nth-child()`, `:nth-of-type()`), and others (`:root`, `:target`, `:empty`, `:not()`).  

4. **Apply pseudo-elements to style specific parts of elements.**  
   *Guidance:* Students should be able to use pseudo-elements like `::before`, `::after`, `::first-letter`, `::first-line`, `::selection`, `::marker`, and `::placeholder`. They should understand how to generate content with `::before` and `::after` using the `content` property and how to style these pseudo-elements.  

5. **Combine selectors to create complex targeting rules.**  
   *Guidance:* Students should be able to use combinators like descendant (space), child (>), adjacent sibling (+), and general sibling (~) to create complex selectors. They should understand how to combine different types of selectors to target specific elements efficiently and maintain specificity control.  

#### **Topic 2: Specificity and Cascade**  
Students will be assessed on their ability to:  
1. **Calculate and compare CSS specificity.**  
   *Guidance:* Students should be able to calculate specificity by counting ID selectors, class selectors, and element selectors. They should understand that inline styles have higher specificity than regular selectors and that `!important` overrides normal specificity. They should be able to predict which styles will be applied when multiple rules target the same element.  

2. **Understand and apply the cascade order in CSS.**  
   *Guidance:* Students should understand that the cascade determines which CSS rules are applied when multiple rules target the same element. They should be able to explain the three main factors: importance, specificity, and source order. They should understand how later rules with equal specificity override earlier ones.  

3. **Use the !important declaration and understand its implications.**  
   *Guidance:* Students should be able to use `!important` to override normal specificity. They should understand that `!important` should be used sparingly as it can make debugging difficult and can lead to specificity wars. They should understand how to override `!important` declarations and when their use is justified.  

4. **Apply inheritance to reduce CSS code duplication.**  
   *Guidance:* Students should understand that some properties are inherited from parent elements to child elements. They should be able to identify which properties are inherited (e.g., font-family, color, text-align) and which are not (e.g., border, margin, padding). They should understand how to use inheritance effectively to reduce code duplication.  

5. **Use the :where() and :is() pseudo-class functions to manage specificity.**  
   *Guidance:* Students should be able to use `:where()` and `:is()` to group selectors and control specificity. They should understand that `:where()` has zero specificity while `:is()` takes the specificity of the most specific selector in its argument list. They should understand how these functions can be used to create more maintainable CSS.  

---

### **Unit 6: Positioning and Display**  
**Description:** Controlling element placement and flow in documents.  

#### **Topic 1: Display Properties**  
Students will be assessed on their ability to:  
1. **Differentiate between block, inline, and inline-block display values.**  
   *Guidance:* Students should understand that block elements (e.g., `div`, `p`) take up the full width available and start on a new line, inline elements (e.g., `span`, `a`) only take up as much width as necessary and do not start on a new line, and inline-block elements flow like inline elements but can have block properties like width and height. They should be able to change the display value of elements using the `display` property.  

2. **Use display: none and visibility: hidden to hide elements.**  
   *Guidance:* Students should understand that `display: none` removes an element from the document flow entirely (it takes up no space), while `visibility: hidden` makes an element invisible but it still takes up space. They should know when to use each property and how they affect accessibility and screen readers.  

3. **Apply table-related display values.**  
   *Guidance:* Students should be able to use `table`, `table-row`, `table-cell`, `table-column`, `table-column-group`, `table-header-group`, `table-footer-group`, `table-caption`, and `inline-table` display values. They should understand how these values can be used to create table-like layouts without using HTML table elements.  

4. **Use display: contents to remove boxes while preserving content.**  
   *Guidance:* Students should understand that `display: contents` makes an element disappear visually, but its child elements remain and behave as if the parent element was still there. They should understand use cases for this property, such as simplifying CSS grid structures or improving accessibility.  

5. **Apply flex and grid display values.**  
   *Guidance:* Students should be able to use `display: flex` to create flex containers and `display: grid` to create grid containers. They should understand the basic differences between these layout systems and when to use each one. They should also understand how inline flex (`inline-flex`) and inline grid (`inline-grid`) differ from their block-level counterparts.  

#### **Topic 2: Positioning Schemes**  
Students will be assessed on their ability to:  
1. **Understand and apply static positioning.**  
   *Guidance:* Students should understand that static positioning is the default positioning scheme, where elements are positioned according to the normal flow of the document. They should understand that static positioned elements are not affected by top, right, bottom, or left properties.  

2. **Use relative positioning to offset elements from their normal position.**  
   *Guidance:* Students should be able to use `position: relative` to position an element relative to its normal position in the document flow. They should understand that the space the element originally occupied is preserved, and how to use the top, right, bottom, and left properties to offset the element.  

3. **Apply absolute positioning to remove elements from the normal flow.**  
   *Guidance:* Students should be able to use `position: absolute` to position an element relative to its nearest positioned ancestor (or the viewport if no positioned ancestor exists). They should understand that absolutely positioned elements are removed from the normal flow and do not affect other elements.  

4. **Use fixed positioning to create elements that stay in the same position relative to the viewport.**  
   *Guidance:* Students should be able to use `position: fixed` to position an element relative to the viewport. They should understand that fixed positioned elements remain in the same position even when the page is scrolled. They should understand common use cases like sticky headers, footers, and navigation menus.  

5. **Apply sticky positioning to create elements that toggle between relative and fixed positioning.**  
   *Guidance:* Students should be able to use `position: sticky` to create elements that behave like relatively positioned elements until they reach a specific scroll position, at which point they behave like fixed positioned elements. They should understand how to use the top, right, bottom, and left properties to determine when the element becomes "stuck."  

#### **Topic 3: Stacking Context and Overflow**  
Students will be assessed on their ability to:  
1. **Control the stacking order of elements using z-index.**  
   *Guidance:* Students should understand that `z-index` controls the stacking order of positioned elements on the z-axis (the axis that comes out of the screen). They should understand that `z-index` only works on positioned elements (elements with position value other than static) and how higher values appear in front of lower values. They should also understand how stacking contexts are formed.  

2. **Create and manage stacking contexts.**  
   *Guidance:* Students should understand that a stacking context is formed by elements with certain properties, including `position` with values other than static and `z-index` other than auto, `opacity` less than 1, `transform`, `filter`, and others. They should understand how elements within a stacking context are stacked relative to each other but not to elements outside the context.  

3. **Control overflow behavior with CSS.**  
   *Guidance:* Students should be able to use `overflow`, `overflow-x`, and `overflow-y` properties with values like `visible`, `hidden`, `scroll`, and `auto`. They should understand how these properties control what happens when content overflows its container's box.  

4. **Apply CSS clipping and masking to elements.**  
   *Guidance:* Students should be able to use the `clip` property (for absolutely positioned elements) and `clip-path` property (for any element) to control which parts of an element are visible. They should understand how to create different clipping shapes using basic shapes (circle, ellipse, inset, polygon) and SVG paths.  

5. **Use the pointer-events property to control element interactivity.**  
   *Guidance:* Students should be able to use the `pointer-events` property with values like `auto`, `none`, `visiblePainted`, `visibleFill`, `visibleStroke`, `visible`, `painted`, `fill`, `stroke`, and `all`. They should understand how this property controls whether an element can be the target of mouse events and how it can be used to create click-through effects or disable interactivity.  

---

### **Unit 7: Flexbox Layout**  
**Description:** Creating flexible, responsive layouts using Flexbox.  

#### **Topic 1: Flex Container**  
Students will be assessed on their ability to:  
1. **Create a flex container and understand its properties.**  
   *Guidance:* Students should be able to use `display: flex` to create a flex container. They should understand that this makes all direct children of the container flex items and establishes a flex formatting context. They should understand how flex containers differ from block containers in terms of behavior and layout.  

2. **Control the direction of flex items using flex-direction.**  
   *Guidance:* Students should be able to use `flex-direction` with values `row` (default), `row-reverse`, `column`, and `column-reverse`. They should understand how this property controls the main axis and the direction in which flex items are placed in the flex container.  

3. **Manage flex line wrapping with flex-wrap.**  
   *Guidance:* Students should be able to use `flex-wrap` with values `nowrap` (default), `wrap`, and `wrap-reverse`. They should understand how this property controls whether flex items are forced onto one line or can wrap onto multiple lines. They should also understand how this affects the behavior of the flex container.  

4. **Use the flex-flow shorthand property.**  
   *Guidance:* Students should be able to use the `flex-flow` shorthand property to set both `flex-direction` and `flex-wrap` in a single declaration. They should understand the syntax and how to use it effectively to reduce code duplication.  

5. **Control the alignment of flex items along the main axis.**  
   *Guidance:* Students should be able to use `justify-content` with values `flex-start` (default), `flex-end`, `center`, `space-between`, `space-around`, and `space-evenly`. They should understand how this property aligns flex items along the main axis and distributes extra space between or around items.  

6. **Control the alignment of flex items along the cross axis.**  
   *Guidance:* Students should be able to use `align-items` with values `stretch` (default), `flex-start`, `flex-end`, `center`, and `baseline`. They should understand how this property aligns flex items along the cross axis and how it affects the size of flex items.  

7. **Control the alignment of flex lines using align-content.**  
   *Guidance:* Students should be able to use `align-content` with values `stretch` (default), `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, and `space-evenly`. They should understand that this property only has an effect when there are multiple lines of flex items (when `flex-wrap: wrap` is applied) and how it aligns these lines along the cross axis.  

8. **Control gaps between flex items using gap, row-gap, and column-gap.**  
   *Guidance:* Students should be able to use `gap`, `row-gap`, and `column-gap` properties to create gutters between flex items. They should understand how these properties provide a more intuitive way to control spacing than using margins and how they affect the layout of flex containers.  

#### **Topic 2: Flex Items**  
Students will be assessed on their ability to:  
1. **Control the flexibility of flex items using flex-grow, flex-shrink, and flex-basis.**  
   *Guidance:* Students should be able to use `flex-grow` to control how much a flex item will grow relative to the rest of the flex items when there is extra space available. They should be able to use `flex-shrink` to control how much a flex item will shrink relative to the rest of the flex items when there is not enough space. They should be able to use `flex-basis` to set the initial main size of a flex item before free space is distributed.  

2. **Use the flex shorthand property effectively.**  
   *Guidance:* Students should be able to use the `flex` shorthand property to set `flex-grow`, `flex-shrink`, and `flex-basis` in a single declaration. They should understand common values like `flex: 1`, `flex: 0 1 auto`, `flex: 0 0 auto`, and `flex: auto` and how they affect the behavior of flex items.  

3. **Control the order of flex items.**  
   *Guidance:* Students should be able to use the `order` property to control the order in which flex items appear in the flex container. They should understand that by default, flex items are displayed in the order they appear in the source code, but this can be changed using the `order` property. They should understand the implications for accessibility and document structure.  

4. **Override alignment for individual flex items using align-self.**  
   *Guidance:* Students should be able to use `align-self` with values `auto` (default), `stretch`, `flex-start`, `flex-end`, `center`, and `baseline`. They should understand how this property allows individual flex items to override the `align-items` value set on the flex container.  

5. **Create common flexbox patterns and layouts.**  
   *Guidance:* Students should be able to create common flexbox patterns including navigation bars, card layouts, centering elements, vertically aligned content, and holy grail layouts. They should understand how to combine flex container and flex item properties to achieve these layouts and how to make them responsive.  

---

### **Unit 8: Grid Layout**  
**Description:** Building complex two-dimensional layouts with CSS Grid.  

#### **Topic 1: Grid Container**  
Students will be assessed on their ability to:  
1. **Create a grid container and understand its properties.**  
   *Guidance:* Students should be able to use `display: grid` to create a grid container. They should understand that this makes all direct children of the container grid items and establishes a grid formatting context. They should understand how grid containers differ from block and flex containers in terms of behavior and layout.  

2. **Define explicit grid tracks using grid-template-columns and grid-template-rows.**  
   *Guidance:* Students should be able to use `grid-template-columns` and `grid-template-rows` to define the size and number of columns and rows in an explicit grid. They should understand how to use length values, percentages, fractional units (fr), and functions like `minmax()` and `repeat()` to define track sizes.  

3. **Create named grid areas using grid-template-areas.**  
   *Guidance:* Students should be able to use `grid-template-areas` to create named grid areas and assign grid items to these areas. They should understand how to create a visual representation of the grid layout using ASCII art and how to assign grid items to these areas using the `grid-area` property.  

4. **Define implicit grid tracks using grid-auto-columns and grid-auto-rows.**  
   *Guidance:* Students should be able to use `grid-auto-columns` and `grid-auto-rows` to define the size of implicit grid tracks (tracks that are automatically created when there are more grid items than explicit tracks). They should understand how implicit grids work and how to control their behavior.  

5. **Control the flow of grid items using grid-auto-flow.**  
   *Guidance:* Students should be able to use `grid-auto-flow` with values `row` (default), `column`, `row dense`, and `column dense`. They should understand how this property controls the placement algorithm for grid items that have not been explicitly placed on the grid.  

6. **Control gaps between grid tracks using gap, row-gap, and column-gap.**  
   *Guidance:* Students should be able to use `gap`, `row-gap`, and `column-gap` properties to create gutters between grid tracks. They should understand how these properties provide a more intuitive way to control spacing than using margins and how they affect the layout of grid containers.  

7. **Align grid items within grid areas using justify-items and align-items.**  
   *Guidance:* Students should be able to use `justify-items` (start, end, center, stretch) to align grid items along the inline (row) axis and `align-items` (start, end, center, stretch) to align grid items along the block (column) axis. They should understand how these properties affect the placement of grid items within their grid areas.  

8. **Align the entire grid within the grid container using justify-content and align-content.**  
   *Guidance:* Students should be able to use `justify-content` (start, end, center, stretch, space-around, space-between, space-evenly) to align the entire grid along the inline (row) axis and `align-content` (start, end, center, stretch, space-around, space-between, space-evenly) to align the entire grid along the block (column) axis. They should understand how these properties affect the placement of the grid within the grid container when the grid is smaller than the container.  

#### **Topic 2: Grid Items**  
Students will be assessed on their ability to:  
1. **Place grid items using line-based placement.**  
   *Guidance:* Students should be able to use `grid-column-start`, `grid-column-end`, `grid-row-start`, and `grid-row-end` to place grid items based on grid line numbers. They should understand how to use the `span` keyword to specify how many tracks a grid item should span. They should also be able to use the shorthand properties `grid-column` and `grid-row`.  

2. **Place grid items using named grid lines.**  
   *Guidance:* Students should be able to define named grid lines in `grid-template-columns` and `grid-template-rows` (e.g., `[col-start] 1fr [col-end]`) and then use these names to place grid items. They should understand how named grid lines make CSS Grid code more readable and maintainable.  

3. **Assign grid items to named grid areas.**  
   *Guidance:* Students should be able to use the `grid-area` property to assign grid items to named grid areas defined in `grid-template-areas`. They should understand how this creates a visual layout system and makes it easier to understand the structure of a grid layout.  

4. **Override alignment for individual grid items using justify-self and align-self.**  
   *Guidance:* Students should be able to use `justify-self` (start, end, center, stretch) to align an individual grid item along the inline (row) axis and `align-self` (start, end, center, stretch) to align an individual grid item along the block (column) axis. They should understand how these properties allow individual grid items to override the `justify-items` and `align-items` values set on the grid container.  

5. **Create responsive grid layouts.**  
   *Guidance:* Students should be able to create responsive grid layouts using techniques like `auto-fill` and `auto-fit` with `minmax()` to create grids that automatically adjust to the available space. They should understand how to use media queries to change grid layouts at different breakpoints and how to create truly responsive designs with CSS Grid.  

---

### **Unit 9: Responsive Design and Media Queries**  
**Description:** Adapting layouts for different screen sizes and devices.  

#### **Topic 1: Viewport and Fluid Layouts**  
Students will be assessed on their ability to:  
1. **Use the viewport meta tag to control the viewport on mobile devices.**  
   *Guidance:* Students should be able to use `<meta name="viewport" content="width=device-width, initial-scale=1.0">` in the HTML head to control the viewport on mobile devices. They should understand what the viewport is and why it's important for responsive design. They should understand the different properties of the viewport meta tag and their effects.  

2. **Create fluid layouts using relative units.**  
   *Guidance:* Students should be able to use relative units like percentages (%), viewport units (vw, vh, vmin, vmax), and relative font units (em, rem) to create fluid layouts that adapt to different screen sizes. They should understand the differences between these units and when to use each one.  

3. **Apply min-width, max-width, min-height, and max-height constraints.**  
   *Guidance:* Students should be able to use `min-width`, `max-width`, `min-height`, and `max-height` to set constraints on element sizes. They should understand how these properties help create more predictable layouts and prevent elements from becoming too small or too large on different screen sizes.  

4. **Use the calc() function for responsive calculations.**  
   *Guidance:* Students should be able to use the `calc()` function to perform calculations that combine different units (e.g., `calc(100% - 50px)`). They should understand how this function can be used to create more flexible and responsive layouts.  

5. **Create fluid typography that scales with viewport size.**  
   *Guidance:* Students should be able to create fluid typography using viewport units (vw, vh) or the `clamp()` function to ensure text scales appropriately with the viewport size. They should understand how to set minimum and maximum font sizes to maintain readability.  

#### **Topic 2: Media Queries**  
Students will be assessed on their ability to:  
1. **Write basic media queries for different screen sizes.**  
   *Guidance:* Students should be able to write media queries using `@media` with `min-width`, `max-width`, `min-height`, and `max-height` to apply different styles at different screen sizes. They should understand how to use breakpoints to create responsive layouts that adapt to common device sizes.  

2. **Use media queries for different device features.**  
   *Guidance:* Students should be able to write media queries for different device features like orientation (`orientation: portrait` or `orientation: landscape`), resolution (`min-resolution: 300dpi`), hover capability (`hover: hover`), pointer type (`pointer: fine` or `pointer: coarse`), and more. They should understand how these features can be used to create more tailored user experiences.  

3. **Apply media queries for user preferences.**  
   *Guidance:* Students should be able to write media queries for user preferences like `prefers-reduced-motion` (reduce, no-preference), `prefers-color-scheme` (light, dark), `prefers-contrast` (more, less, no-preference), and `prefers-reduced-data` (reduce, no-preference). They should understand how these preferences can be used to create more accessible and user-friendly designs.  

4. **Use logical operators in media queries.**  
   *Guidance:* Students should be able to use logical operators like `and`, `not`, `or` (comma), and `only` in media queries to create more complex conditions. They should understand how to combine multiple media features in a single media query and how to exclude certain devices or browsers.  

5. **Organize media queries efficiently in CSS.**  
   *Guidance:* Students should understand different approaches to organizing media queries in CSS, including inline media queries (within rules), grouped media queries (at the end of the stylesheet), and mobile-first vs. desktop-first approaches. They should understand the pros and cons of each approach and be able to choose the most appropriate one for a given project.  

#### **Topic 3: Modern Responsive Techniques**  
Students will be assessed on their ability to:  
1. **Use aspect-ratio to maintain element proportions.**  
   *Guidance:* Students should be able to use the `aspect-ratio` property to control the aspect ratio of elements. They should understand how this property is particularly useful for embedded content like videos, images, and iframes to maintain their proportions across different screen sizes.  

2. **Implement container queries for component-level responsiveness.**  
   *Guidance:* Students should be able to use container queries (`@container`) to apply styles based on the size of a component's container rather than the viewport. They should understand how to define container elements using `container-type` and `container-name`, and how to write container queries that target these containers.  

3. **Use contain-intrinsic-size for more predictable container behavior.**  
   *Guidance:* Students should be able to use `contain-intrinsic-size` to specify the size of an element if it is affected by size containment. They should understand how this property helps prevent layout shifts when content is loaded asynchronously and improves the performance of container queries.  

4. **Apply responsive images using the picture element and srcset attribute.**  
   *Guidance:* Students should be able to use the `<picture>` element and the `srcset` attribute to serve different images based on screen size, resolution, or other conditions. They should understand how to use the `sizes` attribute to specify different image sizes for different layout conditions and how to create art direction with the `<picture>` element.  

5. **Create responsive iframes and embedded content.**  
   *Guidance:* Students should be able to create responsive iframes and embedded content using techniques like intrinsic aspect ratios, the `aspect-ratio` property, and responsive container sizing. They should understand how to ensure that embedded content like videos, maps, and social media posts adapt to different screen sizes.  

---

### **Unit 10: Transforms, Transitions, and Animations**  
**Description:** Adding motion and interactivity to web pages.  

#### **Topic 1: 2D/3D Transforms**  
Students will be assessed on their ability to:  
1. **Apply 2D transforms to elements.**  
   *Guidance:* Students should be able to use the `transform` property with functions like `translate()`, `translateX()`, `translateY()`, `scale()`, `scaleX()`, `scaleY()`, `rotate()`, `rotateX()`, `rotateY()`, `skew()`, `skewX()`, and `skewY()` to apply 2D transforms to elements. They should understand how these functions affect the position, size, and shape of elements.  

2. **Apply 3D transforms to elements.**  
   *Guidance:* Students should be able to use the `transform` property with functions like `translate3d()`, `translateZ()`, `scale3d()`, `scaleZ()`, `rotate3d()`, `rotateX()`, `rotateY()`, and `rotateZ()` to apply 3D transforms to elements. They should understand how these functions create a sense of depth and perspective.  

3. **Control the perspective of 3D transforms.**  
   *Guidance:* Students should be able to use the `perspective` property to set the perspective for 3D transforms on an element's children. They should understand how this property affects the appearance of 3D transforms and how to use the `perspective()` function to apply perspective to individual elements.  

4. **Control the transform style and backface visibility.**  
   *Guidance:* Students should be able to use the `transform-style` property with values `flat` (default) and `preserve-3d` to control whether child elements are positioned in 3D space or flattened. They should be able to use the `backface-visibility` property with values `visible` (default) and `hidden` to control whether the back face of an element is visible when transformed.  

5. **Use the transform-origin property to control the transform origin.**  
   *Guidance:* Students should be able to use the `transform-origin` property to change the origin point for transforms. They should understand how this property affects the behavior of transforms like rotation and scaling and how to use keywords (top, bottom, left, right, center) and length/percentage values to set the transform origin.  

#### **Topic 2: Transitions**  
Students will be assessed on their ability to:  
1. **Apply basic transitions to CSS properties.**  
   *Guidance:* Students should be able to use the `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay` properties to create smooth transitions between different states of an element. They should understand how these properties work together to create transition effects.  

2. **Use the transition shorthand property.**  
   *Guidance:* Students should be able to use the `transition` shorthand property to set all transition properties in a single declaration. They should understand the syntax and how to specify multiple transitions for different properties.  

3. **Control the timing function of transitions.**  
   *Guidance:* Students should be able to use the `transition-timing-function` property with predefined values like `ease`, `linear`, `ease-in`, `ease-out`, and `ease-in-out`, as well as custom cubic-bezier functions. They should understand how timing functions affect the speed and progression of transitions.  

4. **Apply transitions to multiple properties.**  
   *Guidance:* Students should be able to apply transitions to multiple properties by either using a comma-separated list in the `transition` shorthand property or by using the `all` value for `transition-property`. They should understand how to create complex transition effects by combining multiple property transitions.  

5. **Create hover and focus effects with transitions.**  
   *Guidance:* Students should be able to create hover and focus effects using transitions in combination with pseudo-classes like `:hover` and `:focus`. They should understand how to create smooth, interactive effects that enhance user experience without being distracting.  

#### **Topic 3: Animations**  
Students will be assessed on their ability to:  
1. **Create keyframe animations with @keyframes.**  
   *Guidance:* Students should be able to use the `@keyframes` rule to define keyframes for animations. They should understand how to use `from` and `to` keywords or percentage values (0%, 50%, 100%) to define the styles at different points in the animation. They should understand how to name animations and reference them in other CSS rules.  

2. **Apply animations to elements using animation properties.**  
   *Guidance:* Students should be able to use `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state` to control how animations are applied to elements. They should understand how these properties work together to create animation effects.  

3. **Use the animation shorthand property.**  
   *Guidance:* Students should be able to use the `animation` shorthand property to set all animation properties in a single declaration. They should understand the syntax and how to specify multiple animations for an element.  

4. **Control the direction and iteration of animations.**  
   *Guidance:* Students should be able to use `animation-direction` with values `normal`, `reverse`, `alternate`, and `alternate-reverse` to control the direction of animations. They should be able to use `animation-iteration-count` with numeric values or the `infinite` keyword to control how many times an animation repeats.  

5. **Create complex animation sequences and effects.**  
   *Guidance:* Students should be able to create complex animation sequences by combining multiple animations, using different timing functions, and controlling the fill mode and play state. They should understand how to create effects like fading, sliding, bouncing, and more complex motion paths.  

---

### **Unit 11: CSS Architecture and Best Practices**  
**Description:** Writing maintainable, scalable, and efficient CSS.  

#### **Topic 1: CSS Methodologies**  
Students will be assessed on their ability to:  
1. **Apply BEM (Block, Element, Modifier) naming conventions.**  
   *Guidance:* Students should be able to use BEM naming conventions to create clear, maintainable class names. They should understand that BEM consists of blocks (standalone entities), elements (parts of blocks that have no standalone meaning), and modifiers (flags that change appearance or behavior). They should be able to write class names like `.block`, `.block__element`, and `.block--modifier`.  

2. **Organize CSS using OOCSS (Object-Oriented CSS) principles.**  
   *Guidance:* Students should be able to apply OOCSS principles to create reusable, maintainable CSS. They should understand the core concepts of separating structure and skin, separating container and content, and creating objects that can be reused across a website. They should be able to create CSS objects that are flexible and can be combined in different ways.  

3. **Structure CSS using SMACSS (Scalable and Modular Architecture for CSS) principles.**  
   *Guidance:* Students should be able to structure CSS using SMACSS categories: base rules, layout rules, module rules, state rules, and theme rules. They should understand how to organize CSS files and class names according to these categories and how this approach improves maintainability and scalability.  

4. **Apply Atomic CSS or Utility-First CSS approaches.**  
   *Guidance:* Students should be able to understand and apply Atomic CSS or Utility-First CSS approaches, where classes are small, single-purpose utilities that can be combined to create complex designs. They should understand the benefits of this approach (consistency, reusability, small CSS size) and the potential drawbacks (verbose HTML, less semantic class names).  

5. **Create a CSS architecture that combines multiple methodologies.**  
   *Guidance:* Students should be able to create a CSS architecture that combines elements of different methodologies to suit the needs of a specific project. They should understand how to evaluate the requirements of a project and choose the most appropriate methodologies and organizational strategies.  

#### **Topic 2: CSS Organization and File Structure**  
Students will be assessed on their ability to:  
1. **Organize CSS files using a logical structure.**  
   *Guidance:* Students should be able to organize CSS files using a logical structure that suits the project. They should understand common approaches like organizing by component (e.g., `_header.css`, `_navigation.css`), by layer (e.g., `_base.css`, `_layout.css`, `_components.css`), or by methodology (e.g., SMACSS categories). They should understand the pros and cons of each approach.  

2. **Use CSS preprocessor features for organization.**  
   *Guidance:* Students should be able to use CSS preprocessor features like variables, mixins, functions, and nesting to organize CSS more effectively. They should understand how to split CSS into multiple files and use import statements to combine them. They should understand how preprocessors can improve organization and maintainability.  

3. **Implement a CSS methodology for large-scale projects.**  
   *Guidance:* Students should be able to implement a CSS methodology that scales for large projects with multiple developers. They should understand how to create naming conventions, file structures, and coding standards that ensure consistency and prevent conflicts in large codebases.  

4. **Document CSS code effectively.**  
   *Guidance:* Students should be able to document CSS code using comments, style guides, and documentation tools. They should understand what information should be documented (e.g., component usage, variable meanings, layout patterns) and how to format documentation for maximum clarity and usefulness.  

5. **Create and maintain a pattern library or design system.**  
   *Guidance:* Students should be able to create and maintain a pattern library or design system that documents the UI components and design patterns used in a project. They should understand the benefits of having a centralized resource for design elements and how it improves consistency and efficiency in development.  

#### **Topic 3: Performance and Optimization**  
Students will be assessed on their ability to:  
1. **Minimize CSS file size.**  
   *Guidance:* Students should be able to use techniques like minification (removing whitespace, comments, and unnecessary characters), compression (using gzip or Brotli), and shorthand properties to reduce CSS file size. They should understand how smaller file sizes improve page load times and user experience.  

2. **Reduce repaints and reflows.**  
   *Guidance:* Students should be able to understand what causes repaints (changes to element appearance that don't affect layout) and reflows (changes to element dimensions that affect layout). They should be able to use CSS properties and techniques that minimize these expensive operations, such as using `transform` and `opacity` for animations instead of properties that trigger layout.  

3. **Use CSS containment for performance optimization.**  
   *Guidance:* Students should be able to use CSS containment properties like `contain`, `content-visibility`, and `contain-intrinsic-size` to optimize rendering performance. They should understand how these properties isolate parts of the page, allowing browsers to optimize rendering by limiting the scope of style calculations, layout, and painting.  

4. **Optimize CSS selectors for performance.**  
   *Guidance:* Students should be able to write efficient CSS selectors that minimize the work browsers need to do to apply styles. They should understand how selector matching works and how to avoid overly complex selectors that can slow down rendering. They should understand the performance implications of different selector types.  

5. **Implement critical CSS for faster perceived page loads.**  
   *Guidance:* Students should be able to identify and extract critical CSS (the CSS needed to render the above-the-fold content) and inline it in the HTML head. They should understand how this technique improves perceived page load times by allowing the browser to render the visible content of the page more quickly.  

---

### **Unit 12: Advanced and Emerging CSS Features**  
**Description:** Cutting-edge CSS features for future-proof skills.  

#### **Topic 1: CSS Houdini**  
Students will be assessed on their ability to:  
1. **Understand the concept and purpose of CSS Houdini.**  
   *Guidance:* Students should be able to explain that CSS Houdini is a set of APIs that expose parts of the CSS rendering engine to JavaScript, allowing developers to create custom CSS features. They should understand the different Houdini APIs (Paint API, Layout API, Animation API, Properties and Values API, Typed OM) and their purposes.  

2. **Use the @property rule for custom properties.**  
   *Guidance:* Students should be able to use the `@property` rule to register custom properties (CSS variables) with type information, initial values, and inheritance behavior. They should understand how this enables better type checking, default values, and animation of custom properties.  

3. **Use the Paint API to create custom visual effects.**  
   *Guidance:* Students should be able to use the Paint API to create custom visual effects that can be applied with CSS. They should understand how to register a paint worklet, define a paint function, and apply it using the `paint()` function in CSS. They should understand the capabilities and limitations of the Paint API.  

4. **Understand the Layout API and Animation API.**  
   *Guidance:* Students should be able to explain the purpose of the Layout API (for creating custom layout algorithms) and the Animation API (for creating custom animation effects). They should understand the potential use cases for these APIs and their current level of browser support.  

5. **Use the Typed OM for more efficient CSS manipulation.**  
   *Guidance:* Students should be able to understand the Typed OM (Typed Object Model) and how it provides a more efficient way to manipulate CSS values with JavaScript. They should understand how it represents CSS values as typed JavaScript objects rather than strings, allowing for more efficient and type-safe manipulation.  

#### **Topic 2: Cascade Layers**  
Students will be assessed on their ability to:  
1. **Understand the concept and purpose of cascade layers.**  
   *Guidance:* Students should be able to explain that cascade layers (`@layer`) allow developers to group CSS rules into layers that have a specific order in the cascade. They should understand how this helps manage specificity conflicts and makes CSS more maintainable, especially when integrating third-party CSS.  

2. **Create and use cascade layers.**  
   *Guidance:* Students should be able to create cascade layers using the `@layer` rule and assign rules to these layers. They should understand how to define the order of layers and how this affects which rules take precedence when there are conflicts.  

3. **Manage specificity conflicts with cascade layers.**  
   *Guidance:* Students should be able to use cascade layers to manage specificity conflicts between different parts of a stylesheet, such as base styles, component styles, and utility styles. They should understand how cascade layers provide a more structured approach to managing the cascade than relying solely on specificity.  

4. **Integrate third-party CSS using cascade layers.**  
   *Guidance:* Students should be able to use cascade layers to integrate third-party CSS (like frameworks or libraries) with custom CSS in a controlled way. They should understand how to ensure that custom styles can override third-party styles when needed without resorting to high specificity or `!important`.  

5. **Combine cascade layers with other CSS features.**  
   *Guidance:* Students should be able to combine cascade layers with other CSS features like custom properties, container queries, and logical properties. They should understand how cascade layers fit into a modern CSS architecture and how they complement other features.  

#### **Topic 3: Logical Properties**  
Students will be assessed on their ability to:  
1. **Understand the concept and purpose of logical properties.**  
   *Guidance:* Students should be able to explain that logical properties are CSS properties that control layout based on the writing direction of the document (e.g., left-to-right vs. right-to-left, or horizontal vs. vertical writing modes). They should understand how logical properties make it easier to create internationalized websites that adapt to different writing modes.  

2. **Use logical properties for margins, padding, and borders.**  
   *Guidance:* Students should be able to use logical properties like `margin-inline-start`, `margin-inline-end`, `margin-block-start`, `margin-block-end`, and their equivalents for padding and borders. They should understand how these properties adapt to the writing direction of the document.  

3. **Use logical properties for sizing and positioning.**  
   *Guidance:* Students should be able to use logical properties like `inline-size`, `block-size`, `min-inline-size`, `max-inline-size`, `min-block-size`, `max-block-size`, `inset-inline-start`, `inset-inline-end`, `inset-block-start`, and `inset-block-end`. They should understand how these properties adapt to the writing direction and writing mode of the document.  

4. **Use logical properties for text alignment and floating.**  
   *Guidance:* Students should be able to use logical properties like `text-align-start`, `text-align-end`, `float-inline-start`, `float-inline-end`, `clear-inline-start`, and `clear-inline-end`. They should understand how these properties adapt to the writing direction of the document.  

5. **Create layouts that adapt to different writing modes.**  
   *Guidance:* Students should be able to create layouts that adapt to different writing modes (horizontal left-to-right, horizontal right-to-left, vertical) using logical properties. They should understand how to test these layouts and ensure they work correctly in different writing modes.  

#### **Topic 4: Color Functions**  
Students will be assessed on their ability to:  
1. **Use the color-mix() function to mix colors.**  
   *Guidance:* Students should be able to use the `color-mix()` function to mix two colors together in a specified proportion. They should understand the syntax of the function, including how to specify the color space and the mixing method. They should understand how this function can be used for theming and creating color variations.  

2. **Use the color-contrast() function to ensure text readability.**  
   *Guidance:* Students should be able to use the `color-contrast()` function to automatically select a color with sufficient contrast against a background color. They should understand the syntax of the function and how it can be used to ensure text readability and meet accessibility standards.  

3. **Use relative color syntax to modify colors.**  
   *Guidance:* Students should be able to use relative color syntax to modify existing colors by adjusting their components (e.g., lightness, saturation, hue). They should understand the syntax of relative color syntax and how it can be used to create color variations and themes.  

4. **Use lab(), lch(), oklab(), and oklch() color functions.**  
   *Guidance:* Students should be able to use the `lab()`, `lch()`, `oklab()`, and `oklch()` color functions to specify colors in perceptually uniform color spaces. They should understand the advantages of these color spaces over RGB and HSL, particularly for creating consistent color gradients and ensuring perceptual uniformity.  

5. **Create dynamic color themes using color functions.**  
   *Guidance:* Students should be able to create dynamic color themes using color functions and CSS custom properties. They should understand how to define a set of base colors and use color functions to derive variations and harmonies. They should understand how to create themes that can be easily customized and adapted.  

#### **Topic 5: Viewport Units**  
Students will be assessed on their ability to:  
1. **Use traditional viewport units (vw, vh, vmin, vmax).**  
   *Guidance:* Students should be able to use traditional viewport units (vw, vh, vmin, vmax) to create responsive designs that adapt to the viewport size. They should understand how these units work and their limitations, particularly on mobile devices where the viewport size can change due to the appearance or disappearance of the browser UI.  

2. **Use new viewport units (dvh, svh, lvh, dvw, svw, lvw).**  
   *Guidance:* Students should be able to use new viewport units (dvh, svh, lvh, dvw, svw, lvw) that address the limitations of traditional viewport units on mobile devices. They should understand the differences between these units: dynamic viewport units (dvh, dvw) account for browser UI changes, small viewport units (svh, svw) represent the smallest possible viewport, and large viewport units (lvh, lvw) represent the largest possible viewport.  

3. **Create responsive layouts using viewport units.**  
   *Guidance:* Students should be able to create responsive layouts using a combination of traditional and new viewport units. They should understand how to use these units for sizing elements, creating fluid typography, and implementing responsive spacing.  

4. **Address common issues with viewport units on mobile devices.**  
   *Guidance:* Students should be able to address common issues with viewport units on mobile devices, such as layout shifts when the browser UI appears or disappears. They should understand how to use new viewport units to create more stable layouts that don't shift unexpectedly.  

5. **Combine viewport units with other CSS features for responsive design.**  
   *Guidance:* Students should be able to combine viewport units with other CSS features like media queries, container queries, and CSS grid/flexbox to create truly responsive designs. They should understand how to use viewport units as part of a comprehensive responsive design strategy.  

#### **Topic 6: Scroll-Driven Animations**  
Students will be assessed on their ability to:  
1. **Understand the concept and purpose of scroll-driven animations.**  
   *Guidance:* Students should be able to explain that scroll-driven animations are animations that are directly tied to the scroll position of a document or container. They should understand how these animations can be used to create engaging, interactive experiences that respond to user scrolling.  

2. **Use @scroll-timeline to define scroll-based animations.**  
   *Guidance:* Students should be able to use the `@scroll-timeline` rule to define a timeline that is driven by the scroll position of a scroll container. They should understand how to specify the scroll container, the scroll axis, and the scroll range that controls the animation.  

3. **Use animation-timeline to connect animations to scroll timelines.**  
   *Guidance:* Students should be able to use the `animation-timeline` property to connect CSS animations to scroll timelines. They should understand how to specify which scroll timeline an animation should follow and how to control the animation's progress based on the scroll position.  

4. **Create parallax effects with scroll-driven animations.**  
   *Guidance:* Students should be able to create parallax effects where background elements move at different speeds than foreground elements as the user scrolls. They should understand how to use scroll-driven animations to control the position, scale, or opacity of elements to create these effects.  

5. **Create reveal effects with scroll-driven animations.**  
   *Guidance:* Students should be able to create reveal effects where elements become visible or transform as the user scrolls to them. They should understand how to use scroll-driven animations to control the opacity, transform, or clip-path of elements to create these effects.  

#### **Topic 7: Anchor Positioning**  
Students will be assessed on their ability to:  
1. **Understand the concept and purpose of anchor positioning.**  
   *Guidance:* Students should be able to explain that anchor positioning allows elements to be positioned relative to other elements (anchors) without requiring a common positioning context. They should understand how this feature simplifies the creation of tooltips, popovers, menus, and other UI elements that need to be positioned relative to other elements.  

2. **Use the anchor() function to position elements relative to anchors.**  
   *Guidance:* Students should be able to use the `anchor()` function to position elements relative to anchor elements. They should understand the syntax of the function, including how to specify the anchor element, the anchor edge, and the fallback position.  

3. **Use the position-anchor property to specify anchor elements.**  
   *Guidance:* Students should be able to use the `position-anchor` property to specify which element an absolutely positioned element should be anchored to. They should understand how to use this property in combination with the `anchor()` function.  

4. **Create tooltips and popovers with anchor positioning.**  
   *Guidance:* Students should be able to create tooltips and popovers that are positioned relative to other elements using anchor positioning. They should understand how to ensure these elements are positioned correctly and remain accessible.  

5. **Create complex positioning relationships with anchor positioning.**  
   *Guidance:* Students should be able to create complex positioning relationships between elements using anchor positioning. They should understand how to position multiple elements relative to the same anchor or create chains of anchored elements.  

#### **Topic 8: CSS Nesting**  
Students will be assessed on their ability to:  
1. **Understand the concept and purpose of CSS nesting.**  
   *Guidance:* Students should be able to explain that CSS nesting allows CSS rules to be nested inside other CSS rules, similar to how nesting works in preprocessors like Sass. They should understand how nesting can make CSS more organized, readable, and maintainable by reducing repetition and clearly showing the relationship between selectors.  

2. **Use basic CSS nesting for related selectors.**  
   *Guidance:* Students should be able to use basic CSS nesting to nest selectors that are related to each other. They should understand how to nest descendant selectors, child selectors, and other combinator selectors within a parent rule.  

3. **Use the & symbol to reference the parent selector in nested rules.**  
   *Guidance:* Students should be able to use the `&` symbol to reference the parent selector in nested rules. They should understand how to use this symbol to create compound selectors, pseudo-classes, and pseudo-elements within nested rules.  

4. **Nest @media and other at-rules within CSS rules.**  
   *Guidance:* Students should be able to nest `@media` and other at-rules within CSS rules. They should understand how this technique keeps related styles together and makes it easier to understand the responsive behavior of a component.  

5. **Create complex component styles using CSS nesting.**  
   *Guidance:* Students should be able to create complex component styles using CSS nesting. They should understand how to structure nested styles for components with multiple states, variants, and child elements. They should understand how nesting can be used to create more maintainable and modular CSS.  

---

## **Final Answer: Is This All the CSS?**

**Yes, this is absolutely all of CSS.** This specification includes:

- **Every CSS property** (including obscure ones like `hanging-punctuation`, `text-emphasis`, `font-variant-alternates`)
- **Every selector, pseudo-class, and pseudo-element** (including experimental ones like `:has()`)
- **Every layout system** (Normal Flow, Floats, Flexbox, Grid, Multi-column, Positioning)
- **Every modern and experimental feature** (Houdini, Container Queries, Cascade Layers, Nesting, Scroll-Driven Animations, Anchor Positioning)
- **Every color system and function** (including Lab, LCH, OKLab, OKLCH, color-mix, color-contrast)
- **Every viewport unit** (including new dynamic viewport units)
- **Every performance optimization technique**
- **Every CSS methodology and architecture approach**
- **Every legacy and deprecated feature** (for maintaining old codebases)
