# Syntax Highlighting

## Apache

```apache
Listen 80
<VirtualHost *:80>
    DocumentRoot "/var//www/hello.world"
    ServerName hello.world
</VirtualHost>
```

## Diff

```diff
@@ -1,2 +1,2 @@
+ Hello, World!
- hello world

```

## Dockerfile

```dockerfile
FROM image:tag
RUN echo Hello, World!
```

## ini

```ini
message = Hello, World!
```

## JSON

```json
{
    "message": "Hello, World!"
}
```

## Markdown

```markdown
# Hello, World!

Hello, World!

```

## PHP

```php
<?php
    print("Hello, World!");
?>
```

## Python

```python
print("Hello, World!")
```

## sh

```sh
#!/bin/bash

echo "Hello, World!"
```

## SQL

```sql
SELECT msg FROM msg WHERE msg='Hello, World!' LIMIT 1;
```

## YAML

```yaml
messages:
  - "Hello, World!"
```
