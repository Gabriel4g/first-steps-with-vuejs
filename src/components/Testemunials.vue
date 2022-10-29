<template>
    <section id="testemunials">
        <h2>What our customers are <br> saying...</h2>

        <div class="cards-testemunials">
            <div class="card-testemunial">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisci elit, sed eiusmod tempor incidunt ut labore et dolore magna aliqua. 
                    Ut enim ad minim veniam, quis nostrum exercitationem ulla.
                </p>

                <span class="name-testemunia">Jonh Doe</span>
            </div>

            <div class="card-testemunial">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisci elit, sed eiusmod tempor incidunt ut labore et dolore magna aliqua. 
                    Ut enim ad minim veniam, quis nostrum exercitationem ulla.
                </p>

                <span class="name-testemunia">Jonh Doe</span>
            </div>

            <div class="card-testemunial">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisci elit, sed eiusmod tempor incidunt ut labore et dolore magna aliqua. 
                    Ut enim ad minim veniam, quis nostrum exercitationem ulla.
                </p>

                <span class="name-testemunia">Jonh Doe</span>
            </div>
        </div>
    </section>
</template>

<style scoped>
    section#testemunials {
        display: flex;
        flex-direction: column;
        gap: 10rem;
        margin-bottom: 100px;
    }

    #testemunials h2 {
        font-size: 6rem;
        font-family: 'Roboto', sans-serif;
        font-weight: 500;
        color: #F8982C;
    }

    #testemunials .cards-testemunials {
        display: flex;
        gap: 2rem;
    }

    #testemunials .cards-testemunials .card-testemunial {
        position: relative;
        height: 280px;
        width: 40rem;
        padding: 40px 25px;
        background: #232323;
        border-radius: 20px;
        border: 1px solid #F8982C;
        display: flex;
        justify-content: center;
    }

    #testemunials .cards-testemunials .card-testemunial p {
        font-size: 2rem;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        color: #EAEAEA;
        line-height: 24px;
    }

    #testemunials .cards-testemunials .card-testemunial span {
        position: absolute;
        bottom: 40px;
        right: 35px;
        font-size: 2.5rem;
        font-family: 'Roboto', sans-serif;
        color: #EAEAEA;
    }
</style>

<script>

</script>