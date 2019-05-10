<template>
    <section id="main">
        <div class="container">
            <header>
              <div class="title_section">
                    <h1>Welcome to Hotel</h1>
              </div>
              <div class="desc_section">
                  <p>Semper ac dolor vitae accumsan. Cras interdum hendrerit lacinia. 
                    Phasellus accumsan urna vitae molestie interdum. Nam sed placerat libero,
                    non eleifend dolor.</p>
              </div>
            </header>  
            <div class="row">
                <div class="col-md-3">
                    <div class="card">
                        <img class="card-img-top img-fluid" src="../assets/room-1.png" alt="room">
                        <div class="card-body">
                            <h5 class="card-title">Deluxe Room</h5>
                            <p class="card-text">Privacy with more space</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img class="card-img-top img-fluid" src="../assets/room-2.png" alt="room">
                        <div class="card-body">
                            <h5 class="card-title">Double Room</h5>
                            <p class="card-text">Privacy with more space</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img class="card-img-top img-fluid" src="../assets/room-3.png" alt="room">
                        <div class="card-body">
                            <h5 class="card-title">Single Room</h5>
                            <p class="card-text">Privacy with more space</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img class="card-img-top img-fluid" src="../assets/room-4.png" alt="room">
                        <div class="card-body">
                            <h5 class="card-title">Kids Room</h5>
                            <p class="card-text">Privacy with more space</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-12">
                    <div class="btn_more">
                        <a href="#">Show more</a>
                    </div>
                </div>
            </div> 
        </div>
        <div class="container-fluid bg-services">
             <section class="services">
                <div class="row">
                    <div class="col-md-12">
                        <div class="title-section__services">
                            <h1>Services</h1>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="services_image">
                            <img src="../assets/service-img-1.png" alt="services">
                        </div>
                        <h1 class="title_section">
                            Free Wifi
                        </h1>
                        <p class="desc_section">
                            Our guests can use Wi-Fi for free throughout the hotel territory.
                        </p>
                    </div>
                     <div class="col-md-3">
                        <div class="services_image">
                            <img src="../assets/service-img-2.png" alt="services">
                        </div>
                        <h1 class="title_section">
                            Flat-Screen TV
                        </h1>
                        <p class="desc_section">
                            Watch your favorite channels even when you are on a business trip.
                        </p>
                    </div>
                     <div class="col-md-3">
                        <div class="services_image">
                            <img src="../assets/service-img-3.png" alt="services">
                        </div>
                        <h1 class="title_section">
                            Sofa Available
                        </h1>
                        <p class="desc_section">
                         Use a comfortable sofa if you just want to relax for a short period of time.
                        </p>
                    </div>
                     <div class="col-md-3">
                        <div class="services_image">
                            <img src="../assets/service-img-4.png" alt="services">
                        </div>
                        <h1 class="title_section">
                            Air Conditioning
                        </h1>
                        <p class="desc_section">
                            Air conditioner is available at every room of our hotel.
                        </p>
                    </div>
                </div>
            </section>     
        </div>
    </section>
</template>

<script>
export default {
    data() {
        return{

        }
    }
}
</script>
<style lang="scss">
@import "../assets/scss/_main.scss";

</style>




