# Commands and Permissions

## Base Command

**Command** | **Permission** | **Arguments** | **Explanation**
----------- | -------------- | ------------- | ------------------------------------
**/cr**     | cr.crate       |               | The base command for Crate Reloaded.
**/crate**  | cr.crate       |               | The base command for Crate Reloaded.

## Admins

**Command**    | **Permission** | **Arguments** | **Explanation**
-------------- | -------------- | ------------- | ----------------------------
**/cr reload** | cr.reload      |               | Reloads the plugin's config.

## Moderators

**Command**        | **Permission** | **Arguments**                  | **Explanation**
------------------ | -------------- | ------------------------------ | ---------------------------------------------------------
**/cr addnpc**     | cr.addnpc      | [npc id] [crate name]          | Sets the npc to a specific crate.
**/cr give**       | cr.give        | [player] [crate name] [amount] | Gives the player specified amount of crates.
**/cr giveall**    | cr.giveall     | [crate name] [amount]          | Gives every player specified amount of crates.
**/cr givekey**    | cr.givekey     | [player] [key name] [amount]   | Gives every player specified amount of keys.
**/cr giveallkey** | cr.giveallkey  | [key name] [amount]            | Gives every player specified amount of keys.
**/cr set**        | cr.set         | [crate name]                   | Sets a crate at the location the player is looking at.
**/cr remove**     | cr.remove      | [crate name]                   | Removes a crate at the location the player is looking at.
**/cr removenpc**  | cr.removenpc   | [npc id]                       | Removes the npc crate.
**/cr list**       | cr.list        |                                | List available crates.
**/cr commands**   | cr.commands    |                                | List every command available.

## Users

**Command**  | **Permission** | **Arguments** | **Explanation**
------------ | -------------- | ------------- | -------------------------------------
**/cr info** | cr.info        | [crate name]  | Shows information about a crate.
**/cr buy**  | cr.buy         | [crate name]  | Allows the player to purchase crates.
