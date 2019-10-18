# surveyForm.html
HTML code for Survey Form
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" type="text/css" href="SurveyForm.css">

    <title>Survey Page</title>
</head>

<body>
    <header>
        <h1 id="title">Survey Form</h1>
    </header>
    <div id="form-outer">
        <p id="description">
            Let us know how we can improve ElearningCamp
        </p>
        <form id="survey-form" method="GET" action="https://crossorigin.me/https://freecodecamp.com">
            <div class="rowTab">
                <div class="labels">
                    <label id="name-label" for="name">* Name: </label>
                </div>
                <div class="rightTab">
                    <input autofocus type="text" name="name" id="name" class="input-field" placeholder="Enter your name" required>
                </div>
            </div>
            <div class="rowTab">
                <div class="labels">
                    <label id="email-label" for="email">* Email: </label>
                </div>
                <div class="rightTab">
                    <input type="email" name="email" id="email" class="input-field" required placeholder="Enter your Email">
                </div>
            </div>
            <div class="rowTab">
                <div class="labels">
                    <label id="number-label" for="age">* Age: </label>
                </div>
                <div class="rightTab">
                    <input type="number" name="age" id="number" min="1" max="125" class="input-field" placeholder="Age">
                </div>
            </div>
            <div class="rowTab">
                <div class="labels">
                    <label for="currentPos">Which option best describes your current role?</label>
                </div>
                <div class="rightTab">
                    <select id="dropdown" name="currentPos" class="dropdown">
      <option disabled value>Select an option</option>
      <option  value="student">Student</option>
      <option value="job">Full Time Job</option>
      <option value="learner">Full Time Learner</option>
      <option value="preferNo">Prefer not to say</option>
      <option value="other">Other</option>
    </select>
                </div>
            </div>
            <div class="rowTab">
                <div class="labels">
                    <label for="userRating">* How likely is that you would recommend freeCodeCamp to a friend?</label>
                </div>
                <div class="rightTab">
                    <ul style="list-style: none;">
                        <li class="radio"><label>Definitely<input name="radio-buttons" value="1"  type="radio" class="userRatings" ></label></li>
                        <li class="radio"><label>Maybe<input name="radio-buttons" value="2"  type="radio" class="userRatings" ></label></li>
                        <li class="radio"><label>Not sure<input name="radio-buttons" value="3"  type="radio" class="userRatings" ></label></li>
                    </ul>
                </div>
            </div>
            <div class="rowTab">
                <div class="labels">
                    <label for="most-like">What do you like most in ELC: </label>
                </div>
                <div class="rightTab">
                    <select id="most-like" name="mostLike" class="dropdown">
      <option disabled selected value>Select an option</option>
      <option value="challenges">Challenges</option>
      <option value="projects">Projects</option>
      <option value="community">Community</option>
      <option value="openSource">Open Source</option>
    </select>
                </div>
            </div>
            <div class="rowTab">
                <div class="labels">
                    <label for="preferences">Things that should be improved in the future<br>(Check all that apply): </label>
                </div>
                <div class="rightTab">
                    <ul id="preferences" style="list-style: none;">
                        <li class="checkbox"><label><input name="prefer" value="1" type="checkbox" class="userRatings">Front-end Projects</label></li>
                        <li class="checkbox"><input name="prefer" value="2" type="checkbox" class="userRatings">Back-end Projects</li>
                        <li class="checkbox"><label><input name="prefer" value="3" type="checkbox" class="userRatings">Data Visualization</label></li>
                        <li class="checkbox"><label><input name="prefer" value="4" type="checkbox" class="userRatings">Challenges</label></li>
                        <li class="checkbox"><label><input name="prefer" value="5" type="checkbox" class="userRatings">Open Source Community</label></li>
                        <li class="checkbox"><label><input name="prefer" value="6" type="checkbox" class="userRatings">Gitter help rooms</label></li>
                        <li class="checkbox"><label><input name="prefer" value="7" type="checkbox" class="userRatings">Videos</label></li>
                        <li class="checkbox"><label><input name="prefer" value="8" type="checkbox" class="userRatings">City Meetups</label></li>
                        <li class="checkbox"><label><input name="prefer" value="9" type="checkbox" class="userRatings">Wiki</label></li>
                        <li class="checkbox"><label><input name="prefer" value="10" type="checkbox" class="userRatings">Forum</label></li>
                        <li class="checkbox"><label><input name="prefer" value="10" type="checkbox" class="userRatings">Additional Courses</label></li>
                    </ul>
                </div>
            </div>
            <div class="rowTab">
                <div class="labels">
                    <label for="comments">Any Comments or Suggestions?</label>
                </div>
                <div class="rightTab">
                    <textarea id="comments" class="input-field" style="height:50px;resize:vertical;" name="comment" placeholder="Enter your comment here..."></textarea>
                </div>
            </div>
            <button id="submit" type="submit">Submit</button>
        </form>
    </div>
</body>

</html>
