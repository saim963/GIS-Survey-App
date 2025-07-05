Key Features:
📍 GPS Location Tracking

Real-time GPS coordinate capture with accuracy measurement
Location permission handling
Simulated GPS updates (you can integrate with FusedLocationProviderClient for real GPS)

📝 Survey Data Collection

Point name and type classification (Water Point, Building, Road, etc.)
Description field for detailed notes
Timestamp recording for each survey point
Validation to ensure complete data entry

🗺️ Map Interface

Visual list of all collected survey points
Location coordinates display
Point type categorization with chips
Accuracy and timestamp information

💾 Offline Data Management

In-memory data storage (can be extended with Room database)
Point deletion and bulk clear functionality
Data persistence during app session

📤 GIS Export Capabilities

CSV Export: Spreadsheet-compatible format
GeoJSON Export: Standard web mapping format
KML Export: Google Earth compatible format
Export statistics and summaries

Architecture Highlights:

MVVM Pattern: Clean separation with ViewModel
Jetpack Compose: Modern declarative UI
Material Design 3: Contemporary Android design
Navigation Component: Bottom navigation between screens
State Management: Reactive UI with StateFlow

Visual representation:
        <img src="https://github.com/user-attachments/assets/297f1e0f-097f-4431-a09e-1ddefb654341" width="200" height="150">
        <img src="https://github.com/user-attachments/assets/3b501307-858e-4cb0-9400-82868a46132e" width="200" height="150">
        <img src="https://github.com/user-attachments/assets/2b41587e-cf20-4848-801e-9ca10a1c0408" width="200" height="150">        
        <img src="https://github.com/user-attachments/assets/39403d84-b97b-4ccc-896c-4e6f14f63a84" width="200" height="150">
        <img src="https://github.com/user-attachments/assets/6c690269-eca2-4396-89cd-1e272e787098" width="200" height="150">
        <img src="https://github.com/user-attachments/assets/74b0694e-eb14-44da-9a29-897b4c6fa121" width="200" height="150">
        <img src="https://github.com/user-attachments/assets/0d09c2fe-f51f-49dc-9d69-6e0adb45b324" width="200" height="150">



