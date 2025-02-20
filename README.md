# ChatGPT Heatmap and Word Cloud Generator  

⭐ **This script is originally by Chip Huyen and is available at:**  
[GitHub - AI Heatmap](https://github.com/chiphuyen/aie-book/blob/main/scripts/ai-heatmap.ipynb)  

It was modified to work on **Google Colab**, to include a **word cloud**, and to generate the final chart combining the heatmap and the word cloud, as well as minor comments.  

## How to Use This Script  

### 1. Export Your ChatGPT Conversations  
- From your ChatGPT account, go to **Settings** → **Data Controls** → **Export Data**.  

### 2. Unzip the Exported Data  
- You will receive a **.zip** file via email.  
- Extract the file into a folder and rename it **"gptdados"**.  

### 3. Upload the Folder to Google Drive  
- Move the **"gptdados"** folder to your Google Drive.  

### 4. Open the Notebook  
- Access the Colab notebook here: [ChatGPT Data Analysis Notebook](https://lnkd.in/dfMtz_bt).  

### 5. Make a Copy of the Notebook  
- In Google Colab, go to **File** → **Make a Copy in Drive** to save it to your account.  

### 6. Grant Access to Your Google Drive  
- Allow Google Colab to access your Drive.  
- Ensure you are using the same Google account where you uploaded the **"gptdados"** folder.  

### 7. Set Up the Script  
- Set `convo_folder` to the **"gptdados"** folder in your Google Drive.  
- Adjust `local_tz` to your local timezone to ensure correct timestamps for each conversation.  

### 8. Run the Notebook  
- Execute the code cells one by one, or run all at once by clicking **Runtime** → **Run all** (or press **Ctrl + F9**).  

### 9. View the Generated Visualizations  
The script will generate the following:  
✅ A **heatmap** displaying activity in 2024 and 2025.  
✅ A **word cloud** based on conversation data.  
✅ A **combined visualization** of both (as shown in the example).  

Now you're ready to analyze your ChatGPT usage data! 🚀  
