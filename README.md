# Standard-librairy Nua
Extensible stdlib for the nua-lang

## usage:

Modules in the stdlib can be used as a reference in nua programs using the ```local``` keyword. See as below the time module embed.

```
    local x = os.clock()
    local s = 0

    print("Hello, from Nua!\nDeveloped by Timo Sarkar\n")
        for i=1,100000 do s = s + i end
            print(string.format("elapsed time: %.2f\n", os.clock() - x))
```

Then run it using the following command: ```nuac -e time.nua```


