# AI Design System - Data Directory

## Folder Structure
data/
├── raw-images/ # Original photos from LAKARCADE
│ ├── traditional/ # 100-120 traditional items
│ ├── fusion/ # 80-100 fusion items
│ ├── modern/ # 60-80 modern items
│ └── unsorted/ # Photos to categorize later
│
├── metadata/ # Excel/CSV files with product info
│ ├── collection_log.xlsx # Main metadata spreadsheet
│ └── notes.txt # Field notes from visit
│
└── processed/ # Prepared data (created later)
├── train/ # 80% for training
└── test/ # 20% for testing


## Naming Convention

### For Images
Format: `[CATEGORY]_[TYPE]_[NUMBER].jpg`

Examples:
- `TRAD_MASK_001.jpg` (Traditional mask #1)
- `FUSION_ELEPHANT_012.jpg` (Fusion elephant #12)
- `MODERN_METAL_005.jpg` (Modern metal item #5)

### For Metadata
- `collection_log.xlsx` - Main spreadsheet
- `lakarcade_visit_notes.txt` - Field notes
- `permission_letter.pdf` - Written permission

## Data Quality Checklist

Before accepting any image:
- [ ] Resolution ≥ 1920x1080
- [ ] File size 1-5 MB
- [ ] In focus (not blurry)
- [ ] Good lighting
- [ ] No people in frame
- [ ] Product centered

## Backup Strategy

All data must be backed up to 3 locations:
1. Local computer (this folder)
2. External USB drive
3. GitHub repository (after organization)
4. (Optional) Cloud storage (Google Drive)

## Usage Rights

All images collected under research permission from LAKARCADE.
- For academic use only
- Cannot be used commercially
- Proper attribution required
- Permission letter stored in metadata/