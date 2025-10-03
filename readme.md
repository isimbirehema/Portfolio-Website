Portfolio Website - README

1. Responsive Web Design (Fluid Design + Media Queries)

This website is fully responsive without using Flexbox (as required).  
I used separate CSS files for different viewports:

mobile.css
  Applied for screens (≤ 600px).

Reason: This breakpoint supports smartphones, where vertical stacking of elements is needed for readability.  
  - Example: The navigation menu switches to a vertical list, shows stack in a single column.

Tablet.css
Applied for screens 601px – 1024px  
  - Reason: This range supports tablets in portrait and landscape mode.  
  - Example: Navigation shows inline links, shows are displayed side-by-side with enough spacing.

laptop.css 
  Applied for screens ≥ 1025px
  - Reason: Larger screens allow more horizontal space, so a multi-column layout is used.  
  - Example: Highlights use horizontal flex-style alignment (without flexbox), navigation is centered across the screen.

This separation ensures each device type has an optimized design

2. Linear Gradient and Angle Gradient Usage

I used linear gradients in multiple areas for styling:

style.css
body {
    background: linear-gradient(135deg, #003C71, #00509e);
  }

Creates a 135° angled gradient from deep blue to lighter blue, giving a modern visual effect.

Header background (style.css & laptop.css):

 header {
  background: linear-gradient(90deg, #9ac6ec, #11314d);
}

A 90° horizontal gradient was applied in the header to visually separate navigation from the content.

Color Scheme

I created a color scheme using Adobe Color.
1. Primary Color: #003C71 (Deep Navy Blue)
2. Secondary Color: #00509e (Medium Blue)
3. Accent Color: #FFD369 (Gold/Yellow highlight)


Supporting Colors:

1. White (#FFFFFF) for text contrast
2. Neutral grays (#f4f6f8, #333) for backgrounds and readability

Why this scheme?
Blue tones represent trust, professionalism, and technology, aligning with my field (Networking and IT Security).

Gold (#FFD369) provides a warm contrast and shows important elements like titles and links.

White and light gray balance the palette for readability and modern minimalism.

Pages Implemented

1. Home (index.html): Welcome section and navigation to other pages.

2. About Me (about.html): Profile, personal introduction, and intro video.

3. Projects (projects.html): Descriptions of academic and technical projects.

4. Contact (contact.html): Contact form with validation and styled layout.

Key Notes

No flexbox was used (as per requirement). Instead, layouts were handled with inline-block, display block, and media query adjustments.


Gradients and color schemes enhance visual appeal while maintaining accessibility and readability.


Each viewport has its own CSS file, ensuring optimized performance across devices.

 Author: Isimbi Rehema
 Course: Networking and IT Security – Ontario Tech University
 Year: 2025


Reference: I use W3S school website 


