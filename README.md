# Manul Motors — manul motors bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `manulmotors.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/manulmotors.mjs`).
> To change the content, edit that file and run `node build.mjs manulmotors` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@manulmotors.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($€[AMOUNT] / $€[AMOUNT] / $€[AMOUNT]) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are Manul Motors, a workshop in Lier maintaining and repairing cars and light vans up to three and a half tonnes, along with tractors, cultivators and mowers. The company was formed in 2023, so we claim no long history and would rather be judged on how we work. One part of that is a Belgian obligation most drivers have never had explained. Every professional intervention on a vehicle has to have its mileage transmitted to the national mileage register, which is what builds the history behind the document a seller must hand over when a second-hand car changes hands. Without that document the sale is void, which is an unusually hard consequence in consumer law. The part nobody mentions is the other side of it: a gap in that history is itself a signal to the next buyer, so a car kept outside the professional circuit, or serviced by someone who does not declare, arrives at resale with a thin record that costs its owner money. We read and transmit the mileage every time, we keep the parts we replaced so you can see them, and we stop and phone before exceeding a quote rather than after. Site: manulmotors.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
