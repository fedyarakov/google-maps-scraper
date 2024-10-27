# Google Maps Scraper from Presto

🔗 **Website**: [presto-maps-scraper.com](https://presto-maps-scraper.com)

Presto Google Maps Scraper: Extract business data from Google Maps effortlessly with features like Auto Search, comprehensive category and contact info retrieval, and Excel-ready export for lead generation

# What is Presto Google Maps Scraper

Presto Google Maps Scraper is a powerful and easy-to-use tool that helps you extract business listings from Google Maps and Bing Maps for lead generation, market research, and prospecting. Designed to streamline the data collection process, Presto saves countless hours by automating the search, extraction, and download of detailed business information.

---

## Features

- **Auto Search (Beta)**  
  Automatically scrolls, zooms, and pans across map areas, capturing every business listing in the selected region.

- **Comprehensive Data Coverage**  
  Extracts up to 22 data fields per listing, including:
  - Business name and categories
  - Address (international and localized)
  - Contact details (phone numbers, email, website URL)
  - Ratings and reviews count
  - GPS coordinates
  - Thumbnail, reviews URL, and more

- **Precision Control**  
  Adjust the speed vs. detail setting to either capture broad listings quickly or dive deeper for precise data.

- **Excel and CSV Export**  
  Export your data directly to Excel or CSV format with predefined columns for easy sorting, filtering, and analysis.

- **Freemium Model**  
  Start with a free version for limited use, or upgrade to unlock unlimited searches and full functionality.

---

## Why Use Presto Google Maps Scraper?

- **Rated 5.0 on Microsoft Edge**  
  Trusted and highly rated by users for its simplicity, reliability, and advanced features.

- **Popular in International Markets**  
  Especially popular in Brazil, Presto is trusted by businesses globally for effective lead generation from Google Maps.

- **Automated Search Capabilities**  
  The Auto Search feature goes beyond standard extraction by automatically navigating and zooming in on new map segments, ensuring no listings are left behind.

---

## How It Works

1. **Add Presto to Your Browser**  
   Available on both Chrome and Edge extensions stores, Presto can be easily pinned to your browser toolbar for quick access.

2. **Open Google Maps**  
   Go to [Google Maps](https://maps.google.com), zoom in on the area you want to target, and search for a keyword (e.g., "hair salon near Los Angeles").

3. **Extract Listings**  
   With Auto Search enabled, Presto will start extracting listings automatically. You can also click "Download Records" at any time to download the collected data.

4. **Export Your Data**  
   Download the extracted listings as an Excel or CSV file for further analysis or direct use in CRM systems.

---

## Data Fields Extracted

| Field Name                | Description                                 |
|---------------------------|---------------------------------------------|
| `uuid`                    | Unique ID for each listing                  |
| `listing_url`             | URL of the business listing                 |
| `created_at`              | Timestamp of data extraction                |
| `query`                   | Search query used                           |
| `name`                    | Business name (International)               |
| `fulladdr`                | Complete address (International)            |
| `local_name`              | Business name (Local language)             |
| `local_fulladdr`          | Complete address (Local language)          |
| `phone_number`            | Primary phone number                        |
| `international_phone_number` | Phone number in international format    |
| `phone_numbers`           | Comma-delimited phone numbers               |
| `latitude`                | Latitude coordinates                        |
| `longitude`               | Longitude coordinates                       |
| `primary_category`        | Main business category                      |
| `categories`              | All categories (comma-separated)            |
| `reviews`                 | Number of reviews                           |
| `rating`                  | Rating out of 5                             |
| `url`                     | Website URL                                 |
| `domain`                  | Website domain name                         |
| `thumbnail`               | Thumbnail image URL                         |
| `addr1`, `addr2`, `addr3` | Address components                          |
| `district`                | District name                               |
| `timezone`                | Timezone of the listing                     |
| `reviews_url`             | URL to reviews page                         |
| `claimed`                 | Indicates if business is claimed            |
| `fid`                     | Map feature ID                              |
| `cid`                     | Google customer ID                          |

---

## Installation

## Installation

1. **Download and Install**  
   - **Option 1: Microsoft Edge Add-ons Store**  
     Install Presto Google Maps Scraper directly from the [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/Microsoft-Edge-Extensions-Home) store for easy access and automatic updates.

   - **Option 2: Install from Source**  
     Download the latest release from GitHub: [Presto 2.2.0 Full Version](https://github.com/fedyarakov/google-maps-scraper/releases/download/2.2.0/presto-2.2.0-full.zip).
     1. Unzip the downloaded file.
     2. Go to `chrome://extensions/` (or `edge://extensions/`) in your browser.
     3. Enable "Developer Mode" in the top-right corner.
     4. Click on "Load unpacked" and select the unzipped folder to add the extension manually.

2. **Pin to Toolbar**  
   After installation, click the "puzzle" icon on your browser toolbar and pin Presto Maps Scraper for easy access.

---

## Usage Instructions

1. **Access Google Maps**  
   Open [Google Maps](https://maps.google.com) and search for businesses in your area of interest.

2. **Run Auto Search**  
   Click on the Presto Maps Scraper icon, select the "Start Auto Search" option, and let Presto do the rest. You’ll see the number of results increase over time.

3. **Download Data**  
   Once complete, click "Download Records" in the extension popup to export your data as Excel or CSV.

4. **Adjust Search Precision**  
   Use the Precision Control slider to regulate how detailed the search results should be. Higher precision may take slightly more time but captures deeper, more specific data.

---

## Release Notes

### Version 2.2.0 – Auto Search & Enhanced Data Extraction
- **Auto Search Feature**: Automatically scans, zooms, and pans across new areas to capture a complete set of listings.
- **Expanded Data Fields**: Added fields for enhanced business category, verification status, and better support for international addresses.
- **Improved Export Options**: Data can now be exported with customizable column formats for more efficient data analysis.
- **UI Improvements**: Enhanced interface for easier navigation, plus added progress tracking and session duration stats.
- **Bug Fixes**: Improved performance and data retrieval speeds to handle larger volumes of data.

---

## FAQ

**Q: How does the Auto Search feature work?**  
A: The Auto Search feature scrolls and zooms across the map to capture all businesses in the selected area automatically. Simply start Auto Search from the Presto popup, and it will gather data as you browse.

**Q: Is there a limit to the number of records I can extract?**  
A: The free version allows up to 40 records per download. For unlimited records, consider upgrading to the full version.

**Q: Can I export data to use in my CRM?**  
A: Yes! You can export listings as an Excel or CSV file, which can be easily imported into most CRM systems.

**Q: Does it work with other maps like Bing?**  
A: Yes, Presto Google Maps Scraper is also compatible with Bing Maps, making it a versatile tool for extracting business data from multiple map providers.

---

## Support

For troubleshooting or questions, please reach out via the support email in the extension popup or open an issue on GitHub.

---

## License

Presto Google Maps Scraper is licensed under the [MIT License](LICENSE).

---

## Contributing

We welcome contributions! Please fork this repository and open a pull request to propose improvements or bug fixes.

---

With Presto Google Maps Scraper, transform your data extraction experience and get high-quality leads in minutes. Download Presto today and make your prospecting and marketing easier than ever!
