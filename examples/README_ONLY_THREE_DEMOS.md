# Examples (only three demos)

- `2p9_ProductManufacturer/` — 2.9" (168×384)
- `4p2_MultipleLanguages/` — 4.2" (300×400)
- `4p2_calendarAnimation/` — 4.2" (300×400)

Each sketch compiles without including `DisplayConfig.h` and declares local fallback `DISPLAY_WIDTH/HEIGHT`.
Default-pin convenience constructors are used; drivers include `DisplayConfig.h` internally for pins.
