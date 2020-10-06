To load navbar, put this in the header:

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>


Put this in body:

<!--Navigation bar-->
<div id="nav-placeholder"></div>

<script>
    $(function () {
        $("#nav-placeholder").load("navbar.html");
    });
</script>
<!--end of Navigation bar-->
