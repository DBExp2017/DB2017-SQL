# DB2017-SQL
Oracle课程设计 与表相关的文件

使用UTF-8编码

        管理员     教师
账号      admin   02030923
密码      admin   123456

sqlplus远程连接teacher 
    teacher/teacher@//47.94.200.154:1521/orcl

    select sec_id,title 
    from course natural join section natural join teaches 
    where teaches.id='02030923';

