<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    </head>
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
    <tittle>Pengadilan Agama Bengkulu Kelas 1A</tittle>

    <div class="container">
      <div class="row">
        <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
          <h3 class="text-center mb-4">Sistem Layanan Informasi Penerbitan Akta Cerai</h3>
          <h4 class="text-center mb-4">(TEMAN PAKTA)</h4>
          <h5 class="text-center mb-4" id="AC"></h5>
          <br>
          <br>
          <table
            id="example"
            class="table table-striped table-bordered mt-2 mb-2"
            style="width: 100%"
          ></table>
          <br />
          <br />
          <p id="Nomor Perkara"></p>
        </div>
      </div>
    </div>
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
            title: "Status",
            data: "Status",
        },
        {
            data: "Nomor Akta Cerai",
            title: "Nomor Akta Cerai",
        },
        {
            data: "Tanggal Terbit",
            title: "Tanggal Terbit",
        },
        {
            data: "Penggugat",
            title: "Penggugat",
        },
        {
            data: "Tergugat",
            title: "Tergugat",
        },
      ],
      rowId: "Nomor Perkara",
      liveAjax: true,
    });
  });
    </script>
