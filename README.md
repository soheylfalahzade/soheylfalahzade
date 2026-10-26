<p align="center"><img src="assets/banner.svg" alt="Soheil Fallahzadeh: computer vision and road-network algorithms for emergency mobility" width="100%"></p>

<p align="center">
  <a href="https://soheylfalahzade.github.io"><img src="https://img.shields.io/badge/Portfolio-soheylfalahzade.github.io-6fa8d6?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/soheyl-falahzade/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Yazd_University-M.Sc._Computer_Science-2b3a47?style=for-the-badge" alt="Yazd University">
</p>

<h3 align="center">How does a city get an ambulance through when its cameras can fail and its streets are full?</h3>

<p align="center">Open-source research on seeing traffic, simplifying road networks and controlling signals.<br>Every number links to a command that regenerates it, including the results that did not work.</p>

<p align="center">
  <a href="https://soheylfalahzade.github.io"><img src="https://img.shields.io/badge/%F0%9F%9A%91_Read_the_story-soheylfalahzade.github.io-ffb454?style=for-the-badge&labelColor=0a1017" alt="Read the story on the portfolio"></a>
</p>

<p align="center"><i>Every GitHub story has a first commit. Mine starts with one question about an ambulance,<br>and the portfolio tells it as a journey you can click through.</i></p>

<p align="center"><img src="assets/stats.svg" alt="Headline results" width="100%"></p>

## The system

<p align="center"><img src="assets/pipeline.svg" alt="The eyes, the arteries, the reflexes" width="100%"></p>

## 🔬 Research repositories

<table>
<tr><th>Layer</th><th>Repository</th><th>Headline result</th></tr>
<tr><td>👁️ <b>Eyes</b></td><td><a href="https://github.com/soheylfalahzade/perception-reliability-monitor"><b>perception-reliability-monitor</b></a></td><td>Reliability AUC <b>0.938</b>; alarm within <b>3 to 8 s</b> of a real failure</td></tr>
<tr><td>👁️ <b>Eyes</b></td><td><a href="https://github.com/soheylfalahzade/occlusion-aware-queue-estimation"><b>occlusion-aware-queue-estimation</b></a></td><td>Bias under occlusion <b>−2.84 m → −0.63 m</b></td></tr>
<tr><td>👁️ <b>Eyes</b></td><td><a href="https://github.com/soheylfalahzade/ev-perception-for-preemption"><b>ev-perception-for-preemption</b></a></td><td>Road matching <b>0.974</b> vs 0.900; passage <b>34.4 s → ~20 s</b> <sub>(simulation)</sub></td></tr>
<tr><td>👁️ <b>Eyes</b></td><td><a href="https://github.com/soheylfalahzade/vision-travel-time-sensing"><b>vision-travel-time-sensing</b></a></td><td>Association precision <b>0.875</b> vs 0.558 <sub>(appearance only)</sub></td></tr>
<tr><td>🛣️ <b>Arteries</b></td><td><a href="https://github.com/soheylfalahzade/geometric-spanners-lab"><b>geometric-spanners-lab</b></a></td><td><b>990 → 77</b> edges (92.22% pruned), stretch ≤ 1.4</td></tr>
<tr><td>🛣️ <b>Arteries</b></td><td><a href="https://github.com/soheylfalahzade/Research_Geometric_ML_Optimization"><b>Research_Geometric_ML_Optimization</b></a></td><td>Up to <b>42.5× faster</b> than greedy <sub>(Rome, 42,788 nodes)</sub></td></tr>
<tr><td>🛣️ <b>Arteries</b></td><td><a href="https://github.com/soheylfalahzade/delay-bounded-spanner-networks"><b>delay-bounded-spanner-networks</b></a></td><td>One backbone certified for <b>all pairs, all 24 hours</b>, 12 cities</td></tr>
<tr><td>⚡ <b>Reflexes</b></td><td><a href="https://github.com/soheylfalahzade/anti-gridlock-signal-control"><b>anti-gridlock-signal-control</b></a></td><td>Ambulance delay <b>143.3 s → 125.0 s</b> <sub>(p = 0.049)</sub></td></tr>
</table>

## 📷 Computer vision and deep learning

<table>
<tr>
<td width="50%" valign="top"><h4>🚦 <a href="https://github.com/soheylfalahzade/Smart_Traffic_Vision">Smart_Traffic_Vision</a></h4>Vehicle detection and tracking.<br><sub><kbd>YOLOv8</kbd> <kbd>tracking</kbd> <kbd>Python</kbd></sub></td>
<td width="50%" valign="top"><h4>🚑 <a href="https://github.com/soheylfalahzade/Emergency_Vehicle_Recall">Emergency_Vehicle_Recall</a></h4>Deep learning for identifying and prioritizing emergency vehicles in complex urban scenes.<br><sub><kbd>deep learning</kbd> <kbd>Python</kbd></sub></td>
</tr>
<tr>
<td width="50%" valign="top"><h4>🧠 <a href="https://github.com/soheylfalahzade/adaptive-its-priority">adaptive-its-priority</a></h4>Emergency-vehicle priority with hierarchical perception and hybrid co-simulation.<br><sub><kbd>CARLA</kbd> <kbd>SUMO</kbd> <kbd>Python</kbd></sub></td>
<td width="50%" valign="top"><h4>📍 <a href="https://github.com/soheylfalahzade/vision-travel-time-sensing">vision-travel-time-sensing</a></h4>Edge travel times from sparse camera re-identification, and their effect on spanner bounds.<br><sub><kbd>re-ID</kbd> <kbd>spanners</kbd> <kbd>Python</kbd></sub></td>
</tr>
</table>

## 🧪 Where the data said no

> [!WARNING]
> - 🔕 Knowing the camera had failed did **not** improve the signals in simulation.
> - ⏱️ Detecting the ambulance earlier did **not** buy more time on a single queued approach.
> - 🗾 The learned spanner stopped pruning at Tokyo scale (**0.09%** of edges removed).
> - 🐢 The fuzzy controller is slower than both baselines when the bottleneck is loose.

## 🧭 Working principles

> [!NOTE]
> 🔁 Every reported number is regenerated by a documented command with explicit seeds.<br>
> 📐 Statistical claims carry intervals or paired comparisons; negative results are reported.<br>
> 🧩 Simulation and real data are never mixed without saying so.

## 🧰 Stack

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
<img src="https://img.shields.io/badge/YOLOv8-00A7B5?style=for-the-badge" alt="YOLOv8">
</p>
<p>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/SUMO-2b3a47?style=flat-square" alt="SUMO">
<img src="https://img.shields.io/badge/CARLA-2b3a47?style=flat-square" alt="CARLA">
<img src="https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white" alt="OpenStreetMap">
<img src="https://img.shields.io/badge/Fuzzy_logic-2b3a47?style=flat-square" alt="Fuzzy logic">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

<p align="center"><sub>🚑 Built to get one ambulance through one city, a little faster.</sub></p>
