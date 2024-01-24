# TransitionedEventDialogBox
Shows how to setup a Transitioned Event. A Boolean model variable is triggered by a switch and then opens a Dialog Box. Created in 1.3.0.968 * Anything which is not UI cannot trigger UI stuff, so the workaround is to create a variable in MainWindow, make a DynamicLink to the PLC tag (or model variable) and then configure the value change from there.
