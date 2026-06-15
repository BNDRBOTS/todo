# **BNDR | ToDo**

A single-file, browser-based task management webapp designed for simplicty in overwhelm.

## **Overview**

You get two independent lists—"Active Queue" and "Resolved"—to track daily objectives. Made as a self-contained webapp requiring no external dependencies, databases, or cloud accounts.

## **Here's What It Does**

* **Task Lifecycle Management:** Add, edit, mark as complete, or remove tasks.  
* **Persistent Local State:** Data is saved to the browser’s `localStorage`.  (careful if clearing your history, cache, etc - make a backup and reload after)
* **Portable Data:** Export your entire task list as a JSON file and import it on another device to maintain continuity.  
* **Mobile Responsive:** The interface scales across desktops and mobile devices with a layout optimized for touch interaction.  
* **Visual Modes:** Toggle between light and dark modes to suit your environment.

  ## **Technical Stuff**

* **Zero Deps:** Built w/ standard HTML, CSS, \+ Vanilla JavaScript.  
* **Tactile Design:** Interactive elements are sized for reliable use on touchscreens.  
* **Input Integrity:** Text fields are locked to a base font size to prevent layout breakage on mobile browsers.  
* **Data Portability:** Full support for manual state backup and restoration via JSON payloads.

  ## **To Use**

1. Open the source file in any modern web browser. (or click the link here): [BNDR | ToDo](https://bndrbots.github.io/dashboard/)
2. Enter tasks in the "Active Queue" and click "Execute."  
3. Use the toolbar buttons to export your current state or import a saved backup.  
4. Toggle "Night" mode for high-contrast, low-glare visibility.
