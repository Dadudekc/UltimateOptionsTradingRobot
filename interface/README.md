# Interface Directory

The Interface directory houses the PyQt5-based graphical user interface (GUI) for interacting with TradingRobotPlug. This includes the main window, custom widgets, dialogs, and style sheets.

## Structure
- `pyqt5_interface/`: Contains all GUI-related scripts and resources.
  - `widgets/`: Custom widgets for various parts of the interface (e.g., dashboards, settings).
  - `dialogs/`: Dialog windows for settings, notifications, etc.
  - `styles/`: Style sheets for consistent design and themes.

## Guidelines
1. Keep widget code modular by separating different interface components into individual files within `widgets/`.
2. Ensure styles are easily configurable for a consistent look and feel.
3. Maintain a clear directory structure to support easy customization and future extensions.