(づ｡◕‿‿◕｡)づ

# CodingEventsDemo

The purpose of this app.... Users can input information about coding events such as:

     Name of Event
     Description of Event
     Contact Email address for Event
     Event Category 


The current state of this app.... 

     When users input information about a coding Event or Event Category in the web application, 
     our application is now completely configured to store Event and Category objects in our MySQL database.
     When users edit or delete an event, changes will be reflected within the MySQL database.


The future improvements to this app.... A Person class which would allow a person to register for an event:

    in Controllers + "PersonController.cs"
    in Models + "Person.cs" properties such as Name, ContactEmail, Id, Event
    in ViewModels + "AddEventPersonViewModel" with getters and setters & validations i.e. [Required(ErrorMessage ...}] etc
    in Views + "Person" folder + an Index.cshtml, Add.cshtml, Delete.cshtml, Events.cshtml 
    in Data/EventDbContext.cs + public DbSet<Person> Person { get; set; }
    in Views/Shared/_layout.cshtml + asp-controller/action methods
    *complete a migration and update database to store Person object in MySQL database
