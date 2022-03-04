# Create a directory with a file with secret keys

~~~
mkdir /home/key
cd /home/key
~~~

Create a file in /home/key
~~~
nano main.yml
~~~

Add three variables to the file

~~~
 access_key: <you key aws_access_key>
 secret_key: <you key aws_secret_key>
 user_key: <you user name an IAM>
~~~
 
# Clone git repository to folder /home/
~~~
cd /home/
git clone https://github.com/kupa2004/13.git
~~~
