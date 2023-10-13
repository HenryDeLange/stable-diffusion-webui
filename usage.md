# Usage Examples

## Checkpoints
| Name                   | Notes                        | Positive Prompt                                   | Negative Prompt                          |
|------------------------|------------------------------|---------------------------------------------------|------------------------------------------|
| ExpMix Line            | Use VAE `kl-f8-anime2`.      | ((masterpiece:1.2, best quality)) | (worst quality, low quality:1.4), multiple views, blurry, multiple panels, watermark, letterbox, text |
| Dark Sushi             | _Needs__ VAE `ft-mse-840000`.| ((masterpiece:1.2, best quality)) | (worst quality, low quality:1.4), multiple views, blurry, multiple panels, watermark, letterbox, text |
| MeinaMix               | Try using `dark fantasy`.    | (masterpiece, best quality, ultra-detailed, best shadow), (detailed background), (beautiful detailed face), high contrast, (best illumination, an extremely delicate and beautiful) | (worst quality, low quality:1.4), monochrome, zombie, huge breasts, large breasts |
| Oriental Mix           |                              | (masterpiece), best quality, detailed background | EasyNegative, verybadimagenegative_v1.2-6400, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name |
| Nostalgia Mix          |                              | (masterpiece), best quality, detailed background | EasyNegative, verybadimagenegative_v1.2-6400, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name |
| Comi Nior Classic      |                              | (masterpiece), (best quality), (high resolution), detailed background, landscape | nsfw, (worst quality:1.4), (low quality:1.4), (fuze:1.4), bad anatomy, text, bad hands, error, missing fingers, extra digit, incorrect fingers, extra fingers |
| Three Delicacy Wonton  | Keywords (optional): `shuimobysim` or `shukezouma`. | | |
| A to Zovya RPG Tools   |                              | | (worst quality, low quality:1.4), (lowres), (deformed), (dark), (lowpoly), (CG), (3d), (blurry), (out-of-focus), (monochrome:1.3), (oversaturated:1.3), (text), (poorly drawn), (mutilated) |
| A to Zovya RPG Tools   | Flat vector art.             | (masterpiece:1.4), (best quality:1.4), fantasy, flat vector art, flat color, Dancer fine art filigree, paper marbling! Oil splash!! Oil stained!!", intricate hyperdetailed fluid gouache illustration by Android Jones: By Ismail Inceoglu and Jean Baptiste mongue: James Jean: Erin Hanson: Dan Mumford: professional photography | (worst quality, low quality:1.4), (lowres), (deformed), (lowpoly), (CG), (3d), (blurry), (out-of-focus), (monochrome:1.3), (oversaturated:1.3), (text), (poorly drawn), (mutilated) |
| ReV Animated           | Used like AOM. _Needs_ VAE.  | (masterpiece), best quality | nsfw, (worst quality, low quality:1.4) |
| GalaxyTimeMachine      |                              | art by artgerm and greg rutkowski and alphonse mucha | |
| Eerie Orange Mix       | Same as Abyss Orange Mix.    | | |
| Abyss Orange Mix 3     | VAE `orangemix` or `kl-f8-anime2`. | ((masterpiece)), best quality, perfect anatomy, ((hyper detailed)), ((illustrationbest)), ((beautiful detailed face)), detailed background, intricate detail, high detailed eyes, volumetric lighting, good lighting | ((nsfw)), (worst quality, low quality:1.4), (blurry), (greyscale, monochrome), depth of field, ugly, lowres, text, jpeg artifacts, signature, watermark, username, artist name, trademark, title, (tan, muscular, loli, petite, child, infant, toddlers, chibi, sd character:1.4), multiple view, reference sheet, poorly drawn face, poorly drawn asymmetrical eyes, disfigured, mutated, extra limbs, bad anatomy, missing limb, floating limbs, disconnected limbs, poorly drawn hands, malformed hands, bad hands, lineart, 2koma, 3koma, 4koma, manga, 3D, 3Dcubism, 3D face, pablo picasso, disney, marvel |
| Blood Orange Mix       | Same as Abyss Orange Mix.    | | |
| Anything v4            |                              | ((masterpiece)), best quality | (worst quality, low quality:1.4), huge breasts, loli |
| Dalcefo Painting       | Wants HiresFix (DN 0.6).     | <(masterpiece, realistic:1.3), (extremely intricate:1.2)> | (worst quality, low quality:1.4), (depth of field, blurry:1.2), (greyscale, monochrome:1.1), 3D face, cropped, lowres, text, jpeg artifacts, signature, watermark, username, blurry, artist name, trademark, watermark, title, multiple view, Reference sheet, curvy, plump, fat, muscular female, strabismus |
| iCoMix                 |                              | (masterpiece), best quality, inked, thick outlined | (worst quality:1.4), (low quality:1.4), (monochrome:1.1), malformed hands, bad hands, mutated fingers, extra limbs, text, name, signature, logo, blurry, bad anatomy, disfigured, jpeg artifacts, child, depth of field |
| Comic Diffusion        | Recommended to use style keywords: `charliebo artstyle`, `holliemengert artstyle`, `marioalberti artstyle`, `pepelarraz artstyle`, `andreasrocha artstyle`, `jamesdaly artstyle` | | |
| Epic Diffusion         | Good for animals?            | | |
| Dreamlike Photoreal    | Good for animals?            | | |
| Dark Flat Art AI       | Needs `darkflatartai`.       | darkflatartai | nsfw |
| Night Sky YOZORA       | Large canvas. VAE `YOZORA`.  | (masterpiece), best quality, detailed background | (worst quality), (low quality), (blurry), sketch, duplicate, ugly, text, logo, monochrome, worst face, bad hands, multiple limbs, bad anatomy |
| Classic Anime Fantasy  | High Scale (12-15). Use `80s anime style` or `gta style`. | (80s anime style) | illustration, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, ((monochrome)), ((grayscale)), collapsed eyeshadow, multiple eyeblows, vaginas in breasts, (cropped), oversaturated, extra limb, missing limbs, deformed hands, long neck, long body, imperfect, (bad hands), signature, watermark, username, artist name, conjoined fingers, deformed fingers, ugly eyes, imperfect eyes, skewed eyes, unnatural face, unnatural body, error |
| Dreamshaper            | | (masterpiece), best quality, (highly detailed, majestic), detailed background | canvas frame, cartoon, 3d, ((disfigured)), ((bad art)), ((deformed)),((extra limbs)),((close up)), ((b&w)), wierd colors, blurry, (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), Photoshop, video game, ugly, tiling, poorly drawn hands, poorly drawn feet, poorly drawn face, out of frame, mutation, mutated, extra limbs, extra legs, extra arms, disfigured, deformed, cross-eye, body out of frame, blurry, bad art, bad anatomy, 3d render |
| Stable Diffusion v1.5 | Baseline. | | |
| | | | |

