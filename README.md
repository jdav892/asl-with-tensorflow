# ASL with TensorFlow
Performs assumptions on hand gestures to approximate compatibility with hand signs to translate American Sign Language words to English.

## How It's Made:

**Tech used:** TensorFlow, React.js 

This converts a TensorFlow model from python to JavaScript to interact with a React frontend. It integrates the canvas to to draw over the video that is streamed from webcam through browser APIs that support media devices. Utilize rectangles to target and section off hands to label, also displays approximation of hand sign to give accuracy rating. 

## Optimizations:

This became a glue engineering job really quickly, and in hindsight I would go through the trouble self training the model for a more personalized output to stream to Browser. Also would use tailwind to make the UI less a glued together mess to make the display work.

## Lessons Learned:

Learning that the browser supports so many interactions with media devices, and that JavaScript is an available language to port a TensorFlow model to felt rather jarring however the solution did not disappoint. Considering the model will in fact interact with the video input was the end goal, I take this as a success regardless of my preconceived notions. Finding different ways to integrate software around different models, whether it be computer vision such as this, or a LLM, those skills seem to be the route software will be taking for the next decade or more as those with more esteemed backgrounds will be taking part in actually creating said models.
