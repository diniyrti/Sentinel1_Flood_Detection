### Flood Detection using Sentinel-1 & Rainfall Analysis (North Aceh, 2025)

This project analyzes a flood event in North Aceh (November 2025) using Sentinel-1 SAR imagery and rainfall data.
The goal is to identify flood-affected areas and understand their relationship with extreme precipitation.

⚙️ Method
- Process CHIRPS rainfall data to analyze monthly precipitation trends
- Use Sentinel-1 SAR (before vs after flood)
- Apply change detection (backscatter difference) to identify flooded areas
- Visualize results using Python (xarray, rioxarray, matplotlib)

📊 Results
- Peak rainfall occurred in November (~550 mm/month), indicating extreme weather conditions
- Flooded areas are clearly detected through decreased SAR backscatter
- Results show strong agreement between high rainfall and flood occurrence

![image alt](https://github.com/diniyrti/Sentinel1_Flood_Detection/blob/main/images/Flood%20Detection.png)

![image alt](https://github.com/diniyrti/Sentinel1_Flood_Detection/blob/main/images/Monthly%20Rainfall%20in%20North%20Aceh%20Regency%20-%202025.png)
