# Flask_API
The idea of the project is to provide the web API for a database, which holds information about candidates.

The project will use standard HTTP protocol and we will use JSON as a data format. Now we will define a basing model for handling our data. We will create the Candidate, Experience, and Project classes. The candidates have an identifier which is unique and has Python's uuid type. Besides this, the candidate has first_name, last_name, and the collection of Experience objects. The Experience class has the main amount of years the candidate has experience with that domain, and possibly a list of projects that belong to that domain. The Project class also has an identifier, the same as the Candidate class has.

It has a name, description, start and end dates. The start and end date have the time type.
