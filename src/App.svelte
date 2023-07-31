<script>
  // import Counter from "./lib/Counter.svelte";
  import introVideo from "./videos/introvideo.mp4";

  // icons
  import codeBoxLine from "./icons/code-box-line.svg";
  import hardDrive from "./icons/hard-drive-2-line.svg";
  import artboardLine from "./icons/artboard-line.svg";
  import remote from "./icons/remote-control-2-line.svg";
  import instagram from "./icons/instagram.svg";
  import telegram from "./icons/telegram.svg";
  import github from "./icons/github.svg";
  import pagesLine from "./icons/pages-line.svg";
  import quillPen from "./icons/quill-pen-line.svg";
  import androidIcon from "./icons/android-line.svg";
  import barchart from "./icons/bar-chart-box-line.svg";
  import compasses from "./icons/compasses-2-line.svg";
  import smartphone from "./icons/smartphone-line.svg";
  import slideShow from "./icons/slideshow-line.svg";
  import footerImage from "./icons/pexels-denniz-futalan-3453047.jpg";
</script>

<main>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <div class="header_logo">
          <span style="color: var(--primary);">IT</span>CLUB
        </div>
        <div class="header__nav">
          <ul>
            <li><a href="">Asosiy</a></li>
            <li><a href="">Xizmat</a></li>
            <li><a href="">Portfolio</a></li>
            <li><a href="">Blog</a></li>
          </ul>
        </div>
        <div class="btn header__btn">Bog'lanish</div>
      </div>
    </div>
  </header>
  <div class="intro">
    <div class="container">
      <div class="intro__inner">
        <div class="intro__info">
          <h1>
            G'oyalar shu yerda
            <span
              >Real
              <div class="intro__info-animation" /></span
            >likka aylanadi.
          </h1>
          <p>Dasturchilar jamoasini shakillantirib dunyo miqyosiga chiqamiz.</p>
          <a href="#" class="btn">
            Jamoa eshiklari
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g clip-path="url(#clip0_16_663)">
                <path
                  d="M2 21V19H4V4.83499C4 4.35099 4.346 3.93699 4.821 3.85099L14.293 2.12899C14.619 2.06899 14.931 2.28599 14.99 2.61199C14.997 2.64699 15 2.68199 15 2.71899V3.99899L19 3.99999C19.552 3.99999 20 4.44799 20 4.99999V19H22V21H18V5.99999H15V21H2ZM13 4.39599L6 5.66999V19H13V4.39599ZM12 11V13H10V11H12Z"
                  fill="#fff"
                />
              </g>
              <defs>
                <clipPath id="clip0_16_663">
                  <rect width="24" height="24" fill="white" />
                </clipPath>
              </defs>
            </svg>
          </a>
        </div>
      </div>
    </div>
    <div class="intro__showcase">
      <video
        src={introVideo}
        autoplay
        muted
        loop
        width="100%"
        class="intro__video"
      >
        <track kind="captions" />
      </video>
    </div>
  </div>
  <div class="services">
    <div class="container">
      <div class="services__inner">
        <h1 class="services__inner-title">
          Sizga xizmatlarimizni taklif qilamiz.
        </h1>
        <div class="services__cards">
          <div class="services__card">
            <div class="services__card-icon">
              <img src={artboardLine} alt="" />
            </div>
            <h3>Vebsayt dizayni</h3>
            <p>Mahsulotingiz uchun dizayn tayyorlash xizmatimiz.</p>
            <button class="btn">Batafsil</button>
          </div>
          <div class="services__card">
            <div class="services__card-icon">
              <img src={codeBoxLine} alt="" />
            </div>
            <h3>Veb razrabotka</h3>
            <p>
              Adaptiv va chiroyli interfeysga ega vebsaytlar yasash xizmatimiz.
            </p>
            <button class="btn">Batafsil</button>
          </div>
          <div class="services__card">
            <div class="services__card-icon">
              <img src={remote} alt="" />
            </div>
            <h3>Biznesni tizimlashtirish</h3>
            <p>
              Biznesingiz rivoji uchun katta hissa qo'sha oladigan tizimlar.
            </p>
            <button class="btn">Batafsil</button>
          </div>
        </div>
        <div class="services__more">
          <div class="services__more-card">
            <div class="services__more-icon">
              <img src={barchart} alt="" />
            </div>
            <h3 class="services__more-name">SMM</h3>
          </div>
          <div class="services__more-card">
            <div class="services__more-icon">
              <img src={androidIcon} alt="" />
            </div>
            <h3 class="services__more-name">Telegram botlar</h3>
          </div>
          <div class="services__more-card">
            <div class="services__more-icon">
              <img src={smartphone} alt="" />
            </div>
            <h3 class="services__more-name">Mobil ilovalar</h3>
          </div>
          <div class="services__more-card">
            <div class="services__more-icon">
              <img src={slideShow} alt="" />
            </div>
            <h3 class="services__more-name">CRM tizimlar</h3>
          </div>
          <div class="services__more-card">
            <div class="services__more-icon">
              <img src={compasses} alt="" />
            </div>
            <h3 class="services__more-name">Logo dizayn</h3>
          </div>
          <div class="services__more-card">
            <div class="services__more-icon">
              <img src={quillPen} alt="" />
            </div>
            <h3 class="services__more-name">Grafik dizayn</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="team">
    <div class="container">
      <h2 class="team__title">Jamoamiz bilan tanishing.</h2>
      <div class="team__cards">
        <div class="team__card">
          <img
            src={"https://picsum.photos/800"}
            class="team__card-img"
            alt=""
          />
          <h5>Abdulaziz Hoshimov</h5>
          <p>Teamlead, Python developer</p>
          <div class="team__card-links">
            <div class="team__card-link">
              <a href="https://instagram.com/javohiralisherov_">
                <img src={instagram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="https://t.me/completeperson">
                <img src={telegram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="">
                <img src={github} alt="" />
              </a>
            </div>
          </div>
        </div>
        <div class="team__card">
          <img
            src={"https://picsum.photos/800"}
            class="team__card-img"
            alt=""
          />
          <h5>Ihtiyor Keldiyev</h5>
          <p>Frontend developer</p>
          <div class="team__card-links">
            <div class="team__card-link">
              <a href="https://instagram.com/javohiralisherov_">
                <img src={instagram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="https://t.me/completeperson">
                <img src={telegram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="">
                <img src={github} alt="" />
              </a>
            </div>
          </div>
        </div>
        <div class="team__card">
          <img
            src={"https://picsum.photos/800"}
            class="team__card-img"
            alt=""
          />
          <h5>Shohruh Abdurasulov</h5>
          <p>Python developer</p>
          <div class="team__card-links">
            <div class="team__card-link">
              <a href="https://instagram.com/javohiralisherov_">
                <img src={instagram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="https://t.me/completeperson">
                <img src={telegram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="">
                <img src={github} alt="" />
              </a>
            </div>
          </div>
        </div>
        <div class="team__card">
          <img
            src={"https://picsum.photos/800"}
            class="team__card-img"
            alt=""
          />
          <h5>Javohir Alisherov</h5>
          <p>Frontend developer</p>
          <div class="team__card-links">
            <div class="team__card-link">
              <a href="https://instagram.com/javohiralisherov_">
                <img src={instagram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="https://t.me/completeperson">
                <img src={telegram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="">
                <img src={github} alt="" />
              </a>
            </div>
          </div>
        </div>
        <div class="team__card">
          <img
            src={"https://picsum.photos/800"}
            class="team__card-img"
            alt=""
          />
          <h5>Javohir Alisherov</h5>
          <p>Frontend developer</p>
          <div class="team__card-links">
            <div class="team__card-link">
              <a href="https://instagram.com/javohiralisherov_">
                <img src={instagram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="https://t.me/completeperson">
                <img src={telegram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="">
                <img src={github} alt="" />
              </a>
            </div>
          </div>
        </div>
        <div class="team__card">
          <img
            src={"https://picsum.photos/800"}
            class="team__card-img"
            alt=""
          />
          <h5>Javohir Alisherov</h5>
          <p>Frontend developer</p>
          <div class="team__card-links">
            <div class="team__card-link">
              <a href="https://instagram.com/javohiralisherov_">
                <img src={instagram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="https://t.me/completeperson">
                <img src={telegram} alt="" />
              </a>
            </div>
            <div class="team__card-link">
              <a href="">
                <img src={github} alt="" />
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="footer">
    <div class="container">
      <div class="footer__inner">
        <h2>Birgalikda baland cho'qqilarni zabt etamiz</h2>
      </div>
    </div>
    <div class="footer__inner-image">
      <img src={footerImage} alt="" />
    </div>
    <div class="container">
      <div class="footer__infos">
        <div class="footer__infos-logo">
          <h3>IT-CLUB</h3>
          <ul>
            <li>Uzbekistan, Tashkent, Yunusabad-19</li>
          </ul>
        </div>
        <div class="footer__infos-project">
          <h4>Bizning loyihalar</h4>
          <ul>
            <li>Car To-Go</li>
            <li>Avtodrom</li>
          </ul>
        </div>
        <div class="footer__infos-services">
          <h4>Bizning xizmatlar</h4>
          <ul>
            <li>Biznesni tizimlashtirish</li>
            <li>Vebsaytlar</li>
            <li>Telegram botlar</li>
            <li>Smm</li>
            <li>Mobil ilovalar</li>
          </ul>
        </div>
        <div class="footer__infos-contacts">
          <h4>Bog'lanish uchun</h4>
          <ul>
            <li>
              <img width="15" src={instagram} alt="" /><a
                href="https://instagram.com/itc.uz"
              >
                Instagram</a
              >
            </li>
            <li>
              <img width="15" src={telegram} alt="" /><a
                href="https://t.me/itclub21uz"
              >
                Telegram</a
              >
            </li>
            <li>
              <a href="tel:+998883766606"> +998 88 376-66-06</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</main>

<style>
  .header {
    padding-top: 60px;
    padding-bottom: 80px;
  }
  .header__inner {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .header__nav ul {
    display: flex;
    flex-direction: row;
    list-style-type: none;
  }
  .header__nav ul li {
    margin-right: 60px;
    font-weight: 500;
  }
  .header__nav ul li a {
    text-decoration: none;
  }
  .header__nav ul li a:hover {
    transition: 0.2s;
    color: var(--shade-1);
  }
  .header__btn {
    padding: 12px 24px;
    font-weight: 500;
  }
  .header_logo {
    font-size: var(--huge-size);
    font-weight: 700;
  }
  .intro__info h1 {
    font-size: var(--ultra-size);
    font-weight: 500;
    margin-bottom: 20px;
  }
  .intro__info span {
    position: relative;
  }
  .intro__info-animation {
    width: 100%;
    height: 10px;
    background-color: var(--primary);
    position: absolute;
    left: 0;
    animation: titleAnimation 1s infinite linear;
  }
  @keyframes titleAnimation {
    0% {
      background: linear-gradient(90deg, #3f51b5, transparent) #2196f3;
    }
    100% {
      background: var(--primary);
    }
  }
  .intro__info p {
    font-size: var(--large-size);
    margin-bottom: 40px;
  }
  .intro__info a {
    padding: 20px 35px;
    width: 300px;
    font-size: var(--large-size);
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
  }
  .intro .container {
    margin-bottom: 50px;
  }
  .intro__showcase {
    width: 100%;
    height: 200px;
    overflow: hidden;
    margin-bottom: 100px;
  }
  .services {
    margin-bottom: 50px;
  }
  .services__inner-title {
    font-size: var(--giant-size);
    font-weight: 500;
    margin-bottom: 55px;
  }
  .services__cards {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    border: 1px solid var(--shade-2);
    border-radius: 16px;
  }
  .services__card {
    padding: 50px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .services__card-icon {
    padding: 20px;
  }
  .services__card-icon img {
    width: 70px;
  }
  .services__card p {
    text-align: center;
    margin: 15px 0;
    font-weight: 400;
    /* line-height: 26; */
    font-size: var(--large-size);
  }
  .services__card button {
    padding: 10px 30px;
    margin-top: 10px;
  }
  .services__more {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
    gap: 10px;
    margin: 60px 0 100px;
    padding: 20px;
  }
  .services__more-card {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    cursor: pointer;
    box-shadow: 0px 4px 120px 0px #0000000d;
    border: 1px solid var(--shade-2);
    padding: 40px;
    color: #fff;
    border-radius: 10px;
  }
  /* .services__more-card:nth-child(2),
  .services__more-card:nth-child(4),
  .services__more-card:nth-child(6),
  .services__more-card:nth-child(8) {
  } */
  .services__more-card h3 {
    text-align: center;
    font-size: var(--medium-size);
    font-weight: 500;
  }
  .services__more-card:hover .services__more-name {
    color: var(--shade-1);
  }
  .services__more-card .services__more-icon {
    margin-bottom: 15px;
  }
  .services__more-card .services__more-icon img {
    width: 50px;
  }
  .team {
    margin-bottom: 60px;
  }
  .team__title {
    font-size: var(--giant-size);
    font-weight: 500;
    margin-bottom: 55px;
  }
  .team__cards {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    gap: 15px;
  }
  .team__card {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 10px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0px 4px 120px 0px #0000000d;
  }
  .team__card-img {
    height: 310px;
    width: 300px;
    object-fit: cover;
    background-position: center;
    border-radius: 10px;
  }
  .team__card h5 {
    font-size: 18px;
    font-weight: 500;
    margin: 20px 0 0;
  }
  .team__card p {
    color: var(--secondary);
    margin: 10px 0;
  }
  .team__card-links {
    display: flex;
    gap: 20px;
  }
  .team__card-link {
    cursor: pointer;
  }
  .team__card-link img {
    width: 30px;
  }
  .footer {
    margin-top: 100px;
    margin-bottom: 40px;
  }
  .footer__inner h2 {
    font-size: var(--giant-size);
    font-weight: 500;
  }
  .footer__inner-image {
    margin: 70px 0;
    height: 200px;
    overflow: hidden;
  }
  .footer__inner-image {
    width: 100%;
  }
  .footer__infos {
    width: 100%;
    border: 1px solid var(--shade-2);
    padding: 40px;
    border-radius: 10px;
  }
  .footer__infos {
    display: flex;
    justify-content: space-between;
  }
  .footer__infos h4,
  .footer__infos h3 {
    margin-bottom: 10px;
    font-weight: 500;
  }
  .footer__infos ul {
    list-style-type: none;
  }
  .footer__infos ul li {
    display: flex;
    align-items: center;
    gap: 5px;
    margin-bottom: 3px;
    max-width: 200px;
  }
  .footer__infos ul li a {
    text-decoration: none;
  }

  @media all and (max-width: 300px) {
    .services__cards {
      grid-template-columns: 1fr;
    }
    .services__more {
      grid-template-columns: 1fr 1fr 1fr;
    }
    .team__cards {
      grid-template-columns: 1fr 1fr;
      padding: 20px;
    }
  }
</style>
