Note before archiving:
Since I now have a separate repository for manifests, I feel like this is redundant. You can view the updated manifest here https://github.com/nico359/flatpak-repo

Build flatpak:
flatpak-builder --repo=repo --force-clean --sandbox --user --install --install-deps-from=flathub build io.github.brandonp2412.flexify.yml

See [flatpak-flutter](https://github.com/TheAppgineer/flatpak-flutter) for further details.
