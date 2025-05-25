# ECU & TCU Binary and Definition File Collection

This repository contains a collection of ECU (Engine Control Unit) and TCU (Transmission Control Unit) binary files (`.bin`), along with their corresponding definition files (`.xdf`) used for tuning and analysis.

## Repository Structure

The files are organized by manufacturer and model, using a consistent folder hierarchy to support multiple vehicle platforms. Each vehicle follows this structure:

```
Manufacturer/Model/Chassis/EngineCode/VIN/
├── ECU/
│   ├── Base/        # Original, unmodified factory files
│   └── Modified/    # Tuned or optimized versions
└── TCU/
    ├── Base/
    └── Modified/
```

### Example:

```
BMW/3/E46/M54B30/WBA123456789/
├── ECU/
│   ├── Base/
│   └── Modified/
└── TCU/
    ├── Base/
    └── Modified/
```

Future additions will follow the same format. For example:

```
Seat/Leon/1P/CDAA/VSS123456789/
```

## Content Overview

- **Base**: Original, unmodified factory `.bin` files and matching `.xdf` definition files.
- **Modified**: Tuned or optimized versions of the base files, for analysis and comparison.

These resources are intended for **educational and research purposes only**, such as:
- Studying map structures
- Comparing OEM vs. tuned files
- Developing custom tuning strategies

## Contribution Guidelines

- Follow the folder structure strictly as outlined above.
- Include both `.bin` and `.xdf` files when possible.
- Use full or anonymized VINs (`VIN123...`) for folder names to maintain structure and privacy.

## Usage Notice

⚠️ **Important:**  
All files in this repository may be used and modified for personal and non-commercial purposes.  
**Do not distribute** any files from this repository in any form, including resale, sharing, or repackaging.

## Disclaimer

The use of any files in this repository is done entirely at your own risk.  
The repository owner assumes **no liability or responsibility** for any damage, malfunction, or legal issues arising from the use, modification, or misuse of the files provided.
