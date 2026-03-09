# Conditional Component Registration based on CONFIG_BT_ENABLED

if CONFIG_BT_ENABLED
    register_component(${component_name})
endif
