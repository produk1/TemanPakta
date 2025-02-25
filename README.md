<background>![Screenshot 2025-02-19 150716](https://github.com/user-attachments/assets/5ef2f4f6-6234-4197-8bec-c337c7130d19)
<DOCTYPE html>
<html lang="en">
  <head>
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
        <div class="col-lg-20 col-md-12 col-sm-12 col-xs-12">
          <h3 class="text-center mb-4">SISTEM LAYANAN INFORMASI PENERBITAN AKTA CERAI<h3>
            <h3 class="text-center mb-4">(TEMAN PAKTA)</h3>
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
            title: "Nomor",
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

      ],
      rowId: "Nomor Perkara",
      liveAjax: true,
    });
  });
    </script>
    <body>
<html>
