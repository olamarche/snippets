### JAVA - Add parameters to resource bundle

```java
String message = resourceBundle.getBundle(lang).getString("key");
		return MessageFormat.format(message, new Object[] { format.format(new Date()) });
```

### JSTL - Check list if empty

```java
<%@ taglib uri="http://java.sun.com/jsp/jstl/functions" prefix="fn"%>
<c:if test="${fn:length(list) > 0}"></c:if>
```

### JAVASCRIPT - Check empty or spaced string

```javacript
str.match(/^\s*$/g)
```
