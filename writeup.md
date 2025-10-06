# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
I learned how for loops properly work, and pulling form lists work.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
When the user types in a statement, that chat bpt will look if the statement that the user typed in matches with what the chatbot will respond with. If so the chatbot will pull form what the user said at specific index numbers and then will look through the list it was given. Depending on what the user asked, the chatbot eill then respond with an answer from the provided list it has.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
It can be used in other search related inqueries where someone has a question and need an immediate answer, similar to search engines like google. This chatbot system can be improved on by adding a bigger list, or expanding that number of differeing questions the user can ask to get similar results from the chatbot.