# Rural interfaces: four static modules

900 previous distribution records + 4 = 904. Global historical shape independence is unconfirmed. BLEND and GLB are two formats per record.

|ID|Download|Bytes|
|---|---|---:|
|RI101_RaisedFlume|[ZIP](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/distributions/rural-interface-v1/RI101_RaisedFlume_CC0.zip)|71971|
|RI102_SluiceDistributor|[ZIP](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/distributions/rural-interface-v1/RI102_SluiceDistributor_CC0.zip)|73971|
|RI103_DitchFence|[ZIP](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/distributions/rural-interface-v1/RI103_DitchFence_CC0.zip)|78306|
|RI104_EavesDownchute|[ZIP](https://raw.githubusercontent.com/k3peta/tales-on-a-table/main/distributions/rural-interface-v1/RI104_EavesDownchute_CC0.zip)|68838|

## Placement and limits

- RI101_RaisedFlume: 2m NS supported flume. Open ends y+-1, wet width .6m, bed Z1, side top1.3. Ground feet Z0.
- RI102_SluiceDistributor: 2x2m supported distributor. S(0,-1,1), N(0,1,1), E(1,0,1) bed ports, .6m wet width. Gate fixed raised, .39m gap beneath gate. No animated or hydraulic simulation.
- RI103_DitchFence: 2m fence bay across ditch. Bank origin Z0, post bottoms0; centre hanging slat bottom-.46m. Intended .5m deep ditch, .04m clearance. Fixed slats and hinge pins, no movement or collision test.
- RI104_EavesDownchute: Attachment module: NS gutter y-1..1 at bedZ2; chute y1..2 drops to bedZ1. Wet width.6m, walls.3m. Attach to eaves/wall; not ground-supported. Outlet (0,2,1) fits raised flume. Roof and wall not included.

Metres, Z up, origin zero. RI103 origin is the bank datum: its hanging boards extend down into the ditch. RI104 is an elevated attachment, not a ground-standing object; roof and wall are separate. Match channel bed heights and 0.6 m clear widths. Water surfaces are not included.

Static miniature models. Water flow, gate or hinge movement, collision, actual walking, structural strength, Blender 4.3.2 compatibility and full historical independence are unverified. Production checked sampled geometry and Blender 5.2.2 reloading, not complete functional systems. Overlapping solids are not manifold unions. Append the named Collection from BLEND.

Model geometry and included display materials only are CC0-1.0. No source code, images, private records or assembled scenes are included. [Checksums](../distributions/rural-interface-v1/SHA256SUMS.txt).
