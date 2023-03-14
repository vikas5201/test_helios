Helios-CMS
Content Management System Helios Technologies

Usefull Commands

dotnet ef migrations add Migration_tmp8d --project DAL --startup-project CMS --verbose
prod
dotnet ef database update --project DAL --startup-project CMS --verbose --connection "Server=144.76.71.196;Port=3306;Database=helios;Uid=root;Pwd=CjXEaZdGNPFvngO2G8d2u8g;"

Development
dotnet ef database update --project DAL --startup-project CMS --verbose --connection "Server=144.76.71.196;Port=3307;Database=helios;Uid=root;Pwd=CjXEaZdGNPFvngO2G8d2u8g;"

Used Frameworks / Components

Argon Dashboard Pro (Docs) : https://demos.creative-tim.com/argon-dashboard-pro-angular/#/forms/components
Angular 12 & .NET Core 6
Firebase Authorization
Running Environments

dotnet run --launch-profile "LocalDevelopment"
dotnet run --launch-profile "Development"
dotnet run --launch-profile "Production"
Project Requirements

VSCode or Visual Studio 2022 on Windows or OSX
NPM >= 8
Node >= 16
Dotnet CLI >= 6
.NET SDK >= 6
Prepare ENV (MAC)

Install Node 16 LTS: https://nodejs.org/download/release/v16.18.0/node-v16.18.0.pkg
Install .NET Core 6 SDK + Dotnet CLI: https://dotnet.microsoft.com/en-us/download/dotnet/6.0
Install VSCode: https://code.visualstudio.com/download
Run project (VSCode)

Open terminal in the root folder of the repository
cd CMS
npm -i
dotnet restore
dotnet run
http://localhost:5001/signin
Demo Accounts

SuperAdmin: test@test.test - testtest
CityAdmin
MuseaAdmin
HorecaAdmin
EventsAdmin
RecreatieAdmin
EmailNotActivated
AccountLocked
Login Credentials

Email- superadmin@curist.be Pass- superadmin
Email - test@test.test pass- testtest
Access for dev database http://144.76.71.196:8081

Username- root

pass- CjXEaZdGNPFvngO2G8d2u8g

screenshot
