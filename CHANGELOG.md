# LobsterBoard Changelog

All notable changes to LobsterBoard will be documented in this file.

---

## [0.1.0] - 2026-02-05

### 🎉 Initial Release

The first public version of LobsterBoard - a visual dashboard builder for the OpenClaw community.

### Added

#### Core Builder
- Drag-and-drop widget placement on canvas
- Grid snapping (20px) for precise alignment
- Widget resize handles
- Properties panel for configuring widgets
- Live preview modal with inlined styles
- Export to ZIP (standalone HTML/CSS/JS)

#### Canvas Features
- 15+ screen size presets (1080p, 4K, tablets, ultrawide, portrait)
- Custom dimension support
- Zoom controls (+/-, Fit, 1:1)
- Keyboard shortcuts (Ctrl +/-, Ctrl+scroll)

#### Widgets (40+)
- **AI/LLM:** Claude Usage, GPT Usage, Gemini Usage, AI Usage (All), Cost Tracker, API Status, Active Sessions, Token Gauge
- **Basics:** Local Weather, World Weather, Clock, World Clock, Countdown, Stat Card, Battery Status
- **System:** CPU/Memory, Disk Usage, Network Speed, Docker, Uptime Monitor
- **OpenClaw:** Auth Status, Sleep Ring, Release, Activity List, Cron Jobs, System Log
- **Productivity:** Todo List, Calendar, Email Count, Pomodoro, Notes, GitHub Stats
- **Finance:** Stock Ticker, Crypto Price
- **Smart Home:** Indoor Climate, Camera Feed, Power Usage
- **Entertainment:** Now Playing, Quote of Day
- **Content:** Quick Links, RSS Feed, Image Embed, Iframe Embed
- **Bars:** Top Nav Bar, News Ticker, RSS Ticker

#### Branding
- LobsterBoard name and mascot 🦞
- Logo wordmark for header
- Mascot illustration for sidebar
- Favicon and Apple touch icon

#### Design
- Dark theme matching OpenClaw aesthetic
- Consistent `dash-card` styling across all widgets
- Widget headers with icons
- Sample data display (no loading spinners in builder)

### Technical Notes
- Weather widgets use wttr.in (free, no API key required)
- API keys stored as placeholders for users to fill in post-export
- AI usage widgets require backend proxy due to CORS

---

## [0.1.1] - 2026-02-06

### Changed
- Moved mascot from left sidebar to right (properties panel)
- Mascot now pinned to bottom of panel (doesn't float up)

### Fixed
- Mascot positioning with `margin-top: auto` in flexbox

---

## Upcoming

### Planned Features
- GitHub Pages deployment
- Import/export dashboard layouts (JSON)
- Widget templates and presets
- More customization options
- Community widget contributions

---

## Links

- **GitHub:** https://github.com/curbob/LobsterBoard
- **Issues:** https://github.com/curbob/LobsterBoard/issues
