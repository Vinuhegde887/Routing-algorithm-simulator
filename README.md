
# 🌐 Graph-Based Routing Algorithm Visualizer

A comprehensive web-based visualization tool for network routing algorithms, featuring interactive graph topology, real-time path analysis, and advanced network optimization techniques.

---

## 🌟 Features

### 🔗 Network Topology Visualization
- **Interactive Force-Directed Graph**: Drag-and-drop node positioning with D3.js.
- **Multi-Layer Network Architecture**: Core routers, distribution routers, edge devices, subnets, and end devices.
- **Real-Time Visual Updates**: Dynamic link weights and node status changes.
- **Responsive Design**: Bootstrap-powered UI for all screen sizes.

---

### 🛣️ Routing Algorithms
- **Dijkstra's Algorithm**: Shortest path using edge weights.
- **Distance Vector (Bellman-Ford)**: Distributed path discovery.
- **Link State**: Topology-aware routing with global knowledge.
- **Smart Optimization**: Load-aware routing to avoid congestion.
- **Load-Balanced Routing**: Evenly distributes traffic across routes.
- **Breadth-First Search (BFS)**: Unweighted shortest path.

---

### 📊 Advanced Analysis Tools

#### 🔍 Network Analysis
- **Bottleneck Detection**: Identifies high-traffic links using edge betweenness.
- **Resilience Analysis**: Detects critical nodes based on centrality metrics.
- **Connected Components**: Visualizes isolated segments after failure.
- **Real-Time Metrics**: Shows performance and efficiency improvements.

#### ⚡ Performance Optimization
- **Path Comparison**: Visual side-by-side algorithm output.
- **Smart Optimization**: Reroutes traffic through less congested paths.
- **Load Balancing**: Dynamically adjusts weights for flow distribution.
- **Congestion Simulation**: Models real-world traffic stress.

---

### 🚨 Failure Simulation & Recovery

#### Failure Scenarios
- **Random Node Failure**
- **Critical Node (Targeted) Failure**
- **Cascade Failure**
- **Link Failure**
- **Node Congestion**

#### Recovery Features
- **Auto-Recovery**: One-click full reset.
- **Manual Node Management**: Fail/restore nodes as needed.
- **Real-Time Rerouting**: Automatic recalculation after disruptions.

---

### 🎨 Visualization Modes

#### View Types
- **Normal View**: Standard routing.
- **Optimized View**: Shows improved routes.
- **Comparison View**: Displays both paths for algorithm analysis.

#### Visual Cues
- **Animated Packet Flow**: Watch packets travel in real time.
- **Color-Coded Nodes**: Identify core, edge, subnet, and device types.
- **Dynamic Link Styling**: Highlights bottlenecks, optimization, or failures.
- **Interactive Legend**: Explains visualization elements.

---

### 📈 Real-Time Monitoring

- **Live Logging**: Timestamped events and operations.
- **Simulation Results**: Path cost, hop count, and improvements.
- **Metrics Dashboard**: Optimization and algorithm comparison visuals.

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required – everything runs in-browser.

### Quick Start
1. Open `index.html` in your browser.
2. Select **start** and **end** nodes.
3. Choose a **routing algorithm**.
4. Click **"Simulate Routing"** to view results.
5. Explore advanced features and analysis tools.

---

## 🔍 Usage Guide

### Routing Simulation
- Select `Start Node` and `End Node`.
- Pick a `Routing Algorithm`.
- Enable **"Animate Packets"** if desired.
- Click **"Simulate Routing"**.

### Algorithm Comparison
- Switch to **"Compare" View Mode**.
- Choose any two algorithms.
- View path differences and performance metrics.

### Network Resilience Testing
- Go to **"Failure & Recovery"** panel.
- Select failure type (random, critical, cascade, etc.).
- Click **"Simulate Failure"**.
- Observe network adaptation and components.

---

## 🎯 Use Cases

### 🎓 Educational
- Understand how routing algorithms work.
- Explore real-time effects of network congestion or failures.
- Visualize redundancy, centrality, and traffic balancing.

### 💼 Professional
- Evaluate pathfinding strategies for network design.
- Simulate failures to assess recovery capabilities.
- Analyze and compare algorithm performance.

### 🔬 Research
- Test novel routing techniques.
- Study congestion, optimization, and resilience.
- Create or adapt custom topologies.

---

## 🛠️ Technical Overview

### Tech Stack
- **D3.js** – Graph rendering and animations.
- **Bootstrap 5** – UI responsiveness and layout.
- **JavaScript (Vanilla)** – Algorithm logic and simulation control.
- **HTML5/CSS3** – Semantic markup and styling.

### Architecture
- **Force Simulation** for layout.
- **Multiple Algorithm Implementations** (Dijkstra, Bellman-Ford, etc.).
- **Modular Event Handlers** for interaction and toggles.
- **Live DOM Updates** for results and logs.

---

## 🗺️ Default Network Topology

- **2 Core Routers**: `R1`, `R2`
- **3 Distribution Routers**: `R3`, `R4`, `R5`
- **4 Edge Routers**: `EdgeR1`–`EdgeR4`
- **6 Subnets**: `S1`–`S6`
- **6 End Devices**: `PC1`–`PC4`, `Printer1`, `IoT1`

---

## 🖱️ Interactivity

### Mouse Actions
- **Click** – View node details.
- **Drag** – Reposition nodes.
- **Scroll** – Zoom in/out of the graph.

---

## 📊 Metrics & Performance Insights

- **Path Length (hops)**: Total steps in route.
- **Total Cost**: Sum of link weights.
- **% Improvement**: Optimized vs original.
- **Algorithm Comparison**: Efficiency side-by-side.

---

## 🎨 Customization Options

### Add New Routing Algorithms
1. Implement a new function.
2. Register it in `algorithmHandlers`.
3. Add it to the dropdown UI.

### Modify Network Topology
1. Edit the `mockTopologyData` object.
2. Add/remove nodes and links.
3. Adjust weights and node types.

### Styling
- Customize via embedded CSS.
- Tweak node colors, animations, and layout.

---

## 🐞 Troubleshooting

| Issue                    | Solution                                     |
|--------------------------|----------------------------------------------|
| Path not found           | Check for network partitions or failures     |
| Laggy performance        | Reduce node count or disable animations      |
| Broken visuals           | Refresh browser or clear cache               |

✅ Supports all modern browsers with SVG and ES6 support.

---

## 📚 Learn More

### Routing Algorithms
- **Dijkstra** – Greedy shortest path
- **Bellman-Ford** – Handles negative weights
- **Link State** – OSPF-like centralized routing

### Networking Concepts
- **Hierarchical Design** – Core, distribution, access layers
- **Redundancy & Resilience** – Multiple paths, fault-tolerance
- **Load Balancing** – Spreads traffic to avoid bottlenecks

---

## 📝 License

This project is licensed under the **MIT License** – use, modify, and distribute freely.

---

**Built with ❤️ for education, exploration, and innovation.**

##🧑‍💻 Developed By
Vinayak Hegde
Routing Algorithm Simulator https://github.com/Vinuhegde887/Routing-algorithm-simulator/

---
