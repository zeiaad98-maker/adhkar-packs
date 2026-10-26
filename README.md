# adhkar-packs

Permanent hosting for the Adhkar Quran app's download-on-demand packs.
All text is a verbatim split of the workspace packs in packs-v9/ — no text was invented.

Layout:
- packs/jalalayn/{1..114}.json — one list per surah (6236 ayahs total)
- packs/irab/{1..114}.json, except Baqarah which is packs/irab/2a.json (ayahs 1-143) + 2b.json (144-286)
- packs/sarraj/{1..114}.json — ayah-keyed dicts, 3654 entries (source limit)
- packs/asbab/{1..114}.json — ayah-keyed dicts, 504 entries in 83 surahs; other surah files are {}
- packs/tadabbur/{1..114}.json — ayah-keyed dicts, 6235 entries; 80:21 is absent in the source and is not invented
- packs/surah_info/{1..114}.json — one dict per surah
- packs/page_benefits/{1..604}.json — one list per page, 2212 benefits total

Raw base: https://raw.githubusercontent.com/zeiaad98-maker/adhkar-packs/main/packs/
