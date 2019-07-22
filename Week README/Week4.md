engineeringWeek 4 will be about learning to build web apps that use a database.
New concepts:

- Object-relational mappers
- Relationships between data in a database
- SQL, the database query language
- Data encryption
- Rake
- HTML forms
- Web app deployment


And skills:

- Designing data relationships using an object-relational mapper
- Designing a database schema
- Manipulating data using the CRUD cycle
- Structuring more complex MVC applications
- Refactoring more complex apps
- Creating user stories

# Database

- Traditional/ relational database -> table based storage designs. Each of those tables will have a uniq identifier. Different tables can talk one to another.

Post in facebook would have a key to the user

non - relation databases - Mongon - massive series of Jason documents talking to each other

SQL -> sql is a language - structured query language - it is not a full language. It only creates queries databases.

Weekend challenge:

Object with attribute data.time
object of post with date. Time.now
than store it in database
time stamp format
unix time stamp

Person column ? Twitter profile?

- Read more about environmental variables and how to use them - how can is use them with database?

- Params - we are using them to narrow down searches to find specific thing in our table

- What is session - >
We can store params in the session
session and cookies are similar. All the database in encrypted and stored in the browser. It is local to that browser and will stay there for as long as your code runs.

- Using sessions -> If you have a current login user which you have stored in the session.

- If the current session is nil do something if not do something else. That would have been sorted in a session.

- Having a class instance variable which returns a class is useful but might be over engineering in some contexts.

- Diagrams -> Hack.md? markdown editor

- relational databases ->
1:1 ->
1: many -> chitter
user might have many relationships with the post.
many: many -> one hash can be on many post and many post can have the same hash

local key -> local to the current table

foreign keys -> in the context of our post table in the reference of user table that would be a foreign key . They are unique within their table but not in the large context. Identifier of different keys in different tables.
