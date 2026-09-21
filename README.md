# Recovery Dharma Secretary Log Generator

A lightweight, fully interactive, single-page web application designed to help Recovery Dharma meeting secretaries quickly generate, customize, and print structured meeting schedules and rotation logs.

Built with plain HTML, JavaScript, and Tailwind CSS. Runs 100% client-side with zero dependencies, build steps, or backend servers required—making it lightweight and easy to host on GitHub Pages.

---

## Features

- **Period Selection**: Generate logs for H1 (Jan–Jun), H2 (Jul–Dec), or custom multi-month windows (e.g., Aug–Dec).
- **Book Edition Support**:
  - **Recovery Dharma (Second Edition)** pre-configured with all 34 chapters and verified non-overlapping page ranges.
  - **Custom / Other Edition** support allows you to input your own chapter titles and page ranges.
- **Sequential Resume**: Set the last chapter read and topic discussed; the app automatically picks up where you left off.
- **Custom Topic Deck**: Edit, reorder, or add custom topics to your group's deck.
- **Confirmatory Rotation Rules**: Automatically applies standard group rotation logic:
  - **1st Meeting of Month**: Speaker Meeting (includes a fill-in blank line for host/speaker name).
  - **2nd & 4th Meetings**: Book Reading (sequential chapter selection).
  - **3rd & 5th Meetings**: Topic Session (drawn sequentially from your custom topic deck).
- **Print & Export Ready**: Generates a clean, binder-ready printable view and exports directly to PDF formatted for standard 3-ring meeting binders.

---

## Quick Start (Local Use)

1. Clone or download this repository:
   ```bash
   git clone git@github.com:YOUR-USERNAME/rd-secretary-log.git