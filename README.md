# PasswordHash
(PHP 5 >= 5.5.0)
password_hash — Creates a password hash
在PHP5.5之前，我们对于密码的加密可能更多的是采用md5或sha1之类的加密方式(现在还有存放明文的吗？)，
但是简单的md5加密很容易通过字典的方式进行破解，随便找个md5解密的网站就能获取原始密码。
