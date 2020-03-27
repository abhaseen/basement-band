# basement-band

**Brief Description: Java musical instruments GUI Swing app.**

## **Detailed Description:**

This is an application made to play instruments on a desktop environment.

In this application, you start at a Main Menu, that look like this, this takes you to the instruments or exits the application:

![Main Menu](https://abhaseen.github.io/basement-band/MainMenu.PNG)

If you select the piano, you'll be sent to this view:

![Piano](https://abhaseen.github.io/basement-band/Piano.PNG)

In the piano view, I limited it to a full octave. In musical terms, you start at the middle C (Do), often called C4 and then you go up a whole octave, called C5.

In the top right hand corner, you can see the option to select two types of intruments, Electronic Piano and Steel Drum.

Choosing the Drum, we'll be taken here:

![Drum Selection](https://abhaseen.github.io/basement-band/PickDrum.PNG)

If we choose the Acoustic drum kit, we'll be taken to a page rendered like so:

![Acoustic Drum Kit](https://abhaseen.github.io/basement-band/AcousticDrum.PNG)

This layout is made to look like an actual live drum kit. The samples used in this view reflect that.

Now from the Drum Kit Selection Menu, if we choose the Electronic Drum Kit, it will take us to this page:

![Electronic Drum](https://abhaseen.github.io/basement-band/ElectronicDrum.PNG)

This view is made to emulate the electronic drum kits/pads that you often see DJ's or electronic producers use.

![Voice Recorder](https://abhaseen.github.io/basement-band/VoiceRecorder.PNG)

This view allows you to record and playback a microphone recording.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See build executable for notes on how to build the application locally.

### Prerequisites

A version of NetBeans. Recommended 11.2 or higher.

Make sure to use latest version of UTF encoding to get the proper emojis for the Main Menu view, Return Home and Change Kit buttons.

### Development Setup

To first run this program, we must first open the project with NetBeans. The reason why NetBeans is recommended is because it has the strongest Swing Application editor for the visual GUI design.

When adding a new view, make sure to say NEW -> JPanel Form
or NEW -> JFrame Form, depending on your preference.

When the project is built, make sure to choose MainMenu as the main class. This will allow you to start from the main menu rather than any other view.

When using the Voice Recording module, make sure to create a file called Recording_Files in the source folder in order to begin recording.

## Build Executable

Perform a clean build and run from /dist folder. Should be a file of .jar format.

## Libraries or frameworks

* [Java Swing](https://docs.oracle.com/javase/7/docs/api/javax/swing/package-summary.html) - GUI library, also used ImageIcon and JButton from this package.
* [Maven](https://maven.apache.org/) - Dependency Management
* [Java Sound](https://docs.oracle.com/javase/7/docs/technotes/guides/sound/programmer_guide/contents.html) - Used the AudioInputStream, AudioSystem and Clip libraries from the sampled package.
* [Java io](https://docs.oracle.com/javase/7/docs/api/java/io/package-summary.html) - Used for accessing sound samples
* [Java AWT](https://docs.oracle.com/javase/7/docs/api/java/awt/package-summary.html) - Used for formatting the Window

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

Version 2.0.0 - Stable Release, added Recording Module

## Authors

* **Andre Bhaseen** - *Initial work* - [abhaseen](https://github.com/abhaseen)

* [Royce Ayroso-Ong](https://github.com/rjayroso-ong) who participated in this project. - *Responsible for developing Recording Module*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgements
* Initial Piano tutorial and sound samples taken from [this video by DJ Oamen on YouTube](https://www.youtube.com/watch?v=DFnUDyzF1Uk)
* All other samples used in this project are from:
    * [LMMS](https://lmms.io/): A Free and Open Source Software for Music Production in the likes of FL Studio. Samples are Royalty-free.
    * [Cymatics](https://cymatics.fm/): Using the Diamonds Sample Pack, a premium Royalty-Free sample pack
* Images used for the Acoustic Drum Kit are from:
    * [Kick](https://static.thenounproject.com/png/118259-200.png)
    * [Tom-Tom(Timbales)](https://images.vexels.com/media/users/3/148731/isolated/preview/ad5366df452043ef1138519d9084ed3b-hanging-toms-musical-instrument-silhouette-by-vexels.png)
    * [Snare](https://i.dlpng.com/static/png/6596533_thumb.png)
    * [Crash](https://static.thenounproject.com/png/248943-200.png)
    * [Ride](https://static.thenounproject.com/png/248942-200.png)
    * [Hihat](https://images.vexels.com/media/users/3/148739/isolated/preview/e8cb7e256dde8d7a85d3a9a9fe4d94c9-hi-hat-cymbal-instrument-silhouette-by-vexels.png)
    * [Tom](https://images.vexels.com/media/users/3/148688/isolated/preview/b81a2c3172d805bce42f34a462e50cac-floor-tom-musical-instrument-silhouette-by-vexels.png)