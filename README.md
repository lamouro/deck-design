# deck-design

A skill that makes Claude build better slides. Once it's installed, every deck Claude makes for you follows the same rules:

- One clear title at the top of each slide that says the main point
- No tiny labels above the title and no subtitle under it
- Short bullets in big, readable text
- A different layout from slide to slide, not the same thing repeated
- Colors that fit your topic, and your logos and photos used properly
- Accessible by default: alt text on images, strong contrast, color never the only signal
- Speaker notes, so anyone can present it

It works for decks made in Claude Design, PowerPoint files, Google Slides and web slides.

---

## Install on claude.ai (takes 1 minute)

Use this if you use Claude in your browser, the desktop app or Claude Design.

**Step 1. Download the skill**

Click this link: **[Download deck-design.zip](https://github.com/lamouro/deck-design/raw/main/deck-design.zip)**

The file saves to your Downloads folder. Don't unzip it.

**Step 2. Open Skills in Claude**

1. Go to [claude.ai](https://claude.ai) and sign in.
2. Click **Customize** in the left sidebar.
3. Make sure the **Skills** tab is selected at the top.

**Step 3. Upload it**

1. Click the **+ Add** button on the top right.
2. Choose **Upload skill**.
3. Pick `deck-design.zip` from your Downloads folder.

**Step 4. Use it**

Ask Claude for a slide or a deck, for example:

> Make a 6-slide deck about our spring event. Here's our logo.

You don't need to mention the skill. Claude loads it on its own whenever you ask for slides.

---

## Install in Claude Code

Use this if you use Claude Code in a terminal or the Code tab of the desktop app.

Paste this into a terminal:

```bash
git clone https://github.com/lamouro/deck-design ~/.claude/skills/deck-design
```

Restart Claude Code. Then ask for slides, or type `/deck-design`.

---

## Getting updates

The rules get updated from time to time.

- **claude.ai:** download the zip again (Step 1). Go to **Customize > Skills**, open **deck-design**, click the **⋯** button next to its on/off switch, choose **Replace**, and pick the new zip.
- **Claude Code:** run this:

```bash
git -C ~/.claude/skills/deck-design pull
```

---

## Troubleshooting

**I don't see Customize or Upload skill.**
On a Team or Enterprise plan, an admin may need to turn on skills for your organization first. Ask whoever manages your Claude account.

**The upload fails.**
Make sure you uploaded the `.zip` file itself, not an unzipped folder, and that it's the file from the download link above (GitHub's green "Code > Download ZIP" button gives a different file that won't work).

**Claude made slides but didn't follow the rules.**
Start your message with "Use the deck-design skill" and try again.

---

## What's in this repo

| File | What it is |
|---|---|
| `deck-design.zip` | The file you upload to claude.ai |
| `SKILL.md` | The rules themselves, if you want to read them |
| `references/checklist.md` | The check Claude runs on every slide before handing a deck back |
