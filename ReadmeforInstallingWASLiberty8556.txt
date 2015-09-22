Steps for installing Websphere Liberty Profile 8.5.5.6

1. Go to https://github.com/ibmecod/Migration
2. Download wlp-runtime-8.5.5.6.jar 
3. Open command prompt and go to the directory of the jar file.
4. Run the following command:
      java -jar wlp-runtime-8.5.5.6.jar
5. Enter the target directory that you wish to save the files to e.g: C:\wlp8556
6. Go to Servers tab in Eclipse. Right Click in the pane, Select  Server --> New server--> IBM--> Websphere Application Server 
   Add the path to the folder of C:\wlp8556\wlp\ and click Finish.

