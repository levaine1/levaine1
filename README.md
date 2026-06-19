<!-- ====================== HEADER ====================== -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffafbd,100:ffc3a0&height=200&section=header&text=levaine1&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=systems%20programmer%20%E2%80%A2%20rust%20%E2%80%A2%20os%20dev&descAlignY=55&descSize=18" width="100%"/>
</div>

<!-- ====================== TYPING INTRO ====================== -->
<div align="center">
<a href="#">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=E991AA&center=true&vCenter=true&width=600&height=50&lines=building+an+OS+from+scratch+in+Rust;no_std+%2B+nightly+%2B+bare+metal;currently+hacking+on+%E2%9A%99%EF%B8%8F+Erbium" alt="Typing SVG" />
</a>
</div>

<br/>

<!-- ====================== ABOUT (GLASS CARD) ====================== -->
<table align="center" width="100%">
<tr>
<td align="center" style="border-radius: 16px;">

```
╭─────────────────────────────────────────────────────╮
│  whoami                                              │
│  > hobby OS developer, drawn to the bare-metal side  │
│  > Rust nightly, no_std, x86_64, zero excuses        │
│  > currently shipping: Erbium                        │
╰─────────────────────────────────────────────────────╯
```

</td>
</tr>
</table>

<br/>

<!-- ====================== FEATURED PROJECT: ERBIUM ====================== -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=soft&color=0:ffdde1,100:ee9ca7&height=90&section=header&text=%E2%9A%97%EF%B8%8F%20Erbium&fontSize=34&fontColor=ffffff&animation=twinkling&fontAlignY=55" width="100%"/>
</div>

<div align="center">

**A hobby x86_64 operating system, written entirely in Rust.**
Boots via BIOS, runs in QEMU, talks to real ATA disks over FAT32 — no Linux underneath, no training wheels.

[![Rust](https://img.shields.io/badge/Rust-nightly-ee9ca7?style=for-the-badge&logo=rust&logoColor=white&labelColor=ffafbd)](https://www.rust-lang.org/)
[![no_std](https://img.shields.io/badge/no__std-bare%20metal-ffc3a0?style=for-the-badge&logo=rust&logoColor=white&labelColor=ffafbd)](https://docs.rust-embedded.org/book/intro/no-std.html)
[![QEMU](https://img.shields.io/badge/QEMU-tested-ffdde1?style=for-the-badge&logo=qemu&logoColor=white&labelColor=ee9ca7)](https://www.qemu.org/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-ffafbd?style=for-the-badge&labelColor=ee9ca7)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

</div>

<table align="center" width="100%">
<tr>
<td width="50%" valign="top">

**🧩 Stack**
- FAT32 filesystem (own implementation)
- ATA PIO driver (LBA28, ports `0x1F0–0x1F7`)
- PS/2 keyboard + Intellimouse driver
- VGA framebuffer, 8×8 bitmap font renderer
- BMP / PNG / JPEG decoding & on-screen display
- Linked-list heap allocator (16MB)

</td>
<td width="50%" valign="top">

**🐚 Shell**
- Tab completion, history (↑ / ↓)
- Unix-style pipes: `cat file.txt | cat`
- Scrollable console (mouse wheel)
- Anti-flicker partial redraw
- `ls` `cat` `write` `forge` `shred` `tree` `view` …

</td>
</tr>
</table>

<div align="center">

```
Shell → VFS → FAT32 driver → ATA PIO → QEMU emulated IDE disk
                                  ↓
        Console → Framebuffer → VGA (BIOS boot info)
                                  ↑
              PS/2 Keyboard + Mouse → Main loop
```

</div>

<div align="center">

[![Erbium](https://img.shields.io/badge/repo-Erbium-ffafbd?style=for-the-badge&logo=github&logoColor=white&labelColor=ee9ca7)](https://github.com/levaine1/Erbium)

</div>

<br/>

<!-- ====================== STATS (GLASS THEME) ====================== -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=50&section=header&text=Stats&fontSize=24&fontColor=ee9ca7&animation=fadeIn" width="100%"/>
</div>

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=levaine1&show_icons=true&theme=transparent&hide_border=true&count_private=true&include_all_commits=true&title_color=ee9ca7&icon_color=ffafbd&text_color=d8a3ad&bg_color=00000000" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=levaine1&layout=compact&theme=transparent&hide_border=true&langs_count=6&title_color=ee9ca7&text_color=d8a3ad&bg_color=00000000" />
</div>

<div align="center">
<img height="165" src="https://streak-stats.demolab.com?user=levaine1&theme=transparent&hide_border=true&background=00000000&ring=ee9ca7&fire=ffafbd&currStreakLabel=d8a3ad&sideLabels=d8a3ad&dates=d8a3ad&currStreakNum=ffffff&sideNums=ffffff" />
</div>

<!-- ====================== TROPHIES ====================== -->
<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=levaine1&theme=gruvbox&no-frame=true&no-bg=true&margin-w=8&margin-h=8&column=6&title=Stars,Commits,Repositories,Followers" />
</div>

<!-- ====================== ACTIVITY GRAPH ====================== -->
<div align="center">
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=levaine1&theme=react-dark&bg_color=00000000&color=ee9ca7&line=ffafbd&point=ffffff&hide_border=true&area=true&area_color=ffc3a0" />
</div>

<br/>

<!-- ====================== FOOTER ====================== -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffc3a0,100:ffafbd&height=120&section=footer"/>
</div>
