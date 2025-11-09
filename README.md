# Process Visualization Tool 🎨

A **Streamlit-based** application designed to visualize **CPU scheduling algorithms** and provide real-time **system monitoring** capabilities.

---

## 🚀 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithms Supported](#algorithms-supported)
- [System Monitoring](#system-monitoring)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Watch the Demo](#watch-the-demo)
- [Team](#team)

---

## ✨ Features

### 🖥️ **Scheduling Algorithms Visualization:**
- **First-Come, First-Served (FCFS)**
- **Shortest Job First (SJF)** - Preemptive and Non-Preemptive
- **Priority Scheduling** - Preemptive and Non-Preemptive
- **Round Robin** - with configurable time quantum

### 📊 **System Monitoring Dashboard:**
- **Current Running Processes**
- **CPU and Memory Usage**
- **Top 5 Resource-Intensive Processes**
- **Storage Utilization**

### ⚡ **Interactive Features:**
- **Custom Process Configuration**
- **Real-Time Gantt Chart Generation**
- **Performance Metrics Calculation**

---

## 💻 Installation

To set up and run the Process Visualization Tool locally, follow these steps:

### 🔧 Prerequisites
Ensure you have the following installed:
- **Python 3.7+**
- **pip** (Python package installer)

### 🛠️ Steps to Install:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/mohanrao06/process-visualization-tool.git
    ```

2. **Navigate into the project directory:**

    ```bash
    cd process-visualization-tool
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

    The application should open in your default browser.

---

## 🚀 Usage

Once the application is running, you can interact with it in the following ways:

1. **Select a Scheduling Algorithm** from the available options (FCFS, SJF, Priority, Round Robin).
2. **Enter Process Details** (process ID, burst time, arrival time, priority, etc.).
3. **Visualize the Scheduling Process** in real-time with Gantt charts and progress indicators.
4. **View System Monitoring Data**, such as CPU usage, memory usage, and top 5 resource-consuming processes.
5. **Adjust Parameters** like time quantum for Round Robin and observe the effect on scheduling.

---

## 📊 Algorithms Supported

### 1. **First-Come, First-Served (FCFS)**

This is a simple scheduling algorithm where processes are executed in the order they arrive. While easy to implement, it may cause high waiting times for longer processes.

### 2. **Shortest Job First (SJF)**

- **Non-Preemptive**: Processes with shorter burst times are executed first.
- **Preemptive (Shortest Remaining Time First)**: A running process may be preempted by a new process with a shorter burst time.

### 3. **Priority Scheduling**

- **Non-Preemptive**: Processes are executed based on priority (lower numbers = higher priority).
- **Preemptive**: A new process with a higher priority can preempt the currently running process.

### 4. **Round Robin (RR)**

This is a preemptive scheduling algorithm where each process is given a fixed time slice (quantum). If a process does not complete within this time, it is placed at the back of the queue for re-execution.

---

## 🖥️ System Monitoring

The **System Monitoring Dashboard** gives insights into the current state of your system:

- **Running Processes**: Displays active processes, their process IDs, and resource usage.
- **CPU Usage**: Real-time percentage of CPU being used.
- **Memory Usage**: Shows the memory consumption, both system-wide and for individual processes.
- **Storage Utilization**: A breakdown of storage usage across your disks.

---

## ⚙️ Configuration

The tool allows you to configure various aspects of the scheduling algorithms, such as:

- **Time Quantum**: Configurable for Round Robin scheduling.
- **Process Details**: Customize process IDs, burst times, arrival times, and priorities.
- **Visualization Options**: Customize Gantt chart colors and layouts for better understanding.

These settings can be easily adjusted through the user interface provided by Streamlit.

---

## 💡 Contributing

We welcome contributions to enhance the functionality and features of this project! To contribute:

1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b feature-name`).
3. **Make your changes** and write tests if applicable.
4. **Commit your changes** (`git commit -am 'Add new feature'`).
5. **Push to your branch** (`git push origin feature-name`).
6. **Create a pull request** to the main repository.

Please ensure that your code follows the project’s coding style and includes proper documentation.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🎥 Watch the Demo

Here’s a quick video walkthrough of the tool in action:

[**Watch Demo**](#) *(Insert the link to your video here)*

---

## 👨‍💻 Team

This project was developed by the following team members:

- **Mohan Rao** (Lead Developer)

Special thanks to all contributors for their support!

---

Happy coding and enjoy visualizing your processes! 🚀

