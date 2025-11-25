# Data Folder

This folder contains the raw Pokémon data used in our STOR 664 project and a processed version prepared for analysis. The dimension of the dataset is 949 rows × 22 columns. Each row corresponds to a Pokémon species or form. Columns include: - Basic identifiers: pokemon, id, species_id

-   Basic statistics: height, weight, base_experience

-   Base stats: hp, attack, defense, special_attack, special_defense, speed

-   Typing: type_1 (primary type), type_2 (secondary type, often NA for single-type Pokémon)

-   Visual/metadata: color_1, color_2, color_f

-   Breeding: egg_group_1, egg_group_2

-   Design era: generation_id

-   Image/icon URLs: url_icon, url_image

Source: TidyTuesday, 2025-04-01 Pokémon dataset (loaded via `tidytuesdayR::tt_load(2025, week = 13)`).

The processed dataset removed the following columns: `id`, `species_id`, `color_1`, `color_2`, `color_f`, `url_icon`, `url_image`.

## Structure

``` text
dataset/
├── raw/
│   └── pokemon_raw.csv
└── processed/
    └── pokemon_processed.csv
```
