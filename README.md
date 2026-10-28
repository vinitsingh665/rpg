# Game Assets Directory

Organized for a **2D retro / tile-based old-school game**.

---

## Folder Structure

`
assets/
├── spritesheets/                             # Raw grid source images (archived)
│   ├── trees_5x5_raw.png
│   ├── rocks_5x5_raw.png
│   ├── plants_5x5_raw.png
│   ├── houses_4x4_raw.png
│   ├── fences_5x5_raw.png
│   ├── settlements_4x4_raw.png
│   ├── roads_5x5_raw.png
│   └── water_5x5_raw.png
│
├── environment/
│   ├── terrain/
│   │   ├── roads/          (25 sprites)      # Dirt, cobblestone, wooden plank, gravel, stone steps
│   │   └── water/          (25 sprites)      # Open water, shores, edges, islands, docks, bridges, waterfalls, rivers
│   │
│   ├── objects/
│   │   ├── trees/          (25 sprites)      # Deciduous, conifers, exotic, dead
│   │   ├── rocks/          (15 sprites)      # Mossy boulders, ruins, arches, cave entrances
│   │   ├── stumps/          (5 sprites)      # Tree stumps, exposed roots
│   │   ├── logs/            (5 sprites)      # Fallen logs, hollow trunks, broken branches
│   │   └── plants/
│   │       ├── bushes/      (5 sprites)      # Flowering shrubs
│   │       ├── foliage/     (6 sprites)      # Broadleaf, ferns, hosta
│   │       ├── flowers/     (9 sprites)      # Wild flowers, bluebells, cosmos
│   │       └── grass_tufts/ (5 sprites)      # Pampas, reeds, wild grasses
│   │
│   └── structures/
│       ├── houses/         (16 sprites)      # Cottages, taverns, shops, towers, castles, ruins
│       ├── settlements/    (16 sprites)      # Manors, windmills, cathedrals, markets, gates, shrines
│       ├── fences/         (25 sprites)      # Wood rails, stone walls, gates, hedges, iron railings
│       ├── structure_01_stone_arch.png       # Ancient stone arch
│       └── structure_02_cave_entrance.png    # Cave entrance
│
├── characters/
│   ├── player/                               # Player animations — pending
│   ├── enemies/                              # Enemy sprites — pending
│   └── npcs/                                 # NPC characters — pending
│
├── items/                                    # Collectibles, weapons, keys — pending
├── ui/                                       # HUD elements — pending
└── audio/
    ├── sfx/                                  # Sound effects — pending
    └── music/                                # Background / chiptunes — pending
`---

## Asset Catalog

### 🌳 Trees (`environment/objects/trees/`) — 25 sprites

| # | File | Description |
|---|------|-------------|
| 01 | `tree_01_green_oak.png` | Green summer oak |
| 02 | `tree_02_bright_oak.png` | Bright light-green oak |
| 03 | `tree_03_autumn_orange.png` | Autumn orange maple |
| 04 | `tree_04_cherry_blossom.png` | Pink cherry blossom |
| 05 | `tree_05_weeping_willow.png` | Weeping willow |
| 06 | `tree_06_round_oak.png` | Round spreading oak |
| 07 | `tree_07_white_birch.png` | White-bark birch |
| 08 | `tree_08_red_maple.png` | Vivid red maple |
| 09 | `tree_09_golden_birch.png` | Golden autumn birch |
| 10 | `tree_10_white_flowering.png` | White blossom tree |
| 11 | `tree_11_pine_forest.png` | Dark forest pine |
| 12 | `tree_12_tall_fir.png` | Tall fir / spruce |
| 13 | `tree_13_cedar.png` | Cedar / pine |
| 14 | `tree_14_blue_spruce.png` | Blue Colorado spruce |
| 15 | `tree_15_slender_cypress.png` | Slender Italian cypress |
| 16 | `tree_16_spreading_canopy.png` | Wide spreading canopy tree |
| 17 | `tree_17_ancient_bonsai.png` | Ancient gnarled bonsai |
| 18 | `tree_18_flowering_bush.png` | Large flowering bush-tree |
| 19 | `tree_19_broad_acacia.png` | Broad flat-top acacia |
| 20 | `tree_20_slender_birch.png` | Tall slender birch |
| 21 | `tree_21_dead_spooky.png` | Dead bare spooky tree |
| 22 | `tree_22_golden_shrub.png` | Golden-leaf shrub tree |
| 23 | `tree_23_apple_berry.png` | Apple / berry fruit tree |
| 24 | `tree_24_ancient_olive.png` | Ancient twisted olive |
| 25 | `tree_25_wisteria_purple.png` | Purple wisteria vine tree |

---

### 🪨 Rocks (`environment/objects/rocks/`) — 15 sprites

