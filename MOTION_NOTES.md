# Motion notes

The plugin source cites Telegram-iOS commit `fb0e62ba8a14` as motion inspiration. The timings and spring behavior are adapted for Android; they are not measurements from an iPhone screen recording.

The implementation declares 420 ms for opening, 200 ms for the backdrop, 50 ms for action fade-in, 200 ms for closing, and 400 ms for the reaction animation. Spring curves are sampled into an Android `PathInterpolator`; if that is unavailable, the plugin uses Android's built-in interpolators as a fallback.
