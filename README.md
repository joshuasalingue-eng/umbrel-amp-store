# Josh's Umbrel App Store

A small Umbrel community app store with one app: **AMP** (Application Management Panel) by CubeCoders.

## Add this store to Umbrel

1. Open the **App Store** on your Umbrel.
2. Click the **⋯** menu (top right) and choose **Community App Stores**.
3. Paste this repository's URL and click **Add**.
4. Open the store and install **AMP**.

## Using AMP

- Open AMP from your Umbrel home screen. It runs on port **8471**.
- Sign in with username `admin` and the password shown on AMP's page in the Umbrel App Store.
- Enter your CubeCoders licence key when asked. Buy one at https://cubecoders.com/AMP.
- Game ports that are open: Minecraft Java **25565-25570** (TCP and UDP) and Minecraft Bedrock **19132** (UDP). Give each server in AMP one of these ports.
- To let friends outside your home join, forward the port on your router to your Umbrel.
- Your servers and saves are kept in `~/umbrel/app-data/josh-amp/data`.
- When you create an instance in AMP, leave **Use Docker** turned off.

## Notes

This app uses the community-made [AMP-dockerized](https://github.com/MitchTalmadge/AMP-dockerized) image. It is not made or supported by CubeCoders.
