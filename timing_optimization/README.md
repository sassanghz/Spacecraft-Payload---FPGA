# Timing sign-off (DPU 600/300 MHz)

**Sign-off files** (post-route `phys_opt_design -directive AggressiveExplore`):
- `timing_600_300_physopt1.rpt` — all constraints met: WNS 0.000 ns, TNS 0.000, WHS +0.005 ns, WPWS +0.167 ns
- `route_status_600_300_physopt1.rpt` — 166030/166030 nets routed, 0 errors
- `bus_skew_600_300_physopt1.rpt` — 4/4 bus-skew constraints met
- `drc_600_300_physopt1.rpt` — DRC report
- `zusys_600_300_nobit.xsa` — hardware export used for PetaLinux

Not in git (too large; kept as separate backups): `zusys_wrapper_600_300_physopt1.dcp`, `zusys_wrapper_routed_600_300.dcp`, `zusys_wrapper_600_300.bit`.

Other `.rpt` files here are from earlier attempts (including the failed 650/325 MHz runs) and are kept for history only.

Note: timing closes with 0 ns margin. Hardware test results: see the project notes.
