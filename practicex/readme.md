# Practice 1

## First of all
You need to get the whatislinux.txt file by using
```
wget https://raw.githubusercontent.com/ssarunyu/basic-linux-command/main/whatislinux.txt
```

### Question 1
หาจำนวนคำของ file whatislinux.txt

Expect Answer
```
676
```

<details>
<summary>Solution</summary>

```
wc -w whatislinux.txt
```
</details>

### Question 2
มีกี่บรรทัดในไฟล์

Expect Answer
```
32
```

<details>
<summary>Solution</summary>

```
wc -l whatislinux.txt
```
</details>


### Question 3
ไฮไลท์คำว่า 'linux' ในไฟล์ (case-insensitive)

Expect Answer
```
(Every words not care case)
```

<details>
<summary>Solution</summary>

```
grep -i "linux" whatislinux.txt
```
</details>