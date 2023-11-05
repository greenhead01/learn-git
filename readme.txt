Git is a version control system

git is free software

i want to change this file

at last, we can stop this actions

使用git连接remote repository：
1.本地仓库连接远程仓库：git remote add origin git@github.com:liyiheng/**.git
或者回到github上建立的远程仓库，找到对应的**.git
出现问题：ssh密钥无法对应，客户端重新生成密码，填入服务器端。或者清除远程仓库:

2.git push -u origin master

给出解决链接：
https://blog.csdn.net/m0_56982300/article/details/129473306?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522169915542316800185843645%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=169915542316800185843645&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-4-129473306-null-null.142^v96^pc_search_result_base6&utm_term=%24%20git%20push%20-u%20master%20fatal%3A%20master%20does%20not%20appear%20to%20be%20a%20git%20repository%20fatal%3A%20Could%20not%20read%20from%20remote%20repository.%20%20Please%20make%20sure%20you%20have%20the%20correct%20access%20rights%20and%20the%20repository%20exists&spm=1018.2226.3001.4187


https://blog.csdn.net/qq_37185371/article/details/103302004?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522169915471116800197062824%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=169915471116800197062824&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-103302004-null-null.142^v96^pc_search_result_base6&utm_term=git%40github.com%3A%20Permission%20denied%20%28publickey%29.%20fatal%3A%20Could%20not%20read%20from%20remote%20repository.%20%20Please%20make%20sure%20you%20have%20the%20correct%20access%20rights%20and%20the%20repository%20exists.&spm=1018.2226.3001.4187


https://blog.csdn.net/xxwwh/article/details/119841089



//新建分支进行修改：
creating a new branch is quick

master 修改 readme.txt
