SET(SOURCES screens/ui_AlarmArmed.c
    screens/ui_AlarmSet.c
    screens/ui_ChooseCode.c
    screens/ui_MainMenu.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c)

add_library(ui ${SOURCES})
