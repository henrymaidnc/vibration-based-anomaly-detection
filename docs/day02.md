## Day 2 – Frequency Domain Analysis (FFT)

### Basic Concepts

**Acceleration**  
Acceleration is the rate of change of velocity with respect to time.  
In this dataset, the accelerometer measures how fast the vibration velocity changes as the machine operates.

**Amplitude**  
Amplitude represents the magnitude (strength) of the vibration at a given moment in time.  
A larger amplitude indicates stronger vibration, while smaller values indicate weaker vibration.

---

### Transition from Day 1 to Day 2

In Day 1, we focused on understanding the dataset structure and the raw vibration signal in the time domain.  
We observed acceleration values fluctuating around zero, which is expected for mechanical vibration signals.

At this stage, the signal is represented as:

- **Amplitude vs. Time**
- This view shows how vibration changes moment by moment
- However, it does not clearly reveal repetitive or periodic patterns

---

### Why Move to Frequency Domain

In Day 2, we change the perspective of the same data by applying **Fast Fourier Transform (FFT)**.

Instead of asking:
> "How does the vibration change over time?"

We now ask:
> "Which frequencies contribute the most to this vibration?"

This transforms the signal into the **frequency domain**, where we analyze:

- **Frequency (Hz)** on the x-axis
- **Strength (magnitude)** of vibration at each frequency on the y-axis

---

### Key Difference Between Day 1 and Day 2

- **Day 1 (Time Domain):**  
  Amplitude based on time  
  → Useful for observing overall vibration behavior

- **Day 2 (Frequency Domain):**  
  Strength based on frequency  
  → Useful for identifying repetitive vibration patterns caused by rotating mechanical components

This change in perspective is essential for vibration-based anomaly detection and predictive maintenance.
