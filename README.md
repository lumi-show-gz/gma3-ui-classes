# grandMA3 UI Class Reference

An automatically generated property reference for grandMA3 UI classes, compiled directly from the gMA3 Lua engine runtime (`Obj:PropertyName()` and `Obj:Get()`).

## Property Status Legend

| Tag | Meaning |
| :--- | :--- |
| `[W]` | **Writable** — Property can be safely modified via script |
| `[R]` | **Read-Only** — Locked by engine, auto-calculated, or strict Enum |
| `[R-Event]` | **Event Callback** — Signal / Event Hook (`Clicked`, `OnLoad`, etc.) |
| `[R-Object]` | **Reference Object** — Returns a table or C++ userdata handle |
| `[R-System]` | **System Reserved** — Hardware/network property (bypassed to prevent crashes) |
| `[R-Fragile]` | **Fragile Modal** — Property testing skipped to prevent UI crash |
| `[W-Destructive]` | **Writable (Destructive)** — Modifying this property destroyed the object instance |

## How to Update Documentation

1. Place `scripts/dumpClass.lua` into your gMA3 `gma3_library/p2p/` or plugin directory.
2. Run the plugin from the command line or UI:
   ```lua
   LUA 'dumpClass("Button")'
   ```
3. Commit the updated `.md` file to the matching software version folder in `docs/`.
