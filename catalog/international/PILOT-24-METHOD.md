# Public ZIP metadata pilot: FP001–FP024

24 original public Release ZIPs downloaded, each matched the primary ledger SHA256 and size; ZIP CRC passed. Total30,305,877 bytes. BLEND/GLB plus license/readmes, no preview image inside these archives. Models and primary ledgers unchanged. Image coverage remains617/1008 base and104/104 variants;391 base images still need exact mapping or renders.

The packaged README documents metres and Blender Z-up. The [glTF specification](https://registry.khronos.org/glTF/specs/2.0/glTF-2.0.html#coordinate-system-and-units) defines native Y-up coordinates. The parser reads actual POSITION accessors, checks local min/max, applies active-scene hierarchical matrices/TRS and counts indexed triangle instances. No skins, morph targets or animations occurred in this pilot. Bounds are reported in native GLB coordinates and Blender convention using (x,y,z) → (x,−z,y). Triangle counts include each scene instance, not only unique mesh storage. They are not performance or collision guarantees.

Encoded root transforms are recorded. They do not establish intended placement pivots or prop facing. Modular floor/wall origin instructions in the package cannot safely be applied to all FP props; these intended-origin/facing fields remain unknown. English use sentences describe fictional static scene props, not functional products.

Blender startup terminated before model import in this environment. No settings were changed, and no model was saved. These are direct GLB measurements, not Blender readback or rendered-image verification. A later importer cross-check and individual renders remain pending. Existing group/example images are not automatically counted as per-ID previews.

[24 measurement records](pilot24-measurements.json) · [391-record production work manifest](work-manifest-391.json) · [Coverage](COVERAGE.md)

Priority: verify existing exact-model image mappings before rendering; render only missing original models; confirm intended pivots/facing from production evidence; review English uses. No new geometry requested. Image rights remain separate from model CC0; scene restrictions are retained.
