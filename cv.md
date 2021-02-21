# Yury Korenevsky

Minsk, Belarus
**Mobile**: *+375 (29) 506-79-89*
**E-mail**: *southtown456@gmail.com*
**Telegram**: *@Instarasta*



### Skills

***

★★★☆☆ C#
★★★☆☆ WPF
★★★★☆ ASP.NET 

★★★☆☆ SQL

★★★☆☆ HTML/CSS
★★☆☆☆ JavaScript
★★☆☆☆ Vue JS

★★★★☆ Git 
★★★★☆ Vsiual Studio 2017 / Vsiual Studio Code 
★★★☆☆ MS SQL Server

***



### Code Samples

***

``` c#
 public static string[] SortStringArray(string[] array)
    {
        string tmp;

        if (array == null)
        throw new ArgumentNullException("Exception");
        
        for(int i = 0; i < array.Length - 1; i++)
        {
            for(int j = i + 1; j < array.Length; j++)
            {
                if (array[j].Length > array[j + 1].Length)
                {
                    tmp = array[i];
                    array[i] = array[j];
                    array[j] = tmp;

                }
            }
        }
    }
```

***

