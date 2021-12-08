<!-- INSERT INTO `notes` (`sno`, `title`, `desc`, `tstamp`) VALUES (NULL, 'Learn Php', 'Delete after learned', current_timestamp()); -->
<?php
// connecting database
    $servername = "localhost";
    $username = "root";
    $pass = "";
    $database = "notes";
    $insert = false;
    $update=false;
    $delete=false;
    $con = mysqli_connect($servername, $username, $pass, $database);
    if (!$con) {
        die("Sorry we failed to connect due to " . mysqli_connect_error());
    }
    // echo $_POST['snoEdit'];
    // echo $_GET['update'];
    // exit();
if(isset($_GET['delete'])){
    $sno=$_GET['delete'];
    $delete=true;
    $sql="Delete from `notes` where `sno`='$sno' ";
    $res=mysqli_query($con,$sql);
}
if ($_SERVER['REQUEST_METHOD'] == 'POST') {
    if(isset($_POST['snoEdit'])){
        // update
        // echo "Yes";
        // exit();
        $sno=$_POST['snoEdit'];
        $title = $_POST["titleEdit"];
        $desc = $_POST["descEdit"];
        $sql = "Update  `notes` set `title`= '$title' , `desc`='$desc' where `notes`.`sno`=$sno ";
        $res = mysqli_query($con, $sql);
        if (!$res)
            echo "The updation was not successful due to " . mysqli_error($con);
        else
            $update = true;
    }
    else
    {
        $title = $_POST["title"];
        $desc = $_POST["desc"];
        $sql = "Insert into `notes` (`title`,`desc`) values('$title','$desc')";
        $res = mysqli_query($con, $sql);
        if (!$res)
            echo "The insertion was not successful due to " . mysqli_error($con);
        else
            $insert = true;
    }
}
?>
<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
     integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
    <link rel="stylesheet" href="//cdn.datatables.net/1.11.3/css/jquery.dataTables.min.css">
    
    <title>iNotes - PHP - CRUD</title>
    
</head>

<body>
    <!-- Edit modal -->
<!-- <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#editModal">
 Edit modal
</button> -->

<!--Edit  Modal -->
<div class="modal fade" id="editModal" tabindex="-1" aria-labelledby="editModal" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="editModal">Edit this Note</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
    <form action="index.php" method="post">
      <div class="modal-body">
          <input type="hidden" name="snoEdit" id="snoEdit">
            <div class="mb-3">
                <label for="title" class="form-label">Note Title</label>
                <input type="text" class="form-control" id="titleEdit" name="titleEdit" aria-describedby="emailHelp">
            </div>
            <div class="mb-3">
                <label for="desc" class="form-label">Note Description</label>
                <textarea class="form-control" id="descEdit" name="descEdit"></textarea>
            </div>
            <!-- <button type="submit" class="btn btn-primary">Update Note</button> -->
        </div>
        <div class="modal-footer d-block mr-auto">
            <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
            <button type="submit" class="btn btn-primary">Update Note</button>
        </div>
    </form>
    </div>
  </div>
</div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"><img src="inotes.jpg" height="36px" alt="inotes" srcset=""></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link disabled">Contact Us</a>
                    </li>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" />
                    <button class="btn btn-outline-success" type="submit">
                        Search
                    </button>
                </form>
            </div>
        </div>
    </nav>
    <?php
    if ($insert)
        echo "<div class='alert alert-success alert-dismissible fade show' role='alert'>
            <strong>Success!!</strong> Your note has been entered successfully.
            <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
          </div>";
    ?>
    <?php
    if ($delete)
        echo "<div class='alert alert-success alert-dismissible fade show' role='alert'>
            <strong>Success!!</strong> Your note has been deleted successfully.
            <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
          </div>";
    ?>
    <?php
    if ($update)
        echo "<div class='alert alert-success alert-dismissible fade show' role='alert'>
            <strong>Success!!</strong> Your note has been updated successfully.
            <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
          </div>";
    ?>
    <div class="container my-4">
        <h2>Add a Note in iNotes</h2>
        <form action="index.php" method="post">
            <div class="mb-3">
                <label for="title" class="form-label">Note Title</label>
                <input type="text" class="form-control" id="title" name="title" aria-describedby="emailHelp">
            </div>
            <div class="mb-3">
                <label for="desc" class="form-label">Note Description</label>
                <textarea class="form-control" id="desc" name="desc"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Add a Note</button>
        </form>
    </div>
    <div class="container my-4">

        <table class="table" id="myTable">
            <thead>
                <tr>
                    <th scope="col">Sr No.</th>
                    <th scope="col">Title</th>
                    <th scope="col">Description</th>
                    <th scope="col">Actions</th>
                </tr>
            </thead>
            <tbody>
                <?php
                $sql = "Select * from `notes` ";
                $res = mysqli_query($con, $sql);
                $index=1;
                while ($row = mysqli_fetch_assoc($res)) {
                    echo "
                    <tr>
                        <th scope='row'>" . $index++ . "</th>
                        <td>" . $row['title'] . "</td>
                        <td>" . $row['desc'] . "</td>
                        <td>
                            <button class='edit btn btn-sm btn-primary' id=".$row['sno'].">Edit</button>
                            <button class='delete btn btn-sm btn-primary' id=d".$row['sno'].">Delete</button>
                        </td>
                    </tr>";
                    // echo $row['sno'] . " Title is " . $row['title'] . " Desc is " . $row['desc'];
                    // echo "<br>";
                    
                }
                ?>
            </tbody> 
        </table>
    </div>
    <hr>
    <!-- Optional JavaScript; choose one of the two! -->
    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://code.jquery.com/jquery-3.6.0.slim.js" 
    integrity="sha256-HwWONEZrpuoh951cQD1ov2HUK5zA5DwJ1DNUXaM6FsY=" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" 
    integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    <script src="//cdn.datatables.net/1.11.3/js/jquery.dataTables.min.js"></script>
    <script>
        $(document).ready( function () {
        $('#myTable').DataTable();
        } );
    </script>
    <script>
        edits=document.getElementsByClassName('edit');
        Array.from(edits).forEach((element)=>{
            element.addEventListener("click",(e)=>{
                console.log("edit",e.target.parentNode.parentNode);
                tr=e.target.parentNode.parentNode;
                title=tr.getElementsByTagName("td")[0].innerText;
                desc=tr.getElementsByTagName("td")[1].innerText;
                console.log(title,desc);
                titleEdit.value=title;
                descEdit.value=desc;
                $('#editModal').modal('toggle');
                snoEdit.value=e.target.id; 
                console.log(e.target.id);
            })
        })

        deletes=document.getElementsByClassName('delete');
        Array.from(deletes).forEach((element)=>{
            element.addEventListener("click",(e)=>{
                console.log("delete",e.target.parentNode.parentNode);
                sno=e.target.id.substr(1,);
                if(confirm("Do you want to delete this note?")){
                    console.log("Yes");
                    window.location=`index.php?delete=${sno}`;
                }
                else console.log("No");
                // console.log(title,desc);
                // titleEdit.value=title;
                // descEdit.value=desc;
                // $('#editModal').modal('toggle');
                // snoEdit.value=e.target.id; 
                // console.log(e.target.id);
            })
        })
    </script>
    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
</body>

</html>
