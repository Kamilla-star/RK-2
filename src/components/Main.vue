<template>
  <main class="main">
    <div class="container">
      <div class="main__inner">
        <h1 class="main__title">Веб-технологии</h1>
        <section class="main__technologies technologies" id="technologies">
          <h2 class="technologies__title">Технологии</h2>
          <div class="blocks">
            <div class="technologies__block block">
              <h3 class="block__title">TypeScript</h3>
              <p class="block__description">
                Google недавно утвердил TypeScript в качестве предпочтительного
                языка для своего front-end фреймворка AngularJS. Это делает TS
                еще более привлекательным, потому что он помогает сэкономить
                время, как при написании общих скриптов, так и при разработке
                специализированных Angular-проектов.
              </p>
            </div>
            <div class="technologies__block block">
              <h3 class="block__title">Google Web Starter Kit</h3>
              <p class="block__description">
                Google предлагает множество полезных технологий веб разработки,
                и одной из них является Web Starter Kit. Это библиотека полезных
                ресурсов для создания сайтов, модульного кода Sass / CSS,
                локальных HTTP-серверов и многого другого.
              </p>
            </div>
            <div class="technologies__block block">
              <h3 class="block__title">Polymer</h3>
              <p class="block__description">
                Когда вы познакомитесь с Web Components, вам может понадобиться
                библиотека Polymer. Этот проект с открытым исходным кодом
                запустил Google. Он предназначен для создания
                стандартизированных веб-компонентов.
              </p>
            </div>
          </div>
        </section>
        <section class="main__libraries libraries" id="libraries">
          <h2 class="libraries__title">Библиотеки</h2>
          <div class="blocks">
            <div class="technologies__block block">
              <h3 class="block__title">Axios</h3>
              <p class="block__description">
                Библиотека Axios, предназначенная для выполнения HTTP-запросов,
                основана на промисах. Она подходит для использования в среде
                Node.js и в браузерных приложениях. Библиотека поддерживает все
                современные браузеры, и, в том числе, IE8+.
              </p>
            </div>
            <div class="technologies__block block">
              <h3 class="block__title">Superagent</h3>
              <p class="block__description">
                Библиотека Superagent, как и Axios, подходит для Node.js и для
                современных браузеров. Она предоставляет разработчику простое и
                понятное API, с которым удобно работать.
              </p>
            </div>
            <div class="technologies__block block">
              <h3 class="block__title">Supertest</h3>
              <p class="block__description">
                Библиотека Supertest основана на библиотеке Superagent. Она
                предназначена для тестирования HTTP-серверов, построенных на
                основе Node.js. Supertest даёт разработчику доступ к
                собственному API и к низкоуровневому API, предоставляемому
                библиотекой Superagent.
              </p>
            </div>
          </div>
        </section>
        <section class="main__frameworks frameworks" id="frameworks">
          <h2 class="frameworks__title">Фреймворки</h2>
          <div class="blocks">
            <div class="technologies__block block">
              <h3 class="block__title">Express</h3>
              <p class="block__description">
                JavaScript-фреймворк Express взлетает на волне популярности
                Node.js. Сейчас это один из самых трендовых инструментов
                веб-разработки. Его используют крупные компании Accenture, IBM и
                Uber, а также другие фреймворки, например, Kraken, Sails и
                Loopback.
              </p>
            </div>
            <div class="technologies__block block">
              <h3 class="block__title">React</h3>
              <p class="block__description">
                Не очень правильно называть React фреймворком, это скорее
                библиотека компонентов для веб-разработки. Однако его значение
                так велико, что исторически ни одно сравнение без него не
                обходится.
              </p>
            </div>
            <div class="technologies__block block">
              <h3 class="block__title">Vue</h3>
              <p class="block__description">
                Начавшись как проект одного разработчика Google, Vue.js очень
                быстро вырос в один из самых популярных JavaScript-фреймворков.
                Это очень гибкий инструмент с прогрессивной структурой, который
                легко интегрировать в уже существующие проекты. Компонентная
                архитектура и богатая экосистема позволяет разрабатывать сложные
                приложения с минимальными затратами.
              </p>
            </div>
          </div>
        </section>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "Main",
  props: {},
};
</script>

<style>
</style>