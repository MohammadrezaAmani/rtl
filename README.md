# Correct RTL

### About This Tool

- **Developer:** DeepSeek AI Assistant + Mohammadreza Amani's prompt :|
- **Purpose:** A specialized Markdown viewer and editor designed for RTL (Right-to-Left) languages

### The Problem This Solves

When working with AI-generated content (especially from DeepSeek, ChatGPT, Claude, or similar assistants), the output is often formatted in Markdown. However, most standard Markdown viewers and editors have a critical flaw:

> **They don't properly support RTL (Right-to-Left) languages like Persian (Farsi), Arabic, Hebrew, and Urdu.**

This causes several issues:
- ❌ Text alignment breaks (shows as LTR instead of RTL)
- ❌ Lists and bullet points appear in the wrong direction
- ❌ Quotes and blockquotes lose their proper formatting
- ❌ Tables become unreadable with mixed text directions
- ❌ The overall reading experience becomes frustrating

### The Solution

This HTML tool solves all these problems by providing:

✅ **Full RTL Support** - All text displays correctly from right to left  
✅ **Live Markdown Preview** - See changes in real-time as you type  
✅ **Dark Theme (Black & White)** - Clean, minimal, and easy on the eyes  
✅ **Vazir Font Support** - Beautiful Persian/Farsi typography  
✅ **Copy Functionality** - Easily copy Markdown content  
✅ **One-Click Reset** - Restore sample content instantly

### How to Use

1. **Copy the entire HTML code** provided above
2. **Paste it into a new file** and save it as `index.html` (or any name with `.html` extension)
3. **Open the file in any modern web browser** (Chrome, Firefox, Edge, etc.)
4. **Paste your AI-generated Markdown** content into the left editor panel
5. **View the properly formatted RTL preview** on the right panel

### Ideal Use Cases

- 📋 **Copying AI responses** that contain Markdown formatting
- 📝 **Editing and previewing** RTL Markdown content
- 🔄 **Converting** LTR Markdown to RTL-friendly display
- 📚 **Reading documentation** in Persian, Arabic, or Hebrew
- 🎯 **Reviewing AI outputs** before sharing or publishing

### Technical Features

- **No external dependencies** except for:
  - `marked.js` (Markdown parser) - loaded from CDN
  - `Vazirmatn` font - loaded from CDN
- **Fully responsive** - works on desktop and mobile
- **Pure HTML/CSS/JavaScript** - no frameworks needed
- **Dark theme optimized** for long reading sessions
- **RTL-first design** with proper text direction handling

### Why This Tool Matters

> "Most developers and content creators working with RTL languages struggle with Markdown preview tools. This tool bridges that gap by providing a simple, elegant solution that respects the natural reading direction of these languages."

**Key Insight:** AI assistants generate content in Markdown format, but standard viewers are built primarily for LTR (Left-to-Right) languages. This tool fixes that oversight, making it easier for millions of Persian, Arabic, and Hebrew speakers to work with AI-generated content.

### Example Workflow

1. Ask DeepSeek (or any AI) a question
2. Receive a Markdown-formatted response
3. Copy the entire response
4. Paste it into this tool's editor
5. Immediately see the properly formatted RTL preview
6. Copy or export the content as needed

### Customization Options

You can easily modify:
- **Colors** - Change hex values in the `<style>` section
- **Fonts** - Replace "Vazirmatn" with any other font
- **Theme** - Switch from dark to light by adjusting background colors
- **Features** - Add or remove buttons as needed

---

## 🎯 Quick Start Guide

```bash
# Step 1: Create a new HTML file
touch markdown-rtl-viewer.html

# Step 2: Copy the entire HTML code into the file

# Step 3: Open in browser
open markdown-rtl-viewer.html
```

---

**© 2026 DeepSeek AI Assistant + Mohammadreza Amani**  
*Built with ❤️ for the RTL community*
