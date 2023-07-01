# 6_HTML_tags_exercise_decorators
Create a decorator called tags. It should receive an HTML tag as a parameter, wrap the result of a function with the given tag and return the new result. For more clarification, see the examples below
Test Code
@tags('p')
def join_strings(*args):
    return "".join(args)
print(join_strings("Hello", " you!"))

Output
<p>Hello you!</p>
