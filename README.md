# ASCII Flower — *Te-aș fi iubit…*

A self-contained ASCII rose bouquet that grows with a Romanian farewell poem and its music.

Open [`flower-bouquet.html`](flower-bouquet.html) in a browser and press **▶ pornește muzica**.

## What it is

- **One HTML file.** No build step, no dependencies, no external assets. The artwork, styling, animation logic, poem and audio are all inside `flower-bouquet.html`.
- **Embedded audio.** The original [`audio.mp3`](audio.mp3) is embedded in the page as a `data:audio/mp4;base64,…` URI, so the experience works offline. The source file is kept in this repository for reference; the embedded bytes are identical to it.
- **Fullscreen on start.** Clicking the start button requests fullscreen from the same user gesture. If a browser refuses fullscreen, everything still plays normally in the page.
- **At the end**, the button changes to **reia poemul** to play it again.

## Timing

| Time | What happens |
| --- | --- |
| `0–10s` | Stanza 1 |
| `11–19s` | Stanza 2 |
| `20–30s` | Stanza 3 |
| `31–40s` | Stanza 4 |
| `42–57s` | Stanza 5 |
| `58–63s` | Stanza 6 |
| `62s` | The golden farewell appears: **Fii fericit, rămâi cu bine!** |

The bouquet blooms from the soil upward in **2.8s**. The song is trimmed to **71.8s** (the last 2 seconds are cut), after which the replay button appears.

## Ambient effects

- a warm golden aura that brightens stanza by stanza and melts softly into the sides
- rising fireflies that start with the music
- softly falling rose petals that begin as the poem deepens
- brighter golden streaks raining from the top down throughout the poem
- drifting gold dust and a gentle vignette

## The poem

> Te-aș fi iubit cât ține viața  
> De-ai fi știut să crezi în mine  
> Să-mi dai măcar scântei, nu focul  
> Ce l-am simțit eu pentru tine.  
>
> S-a întunecat, se zbate lumea  
> Copacii ard sub nori de scrum  
> Cad corbii înnegrind tăcerea  
> Stinghere umbre trec pe drum.  
>
> Tu n-ai știut cum să iubești  
> Sau n-am fost eu aleasa ta.  
> Și-n toate nopțile de patos  
> Știam mereu că vei pleca.  
>
> Ne despărțeam de dimineață  
> Ne regăseam noaptea târziu  
> Te-aș fi iubit cât ține-o viață  
> De mă lăsai a ta să fiu!  
>
> Am vrut prea mult, am vrut iubire  
> Deși simțeam că tu refuzi  
> Când te visam pe tine mire  
> Alaiul nunții să-l auzi.  
>
> Te-aș fi iubit cât ține-o viață  
> Și ți-aș fi dat bucăți din mine  
> Dar ăsta-i ultimul adio

## Files

- `flower-bouquet.html` — the complete, standalone experience
- `audio.mp3` — original source audio embedded in the HTML
