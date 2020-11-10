<template>
    <div>
        <div>
            <div class="upperNavbar">75TL ve üzeri ÜCRETSİZ KARGO!</div>
        <div  >
            <b-navbar class="center" toggleable="sm" type="light" variant="light">
            <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
            <img class="logo" src="https://kahhve.com/zeplin/img/logo_mini.png" alt="">

           <!-- <b-navbar-brand>Kahve.Com</b-navbar-brand>
                <b-navbar type="light" variant="light">
                    <b-nav-form>
                        <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
                        <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
                    </b-nav-form>
                </b-navbar>-->
            <!-- Right aligned nav items -->
            <b-navbar-nav class="menuItemPadding">
                    <b-nav-item class="menuItems">KAHVELER</b-nav-item>
                    <b-nav-item class="menuItems">EKİPMAN & AKSESUARLAR</b-nav-item>
                    <b-nav-item class="menuItems">TANIŞMA SETLERİ</b-nav-item>
                    <b-nav-item class="menuItems">MARKALAR</b-nav-item>
                    <b-nav-item class="kultur">KÜLTÜR</b-nav-item>
                    <b-nav-item class="menuItems">HEDİYELİKLER</b-nav-item>
                </b-navbar-nav>
                <b-navbar-nav class="ml-auto">
                    <b-nav-item class="menuItems">GİRİŞ</b-nav-item>
                    <img src="https://www.iconsdb.com/icons/preview/orange/search-12-xxl.png" alt="">
                    <b-nav-item href="https://www.iconsdb.com/icons/preview/orange/search-12-xxl.png"></b-nav-item>
                </b-navbar-nav>
        </b-navbar>
        </div>
        </div>
        
        
        
    </div>
</template>

<script>
export default {

}
</script>

<style>

    
    .logo{
        width: 90px;
    }

    .upperNavbar{
        background-color:#C65800;
        color: wheat;
        text-align: center;
    }

    .firstdiv{
        width: 200px;
    }

    .menuItems{
        color: #603813;
        font-size: 18px;
        font-family: sans-serif;
    }

    .kultur{
        color: #C65800;
        font-weight: bold;
        font-size: 18px;
        font-family: sans-serif;
    }

    .center{
        text-align: center;
        align-items: center;
        padding-left: 500px;
    }

    .menuItemPadding{
        padding: 20px;
    }
</style>