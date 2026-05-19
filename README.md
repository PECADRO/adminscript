# adminscript
This admin script is designed for the game Krunker (2025) to protect against hackers, exploiters, abusers, and glitchers.

The interface is easy to use: press "0" to open the script, use the numpad arrows to move (4 = left, 8 = up, 6 = right, 2 = down), and press "5" to execute a command.

Available actions: "Freeze", "Kill", "Kick", and "Ban" players.

You must designate admins and a super admin. The super admin cannot be banned by other admins.

The client checks the server code to verify whether the admins are listed there before executing commands.

#################################

Before using, update both `client.txt` and `server.txt`:

1. Fill in the admin names where "ADMIN NAME" appears.
2. If you are a map maker, add your name to the `#mapmaker` area. Separate parts of your name with `k1+k2` so your name does not appear in the admins list but you are treated as a super admin.
3. Copy and paste the client script into `client.txt` and the server script into `server.txt`.