# LoRa
| Name                          | Notes                            |
|-------------------------------|----------------------------------|
| Blueprint                     | Keyword: `blueprint`. (A bit iffy.) |
| FishClassChinese              |                                  |
| Moxin                         | Keywords: `shuimobysim` or `wuchangshuo` or `bonian` or `zhenbanqiao` or `badashanren`. |
| Assist for Shukezouma         | |
| Moxin + Assist for Shukezouma | Designed to be used together.    |
| Danmumford Style              | Keyword (optional): `danmumford style`. |
| 1MbLORATrainedIn5Mins         | Keyword (optional): `doortoinfinity`. |
| Colorwater (v4)               | |
| Concept Alraune (Plant Girl)  | Keyword: `alraune`. (Better with Anime models.) |
| xiaorenshu (v1/v2)            | |
| Anime Line Art                | Keywords (optional): `monochrome` and `lineart`.|
| Louisap Pixel Art             | |
| Flat Color                    | Keyword (optional): `flat_color` + `ligne_claire`. |
| Anime Screencap Style         | Keyword (optional): `anime screencap`. |
| Anime Tarot Card Style        | Keyword (optional): `tarot`.     |
| DMMID Style                   | Keyword (optional): `dmmid style`. |
| Butterfly AI                  | Keyword: `butterflyai`. (A bit iffy. Supposed to make a stylized butterfly, but adds butterfly theme without keyword.) |
| Freaks of The Heartland       | |
| Gacha Splash                  | Keywords (optional): `[(white background:1.5),::5] hexagon, 1girl/1boy, mid shot, full body` |
| GBA FE Girl                   | Keyword (option): `gbafegirl`.   |
| Glass Sculptures              | Keywords: `glasssculpture ` or `translucent` or `transparent` or `reflection`. (Interesting effect without keywords.)|
| Hand-Painted Portrait         | Keywords (optional): `realistic，pencil drawing，(portrait:1.2)，(sketch:1.2)，painting，rough sketch, (line art:1.2), meticulous painting,white paper，character on paper，black and white，extra lines, clear lines, shadow`. (The keywords on their own almost do a better job...) |
| Jim Lee DC Comics Marvel      | Keyword (optional): `jim lee`. |
| KR Style Game Character       | Keyword (optional): `krface`. |
| Mange General Style           | Keywords: `manga` and `greyscale` and `monochrome`. |
| Monograph                     | |
| Motomurabito Style            | |
| Nature Cthulhu Girl           | |
| Ori Art Style                 | Keywords: `ori` and `spirit tree` and `ori and the blind forest` and `ori and the will of the wisps`. |
| Satsuki KEI Style             | (Made for AbyssOrangeMix, but interesting effect on other models.) |
| Standing Full Body with Background Style | Keywords: `white background` and `full body`. |
| Stylized 3D Model             | Keyword: `scg`. (Better with anime models.) |
| Sydus Art                     | |
| Take On Me Sketchy Style      | Keyword (optional): `tom`. |
| Thick Coat CG Style           | |
| Valerian & Laureline Style    | |
| Vivid Watercolors             | Keyword (optional): `wtrcolor style`. |
| | |


# Textual Inversions
| Name                          | Notes                            |
|-------------------------------|----------------------------------|
| Adventure Diffusion           | Keyword: `advntr`.               |
| Pirate                        | Keyword: `prt`.                  |
| Journal Drawing               | Keyword: `sd15_journalSketch`.   |
| Style Nebula Magic            | (A bit iffy.) Keyword: `Style-NebMagic`. And negative: `Style-NebMagic-neg`. (But emphasized a lot `(((Style-NebMagic)))`.) |
| Style Rustic Magic            | Keyword: `style-rustmagic`. (But emphasized a lot `(((style-rustmagic)))`.) |
| Style Sylva Magic             | Keyword: `style-sylvamagic`. (But emphasized a lot `(((style-sylvamagic)))`.) |
| | |