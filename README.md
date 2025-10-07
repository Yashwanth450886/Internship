<!DOCTYPE html>
<html>
    <head>
        <title> My webpage </title>
    </head>
    <body>
     <h2> Internship Form</h2>
     <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required> <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required> <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required> <br><br>

        <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone" required> <br><br>
        
        <label>Gender:</label>

        <label for="male">Male</label>
        <input type="radio" id="male" name="gender" value="male">

        <label for="female">Female</label>
        <input type="radio" id="female" name="gender" value="female"><br><br>

        <label for="age">Age:</label>
        <input type="number" id="age" name="age" min="18" max="40" required> <br><br>

        <label for="college">College:</label>
        <input type="text" id="college" name="college" required> <br><br>

        <label for="degree">Degree:</label>
        <input type="text" id="degree" name="degree" required> <br><br>

        <label for="year">Year of Study:</label>
        <input type="number" id="year" name="year" min="1" max="5" required> <br><br>

        <label for="skills">Skills:</label>
        <input type="text" id="skills" name="skills" required> <br><br>
        
        <p>Which languages do you know?</p>
        <input type="checkbox" name="C" value="on">C<br>
        <input type="checkbox" name="C++" value="on">C++<br>
        <input type="checkbox" name="Java" value="on">Java<br>
        <input type="checkbox" name="Python" value="on">Python<br>    
        <input type="checkbox" name="JavaScript" value="on">JavaScript<br> 
        
        <P>Duration of internship participation</P>
        <select name="duration">
            <option value="1 month">1 month</option>
            <option value="2 months">2 months</option>
            <option value="3 months">3 months</option>
            <option value="4 months">4 months</option>
            <option value="6 months">6 months</option>
            <option value="1 year">1 year</option>
        </select>

        <p>Upload your Resume</p>
        <input type="file" name="resume" accept=".pdf,.doc,.docx"><br><br>


        <label for="about yourself">About yourself:</label>
        <textarea name="description" rows="4" cols="50"></textarea> <br><br>

     </form> 
     <form id ="internship form">
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
    </form> 
    
    <div id="successMessage" style="color:green;">
    </div>

    <script>
        document.getElementById("internship form").addEventListener("submit", function(event){
            event.preventDefault();
            window.location.href = 'intern form.html'
        });
    </script>
    </body>

</html>

