# Cita417Lab5

For this project, I worked in Unreal Engine 5 and used the First Person Template.
My goal was to change how the bullets work so I could compare performance before and after.
At first, the bullets disappear after 3 seconds. After my change, the bullets never disappear.
This kind of shows the idea of object pooling, because one version keeps spawning and destroying bullets, and the other keeps the bullets alive.
It was actually pretty simple but I learned a lot about how actors work.
You can see the difference in the YouTube video I made.
I also uploaded the whole project to GitHub so everything is there.

# How To Reproduce
1- Open the project in Unreal Engine 5.
2 - Open the FirstPersonMap (the main level).
3 - Press Play.
4 - Press Left Mouse Button to shoot bullets.
5 - In the “before” version, bullets disappear after 3 seconds.
6 - In the “after” version, bullets stay in the world forever.

# What I changed 
I found the BP_FirstPersonProjectile blueprint.I changed the Initial Life Span from 3 to 0 so it stays forever.This makes it easier to see how many actors stay in the world at once. I recorded a before-and-after comparison for my video.
