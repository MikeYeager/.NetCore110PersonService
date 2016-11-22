# .NET Core 1.1.X Person Service

This source code goes along with the "Getting Your Head Around Modern Web for ASP.NET Developers" training session.

## This application consists of:

Person micro-service using .NET Core, ASP.NET Core MVC and Entity Framework Core. Service calls include:

*   Get(string searcString) - retrieves a list of all people where the person's first name, last name, email or phone number begins with the search string.
*   Get(Guid id) - retrieves all data for a particular person
*   Post(Person personToSave) - save changes to a person
*   GetCountWhereEmailContains(string emailDomain) - retrieves a count of people whose email address contains the search string


## For more information about the training session:

*   [Getting Your Head Around Modern Web](http://www.codemag.com/Training/Detail/072a18e7-9c0d-4124-914e-e577978680b8)
*   [CODE Training](http://www.codemag.com/Training)
