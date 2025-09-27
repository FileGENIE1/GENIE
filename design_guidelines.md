# FileFairy Design Guidelines

## Design Approach
**System-Based Approach**: Using a hybrid of Material Design and modern file management interfaces (Google Drive, Dropbox) to balance functionality with visual appeal. This utility-focused application prioritizes efficiency and learnability for file organization tasks.

## Core Design Elements

### A. Color Palette
**Primary Colors:**
- Dark Mode: 220 15% 12% (deep slate background), 220 20% 18% (elevated surfaces)
- Light Mode: 0 0% 98% (light background), 220 10% 95% (surface)
- Accent: 217 91% 60% (primary blue for actions and progress)

**Supporting Colors:**
- Success: 142 71% 45% (for completed operations)
- Warning: 38 92% 50% (for duplicate files)
- Error: 0 84% 60% (for errors/conflicts)
- Neutral: 220 9% 46% (secondary text and borders)

### B. Typography
**Font Stack:** Inter via Google Fonts CDN
- Headers: 600 weight, sizes 24px-32px
- Body: 400 weight, 14px-16px
- Interface labels: 500 weight, 12px-14px
- File metadata: 400 weight, 12px (monospace for technical details)

### C. Layout System
**Tailwind Spacing Units:** Consistent use of 2, 4, 6, 8, 12, 16 units
- Component padding: p-4, p-6
- Margins: m-2, m-4, m-8
- Heights: h-8, h-12, h-16 for buttons and inputs
- Grid gaps: gap-4, gap-6

### D. Component Library

**Navigation:**
- Sidebar navigation with collapsible sections
- Breadcrumb navigation for deep folder structures
- Tab-based interface for different views (Files, Projects, Duplicates)

**File Management:**
- Card-based file display with thumbnails and metadata
- List view toggle for detailed information
- Multi-select checkboxes for batch operations
- Drag-and-drop zones with visual feedback

**Forms & Controls:**
- AI depth slider (0-10) with visual indicators
- Privacy toggle switches with clear states
- Search bar with real-time filtering
- Batch rename templates with preview

**Data Displays:**
- Progress bars for scanning operations
- File tree explorer with expand/collapse
- Duplicate file comparison panels
- Metadata tables with sortable columns

**Overlays:**
- Modal dialogs for confirmations and settings
- Toast notifications for operation feedback
- Tooltip explanations for AI features
- Loading states with descriptive text

### E. Key Interface Sections

**Main Dashboard:**
- Upload zone with drag-and-drop (prominent, centered)
- Quick stats: total files, duplicates found, storage saved
- Recent projects and quick actions

**File Organization:**
- Three-panel layout: folder tree, file grid/list, preview/details
- Project-based folders with color coding
- Smart sorting suggestions based on AI analysis

**AI Controls:**
- Depth slider with descriptions (0: filename only → 10: full content analysis)
- Privacy toggle prominently displayed
- Real-time processing indicators

**Duplicate Detection:**
- Side-by-side file comparison
- One-click resolution with preview
- Bulk action controls with safety confirmations

## Images
No large hero images needed. This is a utility application focused on file thumbnails, folder icons from Heroicons, and progress indicators. Use file type icons and small preview thumbnails throughout the interface for visual context.