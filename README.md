
## Inspiration
Seeing the monumental Runestone, the birth certificate of Denmark and the centrepiece of the museum, and its 3d restored counterpart. We wanted to bring the beauty of the render to the original experience at  the same time, whilst also giving more information about the inspiring history of the rock.

## What it does
We are using AR markers to project a recreated 3D model of how the stone would have originally looked. We took inspiration from the 3D render shown in the museum, with the idea of overlapping the painted model over the real rock.

![walk_round_stone](https://github.com/user-attachments/assets/0a7ac044-d57b-4631-aa5b-8eb21231d63c)

To obtain more information, the user can click the "Stories" button and discover interesting stories about the rock and the history of the people surrounding it. 

![stories_button](https://github.com/user-attachments/assets/b4c10ea1-abf4-4cc5-afe0-5a9009ba8236)

## How we built it
We built it using Astro, Aframe, and AR.JS for the tech stack for the site and deployed on cloudflare.

## Challenges we ran into
Initially, we struggled to load the rock model into the scene due to conflicts with 3DsMax. Later, we had issues with tracking in 3D space and using custom AR tags. Some final issues faced were z-fighting in the text boxes when trying to render text on a background in 3D space.

## Accomplishments that we're proud of
We brainstormed and fleshed out numerous different ideas and decided the idea based on an understanding of the likely scope and team strengths. We are proud to have recreated a 3D model of the runestone and show it in 3D space with good accuracy. We are also proud of how much we have learned about the history of Harald Bluetooth and the founding history of Denmark. Mostly, we are proud of how we have worked as a team and the friendships we've made along the way.

## What we learned
We learned how to use AR.JS, and A-frame. As well as brainstorming and rapid prototyping.

## What's next for AR Jelling Runestone
Using it for further use cases, such as showing images and models at Yggdrasil's runes, with additional information regarding our models of mythical creatures and places. 
Also, being able to visualise historic rooms, houses, and farms as they would have looked during the time of Harald Bluetooth. 

Furthermore, we would love to be able to have Bluetooth connectivity at the rune, such that instead of having to scan a QR code to get to the site, the user is prompted using BLE.
