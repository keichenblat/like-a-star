<template>
  <div class="star-container">
    <svg
      width="144"
      height="154"
      viewBox="0 0 144 154"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M66.5284 4.9512C67.9017 -0.809513 76.0983 -0.809496 77.4717 4.95122L79.7565 14.5352C86.6934 43.6324 110.018 65.9765 139.386 71.658C145.263 72.7949 145.263 81.2051 139.386 82.342C110.018 88.0235 86.6934 110.368 79.7565 139.465L77.4716 149.049C76.0983 154.81 67.9017 154.809 66.5283 149.049L64.2435 139.465C57.3066 110.368 33.9818 88.0235 4.61359 82.342C-1.26322 81.2051 -1.26322 72.7949 4.61359 71.658C33.9818 65.9765 57.3066 43.6324 64.2435 14.5351L66.5284 4.9512Z"
        fill="url(#paint0_linear_3_8)"
      />
      <defs>
        <linearGradient
          id="paint0_linear_3_8"
          x1="72"
          y1="-18"
          x2="72"
          y2="172"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.393335" stop-color="#DA22FF" />
          <stop offset="1" stop-color="#9733EE" />
        </linearGradient>
      </defs>
    </svg>
  </div>
</template>

<style scoped>
.star-container {
  animation: shine 800ms ease-in infinite alternate;
  transform-origin: center;
}

@keyframes shine {
  0% {
    opacity: 100%;
    transform: scale(1);
  }
  100% {
    opacity: 0%;
    transform: scale(0.3);
  }
}
</style>
