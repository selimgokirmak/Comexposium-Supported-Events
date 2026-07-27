## 🤖 [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from trade show exhibitor lists provided by **Comexposium**. Easily scrape company profiles including **company details, websites, social media links, product categories, and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Comexposium** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported Comexposium Events (Exhibitor Lists)](#supported-comexposium-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Comexposium event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Product categories with full hierarchical structure

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product category filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Comexposium exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported Comexposium Events (Exhibitor Lists)

> The following partial list includes Comexposium exhibitor directory URLs that have been tested so far. Other Comexposium events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

- [SIAL Paris 2026 Exhibitor List – sialparis.com](https://www.sialparis.com/en/exhibitors-2026/exhibitors)

- [Gourmet Selection 2026 Exhibitor List – salon-gourmet-selection.com](https://www.salon-gourmet-selection.com/en/exhibitors/exhibitors)

- [Salon International de l'Agriculture (SIA) Exhibitor List – salon-agriculture.com](https://www.salon-agriculture.com/en/exhibitors-and-visiting-tools/catalog/exhibitors)

- [Milipol Qatar 2026 Exhibitor List – milipolqatar.com](https://www.milipolqatar.com/en/visit/search)

- [LE SALON PHOTO & VIDÉO 2026 Exhibitor List – lesalondelaphoto.com](https://www.lesalondelaphoto.com/fr-FR/infos-pratiques/catalogue)

- [TOURISSIMA LILLE Exhibitor List – salons-du-tourisme.com/fr-FR/lille](https://www.salons-du-tourisme.com/fr-FR/lille/catalogue-exposants/exhibitors)

- [Foire de France Exhibitor List – foiredeparis.fr](https://www.foiredeparis.fr/fr-FR/exposants-produits/exhibitors)

- [Rétromobile 2026 Exhibitor List – retromobile.com](https://www.retromobile.com/en/exhibitions-events/exhibitors-list/exhibitors)

- [Cheese and Dairy Products Show 2026 Exhibitor List – salon-fromage.com](https://www.salon-fromage.com/en/recherche/exhibitors)

- [SILMO PARIS 2026 Exhibitor List – silmoparis.com](https://www.silmoparis.com/en/silmo-paris/catalogue/exhibitors)

- [SIA'PRO Exhibitor List – sia-pro.com](https://www.sia-pro.com/en/exhibitors-list/exhibitors)

- [Siec 2026 Exhibitor List – siec-online.com](https://www.siec-online.com/en/visiter/recherche/exhibitors)

- [TOURISSIMA PARIS Exhibitor List – salons-du-tourisme.com/fr-FR/paris](https://www.salons-du-tourisme.com/fr-FR/paris/catalogue-exposants/exhibitors)

- [Destinations Nature Exhibitor List – destinations-nature.com](https://www.destinations-nature.com/fr-FR/catalogue-exposants/exhibitors)

- [Ultimate Supercar Garage Exhibitor List – ultimate-supercar-garage.com](https://www.ultimate-supercar-garage.com/en/exhibitors-and-events/exhibitor-list/exhibitors)

- [ALLFORPACK EMBALLAGE PARIS Exhibitor List – all-for-pack.com](https://www.all-for-pack.com/en/exhibitors/exhibitors)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Categories</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Brands</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td>Description</td>
        </tr>
        <tr>
            <td></td>
            <td>YouTube</td>
            <td></td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://www.sialparis.com/en/exhibitors-2026/exhibitor/ALJOMAR-3",
  "__company_name": "ALJOMAR",
  "_company_address": "Polígono Industrial I.2, C. Río Duero, s/n,, 37770, GUIJUELO, SALAMANCA, Spain",
  "_company_country": "Spain",
  "_company_website": "https://www.aljomar.es/",
  "_social_url_linkedin": "https://www.linkedin.com/company/jamones-aljomar/",
  "_social_url_facebook": "https://www.facebook.com/Aljomar?ref=ts",
  "_social_url_instagram": "https://www.instagram.com/jamonesaljomar",
  "_social_url_youtube": "https://www.youtube.com/@AljomarTV",
  "_hall_stands": "6 A162",
  "description": "ALJOMAR is a family run business exclusively devoted over 35 years to rearing, production of the highest quality IBERICO pork breed Products.",
  "brands": "ALJOMAR",
  "main_business_area": "Meat and tripe",
  "product_categories": [
    {
      "title": "Cured and salted meat",
      "subcategories": [
        {
          "title": "Cooked meat products",
          "subcategories": [
            {
              "title": " ham",
              "subcategories": null
            }
          ]
        }
      ]
    },
    {
      "title": "Meat and tripe",
      "subcategories": [
        {
          "title": " prepacked meat in portions",
          "subcategories": [
            {
              "title": "Prepacked  pork in portions",
              "subcategories": null
            }
          ]
        },
        {
          "title": "Vacuum packed  meat and muscle",
          "subcategories": [
            {
              "title": " vacuum packed pork",
              "subcategories": null
            }
          ]
        }
      ]
    }
  ]
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)