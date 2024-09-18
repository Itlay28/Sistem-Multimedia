<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registrasi</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
    <div class="container">
        <form action="">
            <div class="col-sm-10">
                <div class="form-group">
                    <label for="name">Nama :</label>
                    <input type="text" class="form-control" placeholder="Name" name="nama" required>
                </div>
                <div class="form-group">
                    <label for="nim">NiM :</label>
                    <input type="text" class="form-control" placeholder="nim" name="NIM" required>
                </div>
                <div class="form-group">
                    <label for="email">Email :</label>
                    <input type="email" class="form-control" placeholder="Email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="password">Password :</label>
                    <input type="password" class="form-control" placeholder="Password" name="password" required>
                </div>
                <div class="form-group">
                    <label for="jk">Jenis Kelamin :</label>
                    <select class="form-control" id="jk">
                        <option>Pria</option>
                        <option>Wanita</option>
                    </select>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </div>
        </form>
    </div>
</body>
</html>
