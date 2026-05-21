# Image Inventory — whymovetodallas.com
**Only download what's listed here — images actually used in current pages**

Save each file to this folder (`public/images/`) using the filename in the "Save As" column.
Once all images are here, run `node scripts/swap-image-urls.js` to update all HTML files automatically.

---

## Kristen Photos (5)
| Save As | Squarespace URL | Used In |
|---------|----------------|---------|
| `kristen-headshot-01.webp` | `.../9da8a3c5.../Kristen+Carpentier+01.webp` | All email footers, landing page |
| `kristen-headshot-02.jpg` | `.../0011dbe7.../Kristen2023-04.jpg` | Pages |
| `kristen-headshot-03.png` | `.../2a33af97.../Kristen_Carpentier_02.png` | Pages |
| `kristen-headshot-04.png` | `.../e999da7a.../Kristen+Carpentier+DFW+Realtor.png` | Pages |
| `kristen-headshot-05.jpg` | `.../carpentier-headshot.jpg` | Homepage |

## Logo & Brand (2)
| Save As | Squarespace URL | Used In |
|---------|----------------|---------|
| `logo-white.webp` | `.../Carpentier_Group_Website_Logo_White_01.webp` | Homepage nav |
| `social-og-image.webp` | `static1.squarespace.com/.../social+image+carpentier+group.webp` | OG/social share image |

## Suburb Hero Images (12)
| Save As | Squarespace URL | Used In |
|---------|----------------|---------|
| `frisco-hero.webp` | `.../Living+in+Frisco+Texas+Hero+Image.webp` | Frisco page hero |
| `frisco-the-star.webp` | `.../Living+in+Frisco+Texas+-+The+Star.webp` | Frisco page |
| `frisco-skyline.webp` | `.../frisco-tx-skyline.webp` | Frisco page |
| `flower-mound-hero.webp` | `.../Flower+Mound+Texas+Lakeside+Community....webp` | Flower Mound page hero |
| `flower-mound-high-school.webp` | `.../Flower+Mound+High+School.webp` | Flower Mound page |
| `argyle-hero.webp` | `.../argyle-texas-hero.webp` | Argyle page hero |
| `argyle-harvest.webp` | `.../Argyle_Harvest.webp` | Argyle page |
| `argyle-harvest-community.png` | `.../Argyle_Harvest_Community.png` | Argyle page |
| `allen-hero.webp` | `.../Allen+Texas+Homes+on+Golf+Course.webp` | Allen page hero |
| `arlington-hero.webp` | `.../Arlington+Stadium.webp` | Arlington page hero |
| `plano-hero.webp` | `.../Living+in+Plano+Texas+-+Legacy+West+Shopping.webp` | Plano page hero |
| `mckinney-hero.jpeg` | `.../McKinney+Texas+Downtown+Christmas.jpeg` | McKinney page hero |
| `anna-hero.png` | `.../ANNA-DRONE-TOWER.png` | Anna page hero |
| `addison-hero.webp` | `.../Addison_texas.webp` | Addison page hero |
| `southlake-hero.webp` | `.../Southlake+Texas+Bicentennial+Park.webp` | Southlake page hero |
| `suburbs-hero.webp` | `.../Suburb_Dallas_Hero_01.webp` | Suburbs index hero |

## Suburb Thumbnail Cards — Homepage (12)
| Save As | Squarespace URL | Used In |
|---------|----------------|---------|
| `frisco-thumb.webp` | `.../FRISCO_SUBURB_THUMB.webp` | Homepage suburb grid |
| `flower-mound-thumb.webp` | `.../FLOWER_MOUND_Suburb_Thumb.webp` | Homepage suburb grid |
| `allen-thumb.webp` | `.../ALLEN_SUBURB_THUMB.webp` | Homepage suburb grid |
| `argyle-thumb.webp` | `.../ARGYLE_SUBURB_THUMB.webp` | Homepage suburb grid |
| `plano-thumb.webp` | `.../PLANO_SUBURB_THUMB.webp` | Homepage suburb grid |
| `southlake-thumb.webp` | `.../SOUTHLAKE_SUBURB_THUMB.webp` | Homepage suburb grid |
| `mckinney-thumb.webp` | `.../MCKINNEY_SUBURB_THUMB.webp` | Homepage suburb grid |
| `coppell-thumb.webp` | `.../COPPELL_SUBURB_THUMB.webp` | Homepage suburb grid |
| `colleyville-thumb.webp` | `.../COLLEYVILLE_SUBURB_THUMB.webp` | Homepage suburb grid |
| `keller-thumb.webp` | `.../KELLER_SUBURB_THUMB.webp` | Homepage suburb grid |
| `highland-village-thumb.webp` | `.../HIGHLAND_VILLAGE_SUBURB_THUMB.webp` | Homepage suburb grid |
| `prosper-thumb.webp` | `.../PROSPER_SUBURB_THUMB.webp` | Homepage suburb grid |

---

## How to download from Squarespace
1. Open each Squarespace CDN URL in a browser
2. Right-click the image → Save Image As
3. Rename to the "Save As" filename above
4. Drop into this folder (`public/images/`)

## After all images are downloaded
```
node scripts/swap-image-urls.js
```
This replaces every Squarespace CDN URL in all HTML files with `/images/[filename]` automatically.
