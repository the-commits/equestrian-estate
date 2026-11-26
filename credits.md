# Asset credits

Third-party assets used on this site and their licenses.

| Asset | Source | License | Credit |
|---|---|---|---|
| Oak wood planks | [source](https://polyhaven.com/a/oak_wood_planks) | CC0-1.0 | Poly Haven |
| Dark wooden planks | [source](https://polyhaven.com/a/dark_wooden_planks) | CC0-1.0 | Poly Haven |
| Cobblestone floor 04 | [source](https://polyhaven.com/a/cobblestone_floor_04) | CC0-1.0 | Poly Haven |
| Large sandstone blocks | [source](https://polyhaven.com/a/large_sandstone_blocks) | CC0-1.0 | Poly Haven |
| Brick floor | [source](https://polyhaven.com/a/brick_floor) | CC0-1.0 | Poly Haven |
| Brown leather | [source](https://polyhaven.com/a/brown_leather) | CC0-1.0 | Poly Haven |
| Grass ground | [source](https://polyhaven.com/a/grass_ground) | CC0-1.0 | Poly Haven |
| Evening field (HDRI, Sergej Majboroda) | [source](https://polyhaven.com/a/evening_field) | CC0-1.0 | Poly Haven |
| Shrub 03 | [source](https://polyhaven.com/a/shrub_03) | CC0-1.0 | Poly Haven |
| Shrub 02 | [source](https://polyhaven.com/a/shrub_02) | CC0-1.0 | Poly Haven |
| Close-up of a bay horse (Ashgrove Nocturne) | [source](https://www.pexels.com/photo/close-up-of-a-bay-horse-16884193/) | Pexels | Photo by Klaudia Lorenc on Pexels |
| Chestnut horse in a stable (Thornmere Valerian) | [source](https://www.pexels.com/photo/close-up-shot-of-a-head-of-a-horse-7572099/) | Pexels | Photo by Doğancan Basalak on Pexels |
| Black horse in the arena (Brightwater Aurelius) | [source](https://www.pexels.com/photo/elegant-black-arabian-horse-in-dressage-pose-30728846/) | Pexels | Photo by Moussa Idrissi on Pexels |
| Oak bark (Jolcham) | [source](https://polyhaven.com/a/jolcham_oak_bark_01) | CC0-1.0 | Poly Haven |

## Made for this site

- **Horses** (`scripts/make-horse.mjs`): generated in code as a signed distance field of lofts and anatomical volumes, meshed, simplified and given generated mane, forelock and tail strands. The side silhouette is fitted to within ±5 mm of an outline traced from a side-profile reference photograph of a chestnut sport horse supplied by the site owner (`scripts/trace-reference.mjs`; only the derived outline curves are kept, not the photo); cross-section widths and the hidden edges of the legs follow equine conformation measurements ([Wikipedia: Equine conformation](https://en.wikipedia.org/wiki/Equine_conformation)). The shape of the trunk cross-sections (where the body is widest, how it narrows to the back and withers) follows width ratios measured on a reference 3D horse model that is not part of this site; only those ratios were taken. No third-party model geometry was used.
- **Trees** (`scripts/make-trees.mjs`): grown procedurally (recursive branching with pipe-model radii and leaf-cluster cards); the leaf atlas is drawn in code. Bark uses the CC0 Poly Haven texture listed above.
- **Stable architecture, props and procedural surfaces** (brass, iron, straw, mist): built in code for this site.
