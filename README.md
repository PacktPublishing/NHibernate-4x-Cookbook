#NHibernate 4.x Cookbook
This is the code repository for[NHibernate 4.x Cookbook](https://www.packtpub.com/application-development/nhibernate-40-cookbook?utm_source=github&utm_medium=repository&utm_content=9781784396428), published by Packt.It contains all the supporting
project files necessary to work through the book from start to finish.

## Instructions and Navigation
All of the code is organized into folders. The commands and instructions will look like the following:

```
using System.IO;
using log4net;
namespace MyApp.Project.SomeNamespace
{

    public class Foo
    {
        private static ILog log = LogManag-er.GetLogger(typeof(Foo));

        public string DoSomething()
        {
            log.Debug("We're doing something.");
            try
            {
                return File.ReadAllText("cheese.txt");
            }
            catch (FileNotFoundException)
            {
                log.Error("Somebody moved my cheese.txt");
                throw;
            }
        }
    }
}
```

## Related products:
* [NHibernate 3.0 Cookbook](https://www.packtpub.com/application-development/nhibernate-30-cookbook?utm_source=github&utm_medium=repository&utm_content=9781849513043)
* [Learning NHibernate 4](https://www.packtpub.com/application-development/learning-nhibernate-4?utm_source=github&utm_medium=repository&utm_content=9781784393564)
* [NHibernate 2 Beginner's Guide](https://www.packtpub.com/application-development/nhibernate-2-beginners-guide?utm_source=github&utm_medium=repository&utm_content=9781847198907)


