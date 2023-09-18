<!DOCTYPE html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="device-width, initial-scale = 1.0">
    <link rel="shortcut icon" href="edit.svg">
</head>

<body>
    <p>
    <form>
        <lable for="firstname"> First Name </lable>
        <input type="text" name="firstname" required>
        <br>
        <lable for="lastname"> Last Name </lable>
        <input type="text" name="lasttname" required>
        <br>
        <labee for="sex"> SEX :</labee>
        <input type="radio" name="sex" id="male" value="male">
        <lable for="male"> Male</lable>
        <input type="radio" name="sex" id="female" value="female">
        <lable for="female"> Female</lable>
        <input type="radio" name="sex" id="rathernotsay" value="rathernotsay">
        <lable for="rathernotsay"> Rather Not Say</lable>
        <br>
        <label for="planet">Planet:</label>
        <select name="planet" id="planet">
            <option value="earth"> earth</option>
            <option value="mars"> mars</option>
            <option value="venus"> venus</option>
        </select>
        <br>
        <lable for="reviewMessage">Review Message </lable><br>
        <lable for="email"> email </lable>
        <input type="email" name="email" required>
        <br>
        <lable for="password"> password </lable>
        <input type="password" name="password" required>
        <br>
    </form>
    </p>
</body>
