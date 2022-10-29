<template>
  <footer>
    <div class="content-footer">
      <div class="first-group-footer">
        <div class="info-first">
          <h3>BB8</h3>
          <p>Quality for cheap</p>
        </div>

        <div class="info-first">
          <p>Back to the top</p>
          <p>Login</p>
          <p>Register</p>
        </div>
      </div>

      <div class="copyright-footer">
        <svg
          width="136"
          height="269"
          viewBox="0 0 136 269"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <g opacity="0.5">
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M3.32037 267.488C0.816101 265.736 -0.00460761 262.4 1.40053 259.686L48.7672 168.182C50.316 165.19 53.997 164.02 56.989 165.569C59.981 167.118 61.1509 170.799 59.6021 173.791L33.2075 224.78L117.879 132.703L53.1172 121.193C49.8001 120.604 47.589 117.437 48.1785 114.12C48.7681 110.803 51.935 108.591 55.2521 109.181L130.967 122.637C133.16 123.027 134.966 124.581 135.679 126.692C136.392 128.802 135.898 131.133 134.39 132.773L11.3083 266.619C9.23936 268.869 5.82466 269.241 3.32037 267.488Z"
              fill="white"
            />
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M132.68 1.10242C135.184 2.85493 136.005 6.19027 134.599 8.90473L87.2327 100.409C85.6839 103.4 82.0029 104.57 79.0109 103.022C76.019 101.473 74.849 97.7918 76.3978 94.7999L102.792 43.8103L18.1208 135.888L82.8827 147.397C86.1998 147.987 88.4109 151.154 87.8214 154.471C87.2319 157.788 84.0649 159.999 80.7478 159.41L5.03294 145.953C2.83983 145.563 1.03353 144.009 0.320817 141.899C-0.391894 139.789 0.102311 137.458 1.61005 135.818L124.692 1.97123C126.761 -0.278689 130.175 -0.650088 132.68 1.10242Z"
              fill="white"
            />
          </g>
        </svg>

        <p>© 2022 OnFire Desenvolvimento. All rights reserved.</p>
      </div>

      <div class="contact-footer">
        <h4>Get in touch</h4>

        <p>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M1 3C1 2.46957 1.21071 1.96086 1.58579 1.58579C1.96086 1.21071 2.46957 1 3 1H6.28C6.48979 1.00016 6.69422 1.0663 6.86436 1.18905C7.03449 1.3118 7.1617 1.48496 7.228 1.684L8.726 6.177C8.8019 6.40534 8.79293 6.65339 8.70072 6.87564C8.60851 7.0979 8.43925 7.27945 8.224 7.387L5.967 8.517C7.07332 10.9655 9.03446 12.9267 11.483 14.033L12.613 11.776C12.7205 11.5607 12.9021 11.3915 13.1244 11.2993C13.3466 11.2071 13.5947 11.1981 13.823 11.274L18.316 12.772C18.5152 12.8383 18.6885 12.9657 18.8112 13.136C18.934 13.3064 19.0001 13.511 19 13.721V17C19 17.5304 18.7893 18.0391 18.4142 18.4142C18.0391 18.7893 17.5304 19 17 19H16C7.716 19 1 12.284 1 4V3Z"
              stroke="white"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>

          +55 (99) 98543-5917
        </p>

        <p>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M8 19H12M17 19V3C17 2.46957 16.7893 1.96086 16.4142 1.58579C16.0391 1.21071 15.5304 1 15 1H5C4.46957 1 3.96086 1.21071 3.58579 1.58579C3.21071 1.96086 3 2.46957 3 3V19H17ZM17 19H19H17ZM17 19H12H17ZM3 19H1H3ZM3 19H8H3ZM7 5H8H7ZM7 9H8H7ZM12 5H13H12ZM12 9H13H12ZM8 19V14C8 13.7348 8.10536 13.4804 8.29289 13.2929C8.48043 13.1054 8.73478 13 9 13H11C11.2652 13 11.5196 13.1054 11.7071 13.2929C11.8946 13.4804 12 13.7348 12 14V19H8Z"
              stroke="white"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>

          Centro, Imperatriz, <br> Maranhão <br> Brasil
        </p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  background: #ffa540;
  height: 361px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

footer .content-footer {
  width: 100%;
  max-width: 1200px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

footer .content-footer p {
    font-size: 2rem;
    font-family: 'Roboto', sans-serif;
    color: #fff;
    line-height: 40px;
}

footer .content-footer .first-group-footer {
    display: flex;
    flex-direction: column;
    gap: 3rem;
}

footer .content-footer .first-group-footer h3 {
    font-size: 5rem;
    font-family: 'Roboto', sans-serif;
    font-weight: 700;
    color: #fff;
}

footer .content-footer .copyright-footer {
    display: flex;
    flex-direction: column;
    align-items: center;    
    gap: 2rem;
}

footer .content-footer .contact-footer {
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

footer .content-footer .contact-footer svg {
    margin-top: 10px;
}

footer .content-footer .contact-footer h4 {
    font-size: 3.5rem;
    font-family: 'Roboto', sans-serif;
    font-weight: 700;
    color: #fff;
}

footer .content-footer .contact-footer p {
    display: flex;
    gap: 2rem;
}

</style>

<script>

</script>









