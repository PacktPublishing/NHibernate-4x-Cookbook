


# NHibernate 4.x Cookbook
This is the code repository for [NHibernate 4.x Cookbook](https://www.packtpub.com/application-development/nhibernate-40-cookbook?utm_source=github&utm_medium=repository&utm_content=9781784396428), published by Packt. It contains all the supporting
project files necessary to work through the book from start to finish.

## About the Book
This book will take you from the absolute basics of NHibernate through to its most advanced features, showing you how to take full advantage of each concept to quickly create amazing database applications. You will learn several techniques for each of the four core NHibernate tasks—configuration, mapping, session and transaction management, and querying—and which techniques fit best with various types of applications. In short, you will be able to build an application using NHibernate by the end of the book.

## Instructions and Navigation
All of the code is organized into folders. The commands and instructions will look like the following:

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


## Related products:
* [NHibernate 3.0 Cookbook](https://www.packtpub.com/application-development/nhibernate-30-cookbook?utm_source=github&utm_medium=repository&utm_content=9781849513043)
* [Learning NHibernate 4](https://www.packtpub.com/application-development/learning-nhibernate-4?utm_source=github&utm_medium=repository&utm_content=9781784393564)
* [NHibernate 2 Beginner's Guide](https://www.packtpub.com/application-development/nhibernate-2-beginners-guide?utm_source=github&utm_medium=repository&utm_content=9781847198907)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781784396428">https://packt.link/free-ebook/9781784396428 </a> </p>