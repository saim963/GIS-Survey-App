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
