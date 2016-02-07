# troubleshooting

## Manual Code Review

* Extract versions of dependencies and plugins in Maven Properties.
* Extract DB properties from Code to Properties file.
* Extract string literals into Constants.
* Use Logging instead of `System.out.println()`.

## FindBugs Code Analysis

Use `mvn clean install site` to generate report.