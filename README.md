# README

## RESQUAKE: A Procedural Post-Earthquake Simulation Models for Rescue Training

### Overview
This repository contains the files and models developed for procedural post-earthquake simulation training, specifically tailored to Philippine houses. The primary objective of this research is to enhance earthquake preparedness and rescue training by generating diverse, realistic post-earthquake scenarios using procedural modeling techniques.

### Features
- **Procedural Modeling Framework**: Leveraging Houdini software, this framework generates diverse earthquake simulation models.
- **Architectural Focus**: Includes standard architectural features of Philippine homes for high realism.
- **Dynamic Parameters**: Models are adjusted based on key earthquake parameters like magnitude.
- **Efficiency**: Automatically generates a wide range of scenarios, saving time and resources compared to manual modeling.

### Contents
- **`/models`**: Contains the procedurally generated 3D models of Philippine houses under various earthquake scenarios.
- **`/houdini_files`**: Includes Houdini project files (`.hip` and `.hiplc`) for procedural model generation.

### Getting Started
#### Prerequisites
- Houdini (version 19.5 or later recommended)
- A computer with sufficient processing power for 3D modeling and rendering

#### Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/tyrarose/resquake.git
   ```
2. Navigate to the project directory:
   ```bash
   cd resquake
   ```
3. Open Houdini and load the `.hip` files from the `/houdini_files` folder.

### Usage
1. Open the Houdini project file corresponding to your desired scenario in the `/models` directory.
2. Modify earthquake parameters (e.g., magnitude) as needed. Refer to the documentation in `/papers` for parameter details.
3. Generate models and render outputs using Houdini’s built-in tools.

### Results
Preliminary results demonstrated that:
- Procedural modeling increases the diversity of training scenarios.
- Simulation models effectively replicate real-life post-earthquake environments.
- Time and resource efficiency are significantly improved.

### Applications
- **Rescue Training**: Enhancing the realism of training exercises for rescue personnel.
- **Preparedness Drills**: Simulating diverse earthquake scenarios for emergency response teams.
- **Architectural Resilience Testing**: Assessing the structural response of Philippine homes under varying earthquake conditions.

### Future Work
- Expanding the architectural scope to include commercial and industrial buildings.
- Incorporating additional natural disaster scenarios (e.g., typhoons, floods).
- Developing a user-friendly interface for parameter adjustments.

### Contributing
Contributions to this repository are welcome. If you wish to contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your forked repository.
4. Create a pull request.

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

### Acknowledgments
This research was made possible with the support of:
- Houdini software for procedural modeling.
- Architectural and structural engineers specializing in Philippine housing.
- Rescue training experts who provided insights into realistic scenarios.

---

For any questions or support, please contact https://github.com/Tyrarose
