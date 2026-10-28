# Star Client — starter project

Starter Fabric client mod for Minecraft Java 1.21.11.

## Automatic cloud build

1. Upload the contents of this ZIP to the root of your GitHub `StarClient` repository (not the ZIP file itself).
2. Open the repository's **Actions** tab.
3. Select **Build Star Client** and press **Run workflow**. Alternatively, pushing files to `main` triggers a build automatically.
4. When the workflow finishes, open the run and download the **StarClient-JAR** artifact.

The artifact is a ZIP containing the built JAR. Download and extract it, then place the JAR in your Minecraft `mods` folder alongside Fabric API.

## Important

This is only the initial working project scaffold. It does not yet contain the requested 74 visual modules. Those must be implemented in Java using Minecraft/Fabric rendering and HUD APIs; adding UI toggles alone does not implement them.
