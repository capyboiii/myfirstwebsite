
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Documents</title>
</head>
<body>
    <form action = "index.php" method = "POST" enctype = "multipart/form-data"  >
        
        <label for = "username">username:</label> <!--<label>: Nhãn mô tả cho trường nhập liệu.
        for="username" dùng để liên kết với id="username"-->
        <input type = "text" 
        id = "username" 
        minlength = "6" maxlength = "12" required
        placeholder = "Voquocbao"><br>

        <label for = "password">password:</label>
        <input type = "password"
        id = "password"
        minlength = "6" maxlength = "12" required><br>

        <label for = "email">email:</label>
        <input  type = "email" 
        id = "email"
        placeholder = "voquocbao@gmail.com"><br>

        <label for = "phone">phone #:</label>
        <input type = "tel" 
        id = "phone"
        placeholder = "123-456-7890"
        pattern = "[0-9]{3}-[0-9]{3}-[0-9]{4}"><br>

        <label for = "bday">birthday:</label>
        <input type = "date" id = "bday"><br>

        <lable for ="quantity">quantity:</lable>
        <input type = "number" id = "quantity"
        min = "0" max = "99" value = "1"><br>

        <label for = "title">title:</label>

        <label for = "title">Mr.</label>
        <input type = "radio" id = "Mr." name = "title">
        <label for = "title">Ms.</label>
        <input type = "radio" id = "Ms." name = title>
        <label for = "title">PhD.</label>
        <input type = radio id ="PhD." name = "title"><br>

        <label for = "payment">payment:</label>
        <select id = "payment">
            <option value ="visa">visa</option>
            <option value ="mastercard">mastercard</option>
            <option value = "giftcard">giftcard</option>
        </select><br>

        <label for ="subscribe">subscribe:</label>
        <input type ="checkbox" id = "subscribe"><br>

        <label for = "comment">comment:</label>
        <textarea id = "comment" rows = "3" cols = "10"></textarea><br>

        <label for = "file">file:</label>
        <input type = "file" id = "file" accept="image/png"><br>
        <input type = "reset">
        <input type = "submit">
    </form>
    
</body>
</html>
