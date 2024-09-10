# REAL-Video-Enhancer-Flatpak

sudo flatpak-builder --system --install --force-clean build-dir io.github.tntwise.REAL-Video-Enhancer.yml

flatpak run org.flatpak.Builder  --force-clean --user --install-deps-from=flathub --repo=repo --disable-rofiles-fuse --install builddir io.github.tntwise.REAL-Video-EnhancerV2.yml
