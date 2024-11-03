crave run --no-patch -- "rm -rf .repo/local_manifests; \
repo init -u https://github.com/Evolution-X/manifest.git; \
git clone https://github.com/tillua467/local_manifests.git; \ 
/opt/crave/resync.sh; \
.build/envsetup.sh; \
lunch lineage_$phoenix-userdebug; \ 
m evolution"
