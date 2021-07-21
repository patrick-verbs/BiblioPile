Create React-with-Redux project template with ASP.NET Core
https://docs.microsoft.com/en-us/aspnet/core/client-side/spa/react?view=aspnetcore-5.0&tabs=visual-studio

Name: BiblioPile
 
MVP:
- the user should be able to add physical books to their profile with unique identifiers (e.g. ISBN)
  - book entries may be created by users
  - existing book entries may be added to users’ profiles
- the user should be able to add digital books to their profile (as a list object, not the source binary)
- the user should be able to add devices and physical locations to their profile
  - this allows the user to associate a digital or physical book with its location
  - they can then easily look up where they last stored a book or other document (digital or physical)
- the user should be able to add metadata to books (e.g. storage location, tags/keywords, date acquired, series, reading order, physical condition, MD5/SHA checksums)
- the user should be able to import and export their book lists (compatible with GoodReads CSVs)
- the user should be able to set the public visibility of any books or locations
 
Stretch goals
- the user should be able to create posts associated with a book (e.g. notes to self, public reviews, private GoodReads drafts)
- the user should be able to launch/open digital books based on their recorded location
- the user should be able to highlight and tag content within EPUB and PDF documents by opening them in the browser
- the user should be able to highlight and tag live or locally-stored web pages, and back live pages up on Archive.org
- the user should be prompted to review differences if they create a book entry that may be a duplicate
- the user should be able to click on a book and submit a form to create a plain-text citation from it for use in bibliography
  - all citations are stored for later reference
  - these can be expanded into “fact” objects as a further stretch goal (see below)
- the user can create “facts” by making a concise note on a bibliographic citation linked to a source (i.e. book)
  - facts can be nested (built from one or more other facts)
  - facts must be concise but may have explanatory posts and comments from other users
- the user can import book data from GoodReads or other sites instead of creating entries manually
 
Showcase objectives:
- React frontend
- C# backend
- User authentication and authorization
- Flashy style
