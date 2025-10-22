# Toilet On The Go - WaterAid

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Team](https://img.shields.io/badge/team-ProCritic-orange.svg)]()

A comprehensive mobile sanitation solution combining GIS-based site selection with innovative portable toilet facility design, supporting WaterAid's mission to ensure everyone, everywhere has access to clean water and decent toilets.

## 📋 Table of Contents

- [About](#about)
- [Problem Statement](#problem-statement)
- [Solution Overview](#solution-overview)
- [Project Components](#project-components)
- [Key Features](#key-features)
- [Technical Specifications](#technical-specifications)
- [Methodology](#methodology)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contributors](#contributors)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## 🎯 About

**Toilet On The Go** is an integrated project by **Team ProCritic** that combines geographic information systems (GIS) analysis with sustainable sanitation infrastructure design. The project addresses the critical need for accessible, hygienic, and inclusive public toilet facilities in underserved areas, particularly in Bangladesh.

This initiative aligns with WaterAid's commitment to providing sustainable water, sanitation, and hygiene (WASH) solutions and contributes directly to **UN Sustainable Development Goal 6: Clean Water and Sanitation**.

### Project Objectives
- Deploy mobile/portable toilet facilities in strategically selected locations
- Ensure accessibility for all users including persons with disabilities
- Provide hygienic, self-sustaining sanitation infrastructure
- Support environmental sustainability through proper waste management
- Create inclusive facilities with baby changing stations and emergency supplies

## 🚨 Problem Statement

Bangladesh and many developing regions face severe sanitation challenges:

- **Limited Public Facilities**: Inadequate number of public toilets in urban and peri-urban areas
- **Accessibility Barriers**: Lack of facilities for persons with disabilities, elderly, and parents with young children
- **Location Inefficiency**: Poor placement of existing facilities leading to underutilization
- **Hygiene Concerns**: Insufficient maintenance and water supply in public toilets
- **Emergency Preparedness**: Absence of emergency sanitary supplies and first-aid provisions

## 💡 Solution Overview

**Toilet On The Go** provides a two-pronged approach:

### 1. GIS-Based Site Selection
Using **ArcGIS** spatial analysis to identify optimal locations based on:
- Population density and demographic data
- Proximity to existing facilities
- Accessibility from major routes
- Water collection points and infrastructure
- Community needs assessment

### 2. Innovative Facility Design
A portable, self-contained toilet unit featuring:
- Universal accessibility (wheelchair ramp/staircase)
- Separate male and female facilities
- Baby diaper changing platform
- Emergency sanitary pad dispenser
- Mobile charging station
- Solar power integration
- Dual sludge storage tanks for sustainable waste management

## 🏗️ Project Components

### A. GIS Analysis Module
- **DSCC (Dhaka South City Corporation) Data**: Administrative boundary analysis
- **Manhole DSCC**: Existing sewerage infrastructure mapping
- **Water Collection Point**: Water source proximity analysis
- **Site Suitability Analysis**: Multi-criteria decision analysis for optimal placement

### B. Technical Design Module
- **Architectural Drawings**: Complete facility blueprints with dimensions
- **Structural Specifications**: Materials and construction guidelines
- **Accessibility Features**: Ramp design and wheelchair compatibility
- **Waste Management System**: Septic tank and desludging manhole specifications

## ✨ Key Features

### Accessibility & Inclusivity
- ♿ **Wheelchair Accessible**: Interchangeable ramp-staircase system (60° angle, 1-foot steps)
- 👶 **Diaper Changing Platform**: Dedicated baby care facility
- 🚺🚹 **Gender-Segregated Facilities**: Separate male and female toilets
- 🚪 **Spacious Interior**: 4×4 feet interior space per facility

### Infrastructure & Utilities
- 💧 **Water Tank**: 1000L capacity for handwashing and cleaning
- 🔋 **Solar Powered**: Renewable energy for lighting and utilities
- 📱 **Mobile Charging Station**: Community charging access
- 💡 **LED Lighting**: Energy-efficient illumination
- 🌀 **Exhaust Fan**: Proper ventilation system

### Hygiene & Safety
- 🩹 **Emergency Sanitary Pad Dispenser**: Free access to menstrual hygiene products
- 🧼 **Handwashing Facilities**: Water taps with proper drainage
- 🗑️ **Waste Disposal System**: Designated bins for used diapers and sanitary products
- 🧽 **Easy Maintenance**: Smooth surfaces for cleaning

### Waste Management
- 🚰 **Dual Sludge Storage Tanks**: Efficient waste collection
- 🔧 **Desludging Manhole**: Easy maintenance access
- ♻️ **Environmentally Sound**: Proper waste containment and disposal system

### Community Engagement
- 📢 **Advertisement Space**: Revenue generation through community notices
- 📞 **Feedback System**: QR code or contact for complaints and suggestions
- 📋 **User Guidelines**: Multilingual instructions (Bengali) for proper usage

## 📐 Technical Specifications

### Overall Dimensions
- **Total Length**: 10 feet
- **Total Width**: 8 feet
- **Height**: 7 feet
- **Individual Toilet Size**: 4×4 feet

### Facility Components (per side)
- High commode (Western-style toilet)
- Low commode (Asian-style toilet)
- Water tap and basin
- Exhaust fan and lighting
- Mobile charging point
- Storage space

### Structural Features
- Interchangeable ramp-staircase (4 feet length, 60° angle)
- Diaper changing platform (3.5 feet height)
- Advertisement panels on exterior
- Solar panel mounting structure
- Septic tank access points

### Capacity & Usage
- Water storage: 1000 liters
- Designed for high-traffic areas
- Multiple users per hour capacity
- Easy desludging and maintenance access

## 🗺️ Methodology

### Phase 1: GIS-Based Site Selection
1. **Data Collection**
   - Gather demographic data from DSCC
   - Map existing sanitation facilities
   - Identify water collection points
   - Analyze manhole and sewerage infrastructure

2. **Spatial Analysis (ArcGIS)**
   - Population density mapping
   - Proximity analysis to existing facilities
   - Accessibility assessment from major roads
   - Water source proximity evaluation
   - Multi-criteria overlay analysis

3. **Site Selection**
   - Identify high-priority locations
   - Validate sites through field surveys
   - Community consultation
   - Final site recommendations

### Phase 2: Facility Design & Engineering
1. **Conceptual Design**
   - User requirement analysis
   - Accessibility standards review
   - Space optimization

2. **Detailed Technical Design**
   - Architectural drawings (side views, sections)
   - Structural specifications
   - Plumbing and electrical layout
   - Material specifications

3. **Sustainability Integration**
   - Solar power system design
   - Water conservation features
   - Waste management system
   - Maintenance protocols

### Phase 3: Implementation Planning
1. **Construction Documentation**
2. **Cost Estimation**
3. **Deployment Strategy**
4. **Maintenance Plan**

## 📁 Project Structure

```
Toilet-On-The-Go-WaterAid/
├── DSCC/                          # DSCC administrative data
├── Manhole DSCC/                  # Sewerage infrastructure data
├── Water Collection Point/        # Water source locations
├── Technical Drawings/
│   ├── Technical Drawing 4.pdf    # Complete facility blueprints
│   ├── Side Views.dwg             # Left and right elevations
│   ├── Sections.dwg               # Section A-A and B-B
│   └── Specifications.pdf         # Material and dimension specs
├── GIS Analysis/
│   ├── Site_Suitability.mxd       # ArcGIS project file
│   ├── Population_Density.shp     # Demographic data
│   ├── Existing_Facilities.shp    # Current toilet locations
│   └── Final_Sites.shp            # Recommended locations
├── Documentation/
│   ├── Methodology.pdf            # Detailed methodology
│   ├── User_Manual.pdf            # Facility usage guide
│   └── Maintenance_Guide.pdf      # Operations manual
├── Images/
│   ├── Renders/                   # 3D visualizations
│   └── Field_Photos/              # Site photographs
└── README.md                      # This file
```

## 🚀 Getting Started

### Prerequisites

**For GIS Analysis:**
- ArcGIS ArcGIS Pro
- Spatial Analyst Extension
- Network Analyst Extension (optional)

**For Technical Drawings:**
- AutoCAD 2018
- Adobe Illustrator
- PDF reader for documentation

### Working with GIS Data

1. **Open ArcGIS Project**
```
Open ArcGIS → File → Open → Site_Suitability.mxd
```

2. **Review Data Layers**
   - DSCC boundaries
   - Manhole locations
   - Water collection points
   - Population density
   - Existing facilities

3. **Run Site Suitability Analysis**
   - Use Spatial Analyst tools
   - Apply multi-criteria evaluation
   - Generate suitability maps

### Viewing Technical Drawings

1. Open `Technical Drawing 4.pdf` for complete specifications
2. Review side views, sections, and dimensions
3. Note Bengali instructions for user guidelines
4. Check material specifications and construction notes

## 👥 Contributors

This project represents a collaborative effort by professionals committed to improving sanitation access through innovative design and data-driven planning:

### **Team ProCritic**

**Uday Karmoker**  
*Jr. Design Engineer, CCECC*  
📧 Contact: karmok3r@gmail.com
- Technical design and architectural drawings
- CAD modeling and specifications
- Accessibility feature design
- Construction documentation

**Umme Faria Rahim**
📧 Contact: juthi651@gmail.com
*M.Sc. in Construction Project Management*  
- Project management and coordination
- Budget Scheduling
- Operation and maintenance Ideation
- Requirements analysis and stakeholder engagement
- Implementation planning

---

### How to Contribute

We welcome contributions from:
- Urban planners and GIS specialists
- Civil engineers and architects
- WASH professionals
- Community organizers
- NGOs and development organizations

**To contribute:**
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/GISAnalysis` or `feature/DesignImprovement`)
3. Commit your changes with clear messages
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request with detailed description

## 🙏 Acknowledgments

- **WaterAid Bangladesh** - For their mission and guidance in addressing sanitation challenges
- **CCECC (China Civil Engineering Construction Corporation)** - For supporting sustainable infrastructure development
- **DSCC (Dhaka South City Corporation)** - For providing essential data and collaboration
- **Team ProCritic** - For dedicated effort in design and analysis
- Community members who participated in surveys and feedback sessions

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact & Support

**Repository**: [https://github.com/karmok3r/Toilet-On-The-Go-WaterAid](https://github.com/karmok3r/Toilet-On-The-Go-WaterAid)

**Issues & Suggestions**: [Report here](https://github.com/karmok3r/Toilet-On-The-Go-WaterAid/issues)

**For Implementation Inquiries**: Contact through GitHub or reach out to WaterAid Bangladesh

---

## 🌍 Project Impact

### Sustainable Development Goals
This project directly contributes to:
- **SDG 6**: Clean Water and Sanitation for all
- **SDG 11**: Sustainable cities and communities
- **SDG 3**: Good health and well-being

### Expected Outcomes
- ✅ Improved access to hygienic sanitation facilities
- ✅ Enhanced dignity and safety for vulnerable populations
- ✅ Reduced open defecation and waterborne diseases
- ✅ Better menstrual hygiene management
- ✅ Increased accessibility for persons with disabilities
- ✅ Data-driven infrastructure planning for cities
- ✅ Community empowerment through inclusive facilities

### Key Statistics
- **Target Users**: Thousands of daily users per facility in high-traffic areas
- **Accessibility**: 100% wheelchair accessible
- **Sustainability**: Solar-powered, reducing carbon footprint
- **Inclusivity**: Serves all genders, ages, and abilities

---

## 📊 Technical Highlights

### Innovation Points
1. **Integrated Approach**: Combines GIS analysis with engineering design
2. **Universal Design**: Accessibility for all users including PWDs
3. **Self-Sustaining**: Solar power and water storage
4. **Modular Design**: Easy transportation and installation
5. **Community Features**: Charging station and advertisement space for sustainability
6. **Bilingual Instructions**: Bengali user guidelines for local communities

### Design Excellence
- Compact yet spacious 8×10 feet footprint
- Dual toilet options (high and low commode)
- Emergency sanitary supplies
- Proper ventilation and natural light integration
- Easy maintenance with accessible desludging system

---

## 📚 Additional Resources

### Related Documents
- User Manual (Bengali/English)
- Maintenance and Cleaning Guidelines
- Desludging Schedule and Procedures
- Solar Panel Maintenance Guide
- Community Feedback Forms

### Reference Standards
- Bangladesh National Building Code (BNBC)
- WHO Guidelines for Sanitation and Health
- Universal Design Principles
- WASH Sector Standards

---

**Made with ❤️ by Team ProCritic for universal sanitation access**

**"নির্ভার" - Dependable Sanitation for Everyone, Everywhere**
