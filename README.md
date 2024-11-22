修改的部分为:

1.删除".vs"文件夹内所有文件

2.修改"fsd/global.h"内第22行

"#define PRODUCT "SKYline Technical Server"

改为

#define PRODUCT "The FSD Open Source https://github.com/supermastergui/FSD"

3.删除CMakeCache.txt

---

The modified section reads.

1. Delete all files in the “.vs” folder.
   
2. Modify line 22 in “fsd/global.h”.
   
“#define PRODUCT “SKYline Technical Server”” to #define PRODUCT "The FSD Open Source https://github.com/supermastergui/FSD"

Change it to

#define PRODUCT "The FSD Open Source https://github.com/supermastergui/FSD"

3. Delete CMakeCache.txt.
