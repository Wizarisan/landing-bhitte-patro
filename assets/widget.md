# BhittePatro Widget

CSS-only Nepali Calendar Widget - no images required.

## Usage

The widget is implemented directly in `index.html` using pure CSS.

### Full Calendar Widget
```html
<div class="widget-container">
  <div class="widget-header">
    <div class="widget-month">
      <span class="widget-month-name">चैत</span>
      <span class="widget-month-year">२०८</span>
    </div>
    <div class="widget-today-btn">आज: ७</div>
  </div>
  <div class="widget-body">
    <div class="widget-day-labels">
      <span class="widget-dl">आइत</span>
      <span class="widget-dl">सोम</span>
      <span class="widget-dl">मंगल</span>
      <span class="widget-dl">बुध</span>
      <span class="widget-dl">बिही</span>
      <span class="widget-dl">शुक्र</span>
      <span class="widget-dl sat">शनि</span>
    </div>
    <div class="widget-grid" id="widgetGrid"></div>
  </div>
  <div class="widget-footer">तृतीया</div>
</div>
```

### Compact Icon Widget
```html
<div class="widget-icon">
  <span class="widget-icon-ajja">आज</span>
  <div class="widget-icon-logo">ब</div>
  <span class="widget-icon-date">चैत २०८२</span>
  <span class="widget-icon-tithi">तृतीया</span>
</div>
```

## Features

- **Dark/Light Mode**: Automatically adapts to theme
- **Pure CSS**: No images, no external dependencies
- **Responsive**: Scales for different screen sizes
- **Nepali Typography**: Uses system fonts for Devanagari script

## Pages

- **Home**: Hero section with full calendar widget
- **Features**: Showcase of both widget sizes + menu bar feature
- **Download**: Edition comparison and download links
- **Troubleshoot**: Installation help for macOS
