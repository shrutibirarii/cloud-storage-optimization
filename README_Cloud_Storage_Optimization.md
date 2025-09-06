
# Cloud Storage Optimization Insights

## Overview
This project analyzes cloud storage usage to identify optimization opportunities, reduce costs, and recommend archival strategies using AWS S3 tiers.

## Dataset
- **Records**: 3000 synthetic entries
- **Columns**:
  - File_ID: Unique identifier
  - Department: Business unit (HR, Finance, Marketing, Engineering, Sales)
  - File_Type: Document, Media, Backup, Log, Other
  - Size_GB: File size in GB
  - Last_Access_Date: Date of last access
  - Storage_Tier: Current storage tier (S3 Standard, S3 IA, Glacier)
  - Monthly_Cost_USD: Estimated monthly storage cost

## Project Objectives
1. Identify unused/cold data (last accessed > 180 days).
2. Calculate potential savings by migrating cold data to Glacier.
3. Visualize storage usage trends across departments.

## Tools & Libraries
- Python (Pandas, Numpy, Matplotlib)
- Power BI or Tableau (for dashboard visualization)
- SQL (optional for querying large datasets)

## Potential Insights
- Cost savings potential
- Department-wise storage inefficiencies
- File type impact on storage cost

## Next Steps
- Perform EDA using the provided dataset.
- Create a dashboard to present insights.
- Recommend archival or deletion strategies.
