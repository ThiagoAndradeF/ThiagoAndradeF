<h2 align="center">About Me </h2>

```go

namespace ThiagoAndradeF
{
    public class ThiagoAttributes
    {
        public static (Contact, Life, Coding) GetAttributes()
        {
            var contact = new Contact
            {
                Email = "thiagoandradeferreira16@gmail.com",
                Discord = "thiagoclencysson"
            };
            var life = new Life
            {
                Name = "thiago",
                Alias = "thi",
                Langs = new List<string> { "english", "portuguese" },
                Country = "br",
                Age = 22
            };
            var coding = new Coding
            {
                Langs = new Dictionary<string, List<string>>
                {
                    { "expert", new List<string> { "typescript/angular", "c#/.net" } },
                    { "intermediate", new List<string> { "javascript" } },
                    { "hasExperience", new List<string> { "c#", "c++", "angular", "javascript" } }
                },
                Databases = new List<string> { "sql server", "mysql", "sqlite" },
                Specialities = new List<string> { "fullstack", "software engineering", "apis", "web/app" },
                Ide = new List<string> { "vscode", "visual studio" }
            };
            return (contact, life, coding);
        }
    }
}

```

<h2 align="center">Skills </h2>

<div align="center">
  <a href="https://skillicons.dev" style="display: inline-block; margin-right: 20px;">
    <img src="https://skillicons.dev/icons?i=dotnet,angular,c,cpp,cs,js,ts" />
  </a>
  <a href="https://skillicons.dev" style="display: inline-block;">
    <img src="https://skillicons.dev/icons?i=postgres,mysql,html,css,sass,vscode,visualstudio,docker" />
  </a>
</div>

<p></p>


