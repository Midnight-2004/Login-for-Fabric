##等待重修中
初步想法是将此mod迁移至1.17+版本，但我现在没时间（逃）

-----

# Login
Fabric mod for Minecraft: Java Edition to protect offline mode servers adding /login and /register. This is a server-side mod, clients don't have to download it.

## Features
- Players are invulnerable until they log in
- Players can't interact with the world until they log in
- Players can't move until they log in
- Players can't chat or use commands (only /login and /register) until they log in
- Passwords are saved in `./registered-players.json`
- Maybe I'll add more

## Commands
- /register `<newPassword>` `<confirmPassword>`
- /login `<password>`
