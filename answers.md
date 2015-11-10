# Q0: Why is this error being thrown?
Pokemon is undefined in the Home Controller.
# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
All of them are randomly chosen from the database Pokemons.
# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
It defines a button element that goes to capture_path as a PATCH request on click.
# Question 3: What would you name your own Pokemon?
I would name it Yolo, which has 3 moves - swag, obey and twerk.
# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
I passed trainer_path current_trainer to redirect_to. This sets the id to the id of the current trainer. You can just use current_trainer, you don't need to use a path
# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
For the flash hashmap, the error key would map to the errors variable for pokemon, formatted using full_messages and to_sentence.
# Give us feedback on the project and decal below!
Useful as such, like the Pokemon concept haha.
# Extra credit: Link your Heroku deployed app
https://github.com/dhruvilbadani/proj1
