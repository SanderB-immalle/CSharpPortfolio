# Lists

#### List aanmaken en er over itereren:

```
List<string> l = new List<string>();
```
```
            foreach( var item in l)
            {
                Console.WriteLine(item);
            }
```


links:
https://dotnetfiddle.net/FL9awx

#### List aanmaken van random getallen en er over itereren:

```
			List<int> l = new List<int>();
            Random r = new Random();
```
```
            for (int i = 0; i < 10; i++)
            {

                l.Add(r.Next(0,100));
            }
```
```
            foreach( var item in l)
            {
                Console.WriteLine(item);
            }
```
Links:
https://dotnetfiddle.net/LF23v2