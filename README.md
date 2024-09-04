# Let's create a basic HTML file that includes the specifications provided by the user:
html_content = """
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kişisel Web Sayfam</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            text-align: center;
            max-width: 600px;
            padding: 20px;
            border: 2px solid #fff;
        }
        h1 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hakkımda</h1>
        <p>Buraya kendinizi tanıtan kısa bir biyografi yazısı ekleyebilirsiniz. Bu bölümde eğitim, iş tecrübeleri, ilgi alanları gibi konulardan bahsedebilirsiniz.</p>
    </div>
</body>
</html>
"""

# Save this content to an HTML file.
file_path = "/mnt/data/kisisel_web_sayfasi.html"

with open(file_path, "w") as file:
    file.write(html_content)

file_path
