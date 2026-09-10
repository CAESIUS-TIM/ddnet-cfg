```ddnet_cfg
# 0. cl_dummy_resetonswitch 0
# 1. vertical sync fly
# 2. aim up
# 3. move
bind x "cl_dummy_control 1;cl_dummy_copy_moves 0;bind mouse1 \"+fire;+toggle cl_dummy_fire 1 0\""
bind c "cl_dummy_control 0;cl_dummy_copy_moves 1;dummy_reset;bind mouse1 \"+fire;+toggle cl_dummy_hammer 1 0\""
```
