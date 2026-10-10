# HR Analysis Project
An interactive **Power BI** project for analyzing Human Resources performance. It turns HR information into a clear, visual story through an animated intro page and an interactive dashboard.

---

## About Power BI

**Microsoft Power BI** is a business analytics tool for connecting to data, modeling it, and building interactive reports and dashboards. It is made of three main parts:

| Part | Purpose |
|------|---------|
| **Power BI Desktop** | Free Windows app used to build the report, the data model, and the visuals |
| **Power BI Service** | Online platform for publishing, sharing, and scheduling refresh of reports |
| **Power BI Mobile** | Apps for viewing reports on phones and tablets |

Key concepts used in this project:

- **Semantic model:** the tables, relationships, and calculations behind the report.
- **DAX:** the formula language used to create measures such as totals, averages, and percentages.
- **Power Query:** the tool used to connect to data sources and clean or reshape data.
- **Visuals and slicers:** charts, cards, and filters that let users explore the report interactively.
- **Buttons and navigation:** used to move between pages and add interactive effects.
- 
---

## Project overview

The report has two pages:

| Page | Contents |
|------|----------|
| **Intro** | Animated hero graphic, project title in English and Arabic, feature cards with icons, and an **Open Dashboard** button with a hover effect |
| **Dashboard** | Dropdown slicers, KPI cards with icons, six charts, and a **Home** button to go back |

### Features

- Animated cover page
- Custom icons on cards and buttons
- KPI cards for key HR indicators
- Interactive slicers that filter the whole page
- Cross-filtering between all visuals
- Page navigation buttons
- Dark theme with a consistent color palette
- Bilingual titles (English and Arabic)

### Visuals used

- Column charts
- Bar chart
- Donut chart
- Line chart
- KPI cards
- Dropdown slicers

---

## Getting started

**Requirements:** Power BI Desktop (recent version). If prompted, enable
*File → Options → Preview features → Power BI Project (.pbip) save option* and restart.

1. Unzip the project.
2. Open `HR_Dashboard.pbip` in Power BI Desktop.
3. Explore the two pages, or edit visuals from the **Report** view.
4. To create a template file, use *File → Export → Power BI template (.pbit)*.
5. To share online, use *Home → Publish* and sign in to Power BI Service.


## Animation and interactivity

Power BI does not support native animation for charts. This project creates motion and interactivity with:

- an animated GIF on the intro page,
- hover and pressed colors on buttons,
- page navigation between the intro and the dashboard,
- cross-filtering between visuals and slicers.

For more motion, add **Bookmarks** or enable **Page transitions** in Power BI Desktop.

## Customization

- **Colors:** navy `#0B1F3A`, card `#12305A`, accent `#00D4B4`, gold `#FFB703`, red `#FB5607`
- **Page size:** 1280 × 720
- **Icons:** replace the PNG files in `StaticResources/RegisteredResources/` and keep the same file names

## Tech stack

- Power BI Desktop
- DAX
- Power Query
- PBIP project format (PBIR + TMDL)

---
