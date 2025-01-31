**Exercise 1**.
```bash
ls $HOME | grep '^[A-Z]'
```
**Exercise 2**.
```bash
ls $HOME | grep '^\.'
```
**Exercise 3**.
```bash
ls $HOME | grep '^\. ' | wc -l
```
**Exercise 4**.
```bash
ls $HOME | grep '^[a-zA-Z]*$'
```
**Exercise 5**.
```bash
ls $HOME | grep -v '[A-Z]'
```
**Exercise 6**.
```bash
ls $HOME | grep -E '^[^.]*$|^.*\.[^.]{1,2}$|^.*\.[^.]{4,}$'
```
**Exercise 7**.
```bash
ls /etc | grep '^c.*y$'
```
**Exercise 8**.
```bash
ls /etc | grep 'ss'
```
**Exercise 9**.
```bash
ls $HOME | grep -E '^.{1}[A-Z].{1}[A-Z].{1}e$'
```
**Exercise 10**.
```bash
ls $HOME | grep -E '^[a-zA-Z0-9]{4}$'
```
**Exercise 11**.
```bash
ls /var/log | grep '\.log$'
```