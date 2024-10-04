## 1. Introduction

This document provides a comprehensive technical description of the **Electric Coffee Mug Heater**, a device designed to maintain beverages at optimal drinking temperatures over extended periods. Aimed at individuals who prefer to enjoy their hot beverages slowly without the inconvenience of reheating, the heater combines advanced heating technology with intuitive controls to deliver consistent performance.

The **Electric Coffee Mug Heater** shall be powered using **USB Power Delivery (USB PD)** as defined in **Section 3**. It is crucial that the maximum power supply limits specified by the USB PD standard are not exceeded to ensure safety and compatibility. The target markets for this product are **North America and the European Union**, and the necessary compliance and certifications for these regions are detailed in **Section 5**.

Environmental consciousness is a key aspect of the targeted customer segment. Therefore, sustainability considerations should be integrated into all facets of product design and marketing to align with consumer values.

Compatibility with the **Cozy Coffee Mug** is a fundamental requirement for the Electric Coffee Mug Heater. Detailed specifications of the Cozy Coffee Mug are provided in **Section 2**. Additionally, safety requirements, which are paramount to the product's design and operation, are outlined in **Section 4**.

---

## 2. Specifications for Cozy Coffee Mug

The Electric Coffee Mug Heater shall be compatible with the **Cozy Coffee Mug**. Constructed with a high-quality metallic casing, the Cozy Coffee Mug ensures optimal thermal conductivity, allowing efficient heat transfer from the heater to the beverage.

The mug has a capacity of **350 ml**, accommodating standard beverage sizes. Its dimensions are carefully designed for both aesthetics and functionality: it stands at **110 mm** tall with a **75 mm** base. The handle extends **35 mm** from the mug's side, starting **20 mm** from the bottom, providing a comfortable grip.

Weighing approximately **300 grams** when empty, the Cozy Coffee Mug is lightweight yet sturdy. Its ergonomic design complements the heater aesthetically and ensures a pleasant user experience.

---

## 3. USB PD Power Distribution Characteristics

The Electric Coffee Mug Heater relies on **USB Power Delivery (USB PD)** for its power requirements, ensuring compatibility with a wide range of power sources while adhering to safety standards. The device must operate within the parameters specified by the USB PD standard to maintain both performance and safety.

**Power Distribution Specifications:**

- **Input Voltage Range:** The heater can accept input voltages ranging from **5 V to 20 V**, allowing flexibility in power source options.
- **Maximum Power Input:** The device is designed for a maximum power input of **60 W**. Exceeding this limit is not permissible as per USB PD standards.
- **Maximum Current Ratings per Voltage Level:**
    - At **5 V**: **3 A**
    - At **9 V**: **3 A**,
    - At **12 V**: **3 A**
    - At **15 V**: **3 A**
    - At **20 V**: **3 A**

**Heating Control Adjustment:**==

In situations where the host power supply cannot provide the required power levels, the heater must automatically adjust its heating controls. The device will modulate temperature settings to align with the available power supply without exceeding it. While this adjustment may result in slower heating times, the system is designed to maintain the target temperature within operational constraints to ensure user satisfaction.

---

## 4. Safety Requirements

Safety is a paramount consideration in the design and operation of the Electric Coffee Mug Heater. The device must adhere to the following safety requirements to ensure user protection and product reliability:

- **Overheating Protection:** The heater must automatically shut down if internal temperatures exceed safe operational limits to prevent any risk of fire or damage.

- **Empty Mug Detection:** The device should detect when the mug is empty by monitoring parameters such as weight, heat transfer, or temperature change rates. Upon detecting an empty mug, it must perform an automatic shut-off to conserve energy and prevent potential overheating.

- **Child Lock Feature:** To prevent unintended operation by children or unauthorized users, a child lock mechanism must be incorporated.

- **Non-Slip Base:** The heater should have a non-slip base to provide stability and prevent accidental tipping, minimizing the risk of spills.

- **Surface Temperature Limits:** Accessible surfaces must comply with temperature rise limits as specified in **IEC 60335-1**:
    - For **glass or ceramic surfaces**, the maximum temperature rise is **105 °C**.
    - For **metal or painted surfaces**, the maximum temperature rise is **85 °C**.
    - For **other parts**, the maximum temperature rise is **74 °C**.

- **Device Stability:** The design must ensure that the Cozy Coffee Mug fits securely on the heater, reducing the likelihood of accidental dislodgement.

- **Electrical Protection Mechanisms:**
    - **Over-Voltage Protection (OVP):** To safeguard against input voltage exceeding specified limits.
    - **Over-Current Protection (OCP):** To prevent current from surpassing maximum ratings.
    - **Short-Circuit Protection (SCP):** To automatically disconnect power in the event of a short circuit.

---

## 5. Compliance and Certifications

