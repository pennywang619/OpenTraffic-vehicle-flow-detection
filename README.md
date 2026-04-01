# OpenTraffic-vehicle-flow-detection

Public delivery repository for vehicle-flow detection and its released submodules.

## Delivery Contents

This repository includes:

1. main vehicle-flow shared library in `main/`
2. submodule deliveries in `subtasks/`
3. release index in `index/public_release_index.json`
4. validation summaries, manifests, examples, and checksums for each bundle

## Included Submodules

This repository includes the released submodules:

1. `02_vehicle_motion_state_sample`
2. `04_area_vehicle_counting_sample`
3. `05_lane_turning_flow_rebuild_sample`
4. `06_lane_queue_length_detection_sample`
5. `07_overflow_detection_sample`
6. `08_lane_line_detection_sample`

The current bundle also contains `01_object_tracking_sample` as an upstream support submodule.

## Quick Start

1. Review `index/public_release_index.json`.
2. Verify each bundle with its local `checksums.txt`.
3. Use `main/` for the main vehicle-flow module.
4. Use `subtasks/02_vehicle_motion_state_sample` and `subtasks/04_area_vehicle_counting_sample` through `subtasks/08_lane_line_detection_sample` for submodule-level integration and validation.

See `USAGE.md` and `SUBTASKS.md` for details.
