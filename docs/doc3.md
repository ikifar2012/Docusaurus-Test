---
id: doc3
title: This is Document Number 3
---
# List

- item 1
- item 2
- item 3
- item 4

# Checklist

- [x] this is a checklist
- [x] I did it  

# Code

```yaml
  action: 
    - service: script.say_sonos
      data_template:
        message: "It has started to rain, so I have turned on the Lights"
    - service: homeassistant.turn_on
      entity_id: group.main_floor
```