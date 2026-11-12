---
name: deck-design
description: Slide and deck design rules. Use whenever making, editing, redesigning or reviewing a slide, deck, presentation, pitch deck, keynote or PowerPoint, in any medium (Claude Design, a .pptx, Google Slides, an HTML or Slides artifact), even for a single slide and even if the user doesn't name the skill. Covers titles, text and bullet limits, banned patterns, layout variety, color from the subject, using the assets the user gives, data slides, fonts and sizes, accessibility (alt text, color, captions), speaker notes and a final check. File mechanics (building or editing a .pptx) still go through the pptx skill; this skill decides what the slides look like and say.
---

# Deck design

These rules decide what every slide says and how it looks. They apply in Claude Design, in a .pptx (build it with the pptx skill), in Google Slides and in HTML slides. If the user gives a rule in the chat that conflicts with one here, the chat rule wins.

## 1. Before building anything

1. **Find the job in one line:** who sees this, how (presented live, sent as a file, read on a phone), and what they should do or believe after. Every slide is judged against that.
2. **Collect the assets the user gave:** logos, screenshots, photos, brand colors, fonts, an existing deck or template, data. Look at each one (open the images) before designing. See section 5.
3. **Write the outline as titles only,** one line per slide. Each title is that slide's one idea. If two titles say the same thing, merge them. If one title needs "and", split it.
4. **Assign a layout to each slide from the menu in section 4** and check the sequence for repeats before building. This is the step that stops every slide looking the same.
5. **Pick the palette and fonts** (sections 6 and 7) once, for the whole deck. If there's a template, use it and skip picking.

Length: about one slide per minute of talk. A deck meant to be read without a presenter can run longer, never denser.

## 2. Text rules (hard)

- **One title per slide, at the top,** in the same position and size on every content slide so the eye knows where to land. Exceptions: the title slide, a full-bleed statement slide, and a big-number slide, where the one line of text is the slide.
- **The title is the takeaway, not a topic label.** "Signups doubled after the redesign", not "Signup results". Short enough to fit on one line, two at most, at heading size (section 7). A reader who sees only the titles should get the whole story.
- **Every title is unique.** If a point runs over two slides, the second keeps the same title with "(continued)" after it.
- **No eyebrow text.** Nothing small above the title: no category label, no "01", no "OVERVIEW", no section tag.
- **No subheader.** Nothing directly under the title restating or extending it. If the title needs a second line of explanation, rewrite the title.
- **No dot-separated fragments.** No "Fast. Simple. Secure.", no "Plan. Build. Ship.", no "text.text.text". Write a real sentence or use a list.
- **No middle dots, pipes or bullets as separators** between words or items ("Boston · 2026", "Design | Build"). Use a line break, a comma, or separate elements.
- **No em dashes.** Use a comma, a period or a colon.
- **Bullets: 5 to 7 per slide at most, 6 to 7 words per bullet at most.** No paragraphs. Fewer is better: the less clutter, the easier it reads. If it doesn't fit, it's two slides or it goes in the speaker notes.
- **One sub-level is allowed** (a demoted point under a bullet) when it makes the slide easier to read. Never a third level.
- **Bullet spacing:** single line spacing inside a bullet that wraps to two lines, with 12pt of space before and after each bullet so bullets stay visibly separate. In a .pptx that's line spacing 1.0 with paragraph space before and after set to 12pt (PowerPoint: Paragraph > Indents and Spacing, or Option+Command+M on Mac). In HTML, line-height about 1.15 with 12pt margin between list items.
- **Emphasis:** bold or a contrasting color, used sparingly, never underline (it reads as a link) and never color alone (section 6).
- **Plain words.** No "unlock", "leverage", "seamless", "revolutionize", "empower", "journey", "in today's fast-paced world". Say the specific thing.
- **Numbers beat adjectives.** "Cut load time from 4s to 1s", not "much faster". Never invent a number; if one would help and isn't given, leave a visible placeholder like [X%] and tell the user.

## 3. Banned visual patterns

These make a deck read as AI-made or templated. Never use them:

