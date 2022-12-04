Building JAR
============

		mvn clean compile assembly:single install

Running JAR
===========

		export JAVA_HOME=/Users/bruce/tools/jdk-17.0.5.jdk/Contents/Home
		export JAVAFX_HOME=/Users/bruce/tools/javafx-sdk-19
		$JAVA_HOME/bin/java --module-path $JAVAFX_HOME/lib --add-modules=javafx.controls,javafx.graphics,javafx.fxml,javafx.swing -jar target/hello-javafx-1.0.0-jar-with-dependencies.jar 

		
