# Read configuration

By default, plugin creates a class with name `BytemaskConfig`.
If you've configured the different name
from the [configuration](Configure.md "Configure custom file name and class name"), then you'll have to use that class.

## Example

If properties file is like:

```Generic
API_KEY=AIbuf34ug8o348ih
SECRET=SUPERSECRET!
```

In code, you can access it like

```Kotlin
fun example() {
    val apiKey = BytemaskConfig.API_KEY
    val secret = BytemaskConfig.SECRET
}
```
