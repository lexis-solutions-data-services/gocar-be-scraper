# GoCar.be Scraper

![banner](https://i.ibb.co/B57xgtrC/Screenshot-2025-11-26-at-10-30-27-AM.png)

## What does GoCar.be Scraper do

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `1.0.1` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `gocar-be-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---



GoCar.be Scraper helps you extract vehicle listings data from **gocar.be**, Belgium's leading online automotive marketplace for new and used cars.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-Ajo2d3HK5ITuMKsYd-fP6zMwuaQp-218757002_4658453084182197_3279410346013171365_n.png" alt="Gocar.be Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/gocar-be-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


You can extract detailed vehicle information including prices, mileage, specifications, seller details, and other key information from the website. GoCar.be Scraper supports REST API which gives you access to the extracted dataset, enables you to download it in various formats and use it in other applications.

## What data can I extract from GoCar.be with a web scraper

With this web scraping tool, you can extract the following data from GoCar.be:

<table>
<tr>
<td>🚗 Vehicle brand & model</td>
<td>💰 Price & currency</td>
</tr>
<tr>
<td>📍 Body style & type</td>
<td>🔢 Vehicle ID</td>
</tr>
<tr>
<td>📝 Description</td>
<td>⚙️ Engine power (HP/kW)</td>
</tr>
<tr>
<td>🛣️ Transmission type</td>
<td>⛽ Fuel type & category</td>
</tr>
<tr>
<td>🎨 Exterior color</td>
<td>🖼️ Vehicle images & count</td>
</tr>
<tr>
<td>📅 First registration year & label</td>
<td>⚡ Gearbox type</td>
</tr>
<tr>
<td>📏 Mileage (kilometers)</td>
<td>🏷️ Vehicle condition</td>
</tr>
<tr>
<td>🔧 Number of doors & seats</td>
<td>💨 CO2 emissions & pollution class</td>
</tr>
<tr>
<td>🏪 Seller name & type</td>
<td>📍 Location (city, address, ZIP)</td>
</tr>
<tr>
<td>🗺️ GPS coordinates</td>
<td>⚖️ Vehicle weight</td>
</tr>
<tr>
<td>🛡️ Warranty months</td>
<td>📅 Published date</td>
</tr>
<tr>
<td>🔗 Vehicle URL & slug</td>
<td>📋 Vehicle options list</td>
</tr>
</table>

## Why scrape GoCar.be

GoCar.be is Belgium's premier automotive marketplace with a comprehensive inventory of vehicles. Scraping GoCar.be can help you:

- Monitor vehicle prices and availability across Belgium
- Track inventory from professional dealers and private sellers
- Research market trends for specific makes and models
- Compare prices across different regions
- Identify the best deals in the Belgian market
- Build automotive price comparison tools

## How to use GoCar.be Scraper

GoCar.be Scraper is designed for easy and fast start even if you've never extracted data from websites before. Here's how you can extract data from GoCar.be:

1. Create a free Apify account using your email
2. Open GoCar.be Scraper on the Apify platform
3. Click on the **Try for free** button
4. Enter your search URLs or parameters
5. Click on the **Start** button and wait for the data to be extracted
6. Download your data in JSON, XML, CSV, Excel, or HTML

## Input

The actor accepts the following input parameters:

- `startUrls` (array, required) - List of GoCar.be search URLs to scrape
- `maxItems` (integer, optional) - Maximum number of listings to scrape. If not specified or set to 0, all results will be fetched
- `proxyConfiguration` (object, optional) - Proxy settings for the scraper

Example:

```json
{
  "startUrls": [
    {
      "url": "https://gocar.be/en/search?gbrands=Mercedes&gmodels=C-Class"
    }
  ],
  "maxItems": 100,
  "proxyConfiguration": {
    "useApifyProxy": true
  }
}
```

You can also search by multiple parameters:

```json
{
  "startUrls": [
    {
      "url": "https://gocar.be/en/search?gbrands=BMW&fuel=Electric&min_year=2020"
    }
  ],
  "maxItems": 0
}
```

## Output

The scraped data will be saved as a dataset. Each item will represent a vehicle listing. You can download your data in various formats: JSON, JSONL, HTML table, CSV, Excel spreadsheet, or NDJSON.

Example of the output format:

```json
{
  "id": 4812115,
  "model_name": "170",
  "version": "Sedan",
  "point_of_sale_name": "E&R Classics",
  "brand_name": "Mercedes",
  "vehicle_options_list": [],
  "body_style": "Saloon",
  "gearbox": "Manual",
  "fuel_type": "Petrol",
  "transmission": "Rear",
  "pollution_class": "Not specified",
  "main_color": "Black",
  "first_registration_year": 1952,
  "point_of_sale_city": "Waalwijk",
  "description": "Mercedes-Benz 170 VA | Good condition | 1952...",
  "slug": "27be266c-a956-4f11-86ee-fa36ce7bafd6",
  "vehicle_id": 4812115,
  "cover": "https://cdn-storage-02.prod.gocar.be/vehicles/25/09/9997534/4812115-20o.jpg?width=840",
  "published_at": "2025-09-16 13:59:13",
  "published_date": "2025-09-16",
  "is_pro": 1,
  "vehicle_type": "oldtimer",
  "price": {
    "hasDiscount": false,
    "unformatted": 34950,
    "for_filtering": 34950,
    "formatted": "34.950 €"
  },
  "new": false,
  "first_registration_label": "01/1952",
  "warranty_months": null,
  "weight": 1300,
  "kilometers": 34598,
  "fuel_type_category": "thermic",
  "images_count": 19,
  "condition": "second hand",
  "horse_power": 45,
  "engine_power_kw": 33,
  "CO2_emissions": null,
  "number_of_doors": 4,
  "number_of_seats": 4,
  "url": "https://gocar.be/en/classic-car/mercedes/170/sedan/id/4812115",
  "point_of_sale_type": "Professional",
  "point_of_sale_address": "Kleiweg 1",
  "point_of_sale_zip": "5145 NA",
  "_geo": {
    "lat": 51.692049,
    "lng": 5.046984
  }
}
```

### Additional fields you may see

- **l_bmarque / l_model / l_id_marque / l_id_modele**: Legacy brand and model identifiers
- **model_text / l_b_version**: Additional model and version information
- **discount**: Discount information when applicable
- **price.hasDiscount / price.original_price_gross / price.percent**: Discount details
- **price.professional_price / price.vat / price.price_excl_tax / price.vat_deductible**: Professional pricing and VAT information
- **search_result_weight**: Search ranking weight
- **has_phyron_video / has_carpass_check**: Additional features availability
- **last_sync_timestamp / last_modified_timestamp**: Listing update timestamps
- **smoke_filter / crashed**: Vehicle condition flags
- **fiscal_horse_power**: Fiscal horsepower rating
- **upsell_best_of / upsell_top_result / upsell_color / upsell_facebook**: Upsell features
- **brand_id / brand_slug / model_id**: Internal identifiers
- **point_of_sale_id / point_of_sale_master / point_of_sale_logo / point_of_sale_pro_first**: Seller details
- **documentTemplate**: AI-generated vehicle description and metadata


## Need to scrape other automotive websites

Check out our other automotive scrapers:

- [CarGurus Scraper](https://apify.com/lexis-solutions/cargurus-com) - Extract vehicle listings from America's leading automotive marketplace
- [CARFAX Scraper](https://apify.com/lexis-solutions/carfax-com) - Extract vehicle listings from America's trusted vehicle history platform
- [Mobile.de Scraper](https://apify.com/lexis-solutions/mobile-de-auto-scraper) - Extract vehicle listings from Germany's largest vehicle marketplace

## Want something custom-built

This GoCar.be Scraper doesn't exactly do what you need? You can always build your own! Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!