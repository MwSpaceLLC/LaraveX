# <img src="http://laravex.com/assets/images/72ppi/logo.png" width="45"> LaraveX Official
Portable Development Server with Nginx, Php7, Composer, Node, MySql, Email, Sqlite, Git  & Python!

![image](https://user-images.githubusercontent.com/29952045/108795737-53174200-7587-11eb-9bb8-641fbddec874.png)

Last Build  | Status  | Require
----------- | ------- | -------
23/02/2021  | Beta    |  Win 64

### Why use laravex as Dev Server? 

We work every day to improve the speed at which our developers write applications. This server helps the developer to install only one system to develop his projects, making him focus on the code, not on his environment.
For more, (See [Offical Web Site](https://laravex.com/))

> 💻 Start Engine: 
```
PS C:\Users\Joe> laravex
```


> 👌 Check service status:
```
PS C:\Users\Joe> laravex status
```


🚀 Start single service [mysql, host, mail] | es. only *mysql*:
```
PS C:\Users\Joe> laravex start mysql
```


👻 Update Windows host file with sites avaible:
```
PS C:\Users\Joe> laravex fresh
```


💡 Get all sites avaible in Windows host file:
```
PS C:\Users\Joe> laravex list
```


🎲 Add new site in Windows host file [cussent/directory && project.name] | es. awesome.net to *C:\Users\Joe\project\awesome*
```
PS C:\Users\Joe\project\awesome> laravex link . awesome.net
```
