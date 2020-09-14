# DynamicExpressionParser
This library helps parsing code as dynamic expressions. This library has been forked and you can read more about it below.

You can also find some documentation on the forked repository. More documentation will be added with corresponding changes to this repository.

Please note that this library is not aimed towards using dynamic expressions at database queries. Initial motivation is to use it in soon to be revitalized project called WPFix, which is not related to databases at all. If you are planning to use it for queries, I strongly suggest looking at the forked repository instead since it has extensive tests for database queries.

## Fork history
I had an old open source project called WPFix which used a sample code named Dynamic.cs provided by Microsoft back in 2008. If you are interested, it should be available [here](https://docs.microsoft.com/en-us/previous-versions/bb894665(v=msdn.10)?redirectedfrom=MSDN).

I recently decided to bring my old open source projects WPFix and Geostructor back to life after more than 10 years. Hopefully, they should be on github soon. Key part of WPFix was parsing code at runtime. At the time, using Dynamic.cs was extremely useful but it felt a bit awkward. After all these years, I looked for a better alternative but unfortunately I haven't found anything to my liking. However, I found [zzzprojects/System.Linq.Dynamic.Core](https://github.com/zzzprojects/System.Linq.Dynamic.Core) which was at least working on modern .NET frameworks and had a decent project structure. It had a few conflicting changes with what I have done with Dynamic.cs on WPFix. Since it also mainly focused on database queries and was quite a large repository, I've decided to fork it. To minimize confusion and convey its main goal, I am going to rename this fork as DynamicExpressionParser. I plan to keep the namespace for now.

## License details
There are multiple license files in this repository. [LICENSE](LICENSE) file is there for the contributions in this fork. LICENSE file from the forked repository has been renamed to [LICENSE Stef Heyenrath](LICENSE Stef Heyenrath). I have also added back the license for the Microsoft code samples in [LICENSE Microsoft](LICENSE Microsoft). Microsoft's copyright notice has been removed at the forked project. Since their original fork has been removed, I couldn't find any other copyright notices. I suggest looking at *Dynamic.cs* from the original Microsoft code samples to be sure about the origin of a code file.