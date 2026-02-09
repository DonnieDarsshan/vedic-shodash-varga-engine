# vedic-shodash-varga-engine
Browser-based Vedic divisional chart engine


LIVE LINK
https://donniedarsshan.github.io/vedic-shodash-varga-engine/

---

## How to Use

1. Download or clone the repository.
2. Open `index.html` in any modern web browser.
3. Click **LOAD JSON DATA**.
4. Select a compatible astrology JSON file.
5. Charts will render automatically.

---

## JSON Input Format

The app expects a JSON structure similar to this:

```json
{
  "meta": {
    "name": "Person Name",
    "datetime_utc": "2000-01-01T12:00:00Z"
  },
  "ayanamshas": {
    "Lahiri": {
      "lagna": 123.45,
      "planets": {
        "Surya": 10.5,
        "Chandra": 200.3,
        "Mangala": 150.2
      },
      "planets_retro": {
        "Saturn": true
      }
    }
  }
}
