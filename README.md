# Docker GooglePhotosSync UserScript for Unraid
Script for Unraid User Script to sync all Google Photos Dockers.

## Installing:
- Ensure you have the User Scripts plugin from Community Applications
- Download Master as a .zip
- Extract `GooglePhotosSync` folder to `/boot/config/plugins/user.scripts/scripts/`
- Go to `Settings > User Scripts` then run the script checking for errors and ensuring that it found the correct containers
- Set up a schedule in the User Scripts page to run repetedly

## Customising:
- Edit the script file in `/boot/config/plugins/user.scripts/scripts/` with nano or any other text editor
- If you would like to manually specify docker containers change the `autoFindContainers` line to `false`
- Get your container IDs obtained from enabling Advanced View on the docker container list
- Add these IDs to the `googlePhotosDockers` line seperated by spaces like: `googlePhotosDockers=( d78abn3f912s 9fsa42pabn21 )`

Make sure to leave any issues or improvements you may have in the Issues tab and I will try to help.
