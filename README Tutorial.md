#### For your own sake. Do not copy and paste this! Breakdown the components and learn what each does, and pick what you want to use as your own template.

---

### Preface

ReadMe's can be one of the more tedious and forgotten parts of a project, but are vital for yourself, partner developers, and of course end users.

They can be as simple or as creative as you want, so ReadMe's don't need to be a boring text page if you don't want them to be.

ReadMe's allow you to convey your thought process, and the full extent of usage for your project, as well as instructions for it. My suggestion is to start your ReadMe at the beginning of a project using a pre-made template (that you create yourself), and complete it as you go, with a final update once the project is complete.

The following template is designed to help you discover what you want in your ReadMe while providing the essential structure of it.

**Tip**: Most IDE's such as Atom or VisualStudioCode support CTRL + SHIFT + M to preview any .md file.

---

Please feel free to star and share the repository and follow me on GitHub! Better documentation everywhere means less headaches for all of us.

---

**Tip**: You can go to your GitHub profile and right click your avatar to copy the link address so you can display your own logo.

| ![alt text](https://avatars1.githubusercontent.com/u/46427680?s=100&v=4 "GitHub avatar for author LondresRi") |
|:-----:|
| [**LondresRi**](https://github.com/LondresRi) |


## | <u>**Project Name**</u> |

#### By Shawn Lunsford
###### Initiated April 3rd, 2019. Updated April 3rd, 2019.

----------

## Description
A README template that allows developers to manage their project information all in one place, hopefully allowing them to create their own unique templates that showcase their logistical and creative talents.

## Known Bugs

**Tip**: Always disclose the issues that your project has, for the sake of other developers as well as opensource transparency.

* No known bugs.
* Does not include finished projects for development students.

## Specifications

**Tip**: There are endless ways to structure your specs, and they can be as simple or as extensive as suits you.

<details>
<summary>User stories and specifications</summary>
<table>
  <tr>
    <th> Scenario 01 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a future employer, I want to be able to review quality projects, first by reading the README.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>Well-structured README</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>Employment Opportunity</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td>READMEs don't guarantee job offers, but they certainly don't hurt.</td>
  </tr>
  <tr>
    <td> Completion </td>
    <td>True</td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 02 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a developer, I want to be able understand a project before I decide if I want to clone it.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>Clear README instructions</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>Supporting the technical community</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td>READMEs are important for yourself as a developer, but also for other developers in our highly connected community.</td>
  </tr>
  <tr>
    <td> Completion </td>
    <td>True</td>
  </tr>
</table>
</details>

## Setup and Use

#### Prerequisites
* Understanding of Markdown and HTML languages
* Option 1: [Atom](https://nodejs.org/en/)
* Option 2: [VisualStudioCode](https://www.npmjs.com/)
* [GitHub Account](https://github.com) (Optional)

#### Download Repo
1. Navigate to [LondresRi README repository](https://github.com/LondresRi/README-Assistance)
2. Clone the repository: `$ git clone https://github.com/LondresRi/README-Assistance.git`

#### Use Responsibly
1. Don't simply copy and paste.
2. Breakdown into components to understand them.
3. Utilize to create your own template that reflects your needs and style.

##### Examples of Other Setups
[HairSalon Project](https://github.com/LondresRi/HairSalon.Solution)
```
## Setup and Use

#### Prerequisites
* .NET Core 1.1 SDK or higher
* .NET Core Runtime 1.1 or higher
* [Mono](https://www.mono-project.com/)

#### Download Repo
1. Download required software: .NET Core SDK, .NET Core Runtime, Mono
2. Clone [this repository](https://github.com/LondresRi/HairSalon.Solution): _$ git clone (repo HTTPS)_

#### Open Locally - Browser
1. Navigate to the application directory: _$ cd HairSalon.Solution/HairSalon
2. Execute the commands _$ dotnet restore_, _$ dotnet build_, and then _$ dotnet run_
3. Open the localhost link provided in your preferred browser

D:\user\HairSalon.Solution\HairSalon>dotnet restore
D:\user\HairSalon.Solution\HairSalon>dotnet build
D:\user\HairSalon.Solution\HairSalon>dotnet run
Hosting environment: Production
Content root path: D:\user\HairSalon.Solution\HairSalon
Now listening on: http://localhost:5000
Application started. Press Ctrl+C to shut down.


#### Open Locally - Mono
1. Navigate to the working directory: _$ cd HairSalon.Solution_
2. Use your preferred IDE or editor to edit the project
3. Open the Program.exe file or use _$ mono Program.exe_ to run application

#### Compile Locally
1. Navigate to the project directory: _$ cd HairSalon.Solution/HairSalon_
2. Execute _$ mcs Program.cs Models/Database.cs Models/Client.cs Models/Stylist.cs Models/Specialty.cs_ to compile new Program.exe file

#### MySql Database Import - Data Management
1. Open your preferred database manager
2. Import shawn_lunsford.sql
3. Review database to ensure import was successful

#### MySql Database Import - Testing (No Data)
1. Open your preferred database manager
2. Import shawn_lunsford_test.sql
3. Review database to ensure import was successful

#### MySql Database Recreation
1. Open MySql in your preferred terminal, see [MySql Documentation](https://dev.mysql.com/doc/) for further instructions
2. Execute commands _CREATE DATABASE hair_salon;_, and _USE hair_salon;_ to create and select the database
3. Execute commands _mysql>CREATE TABLE stylists (id serial PRIMARY KEY, name VARCHAR(255), time VARCHAR(255), experience INT(11)), date VARCHAR(255);_, _mysql>CREATE TABLE clients (id serial PRIMARY KEY, name VARCHAR(255), number VARCHAR(20), time VARCHAR(255), stylist_id INT(11));_, and _mysql>CREATE TABLE specialties (id serial PRIMARY KEY, name VARCHAR(255), description VARCHAR(255));_
4. Alternately, use preferred database manager for structuring and data input


D:\user>mysql -u root -p
Password: [Password]
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is [Your connection id here]
Server version: [Your server version and system here]

Copyright (c) 2000, 2019, Oracle and/or its affiliates. All rights reserved.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql>CREATE DATABASE hair_salon;
Query OK, 1 row affected (0.00 sec)

mysql>USE hair_salon;
Database changed

mysql>CREATE TABLE stylists (id serial PRIMARY KEY, name VARCHAR(255), time VARCHAR(255), experience INT(11)), date VARCHAR(255);
Query OK, 0 row affected (0.00 sec)
mysql>CREATE TABLE clients (id serial PRIMARY KEY, name VARCHAR(255), number VARCHAR(20), time VARCHAR(255), stylist_id INT(11));
Query OK, 0 row affected (0.00 sec)
mysql>CREATE TABLE specialties (id serial PRIMARY KEY, name VARCHAR(255), description VARCHAR(255));
Query OK, 0 row affected (0.00 sec)


#### Edit
1. Navigate to the working directory: _$ cd HairSalon.Solution_
2. Use your preferred IDE or editor to edit the project

#### Test
1. Navigate to the working directory: _$ cd HairSalon.Solution/HairSalon.Tests_
2. Execute _$ dotnet tests_ to run application tests
```


## Built With

* Mac OS X El Capitan 10.11.6
* Atom (IDE)
* HTML5
* Markdown

#### Examples of Other Built With's
[HairSalon Project](https://github.com/LondresRi/HairSalon.Solution)
```
* Linux Ubuntu 18.04 bionic
* Atom (IDE)
* C#
* HTML-5 / CSS-3
* Bootstrap 4.0.0
* Microsoft SDK
* .NET Core 2.2
* .AspNetCore
* MySql
* GitBash
```

## Contributors

**Tip**: Make sure to include all contributors that were involved in the project. You can also include a credits portion to your README to breakdown who did what. See [eHappenings](https://github.com/LondresRi/EventPlanner.solution) and [Go'Leir - A Text RPG](https://github.com/LondresRi/rpg-game) projects for examples of this.

| Author | GitHub | Email |
|--------|:------:|:-----:|
| Shawn Lunsford | [LondresRi](https://github.com/LondresRi) |  [lunsford.sk@gmail.com](mailto:lunsford.sk@gmail.com) |

## Support and contact details

**Tip**: If there is a support structure besides contacting the developers, make sure to include that here.

If you have any feedback or concerns, please contact one of the contributors.

## License

**Tip**: Always include a license with your project, by default a MIT License that supports our opensource development community.

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Copyright (C) 2019 Shawn Lunsford. All Rights Reserved.
```
MIT License

Copyright (c) 2019 Shawn Lunsford.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Acknowledgments

#### [Epicodus](https://www.epicodus.com/)
>"A school for tech careers... to help people learn the skills they need to get great jobs."

#### [The Internet](https://webfoundation.org/)
> "...the first thing that humanity has built that humanity doesn't understand..."
> - Eric Schmidt, Google (Alphabet Inc.)

#### [Shawn](https://github.com/LondresRi)
> "You're so cool right now."
> - That one person, that one time
