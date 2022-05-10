# Attended-event-monitoring

Example projects for building attended automations that have to deal with monitoring multiple applications for various events, communicating between multiple processes, updating values across.

See https://www.youtube.com/watch?v=cLBsUzyj2y8 to understand how to build such automations.

Functionalities being used:
* Packages:
    * UI Automation
    * UiPath.IPC
    * System
* Desktop Triggers:
    * Trigger Scope
    * Element State Change Trigger
    * Message Receiver Trigger
    * Process Start Trigger
    * Element Attribute Change Trigger
* Managing multiple running processes using UI Automation 
    * Attended Process (Project property)
    * Background Automation (Project property)
    * Use Foreground (Scope)
    * Block User Input (Scope) 
* Orchestrator
    * Automatically Start Process
    * Process can't be stopped from Assistant
