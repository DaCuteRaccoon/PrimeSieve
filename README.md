# PrimeSieve
A short and simple program written in Java that finds out how many prime numbers are equal to or below a number.

[GitHub]
<br />
[Replit]

# Usage
This is for if you're not running it in Replit.

First, we should recompile the code. It's always better to do that, just in case something has changed.
<br />
Unless you are skipping this step, if you can, delete Main.class before compiling the code:
```sh
javac -classpath .:target/dependency/ -d . $(find . -type f -name '*.java')
```
Yay! Now you should see a file called Main.class (if you deleted it before compiling)!
<br />
Now, we just need to run the code. Run this last command:
```sh
java -classpath .:target/dependency/* Main
```
# Editing
You can also edit the code a bit, so it doesn't just display the amount of primes less than or equal to 100.
<br />
Don't worry though. You need zero knowledge of programming.

Just go into the `Main.java` file. On line 3, it says `int N = 100;`. Change 100 to the number you want to find the amount of primes less than or equal to.
<br />
Here is an example of finding the amount of primes equal to or below 750:
```java
public class Main {
  public static void main(String[] args) {
    int N = 750;
    
    ...
```
Now we gotta recompile and run. (I know, boring).
```sh
javac -classpath .:target/dependency/ -d . $(find . -type f -name '*.java')
java -classpath .:target/dependency/* Main
```
And now, it should display the amount of primes less than or equal to your number!

# Other Stuff
If there is a bug, just create a new issue.

### TL;DR
```sh
javac -classpath .:target/dependency/ -d . $(find . -type f -name '*.java')
java -classpath .:target/dependency/* Main
```
<!--
...:::;;;:::...:::;;;:::...:::;;;:::...:::;;;:::...:::;;;:::...:::;;;:::...
-->

[GitHub]: https://github.com/DaCuteRaccoon/PrimeSieve
[Replit]: https://replit.com/@DaCuteRaccoon/PrimeSieve
