# Poly-Glot AI Workspace — 30-Second Demo Video Script

## FOR CHATGPT / VIDEO CREATOR

You have a **self-animating HTML demo** (`demo.html`) that automatically plays through the entire workflow described below. To create the demo video:

1. **Unzip** the package
2. Run: `python3 -m http.server 8080`
3. Open `http://localhost:8080/demo.html` in a browser (set window to **390×844** for iPhone-style, or **1024×768** for Mac-style)
4. The animation auto-plays after 2 seconds. Screen-record it.
5. Alternatively, use Puppeteer/Playwright to capture frames and stitch with ffmpeg.

---

## STORYBOARD (30 seconds, ~11 steps)

| Time | Screen | Action | What Viewer Sees |
|------|--------|--------|-----------------|
| 0:00–0:03 | **Ask Any AI** | App loads. Green-glowing textarea, "Ask Any AI" header, 4 tabs at top. | Dark themed app with parrot logo, "Ask Any AI" tab active (purple underline). Big green-bordered text area. |
| 0:03–0:05 | **Templates tab** | User taps "Templates" tab. Grid of template cards appears with category pills (All, Free, Money, Business…). | 2-column grid of orange-bordered PRO cards. "All" pill is active (blue). |
| 0:05–0:08 | **Free filter** | User taps "⭐ Free" pill. Grid filters to show only free templates: Summarization Tool, YouTube Script, LinkedIn Post Writer, Code Review Assistant, etc. | Free templates appear — no orange PRO badges. "Free" pill highlighted. |
| 0:08–0:11 | **YouTube Script** | User taps "YouTube Script" card. Editor opens with fields: Topic, Audience, Length (10 minutes), Format (tutorial), Brand Voice (educational). | Editor screen with "← Back" and "YouTube Script" header. Fields stacked vertically with paste/import/mic/clear buttons. |
| 0:11–0:16 | **Fill Topic** | Text types into Topic field: "How to Start a YouTube Channel in 2025" | Typing animation in the Topic input field. |
| 0:16–0:20 | **Fill Audience** | Text types into Audience field: "beginners who want to grow fast" | Typing animation in the Audience input field. |
| 0:20–0:22 | **Tap Send** | User taps the purple "Send" button at the bottom. Send-to-AI bottom sheet slides up. | Bottom sheet with "Send to AI" title, Compare Mode toggle, and AI buttons (ChatGPT, Claude, Gemini, Perplexity, Grok, Copilot, Mistral…). |
| 0:22–0:24 | **Toggle Compare Mode** | User toggles Compare Mode switch ON. Checklist of AIs appears with checkboxes. | Toggle turns green. AI checklist expands showing selectable rows. |
| 0:24–0:26 | **Select ChatGPT** | User taps ChatGPT checkbox. Green checkmark appears. | ChatGPT row gets green checkbox. "Send to Selected (1)" button appears. |
| 0:26–0:28 | **Select Claude** | User taps Claude checkbox. Green checkmark appears. | Claude row gets green checkbox. Button updates to "Send to Selected (2)". |
| 0:28–0:30 | **Tap ChatGPT** | User taps the ChatGPT button. Brief "Prompt copied!" toast appears. | Green toast: "📋 Prompt copied!" — end of demo. |

---

## VISUAL STYLE
- **Background**: #0d1117 (dark navy)
- **Surface**: #161b22
- **Accent purple**: #7c3aed / #a78bfa
- **Accent green**: #10b981 / #34d399
- **Text**: #e6edf3
- **Muted text**: #8b949e
- **ChatGPT green**: #10a37f
- **Claude orange**: #d97706
- **Gemini blue**: #4285f4
- **Compare Mode toggle**: green (#10a37f) when ON
- **PRO badge**: orange gradient (#f59e0b → #d97706)
- **Font**: -apple-system / SF Pro Text / Inter

## DIMENSIONS
- iPhone mock: 390×844
- Mac window: 1024×768 (what the screenshots show)

## KEY UI ELEMENTS
- Header: Parrot logo (base64 inline) + "Poly-Glot AI Workspace" + "poly-glot.ai" + 🇺🇸 EN picker
- Trial banner: purple gradient "✦ 1 free send today — Subscribe for unlimited sends." + Subscribe button
- 4 tabs: 🤔 Ask Any AI | 📱 Templates | 📖 How to Use | 🕐 History
- Category pills: All, ⭐ Free, 💰 Money, 💰 Business, 💻 Coding, 🤖 AI, ✍️ Writing, 📢 Marketing…
- Template cards: 2-column grid, dark surface, emoji + name + description + PRO/FREE badge
- Editor: field labels (uppercase, muted), text inputs, action buttons (paste/import/mic/clear)
- Send sheet: bottom sheet with handle, Compare Mode toggle, AI provider buttons with colored icons
