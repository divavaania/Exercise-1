# Exercise-1
DevC X Hactiv8 : HTML dan CSS  Latihan

<!DOCTYPE html>
<html>
  <head>
    <title>BIODATA DIRI</title>
  </head>
  <body style="background-color: chocolate">
    <div id="kepala" style="background-color:cadetblue">
      <h1 align="center" style="color: wheat">BIODATA DIRI</h1>
    </div>
    <div id="isi" style="background-color: burlywood">
      <form>
        <table align="center">
          <tr>
            <td>Nama</td>
            <td>:</td>
            <td><input type="text" value="Diva Vania Sitindaon" disabled /></td>
          </tr>
          <tr>
            <td>Tempat/Tanggal Lahir</td>
            <td>:</td>
            <td><input type="text" value="Medan/13 April 1999" disabled /></td>
          </tr>
          <tr>
            <td>Jenis Kelamin</td>
            <td>:</td>
            <td>
              <input type="radio" name="jk" value="Laki-laki" />Laki-Laki
              <input type="radio" name="jk" value="Perempuan" checked />
              Perempuan
            </td>
          </tr>
          <tr>
            <td>Agama</td>
            <td>:</td>
            <td>
              <select name="agama" disabled>
                <option value="Islam">Islam</option>
                <option value="Kristen" selected>Kristen</option>
                <option value="Katolik">Katolik</option>
                <option value="Hindu">Hindu</option>
                <option value="Buddha">Buddha</option>
              </select>
            </td>
          </tr>
          <tr>
            <td>Alamat</td>
            <td>:</td>
            <td>
              <textarea
                name="alamat"
                cols="30"
                rows="10"
                disabled
              >Jl.Sulawesi No.20</textarea>
            </td>
          </tr>
          <tr>
            <td>Nomor HP</td>
            <td>:</td>
            <td><input type="text" value="082251946310" disabled /></td>
          </tr>
        </table>
      </form>
    </div>
    <div style="background-color: cadetblue; color: wheat">
      Copyright&copy 2019 by Diva Vania Sitindaon
    </div>
  </body>
</html>
