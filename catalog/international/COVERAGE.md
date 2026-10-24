# ID-level coverage audit / ID別対応監査

Snapshot: 1008 base distribution records +104 material variants. Counts are not unique shapes. **No claim of complete individual image coverage or complete metadata.**

```json
{
  "base": {
    "records": 1008,
    "id_mapped_preview": 1008,
    "preview_not_mapped": 0,
    "dimensions_known": 450,
    "triangles_known": 200,
    "purpose_en_present": 772,
    "formats_known": 521,
    "origin_orientation_verified": 0,
    "all_requested_metadata_verified": 0
  },
  "variant": {
    "records": 151,
    "id_mapped_preview": 151,
    "preview_not_mapped": 0,
    "dimensions_known": 0,
    "triangles_known": 0,
    "purpose_en_present": 151,
    "formats_known": 151,
    "origin_orientation_verified": 0,
    "all_requested_metadata_verified": 0
  }
}
```

Image counts mean verified existing ID-to-file mappings, not a new visual inspection of every model or proof each image isolates one object. Primary preview SHA and published ID/ZIP mappings were checked. Context/group catalogue images were not counted as individual model previews. Existing English names are present but have not all been editorially reviewed.

## Priorities

1. [Render/mapping-needed IDs](render-needed.json): first locate exact existing public-model renders, then render missing IDs. Do not create imagined images or use unrelated scene photos.
2. Confirm placement origin, up/front axes, units and triangle counts from exact distributed GLB/BLEND. Every unknown remains explicit.
3. Review English use descriptions, especially records with only generic text; link variants to their actual geometry baseline and same-condition comparisons.
4. Visually review all mapped previews and mobile pages; keep scene and image licenses separate.

All1112 records now have structured cards with names, use field, formats, dimensions, origin/orientation, polygons, download and license entry points; field presence does not mean the value is known. Fully verified against every requested field:0. No new models/images/variants were added. Primary ledgers and original URLs unchanged.


## Stage2: first24 original public ZIPs

[FP001–024 metadata pilot](PILOT-24-METHOD.md): dimensions/triangle counts/formats/units and English static-use descriptions added. Intended placement origin and facing still unknown. No new individual images. [Production work manifest for391 records](work-manifest-391.json).
