# Fedora Dotfiles

**Author:** Weston Preising

Fedora i3 spin config for development and guitar practice/recording. Emphasis on vim-based applications when possible since vim is fun. A profound thank you to all open source contributors—thank you for making Linux accessible and enjoyable :).

## To-do

1. Update headers on all config files
2. Add install commands
3. add lxqt-policykit
4. lightdm-gtk theme
5. explain dark theme from reddit post
6. explain fedora background default
7. explain lightdm-gtk settings
8. ripgrep-all (banger)

## Main Fedora i3wm Setup

- [Fedora 43 Post Install Guide](https://github.com/devangshekhawat/Fedora-43-Post-Install-Guide) — essential post-install steps
- [Picom](https://github.com/yshui/picom) compositor with EGL backend
- [autorandr](https://github.com/phillipberndt/autorandr) — automatic display configuration based on connected hardware

## Terminal & Shell

- [kitty](https://sw.kovidgoyal.net/kitty/) with [CommitMono](https://commitmono.com/) font (includes Nerd Font glyphs)
- [oh-my-zsh](https://ohmyz.sh/) with plugins:
  - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
  - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
  - [zsh-completions](https://github.com/zsh-users/zsh-completions)
  - [gradle-completion](https://github.com/gradle/gradle-completion)
  - [zsh-nvm](https://github.com/lukechilds/zsh-nvm)
- [starship](https://starship.rs/) prompt
- [eza](https://github.com/eza-community/eza) as ls replacement
- [fastfetch](https://github.com/fastfetch-cli/fastfetch) system info

## Editor & File Management

- [Neovim](https://neovim.io/) via [LazyVim](https://www.lazyvim.org/)
- [yazi](https://github.com/sxyazi/yazi) — terminal file manager
- [zathura](https://pwmt.org/projects/zathura/) with [zathura-pdf-poppler](https://pwmt.org/projects/zathura-pdf-poppler/) for PDF viewing

## Browsers

- [Firefox](https://www.mozilla.org/en-US/firefox/) with [Betterfox](https://github.com/yokoffing/Betterfox) user.js
  - **Productivity & Utilities:**
    - 1Password
    - SponsorBlock
    - Unhook
    - Vimium C
    - Ultimadark (significantly faster than Dark Reader)
  - **Betterfox / Privacy Suite:**
    - uBlock Origin
    - Tampermonkey (w/ AdGuard Twitch AdBlock script)
    - Bypass Paywalls Clean
- [qutebrowser](https://qutebrowser.org/) — keyboard-driven browser, used strictly for [Markdown Preview](https://github.com/iamcco/markdown-preview.nvim)

## Communication

- [Discord](https://discord.com/)

## Development Setup and Tools

- [Fedora Adding New Fonts](https://docs.fedoraproject.org/en-US/quick-docs/fonts/)
- [Fedora Installing Java](https://docs.fedoraproject.org/en-US/quick-docs/installing-java/)
- [Fedora LaTeX / TeXLive](https://docs.fedoraproject.org/en-US/neurofedora/latex/)
- [Docker on Fedora](https://docs.docker.com/engine/install/fedora/)
  - [Post-Install (non-root setup)](https://docs.docker.com/engine/install/linux-postinstall/)
  - [Shell Autocompletion](https://docs.docker.com/compose/completion/)
- [Clang-Format Style Options](https://clang.llvm.org/docs/ClangFormatStyleOptions.html)
- [img2pdf](https://pypi.org/project/img2pdf/) — lossless image to PDF
- [cpdf](https://github.com/coherentgraphics/cpdf-binaries) — PDF manipulation CLI
- [tldr](https://github.com/tldr-pages/tldr) - quick cli tips n' tricks
- [zeal](https://zealdocs.org/) - offline coding reference docs
- [SDKMAN](https://sdkman.io/) for JDK management (Gradle)
- [w3m](https://sourceforge.net/projects/w3m/)

## Music Production / Guitar

- [Linux audio realtime setup](https://wiki.linuxaudio.org/wiki/system_configuration): run `realtime-setup`, enable services, add user to `realtime` group
- [Transcribe!](https://www.seventhstring.com/) — slow down audio, loop sections, transcribe by ear
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — download videos/audio from YouTube
- [DaVinci Resolve Studio](https://www.blackmagicdesign.com/products/davinciresolve) — video editing
  - [davinci-helper](https://github.com/H3rz3n/davinci-helper) — Fedora installation/setup assistant
  - **Fedora 43 fix:** davinci-helper doesn't currently launch on F43; see [howto-davinci-resolve-fedora-43](https://github.com/gerelef/howto-davinci-resolve-fedora-43) for a workaround
- [OBS Studio](https://obsproject.com/) with [DroidCam](https://www.dev47apps.com/)
- [wine-tkg](https://copr.fedorainfracloud.org/coprs/patrickl/wine-tkg/) — sets up wineasio and works with Yousician app
- [Bitwig Studio](https://www.bitwig.com/) (Flatpak)
- [Handbrake](https://handbrake.fr/) — video transcoding
- [VLC](https://www.videolan.org/vlc/)
- [LocalSend](https://localsend.org/) — cross-platform file sharing (Flatpak)

## School / Testing

- [Eclipse](https://eclipseide.org/) (Flatpak)
  - HiDPI fix: `GDK_SCALE=2 GDK_DPI_SCALE=0.5`
- [RARS](https://github.com/TheThirdOne/rars) — RISC-V assembler and simulator (using custom script for antialiasing)
- [esp-idf](https://github.com/espressif/esp-idf) toolchain (not currently in use, but planning ESP32 projects)

## AI Usage

- Claude occasionally used in a Socratic tutor capacity and to help debug code if I'm incredibly stuck; however, never used to generate code.
