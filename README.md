# reference_links
Place holder to store random links

1. Test Flakiness. Google Testing Blog: https://testing.googleblog.com/2017/04/where-do-our-flaky-tests-come-from.html
2. Web Driver logs:
```java 
Logs logs= webDriverManager.getDriver().manage().logs();
        LogEntries logEntries = logs.get(LogType.DRIVER);
        LogEntries logEntries1 = logs.get(LogType.BROWSER);
        for (LogEntry logEntry : logEntries) {
            System.out.println(logEntry.getMessage());
        }

        for (LogEntry logEntry : logEntries1) {
            System.out.println(logEntry.getMessage());
        }

        //List<LogEntry> logEntries2 = webDriverManager.getDriver().manage().logs().get(LogType.PERFORMANCE).getAll();
        //List<String> logMessagesList = logEntries2.stream().map(logEntry -> logEntry.getMessage()).collect(Collectors.toList());

```

3. Selenium GRID docker:  https://github.com/SeleniumHQ/docker-selenium
4. 
