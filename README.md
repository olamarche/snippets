### JAVA - Add parameters to resource bundle

```java
String message = resourceBundle.getBundle(lang).getString("key");
		return MessageFormat.format(message, new Object[] { format.format(new Date()) });
```
