# basement-band

**Brief Description: Java musical instruments GUI Swing app.**

**Detailed Description:**

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

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See build executable for notes on how to build the application locally.

### Prerequisites

A version of NetBeans. Recommended 11.2 or greater.

Make sure to use latest version of UTF encoding to get the proper emojis for the Main Menu view, Return Home and Change Kit buttons.

### Development Setup

To first run this program, we must first open the project with NetBeans. The reason why NetBeans is recommended is because it has the strongest Swing Application editor for the visual GUI design.

When adding a new view, make sure to say NEW -> JPanel Form
or NEW -> JFrame Form, depending on your preference.

When the project is built, make sure to choose MainMenu as the main class. This will allow you to start from the main menu rather than any other view.

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

Version 1.1 - Stable Release, added JavaDocs

## Authors

* **Andre Bhaseen** - *Initial work* - [abhaseen](https://github.com/abhaseen)

* [Royce Ayroso-Ong](https://github.com/rjayroso-ong) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgements
* Initial Piano tutorial and sound samples taken from [this video by DJ Oamen on YouTube](https://www.youtube.com/watch?v=DFnUDyzF1Uk)
* All other samples used in this project are from:
    * [LMMS](https://lmms.io/): A Free and Open Source Software for Music Production in the likes of FL Studio. Samples are Royalty-free.
    * [Cymatics](https://cymatics.fm/): Using the Diamonds Sample Pack, a premium Royalty-Free sample pack
* Images used for the Acoustic Drum Kit are from:
    * [Kick](data:image/png;base64,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)
    * [Tom-Tom(Timbales)](https://images.vexels.com/media/users/3/148731/isolated/preview/ad5366df452043ef1138519d9084ed3b-hanging-toms-musical-instrument-silhouette-by-vexels.png)
    * [Snare](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAD0AAAA9CAMAAAApvJHbAAAAY1BMVEX///8AAAClpaXS0tL29vbJycmHh4ednZ2qqqrh4eGXl5fExMSSkpL7+/u+vr7Ozs5PT0+2trZtbW03Nzfq6up3d3eAgIBWVlZAQEBgYGAiIiIODg5KSkpmZmYvLy+wsLAXFxdVAHh0AAACmklEQVRIie1W27KjIBB0RFAQEa94i+b/v3IHTYwnRjQPW7WnavvBGIdWaHpm8Lx/DwGJo1BKJmUYxSS4TkxiOcA7BhknF7jkZgffh1pEKqaExioS9XC3D2/p2YQNjqpVuQuUqsaIcS+hg4YeBmkDnYusoHC+vADliPoAmhxGiQbwnWxcd8fofnkBZR2u28lm4FGrG/Qt87M4JYSkceaztrcPDfWAHZMD6O01q8fdfo+1shPqwaF6AXipDDqGp5kvWV3VTPpZytEpqd0Mp6oRQOxVw2Y2r1tjvBggcrB9yKEr9Pq/BL7et12HUbfmHmeokGYT4cGDHXAyMdwsYNw7Y+O6myl/l23MJ91i7JydN/OkOVWZAJkpymfbt+YSm77cuF13WV5ib5Dc3rb3K/YOf5EtTtniOLb4nH/O0cnazOnz7rVjCzYvaq0FncXFh4Zvff7Dqa3HmxPVBtDDZ5/fCo3RE81Ji9WlitIyWdlJmUYVVpaWuDUvoQi9qpPNbO5+HGEc57ICjSyMnfm+Vr+Q4DhJ7PewE01C1FAJ8ehEZMKaCZODHczf0eHauMJngIR6jrnYXqz1IyebGxNhlEWhYHnzeNYaR1FcQHDsME21KbqZ0hWmjibsi81xpd9CIY3NHRPJ9idh+BJXF/mJyaq3suXZencQYLuOZWOddeXGZwTYccc77jl25C+ODivKfFYtdxnEBY5kfj7sCA/N/7N/E5vJSCnznc0tArlpwV+alVe2slmnZqFxnxF3IGbOrN7ysYySK+fjJxSWl84uFQ/L6PXTcrSi5IktnXo561rNkV5dJNMlKZ+Jxex3gzu019hWKrZJ6FnqpIDhiPAD6VLP3qGxx1xJ9PLzoNv3W74BQfa1cn7w8avC/w78AU5rHPHYxRKgAAAAAElFTkSuQmCC)
    * [Crash](https://static.thenounproject.com/png/248943-200.png)
    * [Ride](https://static.thenounproject.com/png/248942-200.png)
    * [Hihat](https://images.vexels.com/media/users/3/148739/isolated/preview/e8cb7e256dde8d7a85d3a9a9fe4d94c9-hi-hat-cymbal-instrument-silhouette-by-vexels.png)
    * [Tom](https://images.vexels.com/media/users/3/148688/isolated/preview/b81a2c3172d805bce42f34a462e50cac-floor-tom-musical-instrument-silhouette-by-vexels.png)