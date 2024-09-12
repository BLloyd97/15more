Voter List Organization and Tracking Tool

This tool helps campaign data managers split a master CSV file containing a universe into smaller, organized files and generates a summary 'tracker' file. It is designed to distribute lists of voters to volunteers for a letter-writing campaign or other personalized contact.

Quick Start Guide
- To use this tool, you'll need to have python installed and install pandas if necessary with: pip install pandas 

- You'll need to update the paths for your input and output files to match your local setup. The paths are on lines 70, 71, and 76
  - Input File Path: This should be the path to your master CSV file containing voter data.
  - Output Folder Path: This should be the path where you want to save the split files and generated tracker file.
  - tracker_file_path: This should be the path where you want to save the tracking file.
  
- You may want to change the number of people per file, which you can do by changing the rows_per_file parameter on line 5. 
