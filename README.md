# goit-markup-hw-08

@include for-size(tablet) {

}

@include for-size(desktop) {

}

<div class="container">
      <header class="header header-container">
        <div class="container"><nav class="nav">
          <a href="./">
            <p class="logo"><span class="logo-accent">Web</span>Studio</p>
          </a>
          <button type="button" aria-controls="menu-container" class="burger-btn is-open" data-menu-button>
            <svg width="24" height="16" aria-label="mobile-menu-switcher" class="burger-btn-icon">
              <use class="close-burger-icon" href="./svg/sprite.svg#burger-btn" />
              <use class="burger-icon" href="./svg/sprite.svg#close-burger-btn" />
          </svg>
          </button>
          <div class="menu" id="menu-container" data-menu>
            <ul class="nav-list">
              <li class="nav-item"><a href="./" class="nav-link current">Студия</a></li>
              <li class="nav-item"><a href="./portfolio.html" class="nav-link">Портфолио</a></li>
              <li class="nav-item"><a href="#our-team" class="nav-link">Контакты</a></li>
            </ul>
            <ul class="contacts-list">
              <li class="contacts-item">
                <a href="mailto:info@devstudio.com" class="contacts-link">
                  <svg class="contacts-icon mail-icon" width="19" height="15">
                    <use href="./svg/sprite.svg#mail-icon" />
                  </svg>
                  <span class="contacts-text">info@devstudio.com</span>
                </a>
              </li>
              <li class="contacts-item contact-tel">
                <a href="tel:+380961111111" class="contacts-link">
                  <svg class="contacts-icon tel-icon" width="15" height="19">
                    <use href="./svg/sprite.svg#tel-icon" />
                  </svg><span class="contacts-text">+38 096 111 11 11</span></a>
              </li>
            </ul>
          </div>
        </nav>
      </div>
    </header>
    </div>

@import "./components/header/header";
@import "./components/header/header-logo";
@import "./components/header/nav";
@import "./components/header/header-contacts";
