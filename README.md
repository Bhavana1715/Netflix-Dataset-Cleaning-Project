# **📺 Netflix Dataset Cleaning Project**

Welcome to my **Netflix Dataset Cleaning** project! 🚀  
In this project, I loaded, explored, cleaned, and exported a cleaned version of the popular **Netflix dataset**. 📊

## **📂 Project Steps**
1. **📥 Load the Dataset**  
   🔹 Loaded the Netflix titles dataset using pandas.
   🔹 Previewed the first 10 rows with `.head(10)`.

3. **🔎 Initial Exploration**  
   🔹 Checked the shape (rows × columns) of the dataset.  
   🔹 Displayed data types of each column.  
   🔹 Used `.info()` to get detailed dataset information.  
   🔹 Summarized numerical columns with `.describe()`.
   
   **Explored categorical columns:**
   
   🔹  Displayed unique values (limited to 20).
   🔹 Displayed value counts (top 10 most frequent).

5. **🛠️ Data Cleaning**
   
   **🔹  Missing Value Handling:**
     - Filled missing director, cast, and country values with `'Unknown'`.
     - Smart-filled missing `date_added` based on whether the content was a Movie or a TV Show.
     - Filled missing `rating` values with `'Not Rated'`.
     - Filled missing `duration` values with the most common duration.
   
   🔹  **🔄 Duplicate Rows:**
     - Identified and displayed any duplicate rows.

7. **🧹 Data Type Correction**  
   🔹 Converted `date_added` to **datetime** format.  
   🔹 Converted `release_year` to **integer** type.

8. **📦 Export the Cleaned Dataset**  
    🔹Saved the cleaned dataset as `netflix_cleaned.csv` for further analysis.

## **✨ Key Highlights**
- **✅ Proper missing value imputation** without using `.inplace=True` (future-proof code for pandas 3.0+)
- **✅ Smart date filling strategy** based on content type
- **✅ Corrected column name usage** (case-sensitive!)
- **✅ Dataset exported cleanly** for future Machine Learning, Visualization, or Analytics projects

## **📚 Technologies Used**
- **🐍 Python 3.x**
- **📊 Pandas**
- **💻 Google Colab**

## **📎 Dataset Reference**
- Netflix Movies and TV Shows Dataset (https://shorturl.at/qXJ8z)

🚀 **Thank you for checking this project!** Feel free to ⭐ star the repo if you find it useful!  
🔥 **Let's connect on LinkedIn** and collaborate on more awesome projects!
 (https://shorturl.at/h38hd)
