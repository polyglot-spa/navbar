<script>
    import { Dropdown } from "bootstrap";
    import "./css/custom.css";
    import owlSvgSrc from "./assets/images/owl-svgrepo-com.svg"
</script>

<style>
    .bi {
        vertical-align: -.125em;
        fill: currentColor;
    }
    #owl-logo {
        width: 90px;
    }
    @font-face {
        font-family: "Bananas-Personal";
        src: url("http://localhost:5002/assets/fonts/BananasPersonalUse.ttf") format("truetype");
    }
    #header-text {
        font-family: Bananas-Personal;
        font-size: 75px !important;
        letter-spacing: 10px;
    }
    #primary-header {
        background-color: #e5c7ca;
    }
</style>


<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="/">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Github Repo</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Micro-frontends
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <li><a class="dropdown-item" href="react">React Application</a></li>
                        <li><a class="dropdown-item" href="vue">Vue Application</a></li>
                        <li><a class="dropdown-item" href="angular">Angular Application</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Internet OFF Switch</a>
                </li>
            </ul>
            <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
        </div>
    </div>
</nav>
<header id="primary-header" class="py-0 mb-1 border-bottom">
    <div class="container d-flex flex-wrap justify-content-center">
        <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">
            <img id="owl-logo" src={owlSvgSrc} alt=""/>
            <span id="header-text" class="fs-4">Polyglot SPA</span>
        </a>
    </div>
</header>
