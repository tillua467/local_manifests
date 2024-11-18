crave run --no-patch -- "rm -rf .repo/local_manifests; \
repo init -u https://github.com/Evolution-X/manifest -b udc --git-lfs; \
git clone https://github.com/tillua467/local_manifests.git .repo/local_manifests; \
/opt/crave/resync.sh; \
source build/envsetup.sh; \
lunch lineage_phoenix-userdebug; \
m evolution"
