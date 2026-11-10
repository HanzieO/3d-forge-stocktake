# 3d Forge Stock-Take App

Internal stock-take and photo-capture tool for 3d Forge. Open the live page on a phone or computer, search the catalogue, adjust quantities, and attach photos. Everything is stored in that browser only (IndexedDB and localStorage). Use **Photos ZIP** or **Finish & Export** to download photos and CSVs.

Live site: https://hanzieo.github.io/3d-forge-stocktake/

This repo is published so the app can be served over HTTPS (needed for the camera and local storage). The page is marked `noindex` and `robots.txt` disallows crawlers. Product names, SKUs and prices are the same data already on the public Shopify store. Do not commit API tokens or other secrets.
