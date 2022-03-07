Before enabling the Multilingual Application Toolkit (MAT) in a WPF project, the source culture must be set. In this sample, "en-us" is the default culture. You can set it through Project -> Properties -> Assembly Information -> Neutral Language.

Once MAT is enabled, you should add resource files if you don't yet have any.

Once you have at least one resource files you can add translation languages. To add a new language, in Solution Explorer, right-click the project name, point to Multilingual Application Toolkit, click Add Translation Languages, and select the language(s) from the list. The Language Portal and Microsoft Translator icons indicate whether a language is supported for the corresponding service. 
After adding new languages, build the solution to synchronize the resource files.

After the build step, generate the machine translations: in Solution Explorer, right-click the project name, point to Multilingual Application Toolkit, click Add Translation Languages, and select generate machine translations.
