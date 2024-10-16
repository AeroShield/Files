# Admin Commands - README

This guide explains how to use the available admin commands in your script. These commands allow you to manage players, set permissions, ban players, teleport, and more.

## Commands

### 1. `/ac.myid`
- **Description**: Returns the player's ID.
- **Usage**: `/ac.myid`
- **Example Response**: `Your ID is: (123)`
  
---

### 2. `/ac.setowner [playerId1] [playerId2] ...`
- **Description**: Sets one or more players as `owner`.
- **Usage**: `/ac.setowner [playerId1] [playerId2] ...`
- **Example**: `/ac.setowner 1 2 3`
- **Output**: 
  - Player(s) with the specified ID(s) will be set as `owner`.
  - Example: `Player with ID (1) has been set as owner.`

---

### 3. `/ac.setperm <permission> [playerId1] [playerId2] ...`
- **Description**: Sets the permission level of one or more players.
- **Usage**: `/ac.setperm <permission> [playerId1] [playerId2] ...`
- **Example**: `/ac.setperm admin 1 2`
- **Output**: 
  - Sets specified players' permissions to the provided level.
  - Example: `Player with ID (1) has been set to (admin).`

---

### 4. `/ac.ban [playerId]`
- **Description**: Bans the player with the specified ID.
- **Usage**: `/ac.ban [playerId]`
- **Example**: `/ac.ban 5`
- **Output**: 
  - Bans the player and disconnects them from the server.
  - Example: `Player with ID (5) banned.`

---

### 5. `/ac.bansrc [source]`
- **Description**: Bans the player using the player's source ID.
- **Usage**: `/ac.bansrc [source]`
- **Example**: `/ac.bansrc 20`
- **Output**: 
  - Bans the player with the given source ID.
  - Example: `The administrator used /ac.bansrc to ban the player with the source: (20)`

---

### 6. `/ac.unban [playerId]`
- **Description**: Unbans the player with the specified ID.
- **Usage**: `/ac.unban [playerId]`
- **Example**: `/ac.unban 5`
- **Output**: 
  - Unbans the player with the specified ID.
  - Example: `Player with ID (5) unbanned.`

---

### 7. `/ac.wall`
- **Description**: Enables or disables the wallhack system for the player.
- **Usage**: `/ac.wall`
- **Output**: 
  - Toggles wallhack for the admin. 
  - Example: `The administrator used /ac.wall to enable the wallhack system`

---

### 8. `/ac.notify`
- **Description**: Toggles real-time notifications on or off.
- **Usage**: `/ac.notify`
- **Output**: 
  - Turns real-time notifications on or off.
  - Example: `You turned on real-time notifications!`

---

### 9. `/ac.print [playerId]`
- **Description**: Captures a screenshot of the specified player's screen.
- **Usage**: `/ac.print [playerId]`
- **Example**: `/ac.print 10`
- **Output**: 
  - Takes a screenshot of the player's screen and logs the action.
  - Example: `The administrator used /ac.print to capture a screenshot of the player's screen with the id: (10)`

---

### 10. `/ac.vehicles`
- **Description**: Deletes all vehicles on the server.
- **Usage**: `/ac.vehicles`
- **Output**: 
  - Deletes all existing vehicles.

---

### 11. `/ac.objects`
- **Description**: Deletes all objects on the server.
- **Usage**: `/ac.objects`
- **Output**: 
  - Deletes all existing objects.

---

### 12. `/ac.peds`
- **Description**: Deletes all peds (NPCs) on the server.
- **Usage**: `/ac.peds`
- **Output**: 
  - Deletes all existing peds (NPCs).

---

### 13. `/ac.tp [playerId]`
- **Description**: Teleports the admin to the specified player's location.
- **Usage**: `/ac.tp [playerId]`
- **Example**: `/ac.tp 5`
- **Output**: 
  - Teleports the admin to the player's coordinates.
  - Example: `It was not possible to obtain the player's position.`

---

### 14. `/ac.pull [playerId]`
- **Description**: Teleports the specified player to the admin's location.
- **Usage**: `/ac.pull [playerId]`
- **Example**: `/ac.pull 5`
- **Output**: 
  - Pulls the specified player to the admin's coordinates.
  - Example: `Player with ID (5) not found.`

---

## Permissions
Some commands require the admin to have specific permission levels, such as `owner` or `admin`. Ensure the player using these commands has the appropriate permissions.
