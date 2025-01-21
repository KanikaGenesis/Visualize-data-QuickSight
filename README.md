# Visualizing Netflix Data with AWS QuickSight

This project demonstrates how **AWS QuickSight**, Amazon's cloud-based business intelligence (BI) tool, was used to analyze and visualize Netflix's extensive dataset. The goal was to extract meaningful insights using interactive dashboards, graphs, and reports.

---

## 📸 Dashboard Screenshot

Here is the complete dashboard created using AWS QuickSight:

![Netflix Dashboard](/dashboard_screenshot.png)

---

## 📊 Steps to follow for the project

1. **Upload Dataset to S3**:
   - Uploaded two files: `netflix_titles.csv` and `manifest.json`.
   - **Edit the `manifest.json` file**: Updated the file to include the correct S3 URI of the uploaded dataset. This step ensures QuickSight knows the location of the dataset in your S3 bucket.
   - Example `manifest.json` update:
     ```json
     {
       "fileLocations": [
         {
           "URIPrefixes": ["s3://your-bucket-name/netflix_titles.csv"]
         }
       ],
       "globalUploadSettings": {
         "format": "CSV",
         "delimiter": ",",
         "textqualifier": "\"",
         "containsHeader": true
       }
     }
     ```

2. **Connect S3 to QuickSight**:
   - Sign up for QuickSight account.
   - Enabled QuickSight access to the S3 bucket.

4. **Create Visualizations**:
  - Add fields to the **AutoGraph** section for automatic chart creation.
   - Use filters to refine data for analysis.

5. **Publish and Export Dashboard**:
   - Edited chart titles for clarity.
   - Published the final dashboard and exported it for sharing insights.

---

## Connect with me 

**Kanika Mathur**  
- [E-mail](mkanika.90@gmail.com)
- [GitHub](https://github.com/KanikaGenesis)  
- [LinkedIn](https://www.linkedin.com/in/kanika-mathur-083080121)  


