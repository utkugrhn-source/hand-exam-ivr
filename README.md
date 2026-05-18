# Hand Examination IVR

WebXR-based interactive hand/wrist physical examination training module for medical students. Built with A-Frame, deployable via GitHub Pages, designed for Meta Quest 3 with native hand tracking.

## Access

Once deployed, open the GitHub Pages URL in **Meta Quest Browser** on a Quest 3 headset, click "Enter VR", and proceed through:
1. Lobby (orientation)
2. Klinik (clinical scene with hand tracking palpation of 8 maneuvers)
3. Quiz (placeholder, v6 to integrate 15 MCQ)
4. Survey (placeholder)
5. Thank you

## 8 examination maneuvers

Tinel · Phalen · Finkelstein · Watson scaphoid shift · Grind · FCR · FDS · Bunnel-Littler

## Asset credits

- Clinical environment skybox: **"Hospital Room" HDRI** by Oliksiy Yakovlyev (Poly Haven, [CC0](https://polyhaven.com/license)). https://polyhaven.com/a/hospital_room
- Patient figure: **"CC0 Block Man Auto Rigged Humanoid"** by Liam Pillay (Sketchfab, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)). https://sketchfab.com/3d-models/cc0-block-man-auto-rigged-humanoid-55571b5d47614b4c9973e853fc6b6a72
- Anatomical hand model: **"Hand Skeleton & Skin"** by Novaky (Sketchfab, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)). https://sketchfab.com/3d-models/hand-skeletonskin-e24e96b6bc39423b871b10f098876b8f

## Tech stack

- A-Frame 1.5.0 (WebXR framework)
- Quest 3 native hand tracking (WebXR Hands Module)
- Custom A-Frame component `palpation-zone` for proximity-based maneuver triggering

## Modes

- Default (intervention): all 8 palpation zones active, hand tracking enabled
- Sham control: `?mode=sham` URL parameter; zones hidden, clinical scene visible only

## Status

Research preview / pilot study development. Pre-publication.
