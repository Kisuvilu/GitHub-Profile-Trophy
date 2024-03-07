

GitHub Profile Trophy
🏆 Add dynamically generated GitHub Stat Trophies on your readme

   



You can use this service for free. I'm looking for sponsors to help us keep up with this service❤️



Quick Start
Add the following code to your readme. When pasting the code into your profile's readme, change the ?username= value to your GitHub's username.

[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma)](https://github.com/ryo-ma/github-profile-trophy)


Use theme
Add optional parameter of the theme.

[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)


More detail

About Rank
Ranks are SSS SS S AAA AA A B C UNKNOWN SECRET.

Rank	Description
SSS, SS, S	You are at a hard to reach rank. You can brag.
AAA, AA, A	You will reach this rank if you do your best. Let's aim here first.
B, C	You are currently making good progress. Let's aim a bit higher.
UNKNOWN	You have not taken action yet. Let's act first.
SECRET	This rank is very rare. The trophy will not be displayed until certain conditions are met.
Secret Rank
The acquisition condition is secret, but you can know the condition by reading this code.



There are only a few secret trophies. Therefore, if you come up with interesting conditions, I will consider adding a trophy. I am waiting for contributions.

About Display details


Title name of aggregation target.
Current Rank.
Title according to rank.
Target aggregation result.
Next Rank Bar. The road from the current rank to the next rank.
Optional Request Parameters
title
rank
column
row
theme
margin-w
margin-h
no-bg
no-frame
Filter by titles
You can filter the display by specifying the titles of trophy.

https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Followers


If you want to specify multiple titles.

https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Stars,Followers
Filter by ranks
You can filter the display by specifying the ranks.
Available values: SECRET SSS SS S AAA AA A B C

https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S


If you want to specify multiple ranks.

https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S,AAA
You can also exclude ranks.

https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=-C,-B
Specify the maximum row & column size
You can specify the maximum row and column size.
Trophy will be hidden if it exceeds the range of both row and column.

Available value: number type
Default: column=6 row=3

Restrict only row

https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2
Restrict only column

https://github-profile-trophy.vercel.app/?username=ryo-ma&column=2
Restrict row & column

https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2&column=3


Adaptive column

https://github-profile-trophy.vercel.app/?username=ryo-ma&column=-1
You can set columns to -1 to adapt the width to the number of trophies, the parameter row will be ignored.

Apply theme
Available themes.

theme
flat
onedark
gruvbox
dracula
monokai
chalk
nord
alduin
darkhub
juicyfresh
buddhism
oldie
radical
onestar
discord
algolia
gitdimmed
tokyonight
matrix
apprentice
dark_dimmed
dark_lover
kimbie_dark
flat
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=flat


onedark
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onedark


gruvbox
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=gruvbox


dracula
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dracula


monokai
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=monokai


chalk
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=chalk


nord
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=nord


alduin
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=alduin


darkhub
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=darkhub


juicyfresh
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=juicyfresh


buddhism
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=buddhism


oldie
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=oldie


radical
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=radical


onestar
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onestar


discord
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=discord


algolia
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=algolia


gitdimmed
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=gitdimmed


tokyonight
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=tokyonight


matrix
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=matrix


apprentice
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=apprentice


dark_dimmed
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dark_dimmed


dark_lover
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dark_lover


kimbie_dark
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=kimbie_dark


Margin Width
You can put a margin in the width between trophies.
Available value: number type
Default: margin-w=0

https://github-profile-trophy.vercel.app/?username=ryo-ma&margin-w=15


Margin Height
You can put a margin in the height between trophies.
Available value: number type
Default: margin-h=0

https://github-profile-trophy.vercel.app/?username=ryo-ma&margin-h=15
Example layout
https://github-profile-trophy.vercel.app/?username=ryo-ma&column=3&margin-w=15&margin-h=15


Transparent background
You can turn the background transparent.
Available value: boolean type (true or false)
Default: no-bg=false

https://github-profile-trophy.vercel.app/?username=ryo-ma&no-bg=true


Hide frames
You can hide the frames around the trophies.
Available value: boolean type (true or false)
Default: no-frame=false

https://github-profile-trophy.vercel.app/?username=ryo-ma&no-frame=true


Contribution Guide
Check CONTRIBUTING.md for more details.

License
This product is licensed under the MIT License.
