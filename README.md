# dps-maritime-maps

Map files for the Jetsam docks at the Port of Los Santos: a warehouse interior, dock props and
changes to the port outside. Made as the map half of
[dps-maritime](https://github.com/DaemonAlex/dps-maritime).

## Status

Not running on DelPerroSands. The server uses the paid Prompt Jetsam maps (`prompt_jetsam` and
`prompt_jetsam_warehouse`) for the same docks. Do not run both: they replace some of the same
port map files.

## What it is for

dps-maritime is a dock work and boat delivery job. It needs a warehouse to work from. This
resource is that building and the dock around it. It has no scripts. It only streams map files.

## What is in it

- **Warehouse interior.** The `slth_warehouse` interior: shell, doors, lights, pipes, lockers,
  shelving, curtains and blueprints.
- **Port outside.** Edited pieces of the stock port area (`hei_po1_06` and `id1_31`), with
  collision and light files to match.
- **Containers.** `base_containers.ymap` places containers on the dock.

## On its own, and with other scripts

**On its own.** Players can walk into the Jetsam warehouse at the port and see the changed dock.
Nothing else happens. There are no jobs, markers or doors here.

**With [dps-maritime](https://github.com/DaemonAlex/dps-maritime).** That script runs the dock
work and boat deliveries in and around this building. This resource does not call it. Start the
map first.

**With the paid Prompt Jetsam maps.** They clash. Both replace `hei_po1_06_long_1.ymap`,
`hei_po1_06_strm_0.ymap` and `hei_po1_occl_02.ymap`, and both change the same port collision.
Pick one.

## Requirements

- A FiveM server. No other resource is needed.

## Install

1. Put the folder in your resources.
2. Add `ensure dps-maritime-maps` before `dps-maritime`.
3. Make sure no other map of the Jetsam docks is running.

## Recent changes

- **12 November 2026.** README: status, what it is for, how it works alone and with paid scripts, other DPS scripts. First README.
- **1 January 2026.** First release of the map files (version 1.0.0).

## Author

Made by [DaemonAlex](https://github.com/DaemonAlex) for DelPerroSands.

The warehouse models use the `slth_` name prefix. This repo does not record who made them. If you
know the maker, add the credit here before sharing these files.

## Other DPS scripts

All of these are made for DelPerroSands and run together on one Qbox server. Each one works on
its own. The ones marked "pairs with" do more when both are running.

| Script | What it does |
|---|---|
| [dps-inventory](https://github.com/DaemonAlex/dps-inventory) | The inventory: ox_inventory with equipment slots, backpacks, armour plates and a self status panel, in the DelPerroSands colours. |
| [dps-medical](https://github.com/DaemonAlex/dps-medical) | Patient records, illness and diagnostic tests. A companion to wasabi_ambulance. Pairs with dps-inventory: symptoms and diagnoses show on the status panel. |
| [dps-insurance](https://github.com/DaemonAlex/dps-insurance) | Ties m-Insurance into the MDT, impound, hospital and medical chart. Pairs with dps-medical. |
| [dps-studio](https://github.com/DaemonAlex/dps-studio) | Build rooms, doors and portals in game from one panel (`/studio`), with owners and managers so staff do not have to support them. |
| [dps-shops](https://github.com/DaemonAlex/dps-shops) | Shop clerks who greet and react to a robbery, then player-owned shops. |
| [dps-fleet](https://github.com/DaemonAlex/dps-fleet) | Vehicle browser and workshop on one panel: extras, liveries and mods for emergency vehicles. |
| [dps-parking](https://github.com/DaemonAlex/dps-parking) | Parking with valet, impound, violations and reserved spots. |
| [dps-vehiclepersistence](https://github.com/DaemonAlex/dps-vehiclepersistence) | Vehicles stay where they were parked. Pairs with dps-parking. |
| [dps-towjob](https://github.com/DaemonAlex/dps-towjob) | Queue-based tow job with jg-mechanic integration. |
| [dps-services](https://github.com/DaemonAlex/dps-services) | Request a tow and follow it live on the lb-phone and lb-tablet. Pairs with dps-towjob. |
| [dps-autoshops](https://github.com/DaemonAlex/dps-autoshops) | Self-service repair shops when no mechanic is on duty. |
| [dps-cityworker](https://github.com/DaemonAlex/dps-cityworker) | City infrastructure job and career. |
| [dps-ainpcs](https://github.com/DaemonAlex/dps-ainpcs) | NPCs you can talk to, with trust, quests and intel. |
| [dps-badpeds](https://github.com/DaemonAlex/dps-badpeds) | Police interaction with NPCs: stops, arrests, intel and jail records. |
| [dps-gangwars](https://github.com/DaemonAlex/dps-gangwars) | Ambient gang NPCs, territory population and war reinforcements. |
| [dps-rotations](https://github.com/DaemonAlex/dps-rotations) | Moves dealers, harvests and other spots on a fixed schedule. |
| [dps-trains](https://github.com/DaemonAlex/dps-trains) | The train system. Pairs with dps-trains-stock, dps-traintools and dps-transitapp. |
| [dps-transitapp](https://github.com/DaemonAlex/dps-transitapp) | Live train arrival boards on the lb-phone. |
| [dps-faceplant](https://github.com/DaemonAlex/dps-faceplant) | City help, reports and staff tools on the lb-phone and lb-tablet. |
| [dps-chat](https://github.com/DaemonAlex/dps-chat) | A command box for voice-only servers. No chat feed. |
| [dps-filmmode](https://github.com/DaemonAlex/dps-filmmode) | One key hides every HUD layer and gives a smooth free camera for recording. |
