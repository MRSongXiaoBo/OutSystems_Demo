  
  ## **There is only one correct answer to all the questions**
 
 __1 . Considering Aggregates and the SQL Tool, which of the following is the correct option?__
 
 __A__  All queries that can be written in an SQL Tool can be defined in an Aggregate.
 
 __B__  Joins between entities can only be defined in Aggregates.
 
 __C__  The SQL Tool allows to write queries that contain sub-queries.
 
 __D__  Attribute grouping can only be done with the SQL Tool.
 
  __2 . A developer should favor using a Structure instead of the Entity in the output of a SELECT SQL Query. Do you agree with this statement?__
  
  __A__ Yes, because queries become easier to maintain.
  
  __B__ Yes, because queries will retrieve fewer Attributes and less data
  
  __C__ No, since it is exactly the same.
  
  __D__ No, it is preferable to use the Entity instead of the Structure.

  __3 . Regarding non-SELECT queries, which of the following options is correct?__
  
  __A__ It is not possible to execute DELETE queries with the SQL Tool.

  __B__ It is not possible to use Query Parameters in Non-SELECT queries.

  __C__ It is mandatory to specify all Attributes in an INSERT query.

  __D__ It is mandatory to set the Output Entity or Structure.
  
  
  __4 . Which of the following options is correct, when implementing pagination with Tables or Lists?__
  
  __A__ The Start Index property of the Pagination holds the current page number.

  __B__ The Max Records property of the Pagination holds the number of records to show per page.

  __C__ The Total Count input of the Pagination pattern should be set to the number of records per page.

  __5 . Regarding sorting in a Table, which of the following options is correct?__
  
  __A__ All header cells need to have the Sort Attribute property defined.

  __B__ Only the Sort Attribute of the header cells needs to be defined. Data is refreshed automatically.

  __C__ The On Sort event has an input parameter containing the clicked column.
  
  __6 . Regarding sorting Lists, which of the following options is correct?__
  
  __A__ Lists have a built-in On Sort event.

  __B__ Sort clauses cannot be changed dynamically at runtime when using Lists.

  __C__ Other Widgets should be used to allow the end-user to define the sort criteria.
  
  __7 . Which of the following options is correct regarding Client Variables?__
  
  __A__ The value of a Client Variable is shared among all logged-in users.

  __B__ Lists or Binary Data can also be stored on Client Variables.

  __C__ Client Variables should be used to store confidential information.

  __D__ Client Variables are useful to cache frequently accessed information.
  
  __8 . Which of the following is a good use case for a Site Property?__
  
  __A__ Current user ID

  __B__ Total Stock Quantity of Products

  __C__ REST Web Service API Key

  __D__ Search Keyword
  
  __9 . Considering the Initialize event of a Screen, which of the following would be the best use case for that event?__
  
  __A__ Retrieve data from the server database.

  __B__ Act on data returned by a Data Action.

  __C__ Manipulate the DOM.

  __D__ Set the default value of a Local Variable.
  
  __10 . Which of the following options is false regarding Screen Aggregates?__
  
  __A__ The Render Event on the Screen is triggered when an Aggregate with the Fetch property set to "only on demand" finishes its execution.
  
  __B__ A Screen Aggregate can be triggered when a screen is initializing or only On Demand.
  
  __C__ All Aggregates, by default, have the Fetch property set to On Demand.
  
  __D__T he On After Fetch Event is triggered for every Aggregate, regardless of its Fetch property.
  
  __11 . Consider an Aggregate with the Fetch property set to Only On Demand. When does that Aggregate run?__
  
  __A__ Automatically, when the Screen is initializing.
  
  __B__ Programmatically, using a Refresh Data node in a Screen Action.
  
  __C__ Automatically, when the Aggregates set to run "At Start" finish.
  
  __D__ Programmatically, using a Server Action.
  

  __12 . A Block can be used...__
  
  __A__ Only inside other Screens.
  
  __B__ Inside Screens and Blocks, including itself.
  
  __C__ Inside Screens and Blocks, except on itself.
  
  __D__ Only inside other Blocks.
  
  __13 . Regarding Placeholders, which of the following options is correct?__
  
  __A__ Placeholder reserves space in the interface to be allocated when the block is instantiated.
  
  __B__ When a Block with Placeholders is instantiated, it is mandatory to place at least one widget inside the placeholders.
  
  __C__ Placeholders can be added to Screens and Blocks.
  
  __D__ Only one placeholder may be added per Block.
 

  __14 . Regarding Block Events, which of the following options is false?__
  
  __A__ Events can be defined at the Block or Screen level.
  
  __B__ Events allow to pass information from the Block's scope to the parent scope.
  
  __C__ Events are triggered by a Block and handled by its parent.
  
  __D__ Two instances of a Block may use the same handler for the same event.  
  
  
  __15 . In which of the following situations is it necessary to define a handler for a Block Event?__
  
  __A__ When the event has Input Parameters.
  
  __B__ When the Block has Placeholders.
  
  __C__ When the event Input Parameters are all mandatory.
  
  __D__ When the Event is set to mandatory.

  __16. In which of the following situations is the On Parameters Changed Event triggered?__
  
  __A__ If the value of a Block Input Parameters changes inside a Client Action of the Block.
  
  __B__ The On Parameters Changed must be explicitly triggered by the parent of the Block
  
  __C__ When the parent of the Block changes the value of at least one of the Block Input Parameters.

  __17. Considering that Aggregates can have hidden columns, which of the following options is correct?__
  
  __A__ Hiding columns in the Aggregate only affects the preview of the output.
  
  __B__ Columns that are empty in the database are automatically hidden.
   
  __C__ The hidden columns help optimizing the Aggregate.
  
  __D__ The hidden columns are not part of the output.

  __18. Consider that we want to apply aggregation functions in an Aggregate. Which of the following options is false?__
 
  __A__ We can apply multiple aggregation functions inside an Aggregate.
  
  __B__ The output of the Aggregate will contain all attributes from the Source Entities plus the aggregation columns.
  
  __C__ We can apply the following functions on attributes of integer data type: sum, max, min, count and average.
  
  __D__ The output of the Aggregate will not include the columns at grey.

  __19 . When debugging a consumer module, how do we guarantee that the execution stops on breakpoints defined in the producer module?__

  __A__ We just need to set breakpoints in the producer module. The execution will stop on its breakpoints automatically.
  
  __B__ We need to also start the debugger on the producer module.
  
  __C__ Nothing, just leave Service Studio open.
  
  __D__ In the producer, set the Entry Module property to the consumer module.

  __20 . In OutSystems, how do we restrict access to a Screen?__
  
  __A__ Go to the Users application and associate the Screen to a specific role.
  
  __B__ In the Screen Properties, untick roles to restrict their access.
  
  __C__ Use the CheckRole Action.
  
  __D__ We don't. Only users with a username and password can access.

  __21 . Considering the built-in Role Actions, which of the following options is false?__
  
  __A__ The CheckRole Action checks if a user has that particular Role.
  
  __B__ The GrantRole Action allows to grant a Role to a user programmatically.
  
  __C__ The RevokeRole Action allows to remove a Role from a user programmatically.
 
  __D__ The CreateUserWithRole Action creates an end-user and assigns it the Role.

  __22 . What is the Screen behavior when a widget is not valid (Valid property set to False)?__
  
  __A__ The Screen displays the widget greyed out, and displays the validation error message on the input.
  
  __B__ The widget does not appear on the Screen and the validation message appears in its place.
  
  __C__ Displays the regular widget and displays the validation error message when we hover the mouse.
  
  __D__ Displays the regular widget, applies a specific styling (e.g. red border), and displays the validation error message.

  __23 . Which of the following options is not a built-in validation in OutSystems?__
  
  __A__ Mandatory Fields
  
  __B__ Maximum length of text fields
  
  __C__ Data types of input fields

  __24 . Which of the following options is correct regarding the Valid property of the Form?__
  
  __A__ The Valid property of the Form should be checked after the last custom validation.
  
  __B__ The Valid property of the Form is automatically changed to False when all the input fields of the Form are not valid.
  
  __C__ The Valid property of the Form should be explicitly set to False (e.g. with an Assign) when an input field is not valid.
  
  __D__ When built-in validations are enabled, the Valid property of the Form is automatically checked before executing the client action logic.

  __25 . Which of the following behaviors does not apply to Forms?__
  
  __A__ A Form groups input widgets and allows displaying and editing data.
  
  __B__ A Form has a Source property that will hold the values submitted by the user.
  
  __C__ Besides input widgets, a Form can hold other widgets such as Links and Buttons.
  
  __D__ A Form is useful to validate data submitted by the user.
  
  
  __25-1 . Considering the Dropdown and the Button Group, which of the following options is false?__
 
  __A__ A Button Group needs a Button Group Item to represent each option that the user will have available to choose from.
  
  __B__ The List property of the Dropdown defines the data that will appear as options to a user on a Screen.
  
  __C__ Each Button Group Item within a Button Group has a Variable property to save the option chosen by the user.
  
  __D__The Variable property of the Dropdown will hold the value selected by the user. That value is defined in the Options Value property.
 
  __26 . Considering Inputs and Labels, which of the following options is correct?__
  
  __A__ Every input must have a Label associated with.
  
  __B__ An input widget can only be used for the Text data type.
  
  __C__ To access the value submitted in an Input widget, we can simply use InputName.Value.
  
  __D__Labels associated with mandatory fields will display a visual cue on the Screen.

  __27 . Regarding Indexes, which of the following options is correct?__
 
  __A__ Custom indexes cannot be added to an Entity.
  
  __B__ Indexes speed up data retrieval without any kind of impact.
  
  __C__ Unique indexes help prevent data duplication.
  
  __D__ Indexes over referenced attributes cannot be deleted.

  __28 . Which of the following steps is necessary to create a 1-to-1 relationship between Entity A and Entity B?__
  
  __A__ Set the data type of the identifier attribute of Entity B to Entity A Identifier.
  
  __B__ Add a new Entity C, with two reference attributes of type Entity A Identifier and Entity B Identifier.
  
  __C__ Add a new reference attribute of type Entity B Identifier to Entity A.
  
  __D__ Add a new Entity C, with the identifier attribute being a composition of types Entity A Identifier and Entity B Identifier.

  __29 . Regarding Screen Aggregates, which of the following options is false?__
  
  __A__ Screen Aggregates run asynchronously and in parallel.
  
  __B__ Screen Aggregates only exist within the scope of the Screen where they were defined.
  
  __C__ Screen Aggregates can only be executed when explicitly called.
  
  __D__ Screen Aggregates can only fetch data from the database.
  
  __30 . How is the data fetched by an Aggregate bound to a Table or a List widget?__
 
  __A__ By setting the Source property of the widget to the output of the Aggregate.
  
  __B__ The binding is done automatically since the Aggregate is in the scope of the Screen.
  
  __C__ By adding an Expression inside the widget that refers to an attribute of the data fetched by the Aggregate.
  
  __D__ By creating a Screen Action that programmatically assigns the widget to the data fetched by the Aggregate.

  __31 . Considering ListItem and List Actions, which of the following options is false?__

  __A__ List Actions can only be used inside List Items.
  
  __B__ List Items can be used outside of Lists.
  
  __C__ When List Items have the full swiping option activated, the List Action is not necessary.
  
  __D__ The List Action triggers a Screen Action that will have the logic to be executed on swipe.  
