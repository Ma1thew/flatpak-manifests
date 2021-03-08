# Flatpak package for NeovimGtk
Modified to use the flatpak install of neovim (io.neovim.nvim); this won't work without it. Install with `sudo flatpak-builder --install --force-clean --install-deps-from=flathub org.daa.NeovimGtk org.daa.NeovimGtk.json`. This points at my fork of NeovimGtk; just change the source in the manifest to use upstream.
