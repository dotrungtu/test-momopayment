# Test momopayment
Test project for [MoMo's Java payment library](https://github.com/lnguyen99/momopayment)

### Requirements:
- At least Java 8
- Maven 

Please consult https://developers.momo.vn/#/ for detailed APIs of the library as well as applicable MoMo endpoints for different methods.<br/> 

### About the Test Project 
You can directly clone this repo and run the files (`AllInOne.java` and `Pay.java`) to have an understanding of how [momopayment](https://github.com/lnguyen99/momopayment) library works. 

### The momopayment library
For the snapshot version, you can add the following dependency to your `pom.xml`:
```     
        <dependency>
            <groupId>io.github.lnguyen99</groupId>
            <artifactId>momopayment</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
```
Remember to specify your repository as following:
```
        <repository>
            <id>ossrh</id>
            <url>https://oss.sonatype.org/content/repositories/snapshots</url>
        </repository>
```

And then update and install all the dependencies  in your `pom.xml` (if prompted)
We absolutely recommend creating and modifying your own configurations for log4j 2 and environment setup to your likeness in your resources folder.
 
