<template>
  <header id="nav" class="layout__header">
    <div class="navigation__left">
      <!-- Logo -->
      <svg
        width="88"
        height="89"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill-rule="evenodd"
          clip-rule="evenodd"
          d="M57 19c6 0 12-3 18 0 6 2 9 8 11 13s3 11 1 17c-2 5-7 10-12 13-6 2-12 3-18 1-5-1-9-4-12-8-3-2-5-6-7-9-3-5-11-8-10-14 1-5 7-9 13-11 5-2 10-1 16-2z"
          fill="url(#paint0_radial)"
        />
        <path
          fill-rule="evenodd"
          clip-rule="evenodd"
          d="M57 19c6 0 12-3 18 0 6 2 9 8 11 13s3 11 1 17c-2 5-7 10-12 13-6 2-12 3-18 1-5-1-9-4-12-8-3-2-5-6-7-9-3-5-11-8-10-14 1-5 7-9 13-11 5-2 10-1 16-2z"
          fill="#E0E0E0"
          fill-opacity=".3"
        />
        <path
          fill-rule="evenodd"
          clip-rule="evenodd"
          d="M30 68c-5-3-12-5-13-10-2-6 0-12 3-17s7-10 13-12c6-3 13-3 19-1 6 1 10 5 14 10 2 4 2 9 2 13l-4 11c-1 6 1 13-4 16s-12 1-18 0c-5-2-8-6-12-10z"
          fill="url(#paint1_radial)"
        />
        <path
          fill-rule="evenodd"
          clip-rule="evenodd"
          d="M30 68c-5-3-12-5-13-10-2-6 0-12 3-17s7-10 13-12c6-3 13-3 19-1 6 1 10 5 14 10 2 4 2 9 2 13l-4 11c-1 6 1 13-4 16s-12 1-18 0c-5-2-8-6-12-10z"
          fill="#000"
          fill-opacity=".2"
        />
        <path
          fill-rule="evenodd"
          clip-rule="evenodd"
          d="M56 25c2 5 7 10 6 15-2 6-7 10-12 13-6 3-12 5-19 5-6 0-12-3-17-7-4-4-6-10-6-15s3-9 6-12c2-4 6-6 9-9 4-4 6-11 12-11 6-1 12 4 16 8 3 3 4 9 5 13z"
          fill="url(#paint2_radial)"
        />
        <path
          fill-rule="evenodd"
          clip-rule="evenodd"
          d="M56 25c2 5 7 10 6 15-2 6-7 10-12 13-6 3-12 5-19 5-6 0-12-3-17-7-4-4-6-10-6-15s3-9 6-12c2-4 6-6 9-9 4-4 6-11 12-11 6-1 12 4 16 8 3 3 4 9 5 13z"
          fill="#000"
          fill-opacity=".2"
        />
        <defs>
          <radialGradient
            id="paint0_radial"
            cx="0"
            cy="0"
            r="1"
            gradientUnits="userSpaceOnUse"
            gradientTransform="matrix(0 23.2427 -29.9618 0 58 41)"
          >
            <stop offset=".4" stop-color="#828282" />
            <stop offset=".6" stop-color="#696969" stop-opacity=".5" />
            <stop offset="1" stop-color="#E0E0E0" stop-opacity=".3" />
          </radialGradient>
          <radialGradient
            id="paint1_radial"
            cx="0"
            cy="0"
            r="1"
            gradientUnits="userSpaceOnUse"
            gradientTransform="matrix(18.9772 -16.10119 18.10308 21.33668 46 53)"
          >
            <stop stop-opacity=".5" />
            <stop offset=".4" stop-opacity="0" />
          </radialGradient>
          <radialGradient
            id="paint2_radial"
            cx="0"
            cy="0"
            r="1"
            gradientUnits="userSpaceOnUse"
            gradientTransform="rotate(167 15 18) scale(26.1327 26.6484)"
          >
            <stop stop-color="#141618" />
            <stop offset=".3" stop-color="#141618" stop-opacity=".8" />
            <stop offset="1" stop-color="#141618" stop-opacity="0" />
          </radialGradient>
        </defs>
      </svg>
    </div>

    <div class="navigation__home navigation__link">
      <router-link to="/">01 home<span></span></router-link>
    </div>
    <div class="navigation__work navigation__link">
      <router-link to="/work">02 work<span></span></router-link>
    </div>

    <!-- <router-link class="navigation__blog navigation__link" to="/blog">03 blog</router-link> -->
  </header>

  <main class="layout__main">
    <router-view />
  </main>

  <footer class="layout__footer">
    <section data-name="socials" class="footer__socials">
      <svg
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M12.0605 0.780471C5.69856 0.780471 0.540482 6.07199 0.540482 12.5933C0.540482 17.8128 3.84192 22.2365 8.4192 23.7994C8.48324 23.8131 8.54858 23.8199 8.61408 23.8195C9.04128 23.8195 9.20544 23.5065 9.20544 23.2339C9.20544 22.9507 9.19584 22.2106 9.19008 21.2227C8.80925 21.3121 8.41965 21.3588 8.02848 21.3619C5.81088 21.3619 5.30784 19.6387 5.30784 19.6387C4.78272 18.2755 4.0272 17.9107 4.0272 17.9107C3.024 17.2061 4.02144 17.1859 4.0992 17.1859H4.104C5.2608 17.2886 5.86752 18.4099 5.86752 18.4099C6.44352 19.4179 7.21536 19.7001 7.90464 19.7001C8.36064 19.6905 8.80896 19.5859 9.2208 19.392C9.32352 18.6307 9.62208 18.1114 9.95136 17.8128C7.39584 17.5152 4.70592 16.5014 4.70592 11.976C4.70592 10.6848 5.15328 9.63071 5.88864 8.80799C5.77056 8.51039 5.37408 7.30655 6.00192 5.68127C6.08612 5.66106 6.17266 5.65234 6.2592 5.65535C6.67584 5.65535 7.61664 5.81471 9.16992 6.89471C11.0573 6.36671 13.0531 6.36671 14.9395 6.89471C16.4928 5.81471 17.4346 5.65631 17.8512 5.65631C17.9376 5.65247 18.024 5.66111 18.1085 5.68127C18.7354 7.30655 18.3389 8.50943 18.2208 8.80799C18.9562 9.63551 19.4035 10.6896 19.4035 11.976C19.4035 16.512 16.7088 17.5094 14.1427 17.8032C14.5546 18.168 14.9242 18.888 14.9242 19.9881C14.9242 21.5673 14.9088 22.8432 14.9088 23.2281C14.9088 23.5065 15.0682 23.8195 15.4954 23.8195C15.5645 23.8195 15.6336 23.8137 15.7008 23.8003C20.2838 22.2355 23.5795 17.808 23.5795 12.5933C23.5795 6.07199 18.4214 0.77951 12.0595 0.77951L12.0605 0.780471Z"
          fill="black"
        />
      </svg>

      <svg
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M19 0L5 0C2.239 0 0 2.239 0 5L0 19C0 21.761 2.239 24 5 24H19C21.762 24 24 21.761 24 19V5C24 2.239 21.762 0 19 0ZM8 19H5V8H8V19ZM6.5 6.732C5.534 6.732 4.75 5.942 4.75 4.968C4.75 3.994 5.534 3.204 6.5 3.204C7.466 3.204 8.25 3.994 8.25 4.968C8.25 5.942 7.467 6.732 6.5 6.732ZM20 19H17V13.396C17 10.028 13 10.283 13 13.396V19H10V8H13V9.765C14.396 7.179 20 6.988 20 12.241V19Z"
          fill="#101010"
        />
      </svg>

      <svg
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g clip-path="url(#clip0)">
          <path
            d="M24 4.55699C23.117 4.94899 22.168 5.21299 21.172 5.33199C22.189 4.72299 22.97 3.75799 23.337 2.60799C22.386 3.17199 21.332 3.58199 20.21 3.80299C19.313 2.84599 18.032 2.24799 16.616 2.24799C13.437 2.24799 11.101 5.21399 11.819 8.29299C7.728 8.08799 4.1 6.12799 1.671 3.14899C0.381 5.36199 1.002 8.25699 3.194 9.72299C2.388 9.69699 1.628 9.47599 0.965 9.10699C0.911 11.388 2.546 13.522 4.914 13.997C4.221 14.185 3.462 14.229 2.69 14.081C3.316 16.037 5.134 17.46 7.29 17.5C5.22 19.123 2.612 19.848 0 19.54C2.179 20.937 4.768 21.752 7.548 21.752C16.69 21.752 21.855 14.031 21.543 7.10599C22.505 6.41099 23.34 5.54399 24 4.55699Z"
            fill="#101010"
          />
        </g>
        <defs>
          <clipPath id="clip0">
            <rect width="24" height="24" fill="white" />
          </clipPath>
        </defs>
      </svg>

      <svg
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M19.615 3.18413C16.011 2.93813 7.984 2.93913 4.385 3.18413C0.488 3.45013 0.029 5.80412 0 12.0001C0.029 18.1851 0.484 20.5491 4.385 20.8161C7.985 21.0611 16.011 21.0621 19.615 20.8161C23.512 20.5501 23.971 18.1961 24 12.0001C23.971 5.81512 23.516 3.45113 19.615 3.18413ZM9 16.0001V8.00013L17 11.9931L9 16.0001Z"
          fill="#101010"
        />
      </svg>
    </section>

    <section class="footer__contact">
      <a href="mailto:ognjen@fullstacked.dev">ognjen@fullstacked.dev</a>
    </section>
  </footer>
</template>
