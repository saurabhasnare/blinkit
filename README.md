    <!-- Table Example -->
    <table border="1">
        <caption>Sample Table</caption>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
            <th>Column 3</th>
        </tr>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
            <td>Data 3</td>
        </tr>
        <tr>
            <td>Data 4</td>
            <td>Data 5</td>
            <td>Data 6</td>
        </tr>
    </table>

 <!-- Video Example -->
    <video width="640" height="480" src="https://archive.org/download/Popeye_forPresident/Popeye_forPresident_512kb.mp4" controls>
 
</video>


 <!-- iframe Example -->
<iframe src="https://archive.org/download/Popeye_forPresident/Popeye_forPresident_512kb.mp4" controls>
 
</iframe>

 <!-- Other Advanced Tags -->
    <details>
        <summary>Click to expand</summary>
        <p>Some hidden details...</p>
    </details>

<!-- progress -->
 <progress value="50" max="100"></progress>

=============================================================
https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_areamap

https://www.image-map.net/

=================================================================

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Input Types Demo</title>
</head>
<body>

<h1>HTML Input Types Demo</h1>

<form action="#" method="post">
  <label for="text-input">Text:</label>
  <input type="text" id="text-input" name="text-input" required><br><br>

  <label for="password-input">Password:</label>
  <input type="password" id="password-input" name="password-input" required><br><br>

  <label for="email-input">Email:</label>
  <input type="email" id="email-input" name="email-input" required><br><br>

  <label for="tel-input">Telephone:</label>
  <input type="tel" id="tel-input" name="tel-input" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" required><br><br>

  <label for="number-input">Number:</label>
  <input type="number" id="number-input" name="number-input" min="1" max="100" required><br><br>

  <label for="url-input">URL:</label>
  <input type="url" id="url-input" name="url-input" required><br><br>

  <label for="search-input">Search:</label>
  <input type="search" id="search-input" name="search-input"><br><br>

  <label for="date-input">Date:</label>
  <input type="date" id="date-input" name="date-input" required><br><br>

  <label for="time-input">Time:</label>
  <input type="time" id="time-input" name="time-input" required><br><br>

  <label for="datetime-local-input">Date and Time (Local):</label>
  <input type="datetime-local" id="datetime-local-input" name="datetime-local-input" required><br><br>

  <label for="month-input">Month:</label>
  <input type="month" id="month-input" name="month-input" required><br><br>

  <label for="week-input">Week:</label>
  <input type="week" id="week-input" name="week-input" required><br><br>

  <label for="color-input">Color:</label>
  <input type="color" id="color-input" name="color-input" required><br><br>

  <label for="file-input">File:</label>
  <input type="file" id="file-input" name="file-input" multiple><br><br>

  <fieldset>
    <legend>Checkbox:</legend>
    <input type="checkbox" id="checkbox-input-1" name="checkbox-input-1" value="option1">
    <label for="checkbox-input-1">Option 1</label><br>
    <input type="checkbox" id="checkbox-input-2" name="checkbox-input-2" value="option2">
    <label for="checkbox-input-2">Option 2</label><br>
    <input type="checkbox" id="checkbox-input-3" name="checkbox-input-3" value="option3">
    <label for="checkbox-input-3">Option 3</label><br><br>
  </fieldset>

  <fieldset>
    <legend>Radio:</legend>
    <input type="radio" id="radio-input-1" name="radio-input" value="option1">
    <label for="radio-input-1">Option 1</label><br>
    <input type="radio" id="radio-input-2" name="radio-input" value="option2">
    <label for="radio-input-2">Option 2</label><br>
    <input type="radio" id="radio-input-3" name="radio-input" value="option3">
    <label for="radio-input-3">Option 3</label><br><br>
  </fieldset>

  <button type="submit">Submit</button>
</form>

</body>
</html>
