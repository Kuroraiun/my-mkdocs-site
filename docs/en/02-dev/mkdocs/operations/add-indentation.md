# Add indentation in instruction steps in Material for MkDocs

Indent content correctly inside numbered steps when using Material for MkDocs.

## Steps

1. Write the numbered step.

2. Add indentation using the **Tab** key (and spaces in some cases).

3. Insert the content under the step.

    ![Screenshot](add-indentation-01.png)

## Note

Use consistent indentation:

* Screenshots:

```
[tab][Screenshot](image.png)
```

or

```
[tab][tab]![Screenshot](image.png)
```

* URLs:

```
[tab]https://example.com
```

or

```
[tab][tab]https://example.com
```

* Code blocks:

````
[tab]```bash
[tab]command
[tab]```
````

* Admonitions:

```
[tab][space]!!! Note  
[tab][tab][space]Content
```

* Text:

```
[tab][space][space]Additional explanation text
```
