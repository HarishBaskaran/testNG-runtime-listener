# testNG-runtime-listener
This snippet helps to track the status of the testng run in excel and in csv files

# Dependency for POM
```
<!-- Excel data retrieve -->
<dependency>
       <groupId>org.apache.poi</groupId>
       <artifactId>poi</artifactId>
       <version>3.15</version>
</dependency>
<dependency>
       <groupId>org.apache.poi</groupId>
       <artifactId>poi-ooxml</artifactId>
       <version>3.15</version>
</dependency>
```

# How to run this 
Add this as a listener in your testNG.xml.
```
<listeners>
  <listener class-name="runtimeListener"/>
</listeners>
```
