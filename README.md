
<img src="https://www.pa-bengkulukota.go.id/images/banners/Logo_Header_PA.jpg" alt="Pengadilan Agama Bengkulu" width="full" height="full">
<DOCTYPE html>
<html lang="en">
  <head>
    <style>
      body {
        background-image: url('https://media.istockphoto.com/id/469389478/id/foto/konsep-keadilan-hukum-berskala-pada-latar-belakang-hijau.jpg?s=170667a&w=0&k=20&c=cgHz_VaSIm3a2dQ5SxxKPXmdRroImNOgokjO5jkTW08=');
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-size: 100% 100%;
      }
    </style>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <head>
    <link
      rel="stylesheet"
      type="text/css"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
    />
    <link
      rel="stylesheet"
      type="text/css"
      href="https://cdn.datatables.net/1.11.3/css/dataTables.bootstrap.min.css"
    />
    <link
      rel="stylesheet"
      type="text/css"
      href="https://cdn.datatables.net/fixedheader/3.2.0/css/fixedHeader.bootstrap.min.css"
    />
    <link
      rel="stylesheet"
      type="text/css"
      href="https://cdn.datatables.net/responsive/2.2.9/css/responsive.bootstrap.min.css"
    />
 
  <head>
  <body>
    <div class="container">
      <div class="row">
        <div class="col-lg-11 col-md-12 col-sm-12 col-xs-12">
          <h1 class="text-center mb-4">SISTEM  LAYANAN  INFORMASI  PENERBITAN  AKTA  CERAI<h1>
          <h1 class="text-center mb-4">(TemAN PAktA)<h1>
          <h4 class="text-center mb-4" id="AC"><h4>
          <br>
          <br>
          <table
            id="example"
            class="table table-striped table-bordered mt-4 mb-4"
            style="width: 100%"
          ></table>
          <br />
          <p id="Nomor Perkara"></p>
        <div>
      <div>
    <div>
    <script src="https://code.jquery.com/jquery-3.5.1.js"></script>
    <script src="https://cdn.datatables.net/1.11.3/js/jquery.dataTables.min.js"></script>
    <script src="https://cdn.datatables.net/1.11.3/js/dataTables.bootstrap.min.js"></script>
    <script src="https://cdn.datatables.net/fixedheader/3.2.0/js/dataTables.fixedHeader.min.js"></script>
    <script src="https://cdn.datatables.net/responsive/2.2.9/js/dataTables.responsive.min.js"></script>
    <script src="https://cdn.datatables.net/responsive/2.2.9/js/responsive.bootstrap.min.js"></script>
    <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
    <script type="text/javascript">
       $(document).ready(function () {
    $("#example").DataTable({
      ajax: "https://script.google.com/macros/s/AKfycby0QyUBgOvCfFPVma1rRzk6aGXdMZh-qOSg3ln1DckIw1dm_tkLS9Y6ii0tznDHcNLE/exec",
      columns: [
        {
            title: "No",
            data: "No",
        },
        {
            title: "Nomor Perkara",
            data: "Nomor Perkara",
        },
        {
            title: "  Status  ",
            data: "Status",
        },
        {
            data: "Nomor Akta Cerai",
            title: "Nomor Akta Cerai",
        },
        {
            data: "Penggugat / Pemohon",
            title: "Penggugat / Pemohon",
        },
        {
            data: "Tergugat / Termohon",
            title: "Tergugat / Termohon",
        },
        {
            data: "Nomor Seri",
            title: "Nomor Seri",
        },

      ],
      rowId: "Nomor Perkara",
      liveAjax: true,
    });
  });
    </script>
    <body>
<html>
