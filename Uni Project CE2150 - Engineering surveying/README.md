# Engineering Surveying (CE2150): Total-Station Survey to Civil 3D Drawing

A University of Peradeniya engineering surveying field project (July 2026). Total-station field data was processed into a coordinate list and drawn up as a survey drawing in **Civil 3D**.

**Status:** ✅ Complete.

## Workflow

1. **Field data:** raw observations from a Sokkia CX-102 total station, stored in SDR33 format (job 22A2, 10 Jul 2026).
2. **Point data:** coordinates prepared as a PNEZD point list (point number, northing, easting, elevation, description) in CSV and Excel.
3. **Drawing:** points imported into Civil 3D and the survey drawn up in `Survey.dwg`.

## Survey data

| Item | Value |
|---|---|
| Points | 149 |
| Description codes | B (96 points), D (34), TE (10), P (9) |
| Northing range | 4784.2 – 5016.1 m (≈ 232 m) |
| Easting range | 1996.7 – 2116.5 m (≈ 120 m) |
| Elevation range | 99.19 – 100.83 m (local datum ≈ 100 m) |

Sample of [`My data.csv`](My%20data.csv):

```
1,4989.901,2008.786,100.169,B01
2,4985.942,2008.318,100.183,B02
3,4991.117,2009.994,100.120,B03
```

## Files

| File | Description |
|---|---|
| [`22A2.SDR`](22A2.SDR) | Raw total-station data (Sokkia SDR33, plain text) |
| [`My data.csv`](My%20data.csv) | Point list in PNEZD format |
| `My data.xlsx` | Excel workbook of the point data |
| `Survey.dwg` | Civil 3D survey drawing |

Open `Survey.dwg` in Civil 3D (AutoCAD shows the geometry but not the Civil 3D point objects). The CSV and SDR files can be read on GitHub.
