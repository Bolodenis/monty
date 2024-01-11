<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>0x00. AirBnB clone - The console</title>
</head>
<body>

    <h1>0x00. AirBnB clone - The console</h1>

    <h2>Background Context</h2>
    <p>Welcome to the AirBnB clone project!</p>
    <img src="C:\Users\hp\Downloads" alt="Example Image">

    <p>Before starting, please read the AirBnB concept page.</p>

    <h3>First step: Write a command interpreter to manage your AirBnB objects.</h3>
    <p>This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…</p>

    <p>Each task is linked and will help you to:</p>
    <ul>
        <li>Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances</li>
        <li>Create a simple flow of serialization/deserialization: Instance &lt;-&gt; Dictionary &lt;-&gt; JSON string &lt;-&gt; file</li>
        <!-- Add more list items as needed -->
    </ul>

    <h2>What’s a command interpreter?</h2>
    <p>Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:</p>

    <ul>
        <li>Create a new object (ex: a new User or a new Place)</li>
        <li>Retrieve an object from a file, a database etc…</li>
        <li>Do operations on objects (count, compute stats, etc…)</li>
        <li>Update attributes of an object</li>
        <li>Destroy an object</li>
    </ul>

    <h2>Usage</h2>
    <p>The console works both in interactive mode and non-interactive mode, much like a Unix shell. It prints a prompt (hbnb) and waits for the user for input.</p>

    <table>
        <thead>
            <tr>
                <th>Command</th>
                <th>Example</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Run the console</td>
                <td>./console.py</td>
            </tr>
            <tr>
                <td>Quit the console</td>
                <td>(hbnb) quit</td>
            </tr>
            <tr>
                <td>Display the help for a command</td>
                <td>(hbnb) help &lt;command&gt;</td>
            </tr>
            <tr>
                <td>Create an object (prints its id)</td>
                <td>(hbnb) create &lt;class&gt;</td>
            </tr>
            <tr>
                <td>Show an object</td>
                <td>(hbnb) show &lt;class&gt; &lt;id&gt; or (hbnb) &lt;class&gt;.show(&lt;id&gt;)</td>
            </tr>
            <tr>
                <td>Destroy an object</td>
                <td>(hbnb) destroy &lt;class&gt; &lt;id&gt; or (hbnb) &lt;class&gt;.destroy(&lt;id&gt;)</td>
            </tr>
            <tr>
                <td>Show all objects, or all instances of a class</td>
                <td>(hbnb) all or (hbnb) all &lt;class&gt;</td>
            </tr>
        </tbody>
    </table>

    <h2>GitHub</h2>
    <p>There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.</p>

    <h2>More Info</h2>
    <h2>Execution</h2>
    <p>Your shell should work like this in interactive mode:</p>

    <pre>
        <code>
            $ ./console.py
            (hbnb) help

            Documented commands (type help &lt;topic&gt;):
            ========================================
            EOF  help  quit

            (hbnb)
            (hbnb)
            (hbnb) quit
            $
        </code>
    </pre>

    <p>But also in non-interactive mode: (like the Shell project in C)</p>

    <pre>
        <code>
            $ echo "help" | ./console.py
            (hbnb)

            Document

