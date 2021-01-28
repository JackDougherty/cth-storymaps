# cth-storymaps
Leaflet Storymaps customized for CT Humanities with multi-map setup using uploaded CSV data files, not a linked Google Sheet. Based on [Leaflet Storymaps with Google Sheets](https://github.com/HandsOnDataViz/leaflet-storymaps-with-google-sheets) by Jack Dougherty and Ilya Ilyankou, authors of *Hands-On Data Visualization* https://HandsOnDataViz.org/leaflet-storymaps-with-google-sheets.html


## Live link to individual maps
- https://cthumanities.github.io/cth-storymaps/index.html
- or
- https://jackdougherty.github.io/cth-storymaps/index.html

## To edit an existing storymap

... TODO ...

## To create a new storymap
- choose a keyword for each new storymap (such as *architecture* or *ridgefield-business*)
- in `media` folder, create subfolder with keyword name (such as `architecture`), and upload images (JPG or PNG) or other media
- design your storymap based on your copy of the Leaflet Storymaps with Google Sheets template https://docs.google.com/spreadsheets/d/1AO6XHL_0JafWZF4KEejkdDNqfuZWUk3SlNlQ6MjlRFM/edit#gid=0
- in the spreadsheet template, make sure that pathnames to media files follow the format above, such as `media/architecture/image.jpg`
- in Google Sheets, File > Download as CSV, *carefully* rename to keyword-options.csv and keyword-chapters.csv *with no internal spaces*, then upload to `csv` folder
- in project folder, create duplicate of existing storymap file (such as `architecture.html`), rename to keyword.html, and modify pathnames to CSV files above
- add new link to your keyword.html storymap file in the `index.html` file

#### Geocode your address data with Google Sheets add-on
To geocode (find latitude and longitude coordinates), we recommend installing the free [Geocoding by SmartMonkey add-on for Google Sheets](https://gsuite.google.com/marketplace/app/geocoding_by_smartmonkey/1033231575312). Insert your addresses in place of the samples in the Geocoding Details tab, then use Add-Ons > Geocoding > Geocode Details menu. Learn more in *Hands-On Data Visualization* https://handsondataviz.org/geocode.html

![Geocoding](geocode.png)
