# Mini-task CLI usage

This is a bare minimum usage of cli, according to mini task on **Day 1** (14/04/2025)

## without loop

```cmd
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
type nul> latihan1.txt

type nul> latihan2.txt

type nul> latihan3.txt

type nul> latihan4.txt

type nul> latihan5.txt

dir

del "latihan4.txt

mkdir latihan4.txt

del "latihan5.txt"

mkdir latihan5.txt

dir

rmdir latihan4.txt

```
# with loop
```cmd
mkdir latihan1
cd latihan1
for /l %a in (1,1,5) do echo %a
latihan1>echo 1
1

latihan1>echo 2
2

latihan1>echo 3
3

latihan1>echo 4
4

latihan1>echo 5
5
```

# New Task
```cmd
for %%a in ("Blackpink","Evanescence","Linkin Park") do (
    mkdir %%a
    move "%%*a.mp3" .\%%a
)
```