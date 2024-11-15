<template>
    <div>
        <div class="card bg-dark text-white" style="border-radius: 0;">
            <img class="card-img main-section-img" src="/assets/images/main-image.jpg" alt="Card image">
            <div class="dark-overlay"></div>
            <div class="card-img-overlay card-img-text">
                <div class="moto-container" style="display: flex; flex-direction: column;">
                    <div class="moto-card">
                        <div class="moto-title-size">
                            <h4 class="card-title main-moto">Funny Excavatoare</h4>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text moto-description">Destinația ta principală pentru excavatoare mici de înaltă performanță.</p>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text moto-description">Suntem aici pentru a-ți oferi echipamente de top care să îți îndeplinească toate nevoile de excavare.</p>
                        </div>    
                    </div>
                    <div class="contact-button">
                        <a href="tel:+40743369495">
                            <button class="top-section-button"> 
                                <Icon name="material-symbols:call" size="1.7rem" style="margin-right: 0.7rem;" /> 
                                <span>Contactați-ne</span>
                            </button>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <div id="aboutus" class="section-content" style="padding-top: 2.5rem;">
            <div class="text-content">
                <h1 class="page-title">Despre noi</h1>
                <p class="simple-text">
                    La Funny Excavatoare, ne mândrim cu furnizarea de soluții inovatoare și fiabile pentru toate tipurile de lucrări de excavare. Gama noastră variată de excavatoare mici este concepută pentru a oferi maximă eficiență și durabilitate, asigurându-te că fiecare proiect, oricât de mic sau mare, este realizat cu succes.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>De ce noi?</b>
                </p>
                <p class="simple-text" style="margin-left: 2rem;">
                    <b>• Calitate Superioară:</b> Toate excavatoarele noastre sunt fabricate cu cele mai înalte standarde de calitate și siguranță. Ne asigurăm că fiecare echipament este testat riguros înainte de a ajunge la tine.
                </p>
                <p class="simple-text" style="margin-left: 2rem;">
                    <b>• Eficiență și Performanță:</b> Excavatoarele noastre sunt echipate cu tehnologie de ultimă generație pentru a oferi performanțe excelente în toate condițiile de lucru.
                </p>
                <p class="simple-text" style="margin-left: 2rem;">
                    <b>• Asistență și Suport:</b> Echipa noastră de experți este aici pentru a-ți oferi suportul necesar în alegerea și utilizarea excavatorului potrivit pentru nevoile tale. Oferim consultanță gratuită și servicii post-vânzare de încredere.
                </p>
            </div>
            <div class="image-container">
                <img src="/assets/images/excavator1.png" alt="Worker">
            </div>
        </div>
        <div id="products" class="card bg-dark text-white second-img-section" style="border-radius: 0;">
            <img class="card-img main-section-img" src="/assets/images/second-image.jpg" alt="Card image">
            <div class="dark-overlay"></div>
            <div class="card-img-overlay card-img-text">
                <div class="moto-container second-moto">
                    <div class="moto-card">
                        <div class="moto-title-size">
                            <h4 class="card-title main-moto">Excavatoare</h4>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text moto-description">La Funny Excavatoare, înțelegem importanța alegerii echipamentului potrivit pentru succesul proiectelor tale. De aceea, îți oferim o gamă variată de excavatoare mici, fiecare proiectat să satisfacă diverse nevoi și să ofere performanțe de excepție. Fie că ai nevoie de un excavator compact pentru lucrări de grădinărit sau unul mai robust pentru construcții industriale, avem soluția ideală pentru tine.</p>
                        </div>
                    </div>
                    <div class="moto-card">
                        <div class="moto-title-size">
                            <h4 class="card-title main-moto">Servicii</h4>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text moto-description">Ne dedicăm să oferim nu doar produse de înaltă calitate, ci și servicii complete pentru a asigura succesul proiectelor tale de excavare. Indiferent de dimensiunea sau complexitatea lucrării tale, echipa noastră de experți este aici pentru a te susține la fiecare pas. De la consultanță inițială până la întreținerea continuă a echipamentelor, ne străduim să oferim soluții personalizate și de încredere.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="contact" class="section-content">
            <div class="text-content">
                <h1 class="page-title">Contact</h1>
                <p class="simple-text">
                    La Funny Excavatoare, ne dorim să îți oferim cele mai bune soluții pentru nevoile tale de excavare și să facem fiecare proiect cât mai simplu și eficient posibil. Dacă ai întrebări, vrei să afli mai multe informații despre produsele și serviciile noastre sau ai nevoie de asistență personalizată, nu ezita să ne contactezi.
                </p>
                <p class="simple-text">
                    <b>Informații de Contact:</b>
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    • Adresă: <b>Ocna Sugatag, Strada Lunga Nr.28, Maramures</b>
                    <br>• Telefon: <a class="simple-text" href="tel:+40743369495" style="text-decoration: none;"><b>+40 743 369 495</b></a>
                    <br>• Email: <b>[]</b>
                    <br>• Website: <b>funny-excavatoare.ro</b>
                </p>
                <p class="simple-text">
                    Suntem aici pentru a te ajuta!
                </p>
            </div>
            <div class="image-container">
                <img src="/assets/images/excavator2.jpg" alt="Worker">
            </div>
        </div>
    </div>
