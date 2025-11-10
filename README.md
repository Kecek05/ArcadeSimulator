# NeonFlip: Arcade Simulator

![NeonFlip Arcade Simulator](Arcade/Arcade.png)

## Overview

**NeonFlip: Arcade Simulator** is a business simulation game built with Unreal Engine 5.3 where you manage and grow your own retro arcade. Build your arcade from the ground up, place arcade machines, manage customers, handle finances, and expand your business into a thriving entertainment hub.

Developed by **Cherry Bay**, this game combines management simulation with immersive 3D gameplay, offering players a nostalgic journey through arcade culture.

## Game Description

Step into the shoes of an arcade owner and transform a small space into the ultimate gaming destination. Purchase and place various arcade machines (Standing cabinets, Pinball machines, Claw machines), manage your daily operations, serve customers, and watch your business grow. Experience the satisfaction of building and managing your dream arcade while dealing with day-to-day challenges like cleaning, customer service, and financial management.

## Core Mechanics

### Building & Placement System
- **Machine Types**: Place different types of arcade machines including:
  - Standing Arcade Cabinets (Cat, Robot, Guy, Cellphone themed)
  - Lying Down Arcade Tables (Futebol, Minecraft, Toca Life, Tree, River, Street themed)
  - Pinball Machines
  - Claw Machines
- **Props & Decoration**: Add tables, racks, frames, and decorative elements to enhance your arcade
- **Interactive Builder**: Real-time placement preview system with snap-to-grid functionality
- **Terminal Systems**: Install computer terminals for purchases and management
- **Box Management**: Order and unpack new machines and equipment
- **Arcade Expansion**: Unlock and expand to new areas as your business grows

### Customer & NPC System
- **AI-Powered NPCs**: Customers with autonomous behavior powered by AI task systems
- **Customer Interactions**: NPCs interact with machines, pay at cash registers, and navigate your arcade
- **NPC Masters**: Different customer types with unique behaviors and preferences
- **Customer Satisfaction**: Keep customers happy to maintain steady income

### Economy & Money Management
- **Cash Register System**: Process customer payments and track earnings
- **Expense Tracking**: Monitor daily expenses through the expense data table (DT_Expanses)
- **Computer Purchase System**: Order new machines and supplies through in-game computer terminals
- **Financial Planning**: Balance income against expansion costs and daily expenses

### Day/Night Cycle
- **Time Management**: Dynamic day/night cycle affects gameplay
- **Operating Hours**: Open and close your arcade, managing business hours
- **Lighting System**: Advanced illumination system that changes with time of day
- **Daily Operations**: Each day presents new challenges and opportunities

## Gameplay Loop

### Daily Cycle
1. **Opening**: Start your day by opening the arcade doors
2. **Customer Service**: Welcome customers and ensure machines are operational
3. **Cleaning & Maintenance**: Use the mop to keep your arcade clean and presentable
4. **Cash Management**: Process payments at the cash register and track earnings
5. **Restocking**: Open boxes with new machines and place them strategically
6. **Expansion Planning**: Use earnings to purchase new machines and expand your space
7. **Closing**: End the day, review profits, and plan for tomorrow

### Progression Loop
1. Start with basic machines and limited space
2. Earn money from customers using your machines
3. Invest in new arcade cabinets and equipment
4. Expand your arcade space to accommodate more machines
5. Unlock new machine types and decorations
6. Build a reputation and attract more customers
7. Maximize profits and create the ultimate arcade experience

## Game Systems

### Save/Load System
- **Persistent Progress**: Your arcade state, machine placement, and finances are saved
- **Auto-save**: Game automatically saves your progress
- **Load Game**: Continue from where you left off

### User Interface
- **HUD System**: Real-time display of important information (money, time, notifications)
- **Main Menu**: Start new game, load saved game, access settings
- **Computer UI**: In-game computer interface for purchasing and management
- **Box UI**: Interface for opening and managing deliveries
- **Machine UI**: Interact with individual arcade machines
- **Cash Register UI**: Process transactions and view earnings
- **Tutorial UI**: Guided instructions for new players

### Tutorial System
- **Interactive Tutorial**: Step-by-step guidance through core mechanics
- **Tutorial Scene**: Dedicated tutorial level for learning game systems
- **Hints**: Contextual hints appear during gameplay
- **Progressive Learning**: Mechanics introduced gradually to avoid overwhelming players

### Animation System
- **Character Animations**: Player movement with blend spaces for smooth transitions
- **Machine Animations**: Interactive arcade machines with animated screens and controls
- **Door Animations**: Automatic doors with open/close animations
- **Interactive Objects**: Various animated interactive elements throughout the arcade

### Audio System
- **Sound Effects (SFX)**: 25+ categories of sound effects including:
  - Machine sounds
  - Customer interactions
  - Cash register sounds
  - Door sounds
  - Ambient arcade sounds
  - UI feedback sounds

