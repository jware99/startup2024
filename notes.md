this stores all of the notes that you can use on the midterm and the final
- git pull -> pull repositories last changes from github
- make changes to code
- git commit -> commit that changes that you made
- git push -> pushes changes to github
- A GitHub fork creates a copy of a repository on GitHub. It's typically used to experiment with or contribute to open source projects. While forking copies the repo to GitHub, you can then download it to your local development environment. Forks stay linked to the original repository, making it easy to get updates and merge them. You can also use a fork to suggest changes to the original project by creating a pull request.

- echo - Output the parameters of the command
- cd - Change directory
- mkdir - Make directory
- rmdir - Remove directory
- rm - Remove file(s)
- mv - Move file(s)
- cp - Copy files
- ls - List files
- curl - Command line client URL browser
- grep - Regular expression search
- find - Find files
- top - View running processes with CPU and memory usage
- df - View disk statistics
- cat - Output the contents of a file
- less - Interactively output the contents of a file
- wc - Count the words in a file
- ps - View the currently running processes
- kill - Kill a currently running process
- sudo - Execute a command as a super user (admin)
- ssh - Create a secure shell on a remote computer
- scp - Securely copy files to a remote computer
- history - Show the history of commands
- ping - Check if a website is up
- tracert - Trace the connections to a website
- dig - Show the DNS information for a domain
- man - Look up a command in the manual

html file -> head -> title -> First HTML
html file -> body
lang = attribute
"en" = attribute value
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>First HTML</title>
    </head>
<body>
    <p>Hello world</p>

<img alt="beach"
    src="https://..."/>
</body>
</html>

<a href="https://c260.cick/profile.png>
<a href="profile.png>

div - a block division of content
span - an inline span of content
h<1-9> - text heading. From h1, the highest level, down to h9, the lowest level
p - a paragraph of text
table - table
ol, ul - ordered or unordered list
a - anchor to a hyperlink
img - graphical image reference

<div class="bouncing-ball"></div>
<div id="ground"></div>
<div id="shadow"></div>

form -> Input container and submission (<form action="form.html" method="post">)
fieldset -> Labeled input grouping (<fieldset> ... </fieldset>)
input -> Multiple types of user input (<input type="" />)
select -> Selection dropdown (<select><option>1</option></select>)
optgroup -> Grouped selection dropdown (<optgroup><option>1</option></optgroup>)
option -> Selection option (<option selected>option2</option>)
textarea -> Multiline text input (<textarea></textarea>)
label -> Individual input label (<label for="range">Range: </label>)
output -> Output of input (<output for="range">0</output>)
meter -> Display value with a known range (<meter min="0" max="100" )value="50"></meter>

Here is an example of a simple form that submits the value of a textarea element.

<form action="submission.html" method="post">
  <label for="ta">TextArea: </label>
  <textarea id="ta" name="ta-id">
Some text
  </textarea>
  <button type="submit">Submit</button>
</form>