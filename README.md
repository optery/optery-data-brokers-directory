# Optery Data Brokers Directory

Welcome to Optery's open-source directory of data brokers, the largest of its kind. With detailed profiles for over 645+ data brokers and step-by-step instructions for opting out, we're providing this continuously updated resource to the public for free. We hope this resource helps bring more data broker visibility to the public and helps you take control of your personal information.

## About This Resource

This directory contains comprehensive information about data brokers that Optery covers, including:

- Contact information (websites, emails, phone numbers, addresses)
- Opt-out URLs and step-by-step opt-out guides
- Data collection and sharing methods
- Categories of data collected
- CCPA and GDPR coverage status

Note: Not every data broker entry will have complete information for all fields.

Browse the live version at [optery.com/data-brokers](https://www.optery.com/data-brokers/)

## Data Formats

We provide the data in multiple formats to suit different use cases:

### JSON (Recommended for Developers)
- **File**: `data/data-brokers.json`
- **Best for**: Programmatic access, APIs, data analysis
- **Format**: Structured JSON array with complete field data

### CSV (Recommended for Spreadsheet Users)
- **File**: `data/data-brokers.csv`
- **Best for**: Excel, Google Sheets, database imports
- **Format**: Flattened table format

### Markdown (Recommended for Browsing)
- **File**: `data/data-brokers.md`
- **Best for**: Human-readable documentation, GitHub browsing
- **Format**: Organized markdown with table of contents

## Data Schema

Each data broker entry includes the following fields:

| Field | Type | Description |
|-------|------|-------------|
| `id` | number | Unique identifier |
| `title` | string | Data broker name |
| `website` | string | Official website URL |
| `opt_out_url` | string | Direct link to opt-out page |
| `opt_out_guide` | string | Step-by-step opt-out instructions |
| `email` | string | Contact email |
| `phone` | string | Contact phone number |
| `address` | string | Physical address |
| `description` | string | Description of the broker |
| `data_collection_methods` | string | How they collect data |
| `data_sharing_methods` | string | How they share data |
| `data_categories_collected` | string | Types of data collected |
| `ccpa_covered` | string | CCPA coverage (yes/no) |
| `gdpr_covered` | string | GDPR coverage (yes/no) |

## Use Cases

This data is valuable for:

- **Privacy Researchers**: Analyze data broker practices and trends
- **Journalists**: Investigate data broker industry
- **Educators**: Learn about data privacy
- **Individuals**: Locate and opt out of data brokers


## Updates

This directory is regularly updated. Check back regularly or watch this repository for updates.

## License

This data is provided free of charge for educational, and research use. We only ask that you attribute Optery when using this data.

## About Optery

[Optery](https://www.optery.com) is a privacy company that helps individuals remove their personal information from data brokers. Our automated service monitors and removes your data from hundreds of data broker sites.

## Disclaimer

This information is provided for educational and research purposes. Opt-out processes may change, and we recommend verifying current procedures on each data broker's website.

---


