# NHL highlight enhancement: ready to submit

Recommended: **Seedance 2.5 Edit** · video input `source_vertical_9x16.mp4` · 720p · audio ON · mp4.
Fallback if Edit drifts from the play: **Seedance 2.5** · reference video `source_trimmed_16x9.mp4` · aspect 9:16 · duration 13s · 720p · audio ON.

Timeline of the source (13 s, clock 08:57 to 09:09): the dark-blue attacker carries the puck up the left wing (0 to 4 s), drives to the net with red defenders trailing (4 to 6 s), shoots and scores and the red goalie goes down (about 6 to 7 s), then celebration starts (8 s onward).

## Prompt (paste this)

Enhance this exact ice hockey play into an ultra-photorealistic NHL playoff broadcast highlight. Keep every event, the order of events, the attacking direction, the arena, the rink layout, the camera path and the team colors exactly as in the source: dark-blue team attacking, red team defending. The dark-blue attacker carrying the puck up the left wing is the only goal scorer. Make him an explosive, elite NHL skater: a powerful first step, deep knee bend, sharp crossovers, hard edge work and heavy ice spray, with fast, precise stickhandling that keeps the puck glued to his blade. He pulls away from the red defenders, who react realistically but cannot match his speed. At the net he fires one explosive shot with real stick flex. The puck follows one clean, physically correct path into the same corner of the same goal and the red goalie reacts. Crowd erupts, goal horn sounds, and the scorer begins a natural celebration in the same position and direction as the source. Premium broadcast look: crisp detail, natural motion blur, dramatic arena lighting, detailed ice texture, subtle handheld energy, a restrained speed ramp only around the shot. Audio: skates carving ice, stick-on-puck contact, shot impact, building crowd, cheering on the goal, arena horn. No commentary, no music.

## Negative prompt (if the model has a field for it)

altered play, different scorer, extra passes, extra shots, extra goals, duplicated players, vanishing players, floating or duplicated puck, puck teleporting, bent or warped sticks, extra limbs, impossible skating, video-game look, fast-forward look, excessive slow motion, camera teleport, scene cuts, stretched image, text artifacts

## Notes
- The score bug in the source reads 7-2 and does not update after the goal. If the model "fixes" it, that is acceptable; if it garbles it, add "keep the scoreboard overlay unchanged" to the prompt.
- The 9:16 input was made by cropping a 218 px wide window from a 692 px wide source and upscaling it to 1080x1920, so it is soft. Detail will come from the model, not the crop.
- For the follow-up celebration clip, use **Seedance 2.5 Extend** on the result.
