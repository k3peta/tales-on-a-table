# Stream-end repairs / 川断面修復 / 河道断面修复

**WT007/WT008 — QA status pending / 検査記録の照合待ち / 检查记录待核对**

QA reconciliation pending: final numerical BLEND/GLB report records passes, but a separate summary still records a false reimport flag. The discrepancy is unresolved. This published revision is not fully QA-cleared or a confirmed recommended replacement. Download/CRC/SHA verification does not resolve model QA.

最終数値記録は合格ですが、別QAのfalseフラグと不一致が残っています。解消まで全検査合格・推奨修正版とは扱いません。旧版にも既知の黒断面があり、旧版が正常と確認されたわけではありません。

最终数值记录为通过，另一份QA标志仍为false。差异未解决，不视为全部验证通过或推荐替换版。原版也有已知黑断面。


Two revised distribution records, zero new base models or variants. Original ZIPs/images retained as version history. Revised baseline channel_fitted_water_v2.

WT007/008 black end wedges came from coplanar overlapping water/bank surfaces. Water solid is trimmed to the existing channel, without widening water area or altering bank geometry. Water level -0.01m,2m tile retained; revised outlet water width1.188421m matches both revised tiles. No claim of arbitrary compatibility with every old tile.

水と岸の重複面を、既存岸に沿って水形状を切り詰め修復。水域拡大なし。水位と2m枠保持。欠落UV追加、既存UV保持、水Boolean部分はトポロジー/UV改訂。低ポリ化ではなく水三角形は増加。旧版・失敗初案は保全。

原版黑断面保留为历史；修订水体贴合既有河岸，没有扩大水域。保留水位与2m地块。水体拓扑/UV修改，不是减面版本。

Producer final BLEND/GLB numerical tests use repaired references; the final numerical report records passes, subject to the unresolved summary discrepancy above. Section checks report no below-bank vertices at the repaired outlets, water welded boundary/nonmanifold edges0, no tiny faces. Scoped repair, not full collision/walking/safety/Blender4.3.2 verification. Historic source script unrecovered. These2focused repairs are not added again to the cumulative assessment count.

モデル/埋込材質のみCC0。画像は閲覧用でモデルCC0対象外、[既存画像権利](../LICENSE.md)維持。代码图片私有査定不属模型CC0。

## WT007__repair — Stream straight NS

revision · [ZIP · BLEND/GLB](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/distributions/quality-wt007-008-repair-v1/WT007__repair_CC0.zip)

![WT007__repair thumbnail](../previews/quality-wt007-008-repair-v1/WT007__repair_thumb.png)

[拡大 / Full image](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/previews/quality-wt007-008-repair-v1/WT007__repair_thumb.png)

![WT007__repair comparison](../previews/quality-wt007-008-repair-v1/WT007__repair_comparison.png)

[拡大 / Full image](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/previews/quality-wt007-008-repair-v1/WT007__repair_comparison.png)

left: original base; right: revised model; same overview camera

## WT008__repair — Stream bend NE

revision · [ZIP · BLEND/GLB](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/distributions/quality-wt007-008-repair-v1/WT008__repair_CC0.zip)

![WT008__repair thumbnail](../previews/quality-wt007-008-repair-v1/WT008__repair_thumb.png)

[拡大 / Full image](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/previews/quality-wt007-008-repair-v1/WT008__repair_thumb.png)

![WT008__repair comparison](../previews/quality-wt007-008-repair-v1/WT008__repair_comparison.png)

[拡大 / Full image](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/previews/quality-wt007-008-repair-v1/WT008__repair_comparison.png)

left: original base; right: revised model; same overview camera
