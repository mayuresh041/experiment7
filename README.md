C:\Users\91987>cd rev1

C:\Users\91987\rev1>git init
Reinitialized existing Git repository in C:/Users/91987/rev1/.git/

C:\Users\91987\rev1>git checkout -b fb3
Switched to a new branch 'fb3'

C:\Users\91987\rev1>rev1.txt

C:\Users\91987\rev1>git add .
warning: adding embedded git repository: m05
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> m05
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached m05
hint:
hint: See "git help submodule" for more information.

C:\Users\91987\rev1>rev1.txt

C:\Users\91987\rev1>file1.txt
'file1.txt' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\91987\rev1>8a.txt
'8a.txt' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\91987\rev1>rev2.txt

C:\Users\91987\rev1>git add .

C:\Users\91987\rev1>git commit -m "first"
[fb3 48ebdec] first
 3 files changed, 4 insertions(+)
 create mode 160000 m05
 create mode 100644 rev2.txt

C:\Users\91987\rev1>rev2.txt

C:\Users\91987\rev1>git add .

C:\Users\91987\rev1>git commit -m "second"
[fb3 083bf40] second
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\91987\rev1>git log
commit 083bf400d0f64c8a36730fe906d350283c69c9a7 (HEAD -> fb3)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 10:22:02 2024 +0530

    second

commit 48ebdec5bcff0038212dae1cd84bff48568b8b41
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 10:21:24 2024 +0530

    first

commit 6cd3c13b9642a0683c2c80852cc7b3ea37b0c8b1 (tb1, master, fbn2)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:54:28 2024 +0530

    second commit

commit 119999ee646c5721cfb92d9d98a0d31aff18b542 (fb1)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:49:01 2024 +0530

    first

commit daf99af9bf39c1abc7a223827f38b2ca316734a4
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:42:48 2024 +0530

    first commit

C:\Users\91987\rev1>git tag v3.0

C:\Users\91987\rev1>git log
commit 083bf400d0f64c8a36730fe906d350283c69c9a7 (HEAD -> fb3, tag: v3.0)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 10:22:02 2024 +0530

    second

commit 48ebdec5bcff0038212dae1cd84bff48568b8b41
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 10:21:24 2024 +0530

    first

commit 6cd3c13b9642a0683c2c80852cc7b3ea37b0c8b1 (tb1, master, fbn2)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:54:28 2024 +0530

    second commit

commit 119999ee646c5721cfb92d9d98a0d31aff18b542 (fb1)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:49:01 2024 +0530

    first

commit daf99af9bf39c1abc7a223827f38b2ca316734a4
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:42:48 2024 +0530

    first commit

C:\Users\91987\rev1>git tag 2.0 daf99af9bf39c1abc7a223827f38b2ca316734a4

C:\Users\91987\rev1>git log
commit 083bf400d0f64c8a36730fe906d350283c69c9a7 (HEAD -> fb3, tag: v3.0)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 10:22:02 2024 +0530

    second

commit 48ebdec5bcff0038212dae1cd84bff48568b8b41
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 10:21:24 2024 +0530

    first

commit 6cd3c13b9642a0683c2c80852cc7b3ea37b0c8b1 (tb1, master, fbn2)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:54:28 2024 +0530

    second commit

commit 119999ee646c5721cfb92d9d98a0d31aff18b542 (fb1)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:49:01 2024 +0530

    first

commit daf99af9bf39c1abc7a223827f38b2ca316734a4 (tag: 2.0)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:42:48 2024 +0530

    first commit

C:\Users\91987\rev1>git tag -d 2.0
Deleted tag '2.0' (was daf99af)

C:\Users\91987\rev1>git log
commit 083bf400d0f64c8a36730fe906d350283c69c9a7 (HEAD -> fb3, tag: v3.0)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 10:22:02 2024 +0530

    second

commit 48ebdec5bcff0038212dae1cd84bff48568b8b41
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 10:21:24 2024 +0530

    first

commit 6cd3c13b9642a0683c2c80852cc7b3ea37b0c8b1 (tb1, master, fbn2)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:54:28 2024 +0530

    second commit

commit 119999ee646c5721cfb92d9d98a0d31aff18b542 (fb1)
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:49:01 2024 +0530

    first

commit daf99af9bf39c1abc7a223827f38b2ca316734a4
Author: mayuresh <mayuresh14@gmail.com>
Date:   Mon Mar 4 09:42:48 2024 +0530

    first commit
:# experiment7
