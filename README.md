## Download
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/coffee100percnt/local_manifests/master/manifest.xml --create-dirs
```
## Sync
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
