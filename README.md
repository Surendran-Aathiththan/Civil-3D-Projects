# Civil 3D Projects

Survey and infrastructure work in **Autodesk Civil 3D**.

## [Engineering Surveying, CE2150](Uni%20Project%20CE2150%20-%20Engineering%20surveying)

A University of Peradeniya engineering surveying field project (July 2026): total-station field data was processed into a coordinate list and drawn up as a survey drawing in Civil 3D.

**Status:** ✅ Complete.

### Workflow

| Stage | What I did | File |
|---|---|---|
| 1. Field survey | Raw observations from a Sokkia CX-102 total station (SDR33 format, job 22A2) | [`22A2.SDR`](Uni%20Project%20CE2150%20-%20Engineering%20surveying/22A2.SDR) |
| 2. Data processing | Reduced the observations to a point list in PNEZD format (point, northing, easting, elevation, description) | [`My data.csv`](Uni%20Project%20CE2150%20-%20Engineering%20surveying/My%20data.csv), `My data.xlsx` |
| 3. Survey drawing | Imported the points into Civil 3D and drafted the survey | `Survey.dwg` |

### Survey data summary

| Item | Value |
|---|---|
| Surveyed points | 149 |
| Description codes | B (96 points), D (34), TE (10), P (9) |
| Extent | ≈ 232 m (N) × 120 m (E), local grid (N 4784–5016 m, E 1997–2117 m) |
| Elevation range | 99.19 m to 100.83 m (local datum ≈ 100 m) |

### Skills shown

- Working with total-station raw data (Sokkia SDR format)
- Preparing survey point data in Excel/CSV (PNEZD)
- Point import and survey drafting in Civil 3D

## Opening the files

Open `Survey.dwg` in **Civil 3D** (AutoCAD shows the geometry but not the Civil 3D point objects). The CSV can be viewed directly on GitHub; the `.SDR` file is a plain-text Sokkia raw-data file.
