<!DOCTYPE html>
<html lang="de">

  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!--
    - primary meta tags
  -->
    <title>NitroAutoService - Auto Wartung & Reparatur Service</title>
    <meta name="title" content="NitroAutoService - Auto Wartung & Reparatur Service">
    <meta name="description" content="Dies ist eine Fahrzeugreparatur-HTML-Vorlage von codewithsadee">

    <!--
    - favicon
  -->
    <link rel="shortcut icon" href="./favicon.svg" type="image/svg+xml">

    <!--
    - google font link
  -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@400;600;700&family=Mulish&display=swap"
      rel="stylesheet">

    <!--
    - material icon font
  -->
    <link rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@40,600,0,0" />

    <!--
    - custom css link
  -->
    <link rel="stylesheet" href="./assets/css/style.css">

    <!--
    - preload images
  -->
    <link rel="preload" as="image" href="./assets/images/hero-banner.png">
    <link rel="preload" as="image" href="./assets/images/hero-bg.jpg">

  </head>

  <body>

    <!--
    - #HEADER
  -->

    <header class="header">
      <div class="container">

        <a href="#" class="logo">
          <img src="./assets/images/logo.svg" width="128" height="63" alt="NitroAutoService Startseite">
        </a>

        <nav class="navbar" data-navbar>
          <ul class="navbar-list">

            <li>
              <a href="#" class="navbar-link">Startseite</a>
            </li>

            <li>
              <a href="#" class="navbar-link">Über Uns</a>
            </li>

            <li>
              <a href="#" class="navbar-link">Dienstleistungen</a>
            </li>

            <li>
              <a href="#" class="navbar-link">Projekte</a>
            </li>

            <li>
              <a href="#" class="navbar-link">Kontakt</a>
            </li>

          </ul>
        </nav>

        <a href="#" class="btn btn-primary">
          <span class="span">Angebot Einholen</span>

          <span class="material-symbols-rounded">arrow_forward</span>
        </a>

        <button class="nav-toggle-btn" aria-label="Menü umschalten" data-nav-toggler>
          <span class="nav-toggle-icon icon-1"></span>
          <span class="nav-toggle-icon icon-2"></span>
          <span class="nav-toggle-icon icon-3"></span>
        </button>

      </div>
    </header>





    <main>
      <article>

        <!--
        - #HERO
      -->

        <section class="hero bg-plan" style="background-image: url('./assets/images/hero-bg.png')"
          aria-label="Startseite">

          <div class="container">

            <div class="hero-content">

              <p class="section-subtitle :dark">Wir haben talentierte Ingenieure & Mechaniker</p>

              <h1 class="h1 section-title">Auto Wartung & Reparatur Service</h1>

              <p class="section-text">
                Duis aute irure dolor in reprehenderit in voluptate velit esse Excepteur sint occaecat cupidatat non
                proident.
              </p>

              <a href="#" class="btn">
                <span class="span">Unsere Dienstleistungen</span>

                <span class="material-symbols-rounded">arrow_forward</span>
              </a>

            </div>

            <figure class="hero-banner" style="--width: 1228; --height: 789;">
              <img src="./assets/images/hero-banner.png" width="1228" height="789" alt="Rotes Fahrzeug"
                class="move-anim">
            </figure>

          </div>
        </section>





        <!--
        - #SERVICE
      -->

        <section class="section service has-bg-image" aria-labelledby="service-label"
          style="background-image: url('./assets/images/service-bg.jpg')">
          <div class="container">

            <p class="section-subtitle :light" id="service-label">Unsere Dienstleistungen</p>

            <h2 class="h2 section-title">Wir bieten hervorragende Dienstleistungen für Ihr Fahrzeug</h2>

            <ul class="service-list">

              <li>
                <div class="service-card">

                  <figure class="card-icon">
                    <img src="./assets/images/services-1.png" width="110" height="110" loading="lazy"
                      alt="Motorreparatur">
                  </figure>

                  <h3 class="h3 card-title">Motorreparatur</h3>

                  <p class="card-text">
                    Autem velaum iure reare aenderit rui in ea roluptate esse ruam moles
                  </p>

                  <a href="#" class="btn-link">Mehr lesen</a>

                </div>
              </li>

              <li>
                <div class="service-card">

                  <figure class="card-icon">
                    <img src="./assets/images/services-2.png" width="110" height="110" loading="lazy"
                      alt="Bremsenreparatur">
                  </figure>

                  <h3 class="h3 card-title">Bremsenreparatur</h3>

                  <p class="card-text">
                    Autem velaum iure reare aenderit rui in ea roluptate esse ruam moles
                  </p>

                  <a href="#" class="btn-link">Mehr lesen</a>

                </div>
              </li>

              <li>
                <div class="service-card">

                  <figure class="card-icon">
                    <img src="./assets/images/services-3.png" width="110" height="110" loading="lazy"
                      alt="Reifenreparatur">
                  </figure>

                  <h3 class="h3 card-title">Reifenreparatur</h3>

                  <p class="card-text">
                    Autem velaum iure reare aenderit rui in ea roluptate esse ruam moles
                  </p>

                  <a href="#" class="btn-link">Mehr lesen</a>

                </div>
              </li>

              <li>
                <div class="service-card">

                  <figure class="card-icon">
                    <img src="./assets/images/services-4.png" width="110" height="110" loading="lazy"
                      alt="Batteriereparatur">
                  </figure>

                  <h3 class="h3 card-title">Batteriereparatur</h3>

                  <p class="card-text">
                    Autem velaum iure reare aenderit rui in ea roluptate esse ruam moles
                  </p>

                  <a href="#" class="btn-link">Mehr lesen</a>

                </div>
              </li>

              <li class="service-banner">
                <img src="./assets/images/services-5.png" width="646" height="380" loading="lazy" alt="Rotes Auto"
                  class="move-anim">
              </li>

              <li>
                <div class="service-card">

                  <figure class="card-icon">
                    <img src="./assets/images/services-6.png" width="110" height="110" loading="lazy"
                      alt="Lenkradreparatur">
                  </figure>

                  <h3 class="h3 card-title">Lenkradreparatur</h3>

                  <p class="card-text">
                    Autem velaum iure reare aenderit rui in ea roluptate esse ruam moles
                  </p>

                  <a href="#" class="btn-link">Mehr lesen</a>

                </div>
              </li>

            </ul>

            <a href="#" class="btn">
              <span class="span">Alle Dienstleistungen anzeigen</span>

              <span class="material-symbols-rounded">arrow_forward</span>
            </a>

          </div>
        </section>





        <!--
        - #ABOUT
      -->

        <section class="section about has-before" aria-labelledby="about-label">
          <div class="container">

            <figure class="about-banner">
              <img src="./assets/images/about-banner.png" width="540" height="540" loading="lazy"
                alt="Fahrzeugreparatur Ausrüstung" class="w-100">
            </figure>

            <div class="about-content">

              <p class="section-subtitle :dark">Über Uns</p>

              <h2 class="h2 section-title">Wir verpflichten uns, die Qualität zu erfüllen</h2>

              <p class="section-text">
                Quis autem vel eum iure reprehenderit qui in ea volu velit esse quam nihil molestiae consequatur vel
                illum
                qui dolorem eum fugiat quo voluptas nulla pariatur? At vero eos et accusamus et iusto odio dignissimos
                ducimus qui blanditiis praesentium voluptatum.
              </p>

              <ul class="about-list">

                <li class="about-item">
                  <div class="item-icon icon-1">
                    <ion-icon name="car-sport-outline"></ion-icon>
                  </div>

                  <p class="item-text">Modernes Ausrüstung</p>
                </li>

                <li class="about-item">
                  <div class="item-icon icon-2">
                    <ion-icon name="people-circle-outline"></ion-icon>
                  </div>

                  <p class="item-text">Erfahrene Mitarbeiter</p>
                </li>

                <li class="about-item">
                  <div class="item-icon icon-3">
                    <ion-icon name="thumbs-up-outline"></ion-icon>
                  </div>

                  <p class="item-text">Qualität Wartung</p>
                </li>

                <li class="about-item">
                  <div class="item-icon icon-4">
                    <ion-icon name="trophy-outline"></ion-icon>
                  </div>

                  <p class="item-text">Ausgezeichnete Ausführung</p>
                </li>

              </ul>

              <a href="#" class="btn">
                <span class="span">Über Uns Lesen</span>

                <span class="material-symbols-rounded">arrow_forward</span>
              </a>

            </div>

          </div>
        </section>





        <!--
  - #PROJEKTE
