# The Maven Web Appplication   
creating Web Application using corretto11, Maven in intellij.
 
## Amazon Corretto 11 Installation for macOS
This topic describes how to install and uninstall Amazon Corretto 11 on a host running the Mac OS version 10.13 or later. You must have administrator permissions to install and uninstall Amazon Corretto 11.

[What Is Aamazon Corretto?](https://aws.amazon.com/ko/corretto)

### Install Amazon Corretto 11
1. Download the Mac .pkg file from the [Downloads](https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html) page.

2. Double-click the downloaded file to begin the installation wizard and follow the steps in the wizard.

3. Once the wizard completes, Amazon Corretto 11 is installed in /Library/Java/JavaVirtualMachines/.

You can run the following command in a terminal to get the complete installation path.

<pre>
<code>
/usr/libexec/java_home --verbose
</code>
</pre>

4. Run the following command in the terminal to set the JAVA_HOME variable to the Amazon Corretto 11 version of the JDK. If this was set to another version previously, it is overridden.

<pre>
<code>
export JAVA_HOME=/Library/Java/JavaVirtualMachines/amazon-corretto-11.jdk/Contents/Home
</code>
</pre>


 
## Creating a new project in IntelliJ

## 