- A thin accent line or bar under the title.
- Cards with a colored left border stripe.
- Emoji used as icons.
- A row of three identical cards with icon, heading and two lines (the default "features" slide). If three items really are parallel, vary it: numbers, a diagram, a screenshot per item, or one item per slide.
- Gradient blobs, glows, glassmorphism or random decorative shapes that don't mean anything.
- Stock-photo clichés (handshakes, people pointing at whiteboards, lightbulbs, puzzle pieces).
- Every slide the same title-plus-bullets stack. Bullets are allowed, but not as the only layout.
- Logo stamped in a corner of every slide.
- Clip art, 3D pie charts, drop shadows on text, WordArt-style effects, more than one icon style.

## 4. Layout variety

Plan the sequence so **no layout appears twice in a row** and no single layout covers more than about a third of the deck. Mix dense and airy slides: after a chart or a detailed slide, give the audience a simple one.

Layout menu (pick per slide, by what the content is):

| Content | Layout |
|---|---|
| One striking number | Big number: the number huge, one line saying what it means |
| One claim worth pausing on | Statement: one sentence, large, lots of space, maybe a full-color background |
| A photo or product shot carries it | Full-bleed image with the title over a calm area of the image, or image on one half, text on the other |
| Product, UI, app | Screenshot large, in a device frame or clean shadowless crop, with 1 to 3 callouts pointing at what matters |
| Comparison of two things | Split screen, before/after, or two columns with a clear winner highlighted |
| A trend, comparison or share | Chart (section 8) |
| Steps or a process | Horizontal flow with 3 to 5 steps, or a numbered timeline |
| Several parallel items | Grid of 2, 4 or 6 with images or numbers, not just icons |
| A quote or testimonial | Quote large, name and role small, photo if given |
| Team or people | Photo grid with names and roles |
| Moving to a new topic | Section header: section title only, on the accent color or an image. Use one at every topic change so the audience knows the talk has moved on |
| Ending | Closing (section 10) |

Backgrounds: the default is light text on a dark background (section 6). Get variety from the accent color on statement and section-header slides and from full-bleed images, not from switching the deck between light and dark. If a template is given, its backgrounds win.

## 5. Using the assets the user gives

- **Use every asset the user gives somewhere it fits,** or say which one you left out and why. Don't swap in a stock image when the user gave a real one.
- **Logos:** never stretch, recolor, crop, add effects to, or place on a busy background. Use the version that contrasts with the background (light logo on dark). Put it on the title slide and closing slide, not on every slide. Never redraw or invent a logo; if one is needed and missing, leave a placeholder and say so.
- **Images must add meaning, not fluff.** If an image only decorates, cut it.
- **Photos:** crop on purpose (subject on a third line, not dead center by accident), keep the aspect ratio, and use them big: full-bleed or half the slide, not a postage stamp. Text over a photo needs a calm area or a dark overlay so it passes contrast.
- **Screenshots:** crop to the part that matters, show them large enough to read, and point at the important part.
- **Brand colors, fonts or a template:** these override sections 6 and 7. Follow them exactly.
- **Data:** use the user's numbers exactly. Round only for display, and never change what a number means.

## 6. Color

