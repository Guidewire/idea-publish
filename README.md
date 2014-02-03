Run "gradle publish" to upload everything to Nexus.

Version of IDEA is configured in the gradle.properties

To upload particular component only, run <component>:publish, where <component> is one of:

 * ideace -- IDEA CE binary distributable
 * native -- IDEA CE native code for three platforms (Mac OS X, Linux, Windows)
 * platform -- IDEA core libraries (found in <IDEA HOME>/lib)
 * <plugin> -- IDEA plugin libraries (found in <IDEA HOME>/plugins/<plugin>/lib). You can only choose plugin that is
   listed in the gradle.properties file.

IDEA version, repository to upload to, list of plugins to upload and other settings are configured in the
gradle.properties file.

