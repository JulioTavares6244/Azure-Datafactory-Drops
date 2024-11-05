# Knowledge Drops Repository

This repository contains JSON code examples for Azure Data Factory (ADF) pipelines, organized as "knowledge drops." Each drop focuses on a specific feature or best practice in building and optimizing data pipelines in the cloud using Azure Data Factory.

## Table of Contents

- [Description](#description)
- [Prerequisites](#prerequisites)
- [Repository Structure](#repository-structure)
- [Usage Instructions](#usage-instructions)
- [Contributing](#contributing)

## Description

The goal of this repository is to serve as a quick-reference guide for developers using Azure Data Factory, especially those looking to learn from practical examples. Each "knowledge drop" highlights a particular Azure Data Factory feature, such as triggers, linked services, or integrations with databases and external APIs.

## Prerequisites

- **Azure Subscription**: An active Azure subscription to use Azure Data Factory.
- **Azure Data Factory Access**: Permission to access Azure Data Factory within your subscription.
- **Basic Knowledge of JSON**: Familiarity with JSON to modify and customize pipelines.

## Repository Structure

The repository can be organized as follows:

```
/
├── Drops/
│   ├── Drop1-DataIngestion/
│   │   └── pipeline.json
│   ├── Drop2-DataTransformation/
│   │   └── pipeline.json
│   └── Drop3-DataExport/
│       └── pipeline.json
├── Random_Drops_n_Tips.json
├── README.md
└── CONTRIBUTING.md
```

### Folder Descriptions

- `Drops/`: Each subfolder represents a "knowledge drop" focused on a specific ADF functionality.
- `DropX-DropName/`: Contains a JSON file for a sample pipeline, focusing on a theme (e.g., data ingestion, transformation, export).

## Usage Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/knowledge-drops-repo.git
   ```

2. **Import the Pipeline**:
   In the Azure Data Factory portal, navigate to **Authoring > Pipelines > Import from JSON**. Select the desired pipeline JSON file.

3. **Customize the Pipeline**:
   Update the JSON with your environment-specific details, such as service connections and target tables.

4. **Run the Pipeline**:
   After customization, validate and run the pipeline directly in the portal.

## Contributing

Contributions are welcome! Follow the guidelines in `CONTRIBUTING.md` to submit fixes or add new knowledge drops.

---

### Knowledge Drop Examples

This repository may include examples such as:

- **Data Ingestion Pipeline**: Ingesting data from various sources (e.g., Azure Blob Storage, SQL Database)
- **Data Transformation Pipeline**: Data transformations using Data Flow
- **Data Export Pipeline**: Exporting data to different destinations (e.g., Azure Storage, external API)

