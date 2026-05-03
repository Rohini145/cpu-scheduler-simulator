# CPU Scheduler Simulator

A multi-algorithm CPU scheduling simulator built with vanilla JavaScript. Visualize and compare different scheduling algorithms in real-time.

## Features

- **5 Scheduling Algorithms:**
  - FCFS (First Come, First Served)
  - Round Robin (Time Quantum = 4s)
  - SJF (Shortest Job First)
  - Priority Scheduling
  - Energy-Aware Scheduling

- **Interactive Visualization:**
  - Real-time Gantt chart
  - Performance metrics
  - Execution details table
  - Statistical analysis

- **No Dependencies:**
  - Pure HTML/CSS/JavaScript
  - Works offline
  - Single file application
  - Client-side only
    
- **Comparison Factor:**
 Compares all the algorithms available and displays the algorithm that has:
    -Lowest Waiting Time
    -Best Turnaround Time
    -Most Energy Efficient Time
  
## Quick Start

1. Download `multi_scheduler_enhanced.html`
2. Double-click to open in any browser
3. Add processes (arrival time, burst time)
4. Select algorithm from dropdown
5. Click "Simulate" to see results

## How It Works

All scheduling algorithms run in JavaScript:

- **FCFS:** Processes execute in order of arrival
- **Round Robin:** Each process gets 4s time quantum, then rotates
- **SJF:** Process with shortest burst time executes first
- **Priority:** Higher priority (lower number) executes first
- **Energy-Aware:** Switches CPU modes (HP/LP) based on burst time

## Example
Add processes:
P1: Arrival 0s, Burst 4s
P2: Arrival 1s, Burst 8s
P3: Arrival 2s, Burst 2s
Select algorithm → Click Simulate → View Gantt chart & metrics

## Calculated Metrics

- Total Execution Time
- Average Waiting Time
- Average Turnaround Time
- CPU Utilization
- Context Switches
- Energy Consumption (Energy-Aware mode)

## Technologies

- HTML5
- CSS3 (Gradients, Animations, Glassmorphism)
- Vanilla JavaScript (No frameworks)
- Google Fonts (Poppins, JetBrains Mono)

## Browser Support

Works on all modern browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge

## Usage Tips

- Try different algorithms on the same processes to compare
- Observe how waiting times differ between algorithms
- Use Priority Scheduling with different priority levels
- Check energy savings with Energy-Aware mode

## Educational Value

Perfect for learning:
- CPU scheduling concepts
- Algorithm comparison
- Performance analysis
- OS fundamentals

## License

MIT License - Feel free to use, modify, and distribute

## Author

Created as an educational tool for CPU scheduling simulation

---

**Try it now:** Open `multi_scheduler_enhanced.html` in your browser!
