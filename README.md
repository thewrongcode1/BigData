# Hadoop Setup Script

This repository contains a Python script that provides a quick and easy way to set up Hadoop for practice and learning purposes. It automates the installation and configuration process, making it faster to get started with Hadoop on your local machine.

## Features

- Automated setup of Hadoop on local machines.
- Easy configuration of Hadoop-related environment variables.
- Quick start for learning and practicing with Hadoop.
- Configurable settings for pseudo-distributed mode.

## Prerequisites

Before running the setup script, ensure the following requirements are met:

- Python 3.x installed on your machine.
- Admin/sudo privileges (required for installing Hadoop and editing system configurations).
- Java installed (Hadoop requires Java to run).
- An internet connection to download Hadoop binaries.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/hadoop-setup-script.git
    cd hadoop-setup-script
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure that Java is installed by running:
    ```bash
    java -version
    ```

4. If Java is not installed, follow the instructions [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) to install it.

## Usage

Run the setup script as follows:

```bash
python setup_hadoop.py path-to-hadoop
```