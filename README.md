Singleton.as
============
Extend Singleton from your class
```as
public class YourClass extends Singleton
{
	/* your code here */
}
```
Then, to obtain the instance of your class:
```as
var yourClass:YourClass = Singleton.getInstance(YourClass) as YourClass;
```