# Perseus GNC (Guidance, Navigation, and Control)

Welcome to the Perseus GNC repository! This project serves as the central hub for managing flight control simulations, algorithms, and documentation for the Perseus drone/autonomous vehicle team. We're still in the early stages, and this is a work in progress—but we're actively building here!

## 🚧 Work in Progress

This repository is under active development. We’re iterating on our Guidance, Navigation, and Control (GNC) systems, including Simulink models, scripts, and supporting docs. Expect frequent updates as we refine our work.

## 🤝 Collaboration & Workflow





Committing Changes: All team members commit their work here to track progress and share updates. Use descriptive commit messages (e.g., "Update roll control Simulink model" or "Add Kalman filter documentation").



Pull Requests: For significant changes, create a branch and submit a pull request for review.





Fork the repo (if external contributors).



Create a feature branch: git checkout -b feature/new-controller.



Commit changes: git commit -m "Add PID controller for altitude hold".



Push and open a Pull Request (PR).



Use issues for bugs/tasks (e.g., label as "bug", "enhancement", or "flight-test").



For large files like Simulink models (>100MB), use Git LFS: Install via git lfs install, then git lfs track "*.slx".

## 📚 Sharing Documentation





Upload all relevant documentation (e.g., design specs, flight logs, or Simulink model notes) to the /docs/ folder (create it if needed).



Prefer Markdown (.md) files for text or PDF for detailed reports. Example: /docs/flight_log.md or /docs/control_design.pdf.



Update the README with key links or summaries as the project grows.

## 🌐 Uploading to GitHub





Add Files: Use the web interface (Add file > Upload files) or clone locally (git clone https://github.com/Abdullah24/Persusgnc.git) and push changes.



Large Files: For Simulink models (.slx) or large datasets, enable Git LFS (git lfs install, git lfs track "*.slx") to handle files over 100MB.



Structure: Organize files in folders like /simulink/, /src/, and /docs/ to keep things tidy.

##📋 Project Structure (Initial)

Perseusgnc/
├── README.md              # This file
├── simulink/              # Simulink models (e.g., Roll_Simulinkpers.slx)
│   ├── control/
│   ├── estimation/
│   └── tests/
├── src/                   # Scripts (e.g., Python, MATLAB)
├── docs/                  # Documentation
└── .gitignore             # Ignore temporary files

##🛠️ Getting Started





Clone the Repo: git clone https://github.com/Abdullah24/Persusgnc.git



Requirements: MATLAB/Simulink R2023a+, Python 3.10+ (if applicable).



Contribute: Fork, branch, and submit PRs. Contact @Abdullah24 for access.



👥 Team





@Abdullah24: Lead developer



Add your teammates here!

Questions? Open an issue or ping in #flight-control Slack/Discord.