| # | File | Description |
|---|------|-------------|
| 01 | `rock_01_mossy_boulder.png` | Large mossy boulder cluster |
| 02 | `rock_02_mossy_mound.png` | Mossy stone mound |
| 03 | `rock_03_sharp_stone_peak.png` | Sharp jagged stone peak |
| 04 | `rock_04_stone_slab_altar.png` | Flat stone slab / altar |
| 05 | `rock_05_mossy_outcrop.png` | Mossy rocky outcrop |
| 06 | `rock_06_stepped_boulder.png` | Stepped boulder formation |
| 07 | `rock_07_pillar_ruin.png` | Stone pillar ruin |
| 08 | `rock_08_monolith_cluster.png` | Monolith cluster formation |
| 09 | `rock_09_ruined_stone_stairs.png` | Ruined stone staircase |
| 10 | `rock_10_brick_platform_ruin.png` | Brick platform ruin |
| 11 | `rock_11_large_flat_pedestal.png` | Large flat stone pedestal |
| 12 | `rock_12_stepped_ruin_garden.png` | Stepped ruin with vegetation |
| 13 | `rock_13_twin_stone_peaks.png` | Twin stone peaks |
| 14 | `rock_14_ancient_stone_arch.png` | Ancient stone arch *(also in structures/)* |
| 15 | `rock_15_cave_entrance.png` | Cave entrance *(also in structures/)* |

---

### 🪵 Stumps (`environment/objects/stumps/`) — 5 sprites

| # | File | Description |
|---|------|-------------|
| 01 | `stump_01_cut_stump_mushrooms.png` | Cut stump with red mushrooms |
| 02 | `stump_02_hollow_jagged_stump.png` | Hollow jagged stump |
| 03 | `stump_03_wide_roots_stump.png` | Wide stump with exposed roots |
| 04 | `stump_04_flat_wood_stump.png` | Flat-top wood stump |
| 05 | `stump_05_broken_trunk_stump.png` | Broken trunk stump with mushrooms |

---

### 🪵 Logs (`environment/objects/logs/`) — 5 sprites

| # | File | Description |
|---|------|-------------|
| 01 | `log_01_mossy_fallen_trunk.png` | Large mossy fallen trunk |
| 02 | `log_02_hollow_log_tunnel.png` | Hollow log tunnel |
| 03 | `log_03_stacked_mossy_logs.png` | Stacked mossy logs |
| 04 | `log_04_curved_root_log.png` | Curved root-covered log |
| 05 | `log_05_splintered_rotting_log.png` | Splintered rotting log |

---

### 🌿 Plants (`environment/objects/plants/`)

#### Bushes — 5 sprites
| File | Description |
|------|-------------|
| `bush_01_white_flowering.png` | White flowering bush |
| `bush_02_pink_flowering.png` | Pink flowering bush |
| `bush_03_blue_hydrangea.png` | Blue hydrangea bush |
| `bush_04_red_berry.png` | Red berry bush |
| `bush_05_yellow_buttercup.png` | Yellow buttercup bush |

#### Foliage — 6 sprites
| File | Description |
|------|-------------|
| `foliage_01_broadleaf_shrub.png` | Broadleaf green shrub |
| `foliage_02_autumn_red_shrub.png` | Autumn red-leaf shrub |
| `foliage_03_forest_fern.png` | Forest fern |
| `foliage_04_white_anemone.png` | White anemone foliage |
| `foliage_05_purple_lavender.png` | Purple lavender |
| `foliage_06_broadleaf_hosta.png` | Broadleaf hosta plant |

#### Flowers — 9 sprites
| File | Description |
|------|-------------|
| `flower_01_white_clover.png` | White clover patch |
| `flower_02_yellow_wildflower.png` | Yellow wildflowers |
| `flower_03_white_daisies.png` | White daisies |
| `flower_04_pink_bellflowers.png` | Pink bellflowers |
| `flower_05_bluebells.png` | Blue bluebells |
| `flower_06_forget_me_nots.png` | Blue forget-me-nots |
| `flower_07_red_cosmos.png` | Red cosmos flowers |
| `flower_08_purple_asters.png` | Purple asters |
| `flower_09_orange_marigolds.png` | Orange marigolds |

#### Grass Tufts — 5 sprites
| File | Description |
|------|-------------|
| `grass_tuft_01_pampas.png` | Pampas grass |
| `grass_tuft_02_wild_wheat.png` | Wild wheat grass |
| `grass_tuft_03_golden_reeds.png` | Golden reeds |
| `grass_tuft_04_tall_forest_grass.png` | Tall forest grass |
| `grass_tuft_05_autumn_grass.png` | Autumn red grass |

---

### 🏛️ Structures (`environment/structures/`) — 2 sprites
| File | Description |
|------|-------------|
| `structure_01_stone_arch.png` | Ancient stone arch |
| `structure_02_cave_entrance.png` | Cave entrance |

---

### 🏠 Buildings (`environment/structures/houses/`) — 16 sprites

