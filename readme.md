# Welcome to the Void 🕳️

I'm Om, the digital necromancer. If I were a software, I'd be a Lovecraftian nightmare of spaghetti code and recursive madness. Yet, somehow, I summon functional abominations from the abyss (occasionally).

## About Me (or whatever's left of it)
[![committers.top badge](https://user-badge.committers.top/india/omsandippatil.svg)](https://user-badge.committers.top/india/omsandippatil)
![profile.visit](https://komarev.com/ghpvc/?username=omsandippatil&style=flat-square)

- 🌍 Trapped on this cosmic joke called Earth (it's flat, fight me)
- 💻 Channeling eldritch horrors into code
- 🎮 Professional time-waster, amateur everything else
- 🍕 Pizza cultist (because circular food is clearly superior)

## "Skills" (read: Coping Mechanisms)
- 💬 Whispering sweet nothings to silicon
- 🚀 Launching bugs into production at light speed
- 🕹️ Mastering virtual worlds (because the real one is overrated)
- 🎭 Method acting as a competent developer

## Current Project
🤖 Summoning an AI overlord to take over my job, freeing me to pursue my true calling: professional couch potato.

## Fun Facts (that will haunt your dreams)
- I'm fluent in four languages: English, Hindi, Marathi, and Existential Dread.
- My code is like a black hole - dense, incomprehensible, and prone to crushing all hope.
- I once beat a computer at chess. It was unplugged, but victory is victory.

## Connect with Me (at your own risk)
Want to discuss the futility of clean code or debate the superiority of pineapple on pizza? Reach out, if you dare:

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/omsandeeppatil)
[![Recursion](https://img.shields.io/badge/-Website-brightgreen?style=flat&logo=firefox)](https://github.com/omsandippatil)

## Programmer's Lament
> "Why do programmers prefer dark mode? Because their future is as dark as their IDE." 💀

Thanks for stumbling into my digital dungeon! Now go forth and code, and remember: In the face of merge conflicts, laugh maniacally! 🦇

## Spotify's Soundtrack to My Descent
![Spotify](https://spotify-recently-played-readme.vercel.app/api?user=31uw53f5454epgmtenldpssnng4a&width=1000)

## Github Streak (or Streak of Madness?)
![GitHub Streak](https://streak-stats.demolab.com?user=omsandippatil&theme=merko&hide_border=true&card_width=950)






# Mount your main root filesystem
sudo mount /dev/nvme0n1p3 /mnt

# Mount the EFI partition
sudo mount /dev/nvme0n1p1 /mnt/boot/efi

# Bind necessary system directories
sudo mount --rbind /dev /mnt/dev 

sudo mount --rbind /dev/pts /mnt/dev/pts

sudo mount --rbind /proc /mnt/proc

sudo mount --rbind /sys /mnt/sys

sudo mount --rbind /run /mnt/run

# Now chroot into your actual system
sudo chroot /mnt
