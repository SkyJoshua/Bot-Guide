# Valour Bot Guide
By SkyJoshua

> **This guide is still a work in progress!**

This guide walks you through creating a bot on Valour.gg, connecting it with the SDK and getting it to do things on a planet. Basic knowledge in .NET is not required but is highly recommended!

## Prerequisites
- A [Valour](https://app.valour.gg) account
- [.NET SDK](https://dotnet.microsoft.com/download) installed
- Basic knowledge of C#
- The [Valour SDK](https://www.nuget.org/packages/Valour.SDK) (installed as part of the guide)

## 1. Create a bot account
1. Log into [Valour](https://app.valour.gg) with your regular account.
2. Go to **Developer Settings** (User Settings -> Developer).
3. Click **Create Bot** and give it a name.
4. **Copy the token immediately** - it is only shown once. If you lose it, you can regenerate it from the bot's edit page (this invalidates the old one).

## 2. Making the bot

### Step 1. [Logging in as the bot](Guides/1.Login.md) — Setting up the project and connecting to Valour
### Step 2. [Joining a planet](Guides/2.JoinPlanet.md) — Adding your bot to a planet
### Step 3. [Connecting and Sending a Message to a Planet](Guides/3.ConnectingAndSending.md) — Opening a real-time connection and sending your first message
### Step 4. [Receiving Messages and Commands](Guides/4.MessagesAndCommands.md) — Listening for messages and creating a basic command
### Step 5. [Command Arguments](Guides/5.CommandArguments.md) — Parsing arguments from commands
### Step 6. [Member Info](Guides/6.MemberInfo.md) — Fetching info about the message author
### Step 7. [Permission Checking](Guides/7.PermissionChecking.md) — Restricting commands to members with the right permissions

---

For more information check out the [Valour GitHub](https://github.com/Valour-Software/Valour) and the [Valour SDK on NuGet](https://www.nuget.org/packages/Valour.SDK).
