**Summany**

**Gradle Project**

1.Add gradle plugin name called "net.foragerr.jmeter" to execute the JMeter scripts.

2.First use need to modify the dir of  performancetesting/build/

        i) add sqljdbc4-2.0.jar to performancetesting/build/jmeter/lib/ext
        
        ii) new  a folder at performancetesting/build/jmeter/bin  and put log4j2.xml into this forlder
    
3.Add jmeter-results-detail-report_21.xsl into root directory


**JMeter Scripts**

1.Need to make sure any DataSet in jmx file will use relative path



**Gradle JMeter Command**

1. gradle jmRun

2. gradle jmReport

