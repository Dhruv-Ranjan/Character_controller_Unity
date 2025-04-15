# 🎮 Unity FPS Character Controller – Basic Setup

A lightweight and easy-to-use First Person Shooter (FPS) character controller script for 3D Unity games. Includes basic movement, mouse look, jump, and gravity.

---

## 📁 Files

- `FPSController.cs` — Main script for player movement and look.
- Requires: Unity 3D project (any version with Character Controller support)

---

## 🛠️ Setup Instructions

### 1. **Create the Player GameObject**
- In Unity, right-click in the **Hierarchy** → `Create Empty`.
- Rename it to `Player`.
- Add Component → `Character Controller`.

### 2. **Add the Camera**
- Right-click on `Player` → `Camera`.
- Position the camera at eye level, e.g., `Position: (0, 1.6, 0)`.

### 3. **Add the Script**
- Create a `Scripts` folder in the **Assets**.
- Right-click → `Create > C# Script` → name it `FPSController`.
- Replace the script content with the provided `FPSController.cs` code.
- Drag and drop the script onto the `Player` GameObject.

### 4. **Assign the Camera in the Script**
- Select the `Player` GameObject.
- In the `FPSController` component, drag the **Camera** object into the `Cam` field in the Inspector.

### 5. **Lock the Cursor**
- Play the game. Your mouse should now control the camera.
- Press `ESC` to release the cursor.

### 6. **Setup Ground**
- Create a ground plane (`GameObject > 3D Object > Plane`).
- Add a `Collider` if not already present.
- (Optional) Tag it as `Ground` for extensions.

---

## 🎮 Controls

| Action     | Key / Input         |
|------------|---------------------|
| Move       | `WASD`              |
| Look       | `Mouse Movement`    |
| Jump       | `Spacebar`          |
| Exit Mouse Lock | `Esc`         |

---

## 🧠 Customizable Parameters

| Variable           | Description                          |
|--------------------|--------------------------------------|
| `speed`            | Movement speed                       |
| `mouseSensitivity` | Sensitivity for mouse look           |
| `jumpForce`        | How high the player jumps            |
| `gravity`          | Gravity value (default: -9.81)       |

---

## ✅ To-Do / Extensions

- ✅ Crouch
- ✅ Sprint
- ✅ Headbob
- ✅ Weapon Handling
- ✅ Footsteps
- ✅ Sliding

> Ask for any of the above if you want them added!
