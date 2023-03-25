# Simple modpack Base

This repository contains an empty modpack meant to be used as a base for your project.
<br>It is based on Fabric and Modrinth, and contains no mods, just a structure and a guide to create your own complex pack.
<br>This guide has versionning on github and team collaboration in mind.

## Guide to start creating

1. Download git
<details>
  <summary>Instructions</summary>
  If you are experienced with  savy, just get git the way you usually do and skip this part.
  <br>Otherwise, download a git client : https://desktop.github.com/
  <br>This one is github's official client and comes bundled with git for easy installation.
</details>

2. Create a github account and log in
<details>
  <summary>Instructions</summary>
  Create an account on github : https://github.com/
  <br>You can use your microsoft account, which you already have if you own minecraft.
</details>

3. Fork and clone this repository
<details>
  <summary>Instructions</summary>
  On github, click the "fork" button at the top right of the page https://github.com/Darkxell/SimpleModpackBase/fork
  <br>Then, using Github desktop, click on "file" -> "Clone" -> "Darkxell/SimpleModpackBase".
  <br><br>This steps downloads a copy of the repository's file to your computer, that you will be able to modify and create your own pack from.
  <br>If you are joining a team, do not fork. Ask your team leader to add you to the already forked repository, and clone from Github desktop directly.
</details>

4. Create a modpack on modrinth
<details>
  <summary>Instructions</summary>
  Go on https://modrinth.com, and log in with your github account.
  <br>If you are joining a team, ask your leader to add you to the Modrinth project instead.
</details>

5. Install MultiMc
<details>
  <summary>Instructions</summary>
  We will be using MultiMc available at : https://multimc.org/
  <br>Other options such as ATLauncher are possible : https://atlauncher.com/, but this guide will not cover them.
</details>


6. Create a minecraft fabric instance
<details>
  <summary>Instructions</summary>
  On MultiMc, click "Add Instance" -> Vanilla -> (Your modpack version)
  <br>Enter the name of your pack at the top and validate
  <br>Then, Click your instance -> "Edit Instance" -> "Version" -> "Install Fabric"
  <br>You may want to launch the instance now to make sure you can already play it.
</details>

7. Add the instance to your repository
<details>
  <summary>Instructions</summary>
  Since we can't move a multiMC instance out of the "instances" folder, we'll have to move this repository in the instance, adding all the mods and config.
  <br>In MultiMC, click "Instance folder"
  <br>In the folder that opens, drag and drop the content of the repository you cloned, adding all the mods and config to the instance you just created.
  If done correctly, your instance folder should contain a .minecraft folder and a versioning-mod filder next to each other.
  <br>This will break github desktop.
</details>

## Guide to publishing your pack

Now that your modpack is done and ready to be played, you will want to publish it to platforms like curseforge and modrinth.

WORK IN PROGRESS
https://docs.modrinth.com/docs/modpacks/creating_modpacks/
