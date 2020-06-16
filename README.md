# FreePianoTutor
A free opensource program that can be used to learn Piano/Keyboard.

By while, just a project. But in future, a free alternative to Piano Marvel, Pianu, Playground Sessions, etc.
Will work in Windows, Linux, Android, MacOS, iOS.

With a MIDI Keyboard, a Notebook/Computer/Tablet, anyone will be able to learn to play any music created by the community.

Development Plan:
 * Choose the best platform. Currently evaluating GODOT and Gluon Substrate (JavaFX)
   * GODOT Advantages
     * After setting up the environment, cross compilation to all platforms seems natural
     * The knowledge gained in process can be useful in other projects. Create games seems to be funny.
   * GODOT Disadvantages
     * Need to learn another language/framework
     * Need to port near everything to another language/framework
       * Integration with FluidSynth seems problematic
       * Not all 2d effects that JavaFX has
   * JavaFX Advantages
     * Zong already works in JavaFX. It's just the case to adapt it to my needs
     * I am a Java developer. So, Java is natural to me
   * JavaFX Disadvantages
     * Is Java/JavaFX dead?
     * Has JavaFX any future?
     * JavaFX Ports will be available to a version of Java beyond 8?
     * Cross compiling not possible today
 * Add FluidSynth to project for all the platforms
 * Create modules for all platforms for MIDI input
 * Create a synthesia clone, but with MusicXML as input and a 'mid' file as accompaniment
 * Create program where can be easy to merge MusicXML and 'mid' files.
   * Maybe, create a file format that merges MusicXML and mid.
   * Maybe, port or incorporate MMA in the project.
