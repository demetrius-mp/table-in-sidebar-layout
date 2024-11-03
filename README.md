# repro

Table component is not responsive when used inside sidebar layout

Check `/with-sidebar` and `/without-sidebar` for comparison

It seems the issue is the `flex` class in the `div` rendered by the `<SidebarProvider>`. If you remove it, the table is reponsive again, but everything else is misplaced in the screen.
