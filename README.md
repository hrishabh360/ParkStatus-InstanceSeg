# ParkSlot-Seg3 🚗🅿️
Instance segmentation of **parking slots** into **Empty / Occupied / Wrongly Parked** using **YOLOv8-Seg**.  
We will build a small, novel campus dataset with **polygon masks** and fine-tune a COCO-pretrained model.

## Team
- Hrishabh Mahaju  
- Ayush Dongol

## Motivation
Parking photos often show many slots at once. We need **per-slot** understanding, not just cars.  
Instance segmentation lets us classify each slot as **Empty**, **Occupied**, or **Wrongly Parked**.

## Tasks & Classes
- **Task:** Instance Segmentation (per-slot polygon + class)  
- **Classes (3):** `empty`, `occupied`, `wrongly_parked`

## Data (ours)
- **Source:** Campus photos (self-collected).  
- **Annotation:** `makesense.ai` (Polygon / Segmentation).  
- **Export:** **COCO** JSON with `segmentation` polygons.

> **Privacy:** plates/faces will be blurred before publishing.

## Repo Structure
