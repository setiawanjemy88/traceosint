# traceosint
Trace osint locator

https://trace-osint-7pj4.arcada.app
Website artifact
Done. Built TRACE.OSINT — a geolocation intelligence console with a green hacker/terminal aesthetic inspired by OSINT finder tools.

Key features
Three target vectors — search by phone number, username, or email, each with tailored scan sequences (SS7/HLR for phones, Sherlock-style enumeration for usernames, MX/SMTP/HIBP for emails).

Accurate interactive map — real Leaflet map with a dark CARTO basemap, glowing pulsing green markers, an accuracy-radius circle (±meters), and auto-fit bounds across primary + secondary "sighting" pins. Phone searches auto-detect the country code (e.g. +62 → Indonesia) and bias the geofix to that region.

Live scan terminal — log lines stream in one-by-one with color-coded modules (SS7, CELL, GEO, BREACH…) and a blinking cursor, plus a sweeping radar line over the map during acquisition.

Full intelligence dossier — confidence ring, lat/lng/accuracy/timezone, network signature (IP, ISP, ASN, carrier, connection), device fingerprint (OS/browser/device), social enumeration across 10 platforms with live profile links, and a breach-corpus panel (LinkedIn, Facebook, Collection #1, etc.) with exposed data fields.

Authentic OSINT look — Orbitron/Share Tech Mono fonts, scanline overlay, grid background, glowing text, radar logo, live UTC clock, status pills, and corner brackets on the map feed.

Deterministic engine — same input always yields the same output (FNV-1a hash + mulberry32 PRNG), so results feel consistent and real. A clear disclaimer states all data is synthetically generated and no real networks/people are queried — the tool is for understanding OSINT methodology and privacy risks.

Fully responsive (stacks on mobile, side-by-side on desktop) and deployed.
