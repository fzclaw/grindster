# grindster
MTT Training Suite
# MTT Poker Training Tools - Ready to Use

## 🎯 Quick Start Guide

Your poker training tools are now ready! This package contains both the **MTT Trainer** and **MTT Diagnostic Tool**

### 📦 What's Included

**1. Push/Fold Trainer** (`pushfold_trainer.py`)
- Progressive difficulty training for tournament poker
- Position-based scenarios (Button, Cutoff, SB, BB)
- Stack size training (1-20+ BB ranges)
- Real-time feedback and explanations
- Performance tracking and analytics

**2. Tournament Diagnostics** (`tournament_diagnostics.py`)
- ICM analysis for SNGs, Spin & Gos, and MTTs
- ROI projection and variance analysis
- Bubble play optimization
- Leak detection and personalized recommendations

**3. Graphics Training** (`training_platform/graphics.py`)
- Visual card display with Pygame
- Interactive range charts
- Real-time scenario practice

### 🚀 Immediate Usage

#### Option 1: Easy Launchers (Recommended)
- **Windows**: Double-click `run_trainer.bat`
- **Mac/Linux**: Run `./run_trainer.sh`

#### Option 2: Manual Commands
```bash
# Start interactive training
python poker_solver/training_launcher.py

# Run tournament diagnostics
python poker_solver/tournament_diagnostics_example.py

# Start graphics training
python poker_solver/run_graphics_training.py

# Test push/fold trainer directly
python poker_solver/pushfold_trainer.py
```

### 📊 Training Features

**MTT Trainer:**
- ✅ Beginner to Expert difficulty levels
- ✅ Position-specific ranges (BTN, CO, SB, BB)
- ✅ Stack depth scenarios (1-20+ BB)
- ✅ ICM considerations
- ✅ Performance analytics

**Tournament Diagnostics:**
- ✅ SNG, Spin & Go, MTT analysis
- ✅ ICM pressure calculations
- ✅ ROI projections
- ✅ Variance analysis
- ✅ Bubble play optimization

### 🛠️ Setup Instructions

If dependencies aren't installed:

**Windows:**
```cmd
install.bat
```

**Mac/Linux:**
```bash
chmod +x install.sh
./install.sh
```

### 📁 File Structure
```
mtt-tools/
├── poker_solver/           # Core training modules
├── training_data/          # Progress storage
├── diagnostics_output/     # Analysis reports
├── run_trainer.bat        # Windows trainer launcher
├── run_trainer.sh         # Unix trainer launcher
├── run_diagnostics.bat    # Windows diagnostic launcher
├── run_diagnostics.sh     # Unix diagnostic launcher
├── install.bat            # Windows installer
├── install.sh             # Unix installer
└── README.md             # This file
```

### 🎯 Training Examples

**Console Training:**
```
🎯 Push/Fold Trainer - Master Tournament Poker
================================================
📍 Position: Button
💰 Stack Size: 8 BB
🤔 You're considering pushing all-in. What's your decision?
Enter action (push/fold/call/quit):
```

**Tournament Diagnostics:**
```
🏆 Tournament Analysis: 9-Max SNG
Current Stage: bubble
Players Remaining: 4
Hero Stack: 25 BB

💰 ROI Analysis:
  Expected ROI: 8.5%
  Chip Equity: 31.3%
  Profitable: ✅
```

### 🔧 Troubleshooting

**Dependencies Missing:**
```bash
pip install numpy pygame pygame_gui matplotlib pandas scipy
```

**Python Path Issues:**
```bash
cd mtt-tools
python poker_solver/training_launcher.py --setup
```

### 📞 Support

All tools are fully functional and tested. Your complete MTT trainer and diagnostic system from your other computer is now ready to use on this system!