</template>

<style scoped>
    .mobile-only {
        display: none;
    }
    .main-section-img {
        height: 600px; 
        object-fit: cover;
    }
    .second-section-img {
        height: 600px; 
        object-fit: cover;
    }
    .dark-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%; /* Full width to cover the image */
        height: 100%;
        background: linear-gradient(to right, rgb(0 0 0 / 75%), rgb(0 0 0 / 75%));
        pointer-events: none; /* Prevents interaction with the overlay */
    }
    .main-moto {
        font-size: 3rem;
        font-weight: 700;
        text-transform: uppercase;
        color: #ffc107;
    }
    .moto-description {
        font-size: 1.7rem;
    }
    .top-section-button {
        font-size: 1.5rem;
        color: #ffc107;
        background: transparent;
        border: 3px solid #ffc107;
        border-radius: 0;
        padding: 0.4rem 1.2rem;
        margin-right: 1rem;
        display: inline-flex;
        align-items: center;
    }
    .card-button-size {
        width: 100%; 
        display: flex; 
        justify-content: center;
    }
    .card-button {
        font-size: 1.5rem;
        color: black;
        background: transparent;
        border-width: 2px;
        border-color: black;
        border-radius: 10px;
        padding: 0.4rem 1.2rem;
        margin-right: 1rem;
    }
    .card-button:hover {
        color: white;
        background: black;
    }
    .card-img-text {
        padding: 3rem 5rem;
        display: flex;
        align-items: center;
    }
    .main-section {
        padding: 1rem 5rem;
    }
    .main-section-title {
        width: 100%;
        font-size: 2rem;
        font-weight: 700;
        margin-bottom: 0.5rem;
    }

    .simple-text {
        font-size: 1.2rem;
        color: rgb(54, 54, 54);
        margin-top: 0;
    }

    .small-description {
        font-size: 1.4rem;
    }

    .page-title {
        margin-bottom: 1.2rem;
    }

    .image-container {
        flex: 1;
        max-width: 500px;
        height: auto;
        overflow: hidden;
        border-radius: 5px;
    }

    .image-container img {
        max-height: 500px;
    }

    .section-content {
        display: flex;
        flex-wrap: wrap;
        gap: 2rem;
        align-items: center;
        padding: 2rem 5rem;
    }

    .text-content {
        flex: 1;
    }
    
    .feature-card {
        width: 30%;
        border-width: 3px;
        border-radius: 15px;
        border-color: #656262;
        padding: 2rem;
    }

    .contact-button {
        width: 100%; 
        margin-top: 2rem;
    }

    .moto-container {
        display: flex; 
        width: 100%;
    }

    .moto-card {
        width: 50%;
    }

    .second-moto-container {
        display: flex; 
        width: 100%;
        justify-content: center;
    }

    .second-moto-card {
        width: 70%;
    }

    .second-moto-card .main-moto {
        color: white;
    }
    .moto-title-size {
        width: 100%; 
        margin-top: 1rem;
    }

    .moto-description-size {
        width: 100%; 
        margin-top: 1rem;
    }

    .second-moto .moto-title-size {
        width: 80%; 
        margin-top: 1rem;
    }

    .second-moto .moto-description-size {
        width: 80%; 
        margin-top: 1rem;
    }

    hr {
        margin: 0 5rem;
        border: 1px solid #ccc;
    }

    @media (max-width: 768px) {
    .page-title {
        margin-bottom: 1rem;
    }
    .section-content {
      padding: 1rem 2rem;
      flex-direction: column;
        gap: 1rem;
    }
    .image-container {
      max-width: 100%;
      max-height: 300px;
    }
    .image-container img {
        width: 100%;
    }
    .second-img-section {
        max-height: 700px !important;
        height: 700px;
    }
    .second-img-section .moto-title-size{
        width: 100%;
    }
    .second-img-section .moto-description-size{
        width: 100%;
    }
    .second-img-section img{
        max-height: 700px !important;
    }
    .simple-text {
      font-size: 1rem;
    }
    .moto-container {
        flex-direction: column;
        gap: 1rem;
        text-align: center;
    }
    .moto-card {
        width: 100%;
    }
    .moto-title-size {
        width: 100%;
    }
    .main-moto {
        font-size: 2rem;
    }
    .moto-description-size {
        width: 100%;
    }
    .moto-description, .small-description {
        font-size: 1rem;
    }

    .main-section-img {
        height: 350px;
    }
    .second-section-img {
        height: 800px; 
    }
    .feature-card {
        width: 100%;
        padding: 1rem;
    }
    .card-button {
        font-size: 1.2rem;
    }
    .top-section-button {
        font-size: 1.2rem;
        margin-right: 0;
    }
    .contact-button {
        margin-top: 1rem;
        justify-content: center;
        display: flex;
    }
    .main-section {
        padding: 1rem 1rem !important;
    }
    .card-img-text {
        padding: 1rem 1rem !important;
    }
    hr {
      margin: 0 2rem;
    }
}
</style>