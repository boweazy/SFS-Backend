# SmartFlow Systems Backend Design Guidelines

## Design Approach
**Reference-Based Approach** - Drawing inspiration from **Notion** and **Linear** for their clean, developer-friendly interfaces that balance functionality with modern aesthetics. This backend project requires a professional, technical aesthetic that conveys reliability and automation prowess.

## Core Design Elements

### A. Color Palette
**Dark Mode Primary:**
- Background: 220 15% 8% (deep slate)
- Surface: 220 12% 12% (elevated panels)
- Primary: 200 95% 60% (electric blue - automation/tech theme)
- Text Primary: 220 10% 95% (near white)
- Text Secondary: 220 8% 70% (muted)

**Light Mode:**
- Background: 220 20% 98% (soft white)
- Surface: 220 15% 95% (subtle panels)
- Primary: 200 85% 45% (deeper blue for contrast)
- Text Primary: 220 15% 15% (dark slate)

### B. Typography
- **Primary**: Inter (Google Fonts) - clean, technical readability
- **Code/Monospace**: JetBrains Mono - for API endpoints, file paths
- **Scale**: text-xs to text-2xl, emphasizing readable body text (text-sm/base)

### C. Layout System
**Spacing Primitives**: 2, 4, 6, 8, 12, 16 units
- Micro spacing: p-2, gap-2
- Standard spacing: p-4, m-6, gap-4  
- Section spacing: p-8, mb-12
- Large spacing: py-16 for major sections

### D. Component Library

**Core Navigation:**
- Minimal sidebar with collapsible sections
- Breadcrumb navigation for API routes
- Status indicators (green/red dots for health checks)

**Data Displays:**
- Card-based layouts for API endpoints
- Code blocks with syntax highlighting
- JSON preview panels with collapsible trees
- Table layouts for file listings

**Forms & Inputs:**
- Outlined input fields with subtle borders
- Toggle switches for boolean settings
- Dropdown selectors with search functionality

**Status & Feedback:**
- Toast notifications for API responses
- Loading states with subtle pulse animations
- Success/error badges with appropriate colors

### E. Key Visual Patterns

**API Documentation Style:**
- Left sidebar navigation (collapsible)
- Main content area with generous whitespace
- Inline code styling for endpoints and parameters
- Response examples in formatted JSON blocks

**File Management Interface:**
- Grid/list toggle for data files
- File icons with type indicators
- Path breadcrumbs showing safe navigation
- Preview panels for JSON content

**Dashboard Elements:**
- Health status cards with real-time indicators
- Recent activity feeds
- API usage metrics (simple bar charts)
- Quick action buttons for common tasks

## Visual Hierarchy
1. **Primary Actions**: Bold primary buttons, high contrast
2. **Secondary Content**: Subtle borders, muted text
3. **Status Information**: Color-coded indicators, small badges
4. **Navigation**: Consistent spacing, clear active states

## Interaction Patterns
- Hover states: Subtle elevation and color shifts
- Click feedback: Brief opacity changes
- Loading states: Skeleton screens for content areas
- Error handling: Inline validation with clear messaging

This design system creates a professional, developer-focused interface that emphasizes functionality while maintaining visual appeal appropriate for a technical automation platform.