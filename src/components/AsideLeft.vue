<template>
    <div class="sidebar_left">
        <!-- logo -->
        <div class="logo">
            <img src="@/assets/img/gallery.png" alt="#">
        </div>
        
        <!-- search -->
        <form class="search">
            <button>
                <img src="@/assets/img/search.png" alt="">
            </button>
            <input type="text">
        </form>

        <!-- menu -->
        <div class="menu">Menu</div>
        <ul class="menu_lists">
            <li>
                <a href="#">
                <img src="@/assets/img/Overview.png" alt=""> Overview
                </a>
            </li>
            <li>
                <a href="#">
                <img src="@/assets/img/Product.png" alt=""> Overview
                </a>
            </li>
            <li>
                <a href="#">
                <img src="@/assets/img/Marketing.png" alt=""> Overview
                </a>
            </li>
            <li>
                <a href="#">
                <img src="@/assets/img/Seles.png" alt=""> Overview
                </a>
            </li>
            <li>
                <a href="#">
                <img src="@/assets/img/Cloud.png" alt=""> Overview
                </a>
            </li>
            <li>
                <a href="#">
                <img src="@/assets/img/Settings.png" alt=""> Overview
                </a>
            </li>
        </ul>

        <!-- Profil -->
        <div class="profil">
            <div class="profil_">Profile</div>
            <div class="profil_data">
                <img src="@/assets/img/Account.png" alt="">
                <div class="person">
                    <div class="person_name">Kamolbek</div>
                    <div class="person_admin">Admin Account</div>
                </div>
                <img src="@/assets/img/DotsThree.png" alt="">
            </div>
        </div>

        <!-- Button -->
        <a href="#" class="logout">
            <img src="@/assets/img/Logout.png" alt="">
            Logout
        </a>
    </div>
</template>



<script>
    export default {

    }
</script>



<style>
    .logo{
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 15px 83px;
        width: 191px;
        height: 53px;
    }
    .menu_lists{
        text-decoration: none;
        opacity: 0.3;
    }
    .menu_lists a:hover{
        opacity: unset;
    }
    .logout{
        background: #8649FC;
        height: 83px;
    }
</style>