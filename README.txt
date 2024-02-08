NAME :- VIVEK DAVE
STUDENT ID :- 0849076
Subject :- WEB APPLICATION SECURITY
TERM :- (FALL 2023) 2nd SEM
INSTRUCTOR :- ANDREW STEELE


Part 1 - Initial Setup:

Downloaded and installed Visual Studio without encountering any errors.
The installation process took some time but was otherwise straightforward.
Successfully created a sample project in Visual Studio.
Verified project functionality by displaying "Hello World" in the browser.


Part 2 - ASP.NET Core MVC Web Application:

Created a new ASP.NET Core MVC web application using .NET 7.
Encountered an error due to a mistake in Program.cs during the initial setup.
Rectified the error in Program.cs, resulting in a successful outcome.
Verified the correction by observing the browser displaying "Hello Shruti, NumTimes is: 3" when accessing the URL "https://localhost:44342/HelloWorld/Welcome?name=Shruti&numtimes=3."


Part 3 - Adding a View:

Extended the project by adding a view in Part 3.
Followed the prescribed steps for view creation without encountering any errors.
Ensured the seamless integration of the view into the project.


Part 4- 

Successfully installed Visual Studio after encountering initial errors.
Reinstalled Visual Studio to resolve installation issues.

Model Creation and NuGet Packages:

Created a Movie model class with Entity Framework Core for database management.
Encountered a problem with missing packages during initial setup but resolved by building the project.
 
Scaffolding and Database Initialization:

Used scaffolding to generate CRUD pages and a database context.
Faced an issue where the generated pages couldn't be used due to a non-existing database.

Migration and Testing:

Applied EF Core Migrations to create the database.
Overcame an error during testing where the Movie App link did not display the expected result.


Part 5-

Could not examine the database, could not find ssox in the view menu even after restarting so i moved to the next steps

completed seeddata file, had 4 error because of mvc instead of MVC, fixed them

After getting so many errors, i decided to uninstall visual studio and installed it again 

(2024,Jnauary 31)

Part 6-

Updated the Movie.cs model to improve the presentation by using Display and DataType attributes for the "Release Date" field.

Explored the generation of Edit, Details, and Delete links in the Index.cshtml file using Core MVC Anchor Tag Helper.

Examined the MoviesController with both HTTP GET and POST Edit methods for fetching and processing movie data.

Implemented security measures like the [Bind] attribute to prevent over-posting and the [ValidateAntiForgeryToken] attribute to protect against forgery in the HTTP POST Edit method.

Explored the generated HTML for the Edit form and understood the role of anti-forgery tokens.

Highlighted the importance of adhering to HTTP best practices, especially avoiding data modification in HTTP GET methods.

Now I am able to make changes in the list of movies, even individually with url like:https://localhost:7251/Movies/Edit/4 to edit the 4th one.


Part 7-

I got error because i made a mistake in the moviecontroller.cs file but then i removed 3 unnecessary lines and i received the desired result

I then edited that file which allowd me to  pass the search title as route data (a URL segment) instead of as a query string value. i saw the results when i added /Movies/Index/ghost to the url

After that, I added the searh filter fo the movies

I added search by genre now I am able to test the app by searching by genre, by movie title, and by both

(2024, February 1)

Part 8-

Added rating property to the movie model

Completed build after that

Updated the view templates to display, create, and edit the new Rating property in the browser view.
(2024, February 8)

I Added Rating R for the movie Harry Met Sally and then ran a build in the packager manager console to update the database.

Received no errors so i moved onto the next part

Part 9-

Title, Rating, Genre, Price, Rating

Disabled JavaScript

Couldn't load the files in local host. Then i have enabled the javascript.

After that, i have added new movies and deleted old movies.

It was showing Rating error. The error was to Include letters, numbers.
Then i have edited the rating value.

After that i have created git Repository. Pushed my file in github.

