**Delphi Encrypting and Decrypting Tool for a SQLite Database**

![](media/114b3d1503008a4b6c51642ee6bfad22.png)


**Read my blog for the full details:...**
[Delphi-Sqlite-Encryptor-Decryptor-Tool](https://bayeseanblog.com/blog/delphi-sqlite-encryptor-decryptor-tool/9)

The Firedac SQLite component is encryption ready and is totally unique to Delphi.
When connecting in encryption mode in your application, the database linking
becomes more integrated and once coded, it is better to continue with your
encrypted code as it requires a bit of recoding to compile again as a non-
encrypted setup.

Here is an example of production styled code used in the Data module for SQLite.
The connection definitions use the ‘**params**’ method to hard code the
connection. It allows for the connection to find the database in your
development folder when running in Debug mode and then in Non-Debug mode it will
look for the Database in the folder where you would deploy it to. As this is
Pre- XE5 level coding, it is not targeting mobile ( **TPath** is not used in
this instance) but targeting a Windows X64 and X86 set-up. There are many other
options to select such as :- aes-128 ,aes-192, aes-256,aes-ctr-128 ,aes-ctr-192
, aes-ctr-256 ,aes-ecb-128 , aes-ecb-192 , aes-ecb-256.

I created a simple Encrypt / Unencrypt and Password Re-name tool using the
provided components in Delphi. As I found it useful to me, it would be useful to
other developers.

![](media/d1306e90d03676ce6cdbde83b5218f4f.png)

I have provided the source code for both AnyDac ( XE4 to Delphi 7) and FireDac
for XE5 and Up . The Source and Binaries are included.

Whilst this application is not complex in design and is easy to create. It just
saves a developer from having to go through the trouble to create it. Feel free
to modify it to your requirements. Using this Application makes Decryption an
Encrypting a Database quick and painless.

Happy Coding
