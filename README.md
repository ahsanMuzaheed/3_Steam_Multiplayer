# Unreal Multiplayer Course - Section 3 - Steam Multiplayer

In follow up to our hugely successful [Complete Unreal Engine Developer](http://gdev.tv/urcgithub) course we bring you [Unreal Multiplayer Mastery](http://gdev.tv/uemgithub) - as on featured on [Epic's UE4 blog](https://www.unrealengine.com/en-US/blog/getting-started-with-unreal-multiplayer-in-cpp).

In this section we teach you to connect your games P2P over steam. This game introduces Unreal's Online Sub-System (OSS) and shows you how to use it with the Steamworks API. By the end of the section, you will be able to connect player through Steam lobbies.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: [Unreal Multiplayer Mastery](http://gdev.tv/uemgithub)


### 0 Introduction to Steam Multiplayer ###

+ We overview the section topic.

### 1 Getting The Steamworks SDK ###

+ Introducing Steamworks.
+ Downloading the Steamworks SDK.
+ Steamworks and the Online Sub-System.

### 2 Building SpaceWar In Visual Studio ###

+ Introducing the Steamworks example project.
+ Updating the project.
+ Downloading & installing DirectX SDK.
+ Fixing the build errors.

### 3 Building SpaceWar In Xcode ###

+ Introducing the Steamworks example project.
+ Applying recommended settings.
+ Running with Steam.

### 4 Testing Steam Lobbies ###

+ Finding a testing partner.
+ Testing servers.
+ Testing lobbies.

### 5 The Online Sub-System ###

+ Importing PuzzlePlatforms.
+ Capabilities of Online Sub-Systems.
+ Including the OSS module.
+ Getting a pointer to the sub-system.

### 6 NULL Sub-System For Testing ###

+ Role of the NULL sub-system.
+ Configuring the NULL service.
+ Printing the current service name.

### 7 Memory Management In C++ ###

+ Stack vs Heap.
+ Manual memory management.
+ Reference counting with `TSharedPtr`.
+ Garbage Collection of UObjects.

### 8 Creating Online Sessions ###

+ Creating a session.
+ Asynchronous operations and delegates.
+ Creating a session on host.

### 9 Destroying Online Sessions ###

+ Asynchronous destruction.
+ Checking if a session exists.
+ Destroy the session if we need to.

### 10 Finding Online Sessions ###

+ `FindSessions` and `TShareRef`.
+ Handling `OnFindSessionsCompleteDelegates`.

### 11 Query Parameters & Session Settings ###

+ Configuring Session Settings.
+ Adding query parameters.
+ Iterating over a `TArray`

### 12 Lists Of Widgets With ScrollBox ###

+ Introduction to the `ScrollBox`.
+ Creating a row widget.
+ Add rows in C++.

### 13 Populating The Server List ###

+ Expose the text property.
+ Setting a server list from GameInstance.
+ Clearing the previous list.
+ Requesting a refresh.

### 14 Selecting A Server ###

+ Using `TOptional` values.
+ Setup the `UServerRow`.
+ Adding a `UButton`.
+ Set the selected index.

### 15 Joining A Session ###

+ Passing the index to `GameInstance`.
+ How to `JoinSession`.
+ Handling `OnJoinSessionComplete`.
+ Getting the platform connect string.

### 16 Enabling The Steam OSS ###

+ Enabling the steam plugin.
+ Compiling with the steam module.
+ Configuring the `DefaultEngine.ini`.
+ Reading the verbose logs.

### 17 "Presence" For Steam Lobbies ###

+ Enabling presence for the server.
+ Enabling presence for search.
+ Debugging our connection.

### 18 Row Selection In Lists ###

+ Update text colour on hover.
+ Update all rows when `Selected`.
+ Select colors for `Hovered` and `Selected`.

### 19 Displaying Search Result Properties ###

+ Disabling Steam for testing.
+ Creating a struct.
+ Populating the struct.
+ Updating the UI. 

### 20 Debugging The Search Results ###

+ Disabling Steam fully.
+ Getting the available connections.
+ Padding the text properly.

### 21 Custom Session Settings ###

+ How to set custom settings.
+ How to retrieve custom settings.
+ Setting the server name.

### 22 Continued: Custom Session Settings ###

+ We finish the challenge solution.
+ We make our menu pretty again.

### 23 GameMode And Multiplayer ###

+ Joining into the lobby.
+ Creating a GameMode override.
+ Handling `PostLogin`.
+ Handle `Logout` and count players.

### 24 Enabling Seamless Travel ###

+ Ensuring we call `Super`.
+ Traveling to the game.
+ What is non-seamless travel?
+ Enabling seamless travel.
+ The transition map.

### 25 Debugging Engine Code ###

+ Installing editor symbols.
+ Finding the NULL subsystem code.
+ What code should be called?
+ Attaching and debugging.
+ Fixing the NULL subsystem bug.

### 26 Starting A Session ###

+ Update maximum number of players.
+ Adding a session start timeout.
+ Starting the session.

### 99 Steam Multiplayer Wrap-up

+ We review the topics covered this section.
