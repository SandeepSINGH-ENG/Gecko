# Gecko CSS Framework
/*
 * Copyright (c) 2024 [GECKO CSS]
 * 
 * This software is licensed under the MIT License.
 */
 <!-- Introduction -->

Gecko is a lightweight and flexible CSS framework designed to simplify the process of styling web applications. It provides a set of utility classes to handle text colors, background colors, margins, paddings, borders, flexbox layouts, and more. This README provides instructions on how to use the framework.

Installation

To use Gecko CSS Framework, include the Gecko.css file in your HTML document.

```html
<link rel="stylesheet" href="Gecko.css">

Text Colors

Use the following classes to apply text colors:

.fst-txt - Primary text color
.sec-txt - Secondary text color
.trd-txt - Tertiary text color
.fth-txt - Quaternary text color

<!-- Background Colors -->

Use the following classes to apply background colors:

.fst-bg - Primary background color
.sec-bg - Secondary background color
.trd-bg - Tertiary background color
.fth-bg - Quaternary background color

<!-- Container -->

The .container class provides a centered container with a maximum width of 1200px and 90% of the viewport width.

<!-- Flexbox Utilities -->

Gecko provides several flexbox utility classes for creating flexible layouts:

.flex - Applies display: flex;
.flex-nowrap - Prevents wrapping of flex items
.flex-wrap - Allows wrapping of flex items
.flex-space-between - Distributes space between items
.align-items-center - Centers items vertically

<!-- Responsive Flexbox Utilities -->

For small screens (max-width: 600px):

.flex-s-nowrap - Prevents wrapping of flex items
.flex-s-wrap - Allows wrapping of flex items

<!-- Gap -->

Set gaps between flex items using the following classes:

.gap-1 - 0.25rem gap
.gap-2 - 0.5rem gap
.gap-3 - 1rem gap
.gap-4 - 1.5rem gap
.gap-5 - 3rem gap

<!-- Width -->

Use the following classes to set the width of flex items. For large devices:

.wid-1 to .wid-12 - Width from 8.33% to 100%
For small devices (max-width: 600px):

.wid-s-1 to .wid-s-12 - Width from 8.33% to 100%

<!--  Borders -->

Apply borders using the following classes:

.border - 1px border with primary color
.border-dash - Dashed border style
.border-solid - Solid border style
.border-top, .border-left, .border-right, .border-bottom - Apply border to specific sides
.border-primary - Primary border color
.border-secondary - Secondary border color

<!-- Spacing -->

<!-- Margin -->

Set margins using the following classes:

Margin All Sides
.m-1 to .m-5 - Margin from 0.25rem to 3rem
Margin Top
.mt-1 to .mt-5 - Margin-top from 0.25rem to 3rem
Margin Bottom
.mb-1 to .mb-5 - Margin-bottom from 0.25rem to 3rem
Margin Left
.ml-1 to .ml-5 - Margin-left from 0.25rem to 3rem
Margin Right
.mr-1 to .mr-5 - Margin-right from 0.25rem to 3rem
Margin Auto
.m-auto - Margin auto

<!-- Padding -->

Set padding using the following classes:

Padding All Sides
.p-1 to .p-5 - Padding from 0.25rem to 3rem
Padding Top
.pt-1 to .pt-5 - Padding-top from 0.25rem to 3rem
Padding Bottom
.pb-1 to .pb-5 - Padding-bottom from 0.25rem to 3rem
Padding Left
.pl-1 to .pl-5 - Padding-left from 0.25rem to 3rem
Padding Right
.pr-1 to .pr-5 - Padding-right from 0.25rem to 3rem

<!-- Typography -->

Adjust font sizes using the following classes:

.f-1 to .f-10 - Font size from 1rem to 6rem

<!-- Text Alignment -->
Set text alignment using the following classes:

.txt-center - Center align
.txt-right - Right align
.txt-left - Left align

<!-- Shadows -->

Apply box shadow using the .shadow class.

<!-- Border Radius -->

Set border-radius using the following classes:

.round-1 to .round-5 - Border-radius from 0.25rem to 3rem

<!-- Display -->

<!-- Control element display using the following classes: -->

.block - display: block;
.grid - display: grid;
.overflow-hidden - overflow: hidden;

<!-- Additional Utilities -->
.pointer - cursor: pointer;



//This project is licensed under the MIT License.
