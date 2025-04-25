# lab_exercises

---

### **Basic Electronics Exercises: Resistor Circuits and Measurements**  

#### **1. Basic Series Circuit**  
**Setup:**  
- Build a circuit with a **9V battery**, a **220Ω resistor**, and an LED (with series resistor for protection).  

**Tasks:**  
a) Calculate the theoretical current (Ohm’s Law: \( I = \frac{V}{R} \)).  
b) Measure the voltage across the resistor and LED using a multimeter.  
c) Record values in a table:  

| Component | Theoretical Voltage (V) | Measured Voltage (V) | Theoretical Current (mA) | Measured Current (mA) |  
|-----------|-------------------------|----------------------|--------------------------|-----------------------|  
| Resistor  | \( V = R \times I \)     | (measure)            | \( I = \frac{9V}{220Ω} \) | (measure) |  
| LED       | ~2V (typical)           | (measure)            | Same as above            | Same as above         |  

---  

#### **2. Parallel Circuit**  
**Setup:**  
- Build a circuit with a **12V source** and two parallel resistors: **1kΩ** and **2.2kΩ**.  

**Tasks:**  
a) Calculate the equivalent resistance (\( \frac{1}{R_{eq}} = \frac{1}{R1} + \frac{1}{R2} \)).  
b) Measure the equivalent resistance with the multimeter (*power off!*).  
c) Measure total current and current through each resistor.  

| Resistor | Resistance (Ω) | Voltage (V) | Theoretical Current (mA) | Measured Current (mA) |  
|----------|----------------|-------------|--------------------------|-----------------------|  
| 1kΩ     | 1000           | 12V         | \( I = \frac{12V}{1kΩ} \) | (measure) |  
| 2.2kΩ   | 2200           | 12V         | \( I = \frac{12V}{2.2kΩ} \) | (measure) |  

---  

#### **3. Voltage Divider**  
**Setup:**  
- Build a voltage divider with two resistors (**470Ω** and **1kΩ**) connected to **5V**.  

**Tasks:**  
a) Calculate the expected output voltage (\( V_{out} = 5V \times \frac{R2}{R1 + R2} \)).  
b) Measure the voltage at the midpoint with a multimeter.  
c) Compare with the theoretical value.  

---  

#### **4. Ohm’s Law Verification**  
**Setup:**  
- Build a circuit with a **variable power supply (0-12V)**, a **330Ω resistor**, and an ammeter.  

**Tasks:**  
a) Adjust the supply to **3V, 6V, 9V, and 12V**, then measure the current each time.  
b) Fill the table and verify \( V = R \times I \):  

| Voltage (V) | Measured Current (mA) | Theoretical Current (mA) |  
|-------------|-----------------------|--------------------------|  
| 3V          | (measure)             | \( \frac{3V}{330Ω} \)    |  
| 6V          | (measure)             | \( \frac{6V}{330Ω} \)    |  
| 9V          | (measure)             | \( \frac{9V}{330Ω} \)    |  
| 12V         | (measure)             | \( \frac{12V}{330Ω} \)   |  

---  

#### **5. Resistor Color Code Identification**  
**Task:**  
- Provide mixed resistors (e.g., **220Ω, 1kΩ, 4.7kΩ, 10kΩ**) and ask the student to:  
  a) Identify the value using the color code.  
  b) Confirm with a multimeter.  

---  

### **Potentiometer Exercise (3-Terminal Measurement)**  
**Objective:**  
Demonstrate how a potentiometer works as an **adjustable voltage divider**.  

#### **Materials:**  
✔ Power supply (5V or 9V)  
✔ Linear potentiometer (e.g., 10kΩ)  
✔ Multimeter  
✔ Breadboard and jumpers  

#### **Circuit Setup:**  
1. Connect **terminal 1** to **GND (negative)**.  
2. Connect **terminal 3** to **VCC (positive)**.  
3. **Terminal 2 (wiper)** is the variable output (leave a jumper for measurement).  

#### **Tasks:**  
1. **Total Resistance Check**  
   - Measure resistance between **terminals 1 and 3** (*power off*). Expected: ≈10kΩ.  

2. **Variable Voltage Measurement**  
   - Measure voltage between:  
     - **Terminal 1 (GND) and Terminal 2 (wiper)** at three positions:  
       - **0%** (fully CCW): ≈0V  
       - **50%**: ≈2.5V (for 5V supply)  
       - **100%** (fully CW): ≈5V  
     - Repeat between **Terminal 2 and 3** (values should be complementary).  

3. **Data Table:**  
| Pot Position | Voltage **1-2** (V) | Voltage **2-3** (V) |  
|--------------|---------------------|---------------------|  
| 0%           | (measure)           | (measure)           |  
| 50%          | (measure)           | (measure)           |  
| 100%         | (measure)           | (measure)           |  

4. **Theory Check:**  
   - Calculate expected voltage at, e.g., 30% position:  
     \( V_{1-2} = 0.3 \times V_{supply} \).  
