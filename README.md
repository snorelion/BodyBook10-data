# BodyBook10 — derived anatomy packs

Per-region 3D "packs" used by the **BodyBook10** app (iPhone/iPad): bones, muscles and ligaments
baked at 5° steps of joint motion. Each region is a `*.json` (structure list, piece transforms per
angle) + `*.bin` (vertex data). Regions: body (static whole body), knee, hip, ankle, spine, shoulder,
elbow, forearm, hand (fist / wrist / thumb), neck (flexion / rotation / bend).

## License — CC BY-SA 4.0

These packs are **derivative works of [Z-Anatomy](https://github.com/Z-Anatomy)**
(CC BY-SA 4.0), which is itself based on **BodyParts3D** © The Database Center for Life Science
(CC BY-SA 2.1 Japan). They are therefore shared under the same
[Creative Commons Attribution-ShareAlike 4.0](LICENSE) license.

Changes made by BodyBook10: meshes were selected, cropped, decimated and re-posed per joint angle;
ligament bands were rebuilt from attachment points; muscle paths were recomputed for each angle.
Joint motion is informed by the OpenSim Rajagopal 2016 full-body model (Stanford NMBL).

App code and texts of BodyBook10 are **not** part of this repository.
Web: https://bodybook10.vercel.app · Contact: snorelion@gmail.com
