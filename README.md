# exp_4_characteristics_of_directional_coupler

# Experiment 4 — Directional Coupler Characteristics

---

## Aim

To measure the directivity and coupling factor for the given directional couplers.

## Apparatus Required

Klystron power supply, klystron mount with tube, isolator, variable attenuator, frequency meter, slotted line section, directional coupler, detector mount / crystal detector, matched terminations, Power meter, waveguide stands.

---

## Theory

# Directional Coupler

<img width="549" height="200" alt="image" src="https://github.com/user-attachments/assets/58febc6f-896b-45ab-8f0a-d973b661f5b4" />


A directional coupler is a flanged, built-in waveguide assembly that samples a small amount of microwave power for measurement purposes. It can be designed to measure incident and/or reflected power, SWR values, provide a signal path to a receiver, or perform other desirable operations, and can be unidirectional or bidirectional.

In its most common form the directional coupler is a **four-port waveguide junction** consisting of a primary main waveguide and a secondary auxiliary waveguide. A small portion of the input power at port 1 is coupled to port 4, so this small power can be measured. Ideally, no power should come out of port 3.

The performance of a directional coupler is usually defined by two parameters:

1. **Coupling factor**
2. **Directivity**

---

## Experimental Setup

<img width="783" height="270" alt="image" src="https://github.com/user-attachments/assets/0b0576bb-4b6f-4e21-8a34-8f54ca04adf9" />

## Procedure

1. Switch ON the klystron supply with necessary precautions.
2. Operate the klystron in its best mode and note the corresponding output power as **P₁** (P₁ = incident power).
3. Connect the directional coupler as shown in the experimental setup.
4. Without disturbing the mode of the klystron, connect the directional coupler as shown in the bench setup.

---

## Measurements

P1 = Without directional coupler

P2 = Port 2 Output (P1 is input)

P3 = Port 3 Output (P1 is input)

P4 = Port 3 Output (P2 is input) [P1 is matched termination]

---
## Calculation

Instertion Loss (dB) = P1-P2

Coupling Factor (dB) = P1-P3

Isolation (dB) = P1-P4

Directivity (dB) = P3-P4

---

## Observation

## Operating Parameters

* **Operating Frequency:** $9.45\text{ GHz}$
* **Signal Source:** Reflex Klystron (modulated with $1\text{ kHz}$ square wave)

### Power Level Measurements

| S.No | Port Description           | Port Notation | Power Reading (dB) |
| ---: | -------------------------- | :-----------: | -----------------: |
|    1 | Input / Incident Port      |     $P_1$     |            $-10.5$ |
|    2 | Through / Transmitted Port |     $P_2$     |            $-11.8$ |
|    3 | Coupled Port               |     $P_3$     |            $-20.6$ |
|    4 | Isolated Port              |     $P_4$     |            $-48.2$ |

Using the recorded power values:

$$
P_1 = -10.5\text{ dB}, \quad
P_2 = -11.8\text{ dB}, \quad
P_3 = -20.6\text{ dB}, \quad
P_4 = -48.2\text{ dB}
$$

### 1. Insertion Loss (dB)

$$
\text{Insertion Loss} = P_1 - P_2
$$

$$
= (-10.5) - (-11.8) = \mathbf{1.3\text{ dB}}
$$

### 2. Coupling Factor (dB)

$$
\text{Coupling Factor} = P_1 - P_3
$$

$$
= (-10.5) - (-20.6) = \mathbf{10.1\text{ dB}}
$$

### 3. Isolation (dB)

$$
\text{Isolation} = P_1 - P_4
$$

$$
= (-10.5) - (-48.2) = \mathbf{37.7\text{ dB}}
$$

### 4. Directivity (dB)

$$
\text{Directivity} = P_3 - P_4
$$

$$
= (-20.6) - (-48.2) = \mathbf{27.6\text{ dB}}
$$

**Verification:**

$$
\text{Directivity}
= \text{Isolation} - \text{Coupling Factor}
$$

$$
= 37.7 - 10.1 = \mathbf{27.6\text{ dB}}
$$



## Precautions

1. The beam voltage should be minimum and the repeller voltage should be normal before switching the klystron power supply ON/OFF.
2. Loose connections between the components should be avoided.
3. The directional coupler must be handled carefully while inserting it into the circuit.

---

## Conclusion

The characteristics of the multi-hole directional coupler were studied at an operating frequency of $9.45\text{ GHz}$.The Insertion Loss of the primary line was found to be $1.3\text{ dB}$, indicating low forward attenuation across the main waveguide guide path.The Coupling Factor was determined to be $10.1\text{ dB}$, verifying that the component behaves nominally as a $10\text{ dB}$ directional coupler.The Isolation was measured as $37.7\text{ dB}$, showing high power rejection at the isolated arm.The Directivity of the coupler was evaluated to be $27.6\text{ dB}$, confirming effective discrimination between forward-traveling and reverse-traveling microwave signals.
