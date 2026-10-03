# Dobot

HTML and CSS product pages for the Dobot CR-Series collaborative robot (cobot) arms, part of the Trossen Robotics web projects. The CR Series is a family of 6-axis arms with payloads up to 16 kg, built-in collision detection, and drag-to-teach programming. Also includes the Dobot brand landing page and setup tutorials.

## Products

| Product | Payload | Max reach | Repeatability | Notes | Folder |
|---|---|---|---|---|---|
| CR3 | 3 kg | 795 mm | ±0.02 mm | Smallest of the four, compact for tight spaces. | `Dobot CR3/` |
| CR5 | 5 kg | 1096 mm | ±0.02 mm | Suited to inspection, assembly, screwdriving, and bin picking. | `Dobot CR5/` |
| CR10 | 10 kg | 1525 mm | ±0.03 mm | Longest reach of the four. | `Dobot CR10/` |
| CR16 | 16 kg | 1223 mm | ±0.03 mm | Highest payload of the four. | `Dobot CR16/` |

## Structure

- Each `Dobot CR*` folder holds that model's product page (`.html` and `.css`)
- `Landing Page/` - the Dobot brand landing page
- `carousel-code/` - tutorial carousel for the CR-Series using DobotSCStudio, covering the Tool Coordinate System and a pick-and-place routine with a gripper
- `Proxy edits.md` and `Specifications Edits CSS.md` - working notes for page edits

## Usage

No install or build step. Open any product's `.html` file in a browser to preview it. Keep the folder structure intact, or shared styles and images may not load.

## Notes

- Specs are maximum reach, payload, and repeatability as published by Dobot for the original CR models. Check Dobot's site for the current CRA series.
- The four product pages currently share the same intro text.