-->

        <section class="section projekte" aria-labelledby="projekte-label">
          <div class="container">

            <p class="section-subtitle :light" id="projekte-label">Unsere Arbeit</p>

            <h2 class="h2 section-title">Neueste Projekte, die wir abgeschlossen haben</h2>

            <ul class="has-scrollbar">

              <li class="scrollbar-item">
                <div class="projekt-karte">

                  <figure class="karte-banner img-holder" style="--width: 350; --height: 406;">
                    <img src="./assets/images/work-1.jpg" width="350" height="406" loading="lazy" alt="Motorreparatur"
                      class="img-cover">
                  </figure>

                  <div class="karte-inhalt">
                    <p class="karte-subtitle">Auto Reparatur</p>

                    <h3 class="h3 karte-titel">Motorreparatur</h3>

                    <a href="#" class="karte-btn">
                      <span class="material-symbols-rounded">arrow_forward</span>
                    </a>
                  </div>

                </div>
              </li>

              <li class="scrollbar-item">
                <div class="projekt-karte">

                  <figure class="karte-banner img-holder" style="--width: 350; --height: 406;">
                    <img src="./assets/images/work-2.jpg" width="350" height="406" loading="lazy" alt="Reifenwechsel"
                      class="img-cover">
                  </figure>

                  <div class="karte-inhalt">
                    <p class="karte-subtitle">Auto Reparatur</p>

                    <h3 class="h3 karte-titel">Reifenwechsel</h3>

                    <a href="#" class="karte-btn">
                      <span class="material-symbols-rounded">arrow_forward</span>
                    </a>
                  </div>

                </div>
              </li>

              <li class="scrollbar-item">
                <div class="projekt-karte">

                  <figure class="karte-banner img-holder" style="--width: 350; --height: 406;">
                    <img src="./assets/images/work-3.jpg" width="350" height="406" loading="lazy"
                      alt="Batterieanpassung" class="img-cover">
                  </figure>

                  <div class="karte-inhalt">
                    <p class="karte-subtitle">Auto Reparatur</p>

                    <h3 class="h3 karte-titel">Batterieanpassung</h3>

                    <a href="#" class="karte-btn">
                      <span class="material-symbols-rounded">arrow_forward</span>
                    </a>
                  </div>

                </div>
              </li>

            </ul>

          </div>
        </section>

      </article>
    </main>

    <!--
  - #FOOTER
