# Open MENA keyword list v1 · قائمة الكلمات المفتاحية المفتوحة

A seed list of Arabic marketing and advertising keywords for the Middle East and North Africa, with the spelling, dialect, Arabizi and French variants people actually type, the normalised form, intent and season. **No search volumes**: this list shows how people write a query, not how many search for it.

قائمة أولية بالكلمات المفتاحية التسويقية والإعلانية العربية في الشرق الأوسط وشمال أفريقيا، مع صيغ الإملاء واللهجات والعربيزي والفرنسية التي يكتبها الناس فعلًا، والصيغة الموحّدة، ونية البحث، والموسم. **لا تتضمن أحجام بحث.**

## File
- `open-mena-keywords-v1.csv` (UTF-8 with BOM), one row per keyword form per country.

## Columns
`country` (ISO code) · `dialect_group` (gulf · levant · egypt · maghreb) · `keyword` (as typed) · `variant_type` (`seed` · `spelling` · `dialect` · `arabizi` · `french`) · `is_candidate` (`yes` = a likely form not yet confirmed) · `normalised` (the form after Arabic normalisation) · `seed` (the keyword this row varies) · `lang` (AR · EN · FR) · `intent` (learn · compare · buy) · `season` (evergreen · ramadan · eid-al-fitr · eid-al-adha · white-friday · national-day)

## Please note
- Rows marked `is_candidate = yes` are likely forms, not confirmed ones.
- Volumes are left out on purpose. Don't treat row counts as demand.

## Licence
**CC BY 4.0** (see `LICENSE`), with credit: "Source: Open MENA keyword list by AdsRanger (https://adsranger.com)".

## About AdsRanger
AdsRanger is an Arabic-first platform for agencies in the region, for ads and search. In development, launching 2027.
