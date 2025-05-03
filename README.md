# Manufacturing-Downtime-Analysis
## Project Description
Analysis of manufacturing downtime and production efficiency for a soda bottling production line. The dataset contained operator performance data, product batch times, and downtime factors, providing key insights into process inefficiencies. Attempting to quantify line efficiency, pinpoint the primary causes of downtime, and assess operator performance to recommend data-driven improvements.

## Tech Stack Used
![Image](https://github.com/user-attachments/assets/cc933bb4-0efd-420f-a467-5f42a97f72d4) ![Image](https://github.com/user-attachments/assets/0a4e0383-eb98-4955-8d01-d74081d9064c)

## Requirements and KPIs
- The most and least productive operator
- The most repeated downtime failure
- Production bottlenecks
- Downtime caused by machine vs downtime caused by operator
- Downtime by product
- Actual work time vs batch work time (operator)
- Actual work time vs batch work time (product)

## Data Source
[Manufacturing_Line_Productivity.xlsx](https://github.com/user-attachments/files/20024156/Manufacturing_Line_Productivity.xlsx)

## Data Visualization
<img width="1024" alt="Image" src="https://github.com/user-attachments/assets/39f78323-aedf-433c-a7ae-a8972addf99e" />
<img width="1049" alt="Image" src="https://github.com/user-attachments/assets/75776421-b062-411f-8d56-d932c32861f5" />
<img width="1030" alt="Image" src="https://github.com/user-attachments/assets/e031178a-f6c8-4ef6-9561-49ef26d19e75" />


## Key Insights
- #### 📈 **Utilization Rates**  
  - Max. man utilization rate (overall): 64.65% (Month: August)  
  - Max. by product: LE-600 at 68.05%  
  - Max. by operator: Charlie at 66.84%  

- #### ⏳ **Downtime Analysis**  
  - Total downtime: 1,388 minutes  
  - Max. downtime by production line: CO-600 (494 minutes)  
  - Max. downtime by month: August (853 minutes)  
  - Max. downtime by batch: Batch #424147 (107 minutes on 02/09/2024)  

- #### 🛠️ **Breakdown Causes**  
  - Primary cause: Batch change (160 minutes, 11.53%)  
  - Secondary cause: Batch coding error (145 minutes, 10.45%)  

- #### ⏱️ **Work Time Comparison**  
  - Product with longest actual work time: CO-600 (1,394 minutes vs. 900 minutes batch time)  
  - Month with longest actual work time: 2,413 minutes vs. 1,560 minutes batch time

## Recommendations based on the Analysis

- ### **Operator Training Program**
  - Implement excessive operator training (prioritize Mac operators)
  - Emphasize: Machine adjustments must be performed by technicians only

- ### **Maintenance Strategy**
  - Develop total preventive maintenance plan for production line
  - Key rule: All machine adjustments require technician authorization

- ### **Inventory Management**
  - Create material feeding inventory plan
  - Standardize stock levels for critical components