| Row | Category | Files |
|---|---|---|
| 1 | Cottages & Farmhouses | `house_01_thatched_cottage`, `house_02_tudor_farmhouse`, `house_03_stone_manor`, `house_04_open_market_stall` |
| 2 | Taverns & Shops | `house_05_blacksmith_forge`, `house_06_inn_tavern`, `house_07_merchants_shop`, `house_08_trading_post` |
| 3 | Towers & Castles | `house_09_wooden_watchtower`, `house_10_stone_tower`, `house_11_castle_gatehouse`, `house_12_fort_entrance` |
| 4 | Ruins & Dungeons | `house_13_stone_bridge_arch`, `house_14_ruined_archway`, `house_15_dungeon_gate`, `house_16_shrine_memorial` |

---

### 🚧 Fences (`environment/structures/fences/`) — 25 sprites

| Row | Category | Files |
|---|---|---|
| 1 | Simple Wood | `fence_01` wood rail · `fence_02` rail ivy · `fence_03` picket · `fence_04` cross brace · `fence_05` rope post |
| 2 | Stone Walls | `fence_06` stone rail · `fence_07` stone+wood · `fence_08` stone wall · `fence_09` lamp wall · `fence_10` ivy wall |
| 3 | Gates & Iron | `fence_11` palisade · `fence_12` pointed · `fence_13` wood gate+lamp · `fence_14` stone arch gate · `fence_15` iron railing |
| 4 | Decorative/Mixed | `fence_16` iron lamp gate · `fence_17` x-brace · `fence_18` wicker twig · `fence_19` iron cross · `fence_20` rustic rope |
| 5 | Banner/Garden/Ornate | `fence_21` royal banner · `fence_22` tall plank · `fence_23` garden hedge · `fence_24` bamboo · `fence_25` ornate iron |

---

### 🏰 Settlements (`environment/structures/settlements/`) — 16 sprites

| Row | Category | Files |
|---|---|---|
| 1 | Estates & Landmarks | `settle_01_manor_fountain` · `settle_02_windmill` · `settle_03_signal_tower` · `settle_04_cathedral` |
| 2 | Commerce & Forts | `settle_05_blacksmith` · `settle_06_market_stalls` · `settle_07_castle_gate` · `settle_08_angel_fountain` |
| 3 | Coastal & Crossings | `settle_09_lighthouse` · `settle_10_river_bridge` · `settle_11_warlord_gate` · `settle_12_crystal_fountain` |
| 4 | Rustic & Spiritual | `settle_13_ruined_arch` · `settle_14_stable_barn` · `settle_15_village_well` · `settle_16_chapel_shrine` |

---

### 🛣️ Roads & Paths (`environment/terrain/roads/`) — 25 sprites

| Row | Category | Files |
|---|---|---|
| 1 | Dirt Paths | `road_01_dirt_straight_v` · `road_02_dirt_straight_v2` · `road_03_dirt_curve_bl` · `road_04_dirt_curve_br` · `road_05_dirt_t_junction` |
| 2 | Cobblestone | `road_06_cobble_straight_v` · `road_07_cobble_straight_h` · `road_08_cobble_straight` · `road_09_cobble_curve` · `road_10_cobble_cross` |
| 3 | Plank Bridges & Decks | `road_11_plank_straight_v` · `road_12_plank_straight_h` · `road_13_plank_bridge` · `road_14_plank_curve` · `road_15_plank_junction` |
| 4 | Gravel Paths | `road_16_gravel_straight_v` · `road_17_gravel_straight_h` · `road_18_gravel_wide` · `road_19_gravel_curve` · `road_20_gravel_path` |
| 5 | Stone Stairs & Plazas | `road_21_stone_stairs_left` · `road_22_stone_stairs_mid` · `road_23_stone_landing` · `road_24_cobble_circle` · `road_25_stone_roundabout` |

---

### 🌊 Water & Coastlines (`environment/terrain/water/`) — 25 sprites

| Row | Category | Files |
|---|---|---|
| 1 | Deep & Shallow Waters | `water_01_open_water` · `water_02_deep_water` · `water_03_shallow_water` · `water_04_water_lilypads` · `water_05_shore_shallow` |
| 2 | Shorelines & Edges | `water_06_edge_top` · `water_07_edge_bottom` · `water_08_edge_left` · `water_09_edge_right` · `water_10_corner_topleft` |
| 3 | Corners & Islands | `water_11_corner_topright` · `water_12_corner_bottomleft` · `water_13_corner_bottomright` · `water_14_island_small` · `water_15_island_large` |
| 4 | Docks, Bridges & Falls | `water_16_dock_pier` · `water_17_wooden_bridge` · `water_18_stone_bridge` · `water_19_waterfall_top` · `water_20_waterfall_bottom` |
| 5 | Rivers & Tributaries | `water_21_river_vertical` · `water_22_river_horizontal` · `water_23_river_inflow` · `water_24_river_outflow` · `water_25_river_tjunction` |

---

## Pending Assets
- `characters/player/` — Player sprite sheets
- `characters/enemies/` — Enemy sprites
- `characters/npcs/` — NPC characters
- `items/` — Collectibles, weapons, keys
- `ui/` — HUD elements
- udio/ — Sound effects and music
