# 🧩 Lightwheel_Kitchen (Isaac Sim Ready)

This folder contains a complete kitchen room scene designed for simulation and interaction in **NVIDIA Isaac Sim**. The assets include appliances, cabinets, and structural elements, all organized modularly for flexibility and reuse.

***Welcome to the Lightwheel open-source community!***

Join us, contribute, and help shape the future of AI and robotics.
For questions or collaboration, contact Frank Chen at ming.chen@lightwheel.ai.


## 📁 Folder Structure

- `KitchenRoom.usd`  
  The main USD scene. Load this file in Isaac Sim to view the full kitchen environment.

- `InteractiveAsset/`  
  Contains manipulatable or interactive assets (e.g. doors, handles).

- `CoffeeMachine006/`, `Toaster003/`, `Microwave017/`, `WallStackOven004/`, `Refrigerator001/`, etc.  
  Individual kitchen appliances as modular assets.

- `Kitchen_Cabinet001/`, `Kitchen_Cabinet002/`, `Kitchen_TopCabinet/`, `Kitchen_InsularShelf/`  
  Modular kitchen furniture and cabinetry.

- `Dishwasher054/`, `Sink054/`, `Stovetop012/`, `RangeHood015/`, `Pot057/`, etc.  
  Additional environment props.

- `texture/`  
  All texture maps referenced by the assets.

- `omniverse-content...aws.com/`  
  Cached content pulled from Omniverse's remote servers (optional for reuse).

## 🚀 Usage

Download by clicking

[DOWNLOAD_LINK](https://storage.googleapis.com/sim-cloud-paltform-bucket-file-upload-001/upload-file/Lightwheel_Kitchen.zip)


1. Open **Isaac Sim**.
2. Use the Content browser to navigate to this directory.
3. Double-click on `KitchenRoom.usd` to load the complete scene.
4. You can edit, simulate, or extend the environment directly.

## 🖥️ System Requirements

This project requires **NVIDIA Isaac Sim** and a compatible system. Recommended configuration:

- Ubuntu 20.04 or 22.04 
- NVIDIA RTX 30XX / 40XX series GPU (minimum 16GB VRAM)
- 64GB RAM or more

To get started with Isaac Sim, follow the official setup guide:  
👉 [Isaac Sim: Getting Started](https://docs.isaacsim.omniverse.nvidia.com/4.5.0/installation/index.html)

## 🔧 Notes

- All USD assets are structured for compatibility with Isaac Sim’s physics and rendering pipeline.
- Assets can be reused in other environments by referencing their USDs.
- If any textures appear missing, ensure the `texture/` folder remains in the same directory hierarchy.


---

Happy simulating!


