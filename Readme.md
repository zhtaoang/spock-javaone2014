# Spock JavaOne 2014 Code Samples
## purpose
This is a series of comparisons of junit, groovy test cases, and spock presented by Ken Sipe

## getting started
The code is provided using gradle.  So after you clone the repo, just type:

	> ./gradlew test
or

	> gradlw.bat test

This will download the internet... I mean download and bootstrap gradle + all the dependencies for the project including spock.

#### setting up your IDE
The gradle build file is configured to setup either an eclipse or IDEA project.  just type:

	> ./gradlew idea
or 

	> ./gradlew eclipse	

**I have only tested this on IDEA**

#### reviewing failures at the cmd-line
If a gradle build has a failed test, there isn't much information provided on the cmd-line for what is going on.  The information can be view from stdio if you use the -i switch with gradle such as:

	> ./gradlew test -i

## Demos

### Basics
1. power assert
2. simple calc
3. old
4. with
5. requires java8
5 fast slow
6. hamcrest
7. data driven with unroll

### mocking
1. publisher
2. warehouse
    
    basics
    regex
    returning

3. spying
4. Account

### extension sayonfail





## sharing
you are free to use this as a reference and to share with others... remember where you got it from and share the love!  that includes the awesome guys working spock... namely Peter Niederwieser (@pniederw)

