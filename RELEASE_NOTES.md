## Version 1.0.1 - February 14, 2026

### 🎨 Visual Improvements

- **Updated Zone Colors**: Chart and zone badges now use standard training platform colors
  - Z1: Light cyan (recovery)
  - Z2: Bright cyan (endurance)
  - Z3: Blue (tempo)
  - Z4: Purple (threshold)
  - Z5: Pink (VO2 max)
  - Z6: Red (anaerobic)
- **Enhanced Duration Display**: Total workout duration now displays in HH:MM:SS format for better readability
- **Matching Zone Badges**: Zone pill indicators now match chart colors for consistent visual identity

### 🐛 Bug Fixes

- Improved visual consistency across the interface

---
# Release Notes

## Version 1.0.0 - February 14, 2026

### 🎉 Initial Release

**Triathlon Workout Generator** - AI-powered workout creation for cyclists and triathletes.

### ✨ Features

- **Natural Language Input**: Describe workouts in plain English (e.g., "10 min warmup in Z2, 4x30sec at Z4 with 30sec rest")
- **AI-Powered Parsing**: Uses Claude AI to intelligently parse complex workout descriptions
- **Dynamic Zone Calculator**: Automatically calculates 6 power zones based on your FTP
- **Visual Workout Chart**: Bar chart visualization showing workout structure at a glance
- **Smart Interval Grouping**: Automatically detects and groups repeated interval sets
- **Flexible Recovery Options**: Toggle to include/exclude recovery after the last interval
- **Multiple Export Formats**: 
  - .ZWO (Zwift)
  - .ERG (TrainerRoad)
  - .MRC (Wahoo, percent-based)
- **Real-Time Updates**: Chart and duration update dynamically as you adjust settings

### 🎯 Use Cases

- Create structured workouts for indoor training platforms
- Plan training sessions with precise power targets
- Export workouts to Zwift, TrainerRoad, Wahoo, Garmin, and other platforms
- Visualize workout intensity and duration before executing

### 🏗️ Technical Details

- Built with React and Tailwind CSS
- Claude Sonnet 4 API integration for natural language processing
- Client-side only - no backend required
- Works on any modern browser

### 📝 Known Limitations

- Requires internet connection for AI parsing
- FIT file format not yet supported (coming soon)
- Cadence instructions are parsed but not included in exports

---

**Built by**: Ken Presutti  
**Released**: February 14, 2026 (Valentine's Day - fitting for a passion project!)