# Building A Basic Patch With Eurorack

![A Eurorack Synthesizer With Multicolored Patch Cables](https://i.imgur.com/EhtBfRq.jpg)

The sound design possibilities within the eurorack format of modular synthesizers is effectively only limited by your own creativity. It is, however, import to understand the basics before you dive in. Here we will walk through a basic patch using common modules to create a basic melody.

## 1\. Picking Your Voice

![Plaits by Mutable Instruments](https://i.imgur.com/Q2qqMRO.jpg)

In modular synthesis it is essential to have a voice to work with. Without a voice there wouldn't be any notable sound, perhaps aside from an occasional square wave firing off. Your voice can be anything from a `resonator` to a `sampler` or even a `filter` feeding back into itself. For this tutorial we will be going with a more traditional _voltage controled oscillator_ or `VCO` called __Plaits__ by Mutable Instruments.

## 2\. Finding Your Sound

![Plaits by Mutable Instruments](https://i.imgur.com/REmCpq0.jpg)

As you can see there are a number of adjustable parameters and settings and even secondary functions featured on this particular oscillator. For the sake of keeping things simple we will not be delving into the inner workings of this particular module and working with some basic settings.
+ Picking Your Sound
    + Take two 3.5mm to 1/4" patch cables and connect them to the `OUT`, `AUX` or both and  run them into your mixer connected to your headphones, speakers or audio interface so that we can hear the oscillator.
    + Adjust the `frequency`, `timbre`, `harmonics` and `morph` parameters to your liking. Also be sure to cycle through the different banks using the two black buttons above the LEDs.

## 3\. Creating A Sequence

![Pamela's New Workout and Ornament and Crime modules](https://i.imgur.com/afY7SC4.jpg)

We will be using two modules to create the _sequence_ or melody that the `VCO` will play.
+ The first is a `clock` module called __Pamela's New Workout__.
    + We will select the BPM which is displayed on the screen using the encoder. We'll go with 60BPM today.
    + Next we'll adjust the `division`, or how often the `clock` sends a `gate` based on multiplication or division of the bpm, by using the encoder to move left or right selecting which output we want to use. We'll adjust it to /2.6 for this example.
+ Next we will program our `sequencer`. We will be using a basic `sequencer` applet on the __Ornament and Crime__ open source module or __O_c__.
    + Adjust the 8 different steps of the `sequencer` using the encoder until you have a melody that you like the sound of.
Take a standard 3.5mm patch cable and connect it to `Output 1` on __Pamela's New Workout__ and run it to `TRIG1` on the __O_c__. Next take another patch cable and connect it to `OUT A` on __O_c__ and running it to the _volt per octave_ or `V/OCT` input on __Plaits__. Press the start button on the `clock` module and you will hear your sequence.

![A Basic Patch On A Modular Synthesizer](https://i.imgur.com/zY0RtJO.jpg)

## 4\. Attenuating Your Sequence

![A Silver Voltage Controled Attenuator With Potentiometers and Sliders](https://i.imgur.com/H0qyuJG.jpg)

So we have our sequence but those sounds are way too high pitched for what we were looking for! Not to worry, we can use a _voltage controled attenuator_ or `VCA` to adjust the voltage the `sequencer` is sending to our `VCO` to lower the pitch by essentially "turning down" the voltage being sent to it. First we will remove the patch cable from the `V/OCT` on __Plaits__ and run it to the first `IN` on our `VCA`. Next we will take another patch cable and connect it to the corresponding output jack and run it to the `V/OCT` on __Plaits__. Finally, using the adjustable parameters of the `VCA` we can find a pitch that works for us.

## 5\. You Did It!

![A Eurorack Synthesizer With A 5 Cable Patch](https://i.imgur.com/UyIjx2D.jpg)

You have successfully made a basic melody using your eurorack synthesizer. The fun has just begun, however! From here we can `filter` our voice, add additional voices and `sequences`, adjust volume increases and decreases using the other available inputs of our `VCA` or the onboard `TRIG` and `LEVEL` inputs on our `VCO`, add effects such as `granular processing` and `reverb` and so much more while using various modulation sources to totally reimagine our patch! Please enjoy [this video](https://i.imgur.com/rwap2C2.mp4) demonstrating how we can take our basic melody and turn it into a soundscape full of variation and movement.

