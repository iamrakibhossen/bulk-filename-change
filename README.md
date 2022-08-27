# bulk-filename-change
Change bulk filename with python its simple

```
import os
def main():

    i = 0
    dir = "C:/Users/Rakib Hossen/OneDrive/Pictures/Saved Pictures/"

    for filename in os.listdir(dir):
        des = "img" + str(i) + ".jpg"
        src = dir + filename
        des = dir + des
        os.rename(src, des)
        i += 1
        
if __name__ == "__main__" :
    main()
```
