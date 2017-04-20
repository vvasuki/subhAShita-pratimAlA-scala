# Historical notes
* Initially started out with gradle project <https://github.com/sanskrit-coders/subhAShita-pratimAlA> and tried to import to scala, but failed.
* Switched to this project from scratch, following tutorials here: <https://github.com/scala-android/sbt-android> .
* Realized that one cannot import maven based modules (sanskritnlpjava and subhashita-db-sanskrit) in a sbt based project. [SO Question](http://stackoverflow.com/questions/38713822/intellij-idea-support-both-sbt-and-maven-on-a-single-project).
* Switched back to <https://github.com/sanskrit-coders/subhAShita-pratimAlA> .

Current status: TODO: Stuff does not work after upgrade to using support-v13.

# Initial setup
* Link /home/vvasuki/.android/sbt/sdk to android sdk folder.
* Just use the Build menu in Intellij to generate signed apk.

## Quick sbt commands
    * app/android:run
    * app/android:packageRelease

# Help links
* <https://github.com/scala-android/sbt-android>
* <http://scala-android.org/dependencies/>
* <https://gitter.im/scala-android/sbt-android>
* <http://scala-on-android.taig.io/publishing/>

