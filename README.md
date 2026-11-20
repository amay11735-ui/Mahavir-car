# Mahavir Cars website (GitHub Pages)

All files live in ONE flat folder. No sub-folders, no paths to edit.

## Put it online
1. Create a GitHub repository and upload every file here to its main page (Add file > Upload files).
2. Settings > Pages > Deploy from a branch > `main` / `(root)` > Save.
3. Your site opens at `https://YOUR-NAME.github.io/REPO-NAME/` after about a minute.

## Photos (just upload, no code)
- Customer photos: `customer-1.jpg`, `customer-2.jpg`, `customer-3.jpg` … (numbers in a row, no gaps). They appear in the customer slider automatically.
- Car photos: `CARID-1.jpg` (cover), `CARID-2.jpg`, `CARID-3.jpg` … where CARID is the `id` of the car in cars.json.
- Use lowercase file names and .jpg, .jpeg, .png or .webp. Photos under ~300 KB load fastest.

## Cars
- Open `staff-only.html` on the live site, fill the form, and follow the 3 steps it shows (upload photos, paste into `cars.json`).
- To mark a car sold or reserved, edit that car in `cars.json`: `"status": "Sold"` (or `"Reserved"`, `"Available"`). To remove a car, delete its block.
- Fields: id, brand, model, variant, year, regYear, price, orig, negotiable, km, fuel, trans, owners, body, engine, regNo, insurance, condition, condNote, features (lines separated by \n), desc, status, featured (true/false), created.

## Social links and reviews
Edit `site.json`: paste your Instagram, Facebook and YouTube links, and add only real customer reviews like
`{ "name": "Customer name", "rating": 5, "text": "Review text", "car": "Car bought (optional)" }`