To meet regulatory requirements in the target markets of North America and the European Union, the Electric Coffee Mug Heater must obtain the following certifications:

- **CE Marking:** Indicates conformity with health, safety, and environmental protection standards for products sold within the European Economic Area (EEA).
    
- **RoHS Compliance:** Ensures the restriction of hazardous substances in electrical and electronic equipment, aligning with environmental sustainability goals.
    

Environmental considerations should be integral to the product's design, reflecting the values of the environmentally conscious consumer segment. This includes using sustainable materials, energy-efficient operation, and eco-friendly packaging.

---

## 6. Operating the Heater

The Electric Coffee Mug Heater is designed with user-friendly operation in mind, featuring intuitive controls and a clear display interface.

**Adjustable Settings:**

Users have the ability to adjust two primary settings:

1. **Target Beverage Temperature:** The temperature can be set in **1 °C increments**, with a maximum of **90 °C**. This allows users to customize the temperature according to their preference.

2. **Auto Shut-Off Time:** The auto shut-off timer can be adjusted in **1-minute increments**, ranging from a minimum of **1 minute** to a maximum of **90 minutes**. This feature enhances safety and energy efficiency by ensuring the device does not remain active longer than necessary.


**Button Functions:**
- **Select Button:**
    - A **short press** allows the user to enter edit mode or confirm selections within menus.
    - A **long press** of **3 seconds** powers down the heater.
    - When the device is off, pressing and holding for **2 seconds** powers it on.

 - **Left and Right Buttons:**
	- A **short press** of either button changes the displayed value or enters setting display.
	- A **long press** of **3 seconds** of both Left and Right buttons simultaneously activates the child lock feature.

**Operating Procedures:**

During normal operation, the display shows the actual value of the last active setting and indicates the current operational mode (e.g., "Heating," "Standby"). If the last adjustment was to the beverage temperature, the estimated current beverage temperature is displayed. If the last adjustment was to the auto shut-off time, the remaining time until shut-off is shown.

To adjust settings, the user presses the Select button to enter settings mode. The Left and Right buttons are used to toggle between adjusting the beverage temperature and the auto shut-off time.

When adjusting the beverage temperature, the display shows "Temp" along with the current set value. Users can then increase or decrease the temperature in 1 °C increments up to the maximum of 85 °C. Pressing the Select button confirms the desired temperature.

For adjusting the auto shut-off time, the display shows "Time" along with the current set value. Users can adjust the time in 1-minute increments within the specified range. Pressing the Select button confirms the selection.

If user activity is not detected for **20 seconds** while in user is in edit mode of either of previously mentioned parameters, the device automatically exits to edit mode and start displaying the actual values without any additional indicators.

**Extending Auto Shut-Off Time:**

When the device is within one minute of the scheduled shut-off, the display will show a countdown. When this happens, users can press the Select button to extend the auto shut-off time by an additional **15 minutes**.

**Safety Monitoring:**

The device continuously monitors the heating surface temperature to ensure it does not exceed safe levels. In the event of over-temperature conditions or detection of an empty mug, the device will initiate protective measures, including automatic shutdown. The display will provide notifications or error messages to inform the user of any safety-related actions taken.

---

## 7. User Interface (UI)

The Electric Coffee Mug Heater features a clear and informative display designed to enhance user interaction and provide essential information at a glance.

**Display Features:**

- **Actual Value Display:** In normal operation mode, the display shows the actual value of the last active setting and the current operational mode. Display shall include indication what value is shown currently in the screen
    - **"Temp":** Displays the estimated current beverage temperature.
    - **"Time":** Shows the remaining time until auto shut-off.

- **Settings Mode Indicators:**
    - When the device is in settings (edit) mode, an **"Edit"** indicator appears to inform the user.
    - **"Temp":** Indicates that the user is adjusting the beverage temperature setting.
    - **"Time":** Indicates that the user is adjusting the auto shut-off time.

- **Operational Mode Indicator:** The display indicates the current mode of the device, such as "Heating," "Standby," or "Edit Mode," to keep the user informed of the device's status.

- **Child Lock Indicator:** Illuminates when the child lock is activated, visible in all display modes.

**Button Layout:**

- The **Select Button** is centrally located for easy access and primary interactions.
- The **Left Button** is positioned to the left of the Select button, used for decreasing values or navigating left.
- The **Right Button** is positioned to the right of the Select button, used for increasing values or navigating right.

**Additional UI Behaviors:**

- **Inactivity Timeout:** The device will automatically revert to normal operation mode if no input is detected for **20 seconds** in settings mode.
- **Error Messages:** The display will show error codes or messages if any operational faults are detected, such as over-temperature conditions or empty mug detection.
- **Safety Notifications:** When the device performs an automatic shut-off due to safety reasons, it will provide a notification to inform the user of the action taken.
