# esphome-nodes

[ESPHome](https://esphome.io/) configuration for the various nodes used around my home.

## Layout

- `/` — Individual node configs (to be compiled with [ESPHome](https://esphome.io/)).
  - A `secrets.yaml` needs to be provided here containing static IP addresses for each node.
- `/common/` — Re-usable configuration for boards, sensors etc.
  - A `secrets.yaml` needs to be provided here for various config blocks such as WiFi.
  
If a node config has grown too large, there may be a directory with a matching name containing more config e.g. `/theatrelighting/`.
