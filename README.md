# **BNDR | ToDo**

A single-file, browser-based task management system designed for reliability and local data control.

## **Overview**

This system provides two independent lists—"Active Queue" and "Resolved"—to track daily objectives. It is built as a self-contained application requiring no external dependencies, databases, or cloud accounts.

## **Core Capabilities**

* **Task Lifecycle Management:** Add, edit, mark as complete, or remove tasks.  
* **Persistent Local State:** Data is saved to the browser’s `localStorage`.  
* **Portable Data:** Export your entire task list as a JSON file and import it on another device to maintain continuity.  
* **Responsive Architecture:** The interface scales across desktops and mobile devices with a layout optimized for touch interaction.  
* **Visual Modes:** Toggle between light and dark modes to suit your environment.

  ## **Technical Stuff**

* **Zero Deps:** Built w/ standard HTML, CSS, \+ Vanilla JavaScript.  
* **Tactile Design:** Interactive elements are sized for reliable use on touchscreens.  
* **Input Integrity:** Text fields are locked to a base font size to prevent layout breakage on mobile browsers.  
* **Data Portability:** Full support for manual state backup and restoration via JSON payloads.

  ## **Deployment**

1. Open the source file in any modern web browser.  
2. Enter tasks in the "Active Queue" and click "Execute."  
3. Use the toolbar buttons to export your current state or import a saved backup.  
4. Toggle "Night" mode for high-contrast, low-glare visibility.
