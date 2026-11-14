<div align="center">

# Stylized Buildings & Cities

**24 procedural building styles and 7 city generators for Blender. Built with Geometry Nodes, used by drag and drop.**

![Blender 4.5+](https://img.shields.io/badge/Blender-4.5%2B-orange?logo=blender&logoColor=white)
![Geometry Nodes](https://img.shields.io/badge/100%25-Geometry%20Nodes-2a9d8f)
![Assets](https://img.shields.io/badge/assets-31%20drag%20%26%20drop-e8793a)
![Tested](https://img.shields.io/badge/tested-4.5%20LTS%20%7C%205.2%20LTS-555)

<img src="media/hero.jpg" alt="Isometric stylized sci-fi city" width="100%">

</div>

Drag a whole stylized city into your scene. There are six themes: sci-fi, medieval fantasy, Japanese, wild west,
desert and post-apocalyptic, plus a mixed city that uses every style at once.

Every asset stays fully editable. Change one seed and you get a new building, or a whole new town.

> This repository hosts the **product page and media** only. The asset library is available on Superhive.

## Right inside Blender

Pick a city in Blender's Asset Browser and drop it into the viewport. It arrives with its generator as a modifier:
change Seed and the whole town is rebuilt, raise Blocks and it grows.

<p align="center"><img src="media/blender_dragdrop.gif" alt="Dragging a city from the Asset Browser into the viewport and changing its modifier inputs" width="100%"></p>

![Blender UI](media/blender_ui.jpg)

<p align="center"><img src="media/themes.gif" alt="The seven city generators" width="720"></p>

## Highlights

- **Drag & drop:**
  - Every building and every city is an object asset. Drag one from the Asset Browser and it appears; nothing
    has to be set up first.
  - Tweak everything live in the modifier panel.
- **Real city layouts:**
  - Blocks are surrounded by raised sidewalks, and buildings face their street.
  - Corner buildings turn to the side street, and backyards are planted.
  - There are gardens and parks.
- **Themed parks:**
  - Lawns, paths, a plaza, benches and lamps.
  - The plaza has a themed centre piece: fountains, a koi pond with a red bridge, a medieval market, an oasis,
    a windmill or a dry fountain.
- **Streets:**
  - Lane dashes and zebra crossings.
  - Street trees, corner lamps and props.
  - Cracks, potholes, puddles, manholes, petals and tumbleweeds.
- **Nature:**
  - 112 stylized plant pieces: broadleaf, cherry and autumn trees, firs, cloud pines, palms, bamboo, cacti,
    agaves, bushes and flower beds.
  - They grow in natural groves, with a subtle colour shift on every plant.
- **24 building styles:**
  - Each style is built from its own modular kit: 950+ pieces in total.
  - Kits include roofs with thousands of tiles, chimneys, dormers, signs, rooftop machinery and yard props.
- **Toon look:** inverted-hull outlines, 13 colour roles per building, window glow and grime.
- **Diorama base:** a planted tabletop base for isometric shots. Turn it off to place the city on your own terrain.

## Procedural

| New seed, new town | From one block to twelve |
|---|---|
| ![seeds](media/city_seeds.gif) | ![grow](media/city_grow.gif) |

| Fully 3D | Floors, wings, towers | 24 styles |
|---|---|---|
| ![turntable](media/turntable.gif) | ![floors](media/floors.gif) | ![styles](media/styles.gif) |

## The seven cities

| | |
|---|---|
| ![Sci-Fi](media/city_sci_fi.jpg) **Sci-Fi** | ![Medieval Fantasy](media/city_medieval_fantasy.jpg) **Medieval Fantasy** |
| ![Japanese](media/city_japanese.jpg) **Japanese** | ![Wild West](media/city_wild_west.jpg) **Wild West** |
| ![Desert](media/city_desert.jpg) **Desert** | ![Post-Apocalyptic](media/city_post_apocalyptic.jpg) **Post-Apocalyptic** |

![Mixed](media/city_mixed.jpg)
**Mixed**: all 24 styles in one city.

## Close-ups

| | |
|---|---|
| ![street](media/closeup_street.jpg) | ![park](media/closeup_park.jpg) |
| ![koi](media/closeup_koi.jpg) | ![market](media/closeup_market.jpg) |

![plants](media/plants.jpg)

## Building styles

| Theme | Styles |
|---|---|
| Sci-Fi | Medical Tower, Eco Office, Industrial Slum, Cozy Cafe, Neon Night, Residential Pastel |
| Medieval Fantasy | Tudor Townhouse, Stone Cottage, Tavern & Inn, Blacksmith, Wizard Tower, Guard Keep |
| Japanese | Machiya Townhouse, Pagoda, Tea House |
| Wild West | Saloon, General Store, Sheriff Office |
| Desert | Adobe House, Bazaar Shop, Domed Hall |
| Post-Apocalyptic | Scrap Shack, Wasteland Bunker, Ruined Block |

## City inputs

| Panel | Inputs |
|---|---|
| Layout | Seed, Blocks X / Y, Plots X / Y, Plot Size, Street Width, Sidewalk Width |
| Buildings | Gardens, Parks, Frontage, Corner Turn, Size Variation, Floor Variation, Yard |
| Nature | Street Trees, Tree Spacing, Garden Trees, Bushes & Flowers, Plant Scale |
| Ground | Lane Lines, Crosswalks, Road Decals, Street Props, Diorama Base, Base Depth & Margin |
| Colours | Road, Sidewalk, Curb, Lot, Grass, Line, Plaza, Soil, Water, Terrain |
| Look | Outline on / off, Outline Thickness |

## Requirements

- Blender 4.5 or newer (tested on 4.5 LTS and 5.2 LTS).
- No add-on, no Python, no internet connection: it is a plain `.blend` asset library.
- Cities are heavy because every building is fully detailed. A default 3×2-block city is roughly 1 to 6.5 million
  triangles depending on the theme.

## Install

1. Unzip the library somewhere permanent.
2. Go to *Edit > Preferences > File Paths > Asset Libraries*, click **+** and pick the folder.
3. Set the library's import method to **Append (Reuse Data)**.
4. Open an Asset Browser, pick *Stylized Buildings* and drag a building or a city into the viewport.
