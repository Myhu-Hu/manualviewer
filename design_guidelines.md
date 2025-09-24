# Design Guidelines: 監控錄影操作手冊手機版

## Design Approach
**Reference-Based Approach** - Drawing inspiration from mobile-first instructional apps like Duolingo and step-by-step tutorial interfaces, focusing on clarity and ease of use for Chinese-speaking users.

## Core Design Elements

### A. Color Palette
- **Primary**: 220 85% 45% (深藍色 - 專業可信賴感)
- **Secondary**: 220 20% 95% (淺灰藍 - 背景色)
- **Success**: 142 76% 36% (綠色 - 完成狀態)
- **Warning**: 38 92% 50% (橙色 - 注意事項)
- **Text**: 220 15% 20% (深灰色)
- **Background**: 0 0% 98% (淺灰白)

### B. Typography
- **Primary Font**: 'Noto Sans TC' (Google Fonts) - 繁體中文優化
- **Headings**: 700 weight, sizes 24px-32px
- **Body**: 400 weight, 16px-18px for readability on mobile
- **Captions**: 400 weight, 14px for step indicators

### C. Layout System
**Tailwind spacing primitives**: 2, 4, 6, 8, 12, 16
- Consistent padding: p-4, p-6 for containers
- Margins: mb-4, mb-6 between sections
- Gap spacing: gap-4 for component spacing

### D. Component Library

**Step Cards**
- Rounded corners (rounded-xl)
- Shadow elevation (shadow-lg)
- Sequential numbering with colored circles
- Clear action buttons for each step

**Progress Indicator**
- Top navigation bar showing current step
- Visual progress completion
- Step titles in Chinese

**Interactive Elements**
- Large touch targets (min 44px height)
- High contrast buttons with clear CTAs
- Collapsible sections for detailed explanations

**Alert Components**
- Warning boxes for important notes (WiFi timing, loading states)
- Success indicators for completed steps
- Loading state representations

### E. Page Structure

**Header Navigation**
- App title: "V380 Pro 操作指南"
- Progress indicator
- Back/forward navigation

**Main Content Areas**
1. **步驟總覽** (Step Overview)
2. **WiFi 設定** (WiFi Setup) 
3. **應用程式開啟** (App Launch)
4. **即時觀看** (Live View)
5. **錄影回放** (Playback)
6. **日期選擇** (Date Selection)

**Bottom Navigation**
- Previous/Next step buttons
- Home shortcut
- Help/FAQ access

## Mobile-Specific Considerations

- **Single-column layout** optimized for portrait orientation
- **Large typography** for Chinese characters readability
- **Touch-friendly spacing** between interactive elements
- **Swipe gestures** for step navigation
- **Sticky header** with current step indicator
- **Collapsible details** to reduce cognitive load

## Content Presentation Strategy

- **One primary action per screen** to avoid confusion
- **Visual step indicators** with numbers and icons
- **Important timing notes** highlighted in warning boxes
- **Screenshots placeholders** for key interface elements
- **Progressive disclosure** - show details only when needed

## Images Section

**Hero Image**: No large hero image - focus on functional, step-by-step interface

**Step Illustrations**:
- Small interface mockups showing V380 Pro app screens
- WiFi connection visual indicators
- Camera angle adjustment diagrams
- Calendar selection interface examples
- Video timeline scrubbing illustrations

**Icon Usage**:
- Heroicons for navigation and UI elements
- Camera, WiFi, play button, calendar icons
- Status indicators (loading, success, warning)

These images should be positioned inline with their respective steps, sized appropriately for mobile viewing (max width 100% of container, aspect ratio preserved).