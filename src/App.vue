<script setup></script>

<template>
  <div>
    <div class="upper"></div>
    <RouterView />
    <div class="bottom"></div>
  </div>
</template>

<style scoped></style>

<style>
/* Pretendard */
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css');

* {
  font-family: 'Pretendard Variable', Pretendard, -apple-system,
    BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI',
    'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', 'Apple Color Emoji',
    'Segoe UI Emoji', 'Segoe UI Symbol', sans-serif;

  --gray900: #191f28;
  --white: #fdfdfd;
  color: var(--gray900);
}

#app {
  height: 100dvh;
  min-width: 300px;
  max-width: 600px;
  /* padding-top: env(safe-area-inset-top); */
  margin: 0 auto;
  position: relative;
}

.upper {
  position: absolute;
  width: 100%;
  height: 40px;
  top: 10px;
  background-color: var(--gray900);
}

.bottom {
  position: absolute;
  width: 100%;
  height: 40px;
  bottom: 10px;
  background-color: var(--gray900);
}
</style>