-->

    <footer class="footer">

      <div class="footer-top section">
        <div class="container">

          <div class="footer-brand">

            <a href="#" class="logo">
              <img src="./assets/images/logo.png" width="128" height="63" alt="NitroAutoService Startseite">
            </a>

            <p class="footer-text">
              Rerum necessitatibus saepe eveniet aut et voluptates repudiandae sint et molestiae non recusandae.
            </p>

            <ul class="social-list">

              <li>
                <a href="#" class="social-link">
                  <img src="./assets/images/facebook.svg" alt="facebook">
                </a>
              </li>

              <li>
                <a href="#" class="social-link">
                  <img src="./assets/images/instagram.svg" alt="instagram">
                </a>
              </li>

              <li>
                <a href="#" class="social-link">
                  <img src="./assets/images/twitter.svg" alt="twitter">
                </a>
              </li>

            </ul>

          </div>

          <ul class="footer-list">

            <li>
              <p class="h3">Öffnungszeiten</p>
            </li>

            <li>
              <p class="p">Montag – Samstag</p>
              <span class="span">12.00 – 14.45</span>
            </li>

            <li>
              <p class="p">Sonntag – Donnerstag</p>
              <span class="span">17.30 – 00.00</span>
            </li>

            <li>
              <p class="p">Freitag – Samstag</p>
              <span class="span">12.00 – 14.45</span>
            </li>

          </ul>

          <ul class="footer-list">

            <li>
              <p class="h3">Kontaktinformationen</p>
            </li>

            <li>
              <a href="tel:+49 999 99 999" class="footer-link">
                <span class="material-symbols-rounded">call</span>
                <span class="span">+49 999 99 999</span>
              </a>
            </li>

            <li>
              <a href="mailto:info@NitroAutoService.de" class="footer-link">
                <span class="material-symbols-rounded">mail</span>
                <span class="span">info@NitroAutoService.de</span>
              </a>
            </li>

            <li>
              <address class="footer-link address">
                <span class="material-symbols-rounded">location_on</span>
                <span class="span">Lauterbacher Str 4, 04651 Bad Lausick</span>
              </address>
            </li>

          </ul>

        </div>

        <img src="./assets/images/footer-shape-3.png" width="637" height="173" loading="lazy" alt="Shape"
          class="shape shape-3 move-anim">

      </div>

      <div class="footer-bottom">
        <div class="container">

          <p class="copyright">Urheberrecht 2024, NitroAutoService Alle Rechte vorbehalten.</p>

          <img src="./assets/images/footer-shape-2.png" width="778" height="335" loading="lazy" alt="Shape"
            class="shape shape-2">

          <img src="./assets/images/footer-shape-1.png" width="805" height="652" loading="lazy" alt="Rotes Auto"
            class="shape shape-1 move-anim">

        </div>
      </div>

    </footer>

    <!--
  - custom js link
-->
    <script src="./assets/js/script.js"></script>

  </body>

</html>
