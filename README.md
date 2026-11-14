# PaiPlao (ไปป่าว)

**Wanna go? Learn Thailand one quest at a time.**

The name comes from the Thai phrase "ไปป่าว" (pai plao), casual Thai for "wanna go?" or "going with me?".

PaiPlao is a travel quest app for foreign visitors (and Thai travelers) to learn Thai language, culture and history through real-world missions, such as ordering food in Thai, bargaining at a market, or following the filming locations of Thai series.

🔗 **Live prototype:** https://painaideethailand.netlify.app

> This is a clickable UI prototype. Voice scoring, payments and location checks are simulated.

## What's in the prototype

**Traveler app (English)**
- Onboarding: name, country, food preferences, travel style, Trip Pass
- Quest map of Yaowarat (Bangkok Chinatown), drawn from real coordinates
- Quest flow: practice the Thai phrase with tone feedback → walk to the spot → scan the shop QR → stamp and reward
- Explore: categories, search, a Series Trail (Duang With You filming locations)
- Create a route (Phase 2 preview): build a quest route from verified public places, write a scenario, send it for review, earn coins when others play it
- Squad: private friend groups by invite link, location sharing within the squad, chat
- Passport: streak, stamps, coupons, coin rewards

**Partner app (Thai)**
- Shop dashboard: credit balance, verified visits, visitor nationalities
- Propose a new quest and track approval
- Top up credit (pay per verified visit)
- Shop QR code

## Business model

- Partner shops pay per verified visit (QR + GPS), not a flat ad fee
- Booking commissions (classes, tours, experiences)
- Trip Pass: one-time 7 or 14-day pass, no auto-renew
- Affiliate sales: eSIM, travel insurance, airport transfers

Roadmap (not in the MVP): sponsored campaigns, team mode, seasonal events, creator-made routes (preview screen in the prototype), official licensed series trails.

## Data notes

- Places, history and filming locations are real. Sources: MICHELIN Guide Thailand (2019 article on Yaowarat street food), BL Scene filming-location guides, Wikipedia/Wikivoyage.
- Partner deals shown at real shops are examples. These shops have not joined PaiPlao.
- The partner shop "ร้านเจ๊น้อยผัดไทย" and all user names and numbers are fictional.
- The Series Trail is an unofficial fan trail and lists only public places.

## Run locally

Open `index.html` in a browser. No build step. Fonts load from Google Fonts, so an internet connection is needed.
