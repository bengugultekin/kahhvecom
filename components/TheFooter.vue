<template>
    <div class="footerBackround">
        <div class="footerContent">
            <div class="infoArea">
                <div class="rowOne">
                    <span class="brandHeader">KAHHVE.COM</span>
                    
                        <p class="footerList">Hakkımızda <br> Sipariş Takip <br>Ödeme Seçenekleri <br>
                         Sık Sorulan Sorular <br> Gizlilik Politikası <br> Yasal Uyarı <br> 
                         Mesafeli Satış Sözleşmesi <br> Cayma Hakkı </p>
                        
                </div>
                <div class="rowOne">
                    <span class="brandHeader">KATEGORİLER</span>
                    <p class="footerList">Kahveler <br> Kapsül Kahveler <br> Kahve Demleme Ekipmanları <br> Moka Pot <br>
                    French Press <br> Öğütücüler <br> Filtreler <br> Soğuk Kahve <br> Yedek Parçalar <br> Aksesuarlar <br> Barista Ekipmanları <br>
                    Kettle <br> Chemex <br> Hario <br> Aeropress <br> Termos&Mug </p>
                    
                </div>
                <div class="rowOne">
                    <span class="brandHeader">MARKALAR</span>
                    <p class="footerList">Able <br> American Press <br> Bialetti <br> Bodum <br> Caffe Fresco <br> 
                    Cafflano <br> Coffee Sapiens <br> Coffeerem <br> Delter <br> Dripmaker <br> Federal Coffee <br> Hario <br>
                    KahhveCom <br> Kronotrop <br> Petra <br> Punctum Coffee <br> Shorts Coffee <br> Taft Coffee 
                    <br> Urban Grind <br> Wacaco </p>
                </div>
                <div class="rowOne">
                    <span class="brandHeader"></span>
                    <p class="footerList">Aeropress <br> Baratza <br> Bianco <br> Bravilor Bonamat <br> Caffe Vergnano
                    <br> Chemex <br> Coffeemamma <br> Cool Beans <br> Dripdrip <br> Eureka <br> Handground <br> Illy <br> Konchero <br> Motta <br>
                     Pully Caff <br> Rommelsbacher <br> Sozen Degirmenleri <br> The Dripster <br> Urban Tools</p>
                </div>
                    <div class="rowOneO">
                        
                        <div class="rowOne">
                        <span class="brandHeader">İLETİŞİM</span>
                        <p class="footerListOrange">5A GRUP MAĞAZACILIK BİLİŞİM <br> TEKNOLOJİ VE DANIŞMANLIK A.Ş.</p>
                        <p class="footerList">Evren Sitesi E Blok İçerenköy / Ataşehir / İstanbul</p>
                        <p class="footerListOrange">info@kahhve.com 0 850 522 04 94</p> 
                        <span class="brandHeader">BİZİ TAKİP EDİN</span>

                    </div>
                </div>
                
            </div>
            <div class="bottomAreaBackround">
                <div class="bottomAreaContent">
                    <div class="bottomArea">
                    <div class="bottomLeftText">
                    <p>
                        İnternette Güvenli <br> Alışveriş
                    </p>
                </div>
                
                <div class="ml-auto" >
                    <span class="copyrightText">© 2014 - 2020 kahhve.com Tüm hakları saklıdır. <br> Çağrı Merkezi: 0 (850) 522 04 94 - info@kahhve.com </span>
                </div>
                
                </div>
                </div>
                
                
            </div>
        </div>

    </div>
</template>

<script>

export default {

}
</script>

<style>
    .footerBackround{
        background-color: #EBEBEB;
    }
    .footerContainer{
        
        
        align-items: center;
        position: fixed;
        left: 0;
        bottom: 0;
        background-color: #EBEBEB;
        height: auto;
        color: white;
        width: 100%;
        align-items: center;
    }

    .footerContent{
        width: 100%;
        
        
    }

    .infoArea{
        display: flex;
        flex-direction: row;
        width: 2000px;;
        height: 600px;
        padding:20px;
        padding-left: 100px;
    }

    .rowOne{
        width: 20%;
        
        font-family: Arial, Helvetica, sans-serif;
    }
    .rowOneO{
        width: 20%;
        font-family: Arial, Helvetica, sans-serif;
        
    }

    .brandHeader{
        font-size: 18px;
        font-weight: 700;
        color: #CD5D00;
        font-family: sans-serif;
    }

    .imgkahve{
        width: 60%;
        height: 60px;
    }

    .rowTwo{
        width: 40%;
        padding: 20px;
    }

    .rowThree{
        width: 30%;
        padding: 20px;
    }

    .bottomArea{
        display: flex;
        flex-direction: row;
        
    }

    .bottomAreaText{
        padding: 30px;
    }
    .bottomAreaBackround{
        background-color: white;
    }

    .copyrightText{
        margin-top: 15px;
        font-size: 12px;
        color: gray;
        align-items: flex-end;
        padding-right: 40px;
    }

    .footerList{
        font-size: 16px;
        color: #7E5F42;
        font-family: sans-serif;
    }
    .footerListOrange{
        font-size: 16px;
        color: #CD5D00;
        font-family: sans-serif;
    }
    .bottomLeftText{
        display: flex;
        flex-direction: column;
        font-size: 16px;
        color: gray;
        align-items: left;
    }
    .bottomAreaContainer{
        display: flex;
        flex-direction: column;
        position: fixed;
        left: 0;
        bottom: 0;
        background-color: white;
        height: auto;
        width: 100%;
    }
    .bottomAreaContent{
        width: 100%;
    }
</style>