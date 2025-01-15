# ChatGPT Heatmap and Word Cloud Generator

⭐ **This script is originally by Chip Huyen and is available at:**

https://github.com/chiphuyen/aie-book/blob/main/scripts/ai-heatmap.ipynb

It was modified to work on **Google Colab**, to include a **word cloud**, and to generate the final chart combining the heatmap and the word cloud, as well as minor comments.

## How to Use This Script

1. **Export your ChatGPT conversations:**
   - From your ChatGPT account, go to `Settings` -> `Data controls` -> `Export`.
   
2. **Unzip the data export.**

3. **Set up the script:**
   - Point `convo_folder` to your exported data folder (at your Google Drive).
   - Change `local_tz` to your local timezone so that it gets the correct timestamp of each conversation.
