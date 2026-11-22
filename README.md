<p align="center">
  <img src="banner.png" alt="Harshit Rawal Banner" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3200&pause=1100&color=00FF88&center=true&vCenter=true&width=640&lines=Intelligence+is+liberation.;Embedded+Systems;Human-Machine+Interaction" alt="Intelligence is liberation." />
</p>

<p align="center">
  <a href="https://vasco1290.github.io"><img src="https://img.shields.io/badge/portfolio-vasco1290.github.io-00ff88?style=flat-square&labelColor=0a0a0a" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/rawal-harshit"><img src="https://img.shields.io/badge/linkedin-rawal--harshit-00e5ff?style=flat-square&labelColor=0a0a0a" alt="LinkedIn" /></a>
  <a href="mailto:harshitrawal.dev@gmail.com"><img src="https://img.shields.io/badge/email-harshitrawal.dev-ffffff?style=flat-square&labelColor=0a0a0a" alt="Email" /></a>
</p>

---

## 🔌 Pinout

I'm Harshit, an AI graduate from Mumbai who likes his neural networks small and his signals faint. I build at the meeting point of people and machines: intelligence that fits on tiny hardware, listens closely, and does something useful in the real world. No GPU was harmed in the making of any of it, mostly because I don't own one.

---

## 🔬 Specimens

<sub>Four things from the bench. Each one has a label: open it to see what's inside, and what isn't yet.</sub>

<table>
<tr>
<td width="50%" valign="top">

### [Brokkr](https://github.com/Vasco1290/Brokkr)
<a href="https://github.com/Vasco1290/Brokkr"><img src="assets/brokkr.jpg" width="100%" alt="Brokkr: a small anvil fused onto a computer chip" /></a>

*What happens to a model's sense of doubt when you shrink it, then blind it with fog?*

Shrinks image models to 8-bit, then stress-tests them with fog, darkness and blur. Each one gets a nutrition label showing what the shrinking cost.

<details>
<summary><code>read the label</code></summary>

```text
does              FP32 → INT8 (ONNX Runtime), then
                  12 kinds of damage
tested            10 torchvision models,
                  10k ImageNet val images
measures          accuracy, conformal coverage
                  + set size, ECE, E-AURC
found             the doubt signal mostly breaks
                  when conditions shift
──────────────────────────────────────────────
not yet           a real edge device, PyPI,
                  your own model (in progress)
```
[Live labels →](https://vasco1290.github.io/Brokkr/)
</details>

</td>
<td width="50%" valign="top">

### [MindNav](https://github.com/Sakib-Dalal/Mind-Nav)
<a href="https://github.com/Sakib-Dalal/Mind-Nav"><img src="assets/mindnav.jpg" width="100%" alt="EEG electrode placement on the forehead wired to an amplifier and Arduino Uno" /></a>

*Typing without touching anything.*

Types words on screen from EEG signals picked up on the forehead, no hands needed. A team of four; I handled the neuroscience.

<details>
<summary><code>read the label</code></summary>

```text
hardware          Arduino Uno, amplifier board,
                  3 gel electrodes
signal            EEG, streamed to a laptop
does              hands-free on-screen typing
team              4 (final-year project)
──────────────────────────────────────────────
not yet           the paper; a device rebuilt
                  from scratch
```
</details>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Quantized Arm Control](https://github.com/Vasco1290/quantized-arm-control-mcu)
<a href="https://github.com/Vasco1290/quantized-arm-control-mcu"><img src="assets/arm.gif" width="100%" alt="A seated figure wearing a simulated exoskeleton arm reaching for a red target" /></a>

*An arm that thinks in a quarter of the bits.*

A 5.4 KB network doing 8-bit maths steers a simulated exoskeleton arm and lands every reach. It holds at 6 bits and breaks at 4.

<details>
<summary><code>read the label</code></summary>

```text
sim               MuJoCo, 2-joint arm with gravity
controller        10 → 64 → 64 → 2 network,
                  INT8, 5.4 KB
result            100/100 reaches within 3 cm
precision         fine at 6 bits, breaks at 4
──────────────────────────────────────────────
not yet           running on a real Pi Zero W /
                  ESP32-S3 (loop is built)
```
</details>

</td>
<td width="50%" valign="top">

### [2-DOF Robotic Arm](https://github.com/Vasco1290/2-DOF-Robotic-Arm)
<a href="https://github.com/Vasco1290/2-DOF-Robotic-Arm"><img src="assets/2dof-arm.jpg" width="100%" alt="A simulated robot arm with a rotating base and a sliding extension" /></a>

*You type. It reaches.*

Type `move TCP to x 0.1 y 0.3` and inverse kinematics swings the base and slides the arm to get there.

<details>
<summary><code>read the label</code></summary>

```text
joints            1 rotating + 1 sliding
sim               MuJoCo, Python
input             typed commands, joint or x/y/z
status            about halfway
──────────────────────────────────────────────
not yet           real hardware
```
</details>

</td>
</tr>
</table>

---

## 🛠️ Instruments

<p>
  <img src="https://skillicons.dev/icons?i=py,cpp,rust,go,bash,pytorch,tensorflow,sklearn,arduino,raspberrypi,linux,docker,fastapi,flask,git,github,vscode,latex&perline=9&theme=dark" alt="Tools" />
</p>
<p>
  <img src="https://img.shields.io/badge/ESP32--S3-0a0a0a?style=flat-square&logo=espressif&logoColor=E7352C" alt="ESP32-S3" />
  <img src="https://img.shields.io/badge/ONNX_Runtime-0a0a0a?style=flat-square&logo=onnx&logoColor=white" alt="ONNX Runtime" />
  <img src="https://img.shields.io/badge/MuJoCo-0a0a0a?style=flat-square" alt="MuJoCo" />
  <img src="https://img.shields.io/badge/NumPy-0a0a0a?style=flat-square&logo=numpy&logoColor=4DABCF" alt="NumPy" />
  <img src="https://img.shields.io/badge/KiCad-0a0a0a?style=flat-square&logo=kicad&logoColor=white" alt="KiCad" />
</p>

<sub>Still tuning: Rust, MuJoCo, KiCad.</sub>

---

<details>
<summary><b>📈 Activity</b></summary>
<br/>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Vasco1290&bg_color=0a0a0a&color=00ff88&line=00ff88&point=ffffff&area=true&hide_border=true" alt="Activity graph" width="100%" />
</p>
</details>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Vasco1290&color=00ff88&style=flat-square&label=visitors" alt="Visitors" />
</p>
