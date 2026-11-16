# Elkin's Pool Service: sample site

A one-page sample site I put together for Elkin's Pool Service (Fort Worth, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-elkins-pool.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to elkin.poolservice@gmail.com, and the phone buttons dial (817) 448-5739. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from Elkin's Pool Service's own website and public listings: business name, owner Elkin Agudelo (BBB profile), southwest Fort Worth, phone, email, the services and neighborhoods listed on elkinpoolservice.com, and a short quote from its contact page. Anything I couldn't confirm is left out or marked to be confirmed. There are no reviews, ratings, prices, years in business or team photos.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows Elkin's Pool Service, its people or its work.

- `backyard-pool.jpg`: "A Swimming Pool beside a Wooden Plank" by Matheus Bertelli on Pexels (https://www.pexels.com/photo/a-swimming-pool-beside-a-wooden-plank-9056671/)
- `ripples.jpg`: "Rippling Water Effect in a Blue Pool" by P Lemme on Pexels (https://www.pexels.com/photo/rippling-water-effect-in-a-blue-pool-38492036/)
- `garden-pool.jpg`: "A Swimming Pool in the Garden" by Igor Kocka on Pexels (https://www.pexels.com/photo/a-swimming-pool-in-the-garden-17577509/)

Fonts: Fraunces, Work Sans (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil
