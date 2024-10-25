# website-builder
name = "Apka Naam"

html_content = f"""
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{name}'s Website</title>
</head>
<body>
    <h1>Welcome to {name}'s Website</h1>
    <p>This is a simple website created using Python.</p>
</body>
</html>
"""

with open("index.html", "w") as file:
    file.write(html_content)

print("Website 'index.html' successfully created!")
