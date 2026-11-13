# PaiNai (ไปไหน)

**Learn Thailand by doing, one quest at a time.**

PaiNai is a travel quest app for foreign visitors (and Thai travelers) to learn Thai language, culture and history through real-world missions, such as ordering food in Thai, bargaining at a market, or following the filming locations of Thai series.

🔗 **Live prototype:** https://painaideethailand.netlify.app

> This is a clickable UI prototype. Voice scoring, payments and location checks are simulated.

## What's in the prototype

**Traveler app (English)**
- Onboarding: name, country, food preferences, travel style, Trip Pass
- Quest map of Yaowarat (Bangkok Chinatown), drawn from real coordinates
- Quest flow: practice the Thai phrase with tone feedback → walk to the spot → scan the shop QR → stamp and reward
- Explore: categories, search, a Series Trail (Duang With You filming locations)
- Squad: friends, location sharing during team quests, chat, public groups
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
- Sponsored seasonal quest campaigns
- Studio partnerships for official series trails

## Data notes

- Places, history and filming locations are real. Sources: MICHELIN Guide Thailand (2019 article on Yaowarat street food), BL Scene filming-location guides, Wikipedia/Wikivoyage.
- Partner deals shown at real shops are examples. These shops have not joined PaiNai.
- The partner shop "ร้านเจ๊น้อยผัดไทย" and all user names and numbers are fictional.
- The Series Trail is an unofficial fan trail and lists only public places.

## Run locally

Open `index.html` in a browser. No build step. Fonts load from Google Fonts, so an internet connection is needed.
