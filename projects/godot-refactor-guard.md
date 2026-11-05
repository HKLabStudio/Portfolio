# Godot Refactor Guard

**Publisher:** HK Lab Studio<br>
**Version:** 0.1.1<br>
**Type:** Godot editor addon / developer tool<br>
**Verified with:** Godot 4.7.2 stable<br>
**Release status:** Limited beta

Godot Refactor Guard helps developers catch editor-connected scene signals that disappear during a refactor. It is a limited beta verified for the documented text-scene workflow in Godot 4.7.2 stable.

## Workflow

1. Save a connection baseline in the Godot editor before refactoring.
2. After editing, compare serialized signal connections in text `.tscn` scenes against that baseline.
3. Inspect a missing connection or a possible missing handler in a directly attached GDScript receiver script.
4. Review or edit the proposed source, signal, destination and method, then preview the repair.
5. Approve the write to back up the affected scene and apply the repair, then reopen and test the scene.

## Scope

The addon checks the documented text-scene workflow. It does not analyze programmatic `connect()` calls, C# handlers, binary `.scn` scenes, inherited methods or arbitrary runtime wiring. A proposed signal signature is not guaranteed to be valid; test each applied repair. The Godot editor is required separately.

## Package contents

The commercial package includes the editable addon, a demo, README documentation, small verification tests, a licence and terms. The paid ZIP, addon source, demo source and customer files are maintained privately.

## Product and licence

[Buy on FastSpring](https://hklabstudio.onfastspring.com/godot-refactor-guard)  [View product licence](https://www.hklabstudio.com/product-licence)
