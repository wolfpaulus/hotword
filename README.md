# WakeWord4Android
# hotword
This projects emonstrate, how a wake-up word (a.k.a. hot word) can be used inside an android app, to wake it up. Imagine a scenario, where the android app is already launched and running in the foreground, just waiting for a user to say the wake-up word or phrase, to start the full experience, i.e., start the next activity.

Waiting is somewhat indeterministic, we don’t really know how long we have to wait, until the wake-up word gets spoken, which means using an on-line speech recognition service doesn’t sound like a good idea. Fortunately, there is PocketSphinx, a lightweight speech recognition engine, specifically tuned for handheld and mobile devices that works locally on the phone. Let’s get started, by creating a simple project with Android Studio.

More details are available here: https://wolfpaulus.com/mac/custom-wakeup-words-for-an-android-app/