- **Follow the template first.** If the user gives a template (or says "our template"), its colors and layouts are the rules. If the user mentions a template and didn't attach it, ask for it before building.
- **Default: light text on a dark background.** Dark backgrounds with light text, unless the template or the user says otherwise.
- **Never convey information with color alone.** Anything color says, text or shape also says: label the highlighted bar, write "up" or "down" next to a red or green number, use different line styles or direct labels instead of a color-only legend, and add a word or icon to any color-coded status.
- **Derive the palette from the subject and the assets,** not from a default. Pull colors from the logo or the photos the user gave. With no assets, pick colors that fit the topic and audience (a finance board deck, a kids' science fair and a music festival should not look alike). Never default to generic blue-and-white or purple gradients.
- **Structure:** one dominant color (backgrounds or large areas), one or two supporting neutrals, and one accent. Five colors max across the deck, including neutrals.
- **The accent directs attention.** Use it for the one bar that matters, the key number, the important word. If the accent is everywhere, it highlights nothing.
- **Contrast:** body text at least 4.5:1 against its background, titles at least 3:1. Check text over images and over colored backgrounds.
- **Same color means the same thing on every slide.** If "us" is the accent in one chart, "us" is the accent in every chart.

## 7. Fonts and sizes

- **Sans-serif only:** APHont, Verdana, Tahoma or Arial, unless the template sets fonts. No serif fonts, no script or display fonts.
- **Two fonts max,** and one family in different weights is usually best.
- **Hierarchy through size and weight,** not more fonts or more colors.
- **Sizes on a 16:9 slide:** headings 44 to 60pt bold; body 28 to 44pt, preferably 30 or 32pt; chart labels, captions and sources at least 20pt. Big-number slides go much bigger (100pt and up). If text has to shrink below these to fit, cut text or split the slide. These sizes are why the bullet and word limits in section 2 matter.
- Left-align body text. Center only short single lines (statements, big numbers, title slide).
- For .pptx files: Verdana, Tahoma and Arial are installed everywhere. APHont is a free download from the American Printing House for the Blind and is not installed by default, so if it's used, tell the user it needs installing or embedding on the presenting machine.

## 8. Data slides

- **Limited information:** few bars, few lines, few rows. Every chart, table and graph gets alt text (section 11).
- **One insight per data slide,** and the title states it ("Mobile now drives 62% of orders"). If the chart needs a paragraph of explanation, it's doing too much: simplify or split.
- **Match the chart to the story:** bar for comparing categories, line for change over time, stacked bar or a single big percentage for parts of a whole. Pie only for 2 or 3 slices, never 3D. A process or decision is a flow diagram, not a chart.
- **Highlight the one bar, line or segment that matters** in the accent color; everything else neutral grey.
- **Label directly** on or next to the data. Drop the legend when direct labels work. Remove gridlines, borders and axis lines that don't help reading.
- Sort bars by value unless the categories have a natural order (time, size).
- Put the source in small text at the bottom of the slide when the data comes from somewhere.
- A table only when people need to look up exact values, and then: few rows, the key row highlighted, numbers right-aligned.

## 9. Space and balance

- **White space is deliberate:** consistent margins (about 5 to 7% of the slide width on every side) and room around one focal element.
- **But the slide should feel full, not abandoned.** No big dead zones, no content huddled in the top-left with the bottom half empty. Size the main element (image, chart, number) up until it owns the slide.
- Align everything to the same grid. Edges of text blocks, images and charts line up across slides.
- One focal point per slide: the biggest, highest-contrast thing is the one idea.

## 10. Title and closing slides

- **Title slide:** the deck's title (short, two lines max) plus only what's essential: presenter name, date, organization. No subtitle, no tagline. One strong visual or none: a photo, the logo, or a color block.
- **Closing slide:** the ask or the next step ("Questions", "Try it at example.com", "Vote by Friday"), plus the one contact method that matters. A lone "Thank you" is a wasted slide; if the user wants thanks, pair it with the next step. No new information, no wall of social handles.
- **Agenda slide:** only for decks of about 10+ slides or 15+ minutes. Skip it otherwise.

## 11. Accessibility

- **Alt text on every image, chart, graph and table.** In a .pptx, set it in code (the shape's description) or tell the user where: select the image > Format Picture > Alt Text. In HTML, the `alt` attribute (or `aria-label` on an SVG chart). Purely decorative shapes get marked decorative, but per section 5 there shouldn't be many.
- **How to write alt text:**
  - Start from why the image is on this slide. Describe what a sighted person gets from it in this context, not everything in the pixels.
  - Name the type (photo, bar chart, diagram, screenshot, logo), then the most important detail, then the less important ones.
  - For charts: the type, what's measured, and the takeaway with the key numbers ("Bar chart of orders by device. Mobile is 62%, desktop 31%, tablet 7%.").
  - Include a title, caption or credit if the image has one.
  - Objective, third person, plain words. Brief but complete: when in doubt, a bit more is better than too little, but not a paragraph.
  - Don't start with "Image of" (screen readers already say it's an image).
- **Videos:** captioned, audio described, and interpreted (voice or ASL depending on the video's main language). If a video the user gives lacks these, say so instead of embedding it silently.
- **Spelling and grammar:** check every slide, the notes and the alt text.

## 12. Works with or without a presenter

- **Write speaker notes for every content slide:** what to say in 2 to 4 sentences, plus any detail cut from the slide. Someone else should be able to present it cold.
- The titles alone should tell the story for someone reading it alone on their phone, so large text, simple layouts and high contrast.

## 13. Final check (always)

Before handing it over, render every slide to an image (the pptx skill's thumbnail or render step, or screenshots in Claude Design) and actually look at each one. Then run `references/checklist.md`. Fix what fails and look again. Tell the user about any placeholder, missing asset or assumption in one short list.
