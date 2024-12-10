# sort-csv-file-example
Sort CSV file example

## Run

```bash
cat sample1.csv | sort -t ',' -k1,1
```

```bash
$ cat sample1.csv | sort -t ',' -k1,1
apple,110
banana,90
cherry,100
kiwi,60
lemon,50
orange,120
```

```bash
cat sample2.csv | sort -t ',' -k1,2
```

```bash
$ cat sample2.csv | sort -t ',' -k1,2
apple,110,Shiga
apple,120,Tokyo
banana,100,Nagoya
banana,900,Hokkaido
cherry,100,Kobe
cherry,110,Fukuoka
kiwi,60,Saitama
kiwi,70,Chiba
lemon,50,Sendai
lemon,60,Yokohama
orange,120,Kyoto
orange,130,Osaka
```
