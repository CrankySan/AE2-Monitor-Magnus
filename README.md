# AE2-Monitor-Magnus

Monitor script for Applied Energistics 2 bridges that displays stored items, fluids, and chemicals on a connected ComputerCraft monitor.

## Features
- Supports AE2 item, fluid, and chemical bridges (including Mekanism chemicals) with per-type filtering.
- Tracks storage changes over multiple time windows (seconds, minutes, hours, days) and shows per-hour/day deltas.
- On-screen scroll buttons let you move through long lists without a keyboard.
- Touch controls for changing type filters (All/Items/Fluids/Chemicals) and time units directly on the monitor.

## Usage
1. Connect a `me_bridge` and `monitor` peripheral to your ComputerCraft computer.
2. Place this script on the computer and run it; the monitor will automatically render the grid.
3. Tap the on-screen buttons to switch time units, filter by resource type, sort columns, or scroll through entries.