### Interaction System
- **Outline System**: Visual highlighting of interactable objects
- **E to Interact**: Press E to interact with machines, computers, boxes, and more
- **Context-Sensitive Actions**: Different interactions based on object type
- **Carry System**: Pick up and carry items like boxes and cleaning supplies

## Controls

### Keyboard & Mouse
- **WASD**: Movement
- **Mouse**: Look around / Aim
- **E**: Interact with objects
- **Left Click**: Primary action
- **Right Click**: Secondary action
- **ESC**: Pause menu / Exit interfaces
- **Tab**: Inventory / Management screen (if available)
- **Shift**: Sprint (if available)

### Gamepad Support
- Full gamepad support with customizable button mapping
- Left Stick: Movement
- Right Stick: Camera control
- A/Cross: Interact
- B/Circle: Cancel
- Start: Pause menu

## Technical Details

### Built With
- **Engine**: Unreal Engine 5.3
- **Target Platform**: Windows
- **Programming**: C++ and Blueprint Visual Scripting
- **Development**: Unreal Editor 5.3

### System Architecture
- **Modular Blueprint System**: Organized into logical categories (AI, Builder, Player, UI)
- **Component-Based Design**: Reusable actor components for common functionality
- **Data-Driven**: Uses Data Tables for machine types, expenses, and expansion data
- **Optimized Performance**: Level streaming and asset optimization for smooth gameplay

## Features

### Current Features
✅ Multiple arcade machine types (10+ varieties)
✅ Dynamic building and placement system
✅ AI-powered customer system
✅ Day/night cycle with lighting
✅ Complete economy and money management
✅ Save/load game functionality
✅ Interactive tutorial system
✅ Cash register and payment processing
✅ Computer-based purchasing system
✅ Box delivery and unpacking
✅ Cleaning and maintenance tools
✅ Arcade expansion system
✅ Multiple game levels (Main Menu, Tutorial, Testing levels)
✅ Comprehensive UI/Widget system
✅ Full audio implementation
✅ Automatic door system
✅ Props and decoration system

### Content
- **Arcade Machines**: 10+ unique machine designs
- **Props**: Tables, racks, frames, and decorative items
- **Levels**: Multiple scenes including Main Menu, Tutorial, and gameplay areas
- **Materials**: Custom materials for machines, dirt effects, and environments
- **Audio**: Extensive SFX library for immersive arcade atmosphere

## Installation

### Prerequisites
- Unreal Engine 5.3 installed
- Windows Operating System
- Git for cloning the repository

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Kecek05/ArcadeSimulator.git
   cd ArcadeSimulator
   ```

2. **Open the Project**
   - Navigate to the `Arcade` folder
   - Double-click `Arcade.uproject` to open in Unreal Engine 5.3
   - Wait for the project to compile (first time may take several minutes)

3. **Build the Project** (Optional, for C++ changes)
   - Right-click `Arcade.uproject`
   - Select "Generate Visual Studio project files"
   - Open the generated `.sln` file in Visual Studio
   - Build the solution

4. **Play in Editor**
   - Click the "Play" button in the Unreal Editor toolbar
   - Or press Alt+P to start playing in the editor

5. **Package the Game** (For distribution)
   - In Unreal Editor: File → Package Project → Windows → Windows (64-bit)
   - Select output directory
   - Wait for packaging to complete

## Project Structure

```
ArcadeSimulator/
├── Arcade/                          # Main project folder
│   ├── Content/                     # All game assets
│   │   ├── Blueprints/              # Blueprint logic
│   │   │   ├── AI/                  # NPC and customer AI
│   │   │   ├── Builder/             # Building and placement system
│   │   │   ├── Player/              # Player character
│   │   │   ├── DayCicle/            # Day/night system
│   │   │   ├── SaveLoad/            # Save system
│   │   │   └── ...
│   │   ├── Widgets/                 # UI elements
│   │   ├── Levels/                  # Game maps
│   │   ├── Materials/               # Visual materials
│   │   ├── Meshs/                   # 3D models
│   │   ├── SFX/                     # Sound effects
│   │   └── ...
│   ├── Source/                      # C++ source code
│   │   └── Arcade/                  # Game module
│   ├── Config/                      # Configuration files
│   └── Arcade.uproject              # Main project file
└── README.md                        # This file
```

## Development Status

This project is under active development. Current focus areas include:
- Expanding machine variety
- Enhancing AI customer behaviors
- Adding more expansion options
- Improving UI/UX
- Performance optimization
- Additional gameplay features

## Credits

**Developer**: Cherry Bay
**Project Name**: NeonFlip: Arcade Simulator
**Engine**: Unreal Engine 5.3
**Repository**: [Kecek05/ArcadeSimulator](https://github.com/Kecek05/ArcadeSimulator)

---

**Note**: This is an Unreal Engine project. Make sure you have Unreal Engine 5.3 installed before attempting to open the project.
