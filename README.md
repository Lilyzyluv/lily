# html
form pendaftaran
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pendaftaran</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 claas ="highlight">FORMULIR PENDAFTARAN</h1>
    <p class ="highlight">Selamat datang di formulir pendaftaran, Silahkan isi data diri dengan benar!</p>
    <form action="proses.php" method="post">
        <table>
            <tr>
                <td>Nama Lengkap</td>
                <td>:</td>
                <td><input type="text" name="nama_lengkap"></td>
            </tr>
            
            <tr>
                <td>Tempat Lahir</td>
                <td>:</td>
                <td><input type="text" name="tempat_lahir"></td>
            </tr>

            <tr>
                <td>Pekerjaan</td>
                <td>:</td>
                <td><input type="text" name="pekerjaan"></td>     
            </tr>

            <tr>
                <td>Agama</td>
                <td>:</td>
                <td>
                    <select name="agama">
                        <option></option>
                        <option>Islam</option>
                        <option>Kristen</option>
                        <option>Budha</option>
                        <option>Hindu</option>
                        <option>Protestan</option>
                    </select>
                </td>
            </tr>
        
            <tr>
                <td>Pendidikan</td>
                <td>:</td>
                <td>
                    <select name="pendidikan">
                        <option></option>
                        <option>SD</option>
                        <option>SMP</option>
                        <option>SMA</option>
                        <option>SMK</option>
                        <option>S1</option>
                        <option>S2</option>
                        <option>S3</option>
                    </select>
                </td>
            </tr>
        
            <tr>
                <td>Tanggal Lahir</td>
                <td>:</td>
                <td><input type="date" name="tanggal_lahir"></td>
            </tr>
        
            <tr>
                <td>Jenis Kelamin</td>
                <td>:</td>
                <td>
                    <input type="radio" name="jenis_kelamin" value="pria"/>Pria
                    <input type="radio" name="jenis_kelamin" value="perempuan"/>Perempuan
                </td>
            </tr>
        
            <tr>
                <td>Alamat</td>
                <td>:</td>
                <td><textarea name="alamat" cols="22" rows="3"></textarea></td>
            </tr>
        
            <tr>
                <td>No Hp</td>
                <td>:</td>
                <td><input type="number" name="no_hp"></td>
            </tr>
        
            <tr>
                <td>Kota</td>
                <td>:</td>
                <td>
                    <select name="kota">
                        <option></option>
                        <option>Bogor</option>
                        <option>Jakarta</option>
                        <option>Bekasi</option>
                        <option>Tangerang</option>
                        <option>Depok</option>
                        <option>Cikarang</option>
                        <option>Banten</option>
                    </select>
                </td>
            </tr>
        
            <tr>
                <td>Status</td>
                <td>:</td>
                <td>
                    <select name="status">
                        <option></option>
                        <option>Lajang</option>
                        <option>Menikah</option>
                    </select>
                </td>
            </tr>
           
            <tr>
                <td>Email:</td>
                <td>:</td>
                <td><input type="email" id="email" name="email" required></td>
            </tr>
            
            <tr>
                <td>&nbsp;</td>
                <td>&nbsp;</td>
                <td>
                    <input type="submit" name="submit" value="Simpan"/>
                    <input type="reset" name="reset" value="Batal" />
                </td>
            </tr>
        </table>
    </form>
</body>
</html>
