
# 🔌 MATLAB Arduino Real-Time Voltage Plotter GUI

This project provides a protected MATLAB GUI tool to monitor and plot real-time voltage data from an Arduino board. It uses `.p`-coded files to safeguard the source code and is ideal for sharing with others who need to run but not view or modify your implementation.

![MATLAB GUI Screenshot](assets/MATLAB_Arduino_Plotting.png)

---

## 📦 Features

- Real-time voltage plotting from Arduino Analog Pin A0
- GUI-based interface: Start, Stop, Reset, Export Data
- Adjustable Y-axis limits
- COM port selection on startup
- Data export to `.csv` or `.xls`
- Secure distribution using `.p` files (MATLAB’s protected format)

---

## 🛠 Requirements

- **MATLAB R2021a** or newer
- **Arduino Board** (Uno or compatible)
- **Arduino connected via USB**
- **MATLAB Support Package for Arduino Hardware**

To install the Arduino support package:
```matlab
matlab.addons.installer.install('arduino-support.mlpkginstall')
```

Or from MATLAB: **Home > Add-Ons > Get Hardware Support Packages**

---

## 🚀 How to Run

1. Clone or download this repository:
   ```
   git clone https://github.com/yourusername/arduino-voltage-plotter.git
   ```

2. Open MATLAB and navigate to the project folder:
   ```matlab
   cd('path_to_downloaded_folder')
   ```

3. Run the application:
   ```matlab
   MATLAB_Arduino_Plotting_Oscilloscope
   ```

4. Select the correct COM port when prompted.

---

## 📁 Folder Structure

```
arduino-voltage-plotter/
├── README.md
├── MATLAB_Arduino_Plotting_Oscilloscope.p
├── helper_functions.p (if any)
├── assets/
│   └── screenshot.png (optional GUI preview)
```

---

## 📤 Exporting Data

After acquisition:
- Click **"Export Data"** to save the logged voltage readings.
- Data can be saved as `.csv` or `.xls`.

---

## 🔒 Code Protection

Only `.p` files are distributed. These are precompiled and cannot be reverse engineered into the original `.m` code, ensuring the implementation remains protected.

---

## 📄 License

[MIT License](LICENSE) *(or your chosen license)*

---

## 🙋 Support

For any issues, open an [issue](https://github.com/yourusername/arduino-voltage-plotter/issues) on this GitHub repository.

