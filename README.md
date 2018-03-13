# blog_question
1、创建database
  a. docker run -d --name mysql -e MYSQL_ROOT_PASSWORD=root  hub.c.163.com/library/mysql
  b. 登陆数据库，创建demo库
     CREATE DATABASE `demo` CHARACTER SET utf8 COLLATE utf8_general_ci;
2、刷库
   python3.5  manage.py db init
   python3.5  manage.py db migrate
   python3.5 manage.py db upgrade

3、运行main程序
  python -u blog_main.py
  
  执行结果：
  
 * Running on http://0.0.0.0:9000/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 125-618-658
 * Detected change in '/Users/shibabunchou/blog_main.py', reloading
 * Restarting with stat
 * Debugger is active!
