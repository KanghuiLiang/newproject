<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light my-0 my-sm-0 sticky-top" >
        <a href="#" class="navbar-brand "><i class="fa">&#xf285;</i></a>
        <a class="navbar-brand ml-4" href="#">&nbsp;&nbsp;&nbsp;STEM</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggle" aria-controls="navbarToggle" aria-expanded="false" aria-label="Toggle navigation" >
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarToggle">
            <ul class="navbar-nav  mx-auto pull-center" align="center">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Classes</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Be our Coach</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">STEM Blog</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About Us</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#">Contact Us</a>
                </li>
            </ul>
            <ul class="navbar-nav pull-center">
                <button class="btn btn-outline-success my-2 my-sm-1 ml-2">Login</button>
                <button class="btn btn-outline-danger my-2 my-sm-1 ml-2">Sign Up</button>
            </ul>
        </div>
    </nav>
    <!-- LANDING_MEDIA -->
    <div id="home">
        <div class="greeting">
            <h1>STEM</h1>
            <h3>Knowledge is Treasure</h3>
            <div class="scrollArrow">
                <p class="scrollText"></p>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name: 'Nav'
    }
</script>
