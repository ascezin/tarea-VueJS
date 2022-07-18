<template>
<div id="vue-app">
      <section>
        <div class="jobs center">

          <!-- search bar -->
          <div class="search center">
            <div class="input-group">
              <div class="search-icon">
                <span class=""><svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="search" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class=""><g data-v-de07d972=""><path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"></path></g></svg></span>
              </div>
              <div class="input2">
                <input type="text" placeholder="Busca por cargo, salario, ubicación o empresa" class="">
              </div>
            </div>
            <div class="filters">
              <button>Area de trabajo <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="caret down fill" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class=""><g transform="translate(8 8) scale(0.7 0.7) translate(-8 -8)"><path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"></path></g></svg></button>
              <button>Cargo <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="caret down fill" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class=""><g transform="translate(8 8) scale(0.7 0.7) translate(-8 -8)"><path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"></path></g></svg></button>
              <button>Salario <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="caret down fill" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class=""><g transform="translate(8 8) scale(0.7 0.7) translate(-8 -8)"><path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"></path></g></svg></button>
              <button>Ubicacion <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="caret down fill" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class=""><g transform="translate(8 8) scale(0.7 0.7) translate(-8 -8)"><path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"></path></g></svg></button>
            </div>
          </div>

          <!-- cards -->
          <div class="jobs-list center">
            <div class="card card_2">
              <img src="https://s3-us-west-2.amazonaws.com/peakuresumes/company_logos/2078/PeakU_Inc._logo.png?AWSAccessKeyId=AKIAIVHM6DISVPRGW5OQ&amp;Signature=O6qS7%2BDDuNZECbweFsefwzAJG9w%3D&amp;Expires=1658182685" alt="Logo empresa" width="90" height="90" class="rounded">
              <div class="card-body">
                <a class="tituloCard">Arquitecto Cloud</a>
                <div class="card-info">
                  <div class="info-item">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g><path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path><path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path></g></svg>
                    <span>
                      Confidencial
                    </span>
                  </div>
                  <div class="info-item">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g><path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path><path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path></g></svg>
                    <span>
                      Remoto
                    </span>
                  </div>
                  <div class="info-item">
                    <svg  viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g ><path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path><path d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z"></path></g></svg>
                    <span>
                      Confidencial
                    </span>
                  </div>
                  <div class="info-item">
                    <svg data-v-1c70d678="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi"><g data-v-1c70d678=""><path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"></path></g></svg>
                    <span>
                      1 Vacante
                    </span>
                  </div>
                  <div class="info-item">
                    <svg data-v-1c70d678="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-calendar3 b-icon bi"><g data-v-1c70d678=""><path d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"></path><path d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"></path></g></svg>                    <span>
                      1 day ago
                    </span>
                  </div>
                </div>
                <div class="tags">
                  <div>
                    <button>aws</button>
                    <button>arquitectura de software</button>
                    <button>aws</button>
                  </div>
                  <div>
                    <button>team building</button>
                    <button>curso de ingles</button>
                    <button>trabajo remoto</button>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="jobs-list center">
            <div class="card card_2">
              <img src="https://peaku.co/img/company.svg" alt="Logo empresa" width="90" height="90" class="rounded">
              <div class="card-body">
                <a>Analista de Logistica y Compras</a>
                <div class="card-info">
                  <div class="info-item">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g><path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path><path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path></g></svg>
                    <span>
                      Inversiones J...
                    </span>
                  </div>
                  <div class="info-item">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g><path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path><path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path></g></svg>
                    <span>
                      Medellin
                    </span>
                  </div>
                  <div class="info-item">
                    <svg  viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g ><path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path><path d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z"></path></g></svg>
                    <span>
                      $1.7M - 1.8M COP
                    </span>
                  </div>
                  <div class="info-item">
                    <svg data-v-1c70d678="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi"><g data-v-1c70d678=""><path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"></path></g></svg>
                    <span>
                      1 Vacante
                    </span>
                  </div>
                  <div class="info-item">
                    <svg data-v-1c70d678="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-calendar3 b-icon bi"><g data-v-1c70d678=""><path d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"></path><path d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"></path></g></svg>                    <span>
                      2 days ago
                    </span>
                  </div>
                </div>
                <div class="tags">
                  <div>
                    <button>analisis de informacion</button>
                    <button>logistica</button>
                    <button>inventarios</button>
                  </div>
                  <!-- <div>
                    <button>bbbbbb</button>
                    <button>bbbbbb</button>
                    <button>bbbbbb</button>
                  </div> -->
                </div>
              </div>
            </div>
          </div>

          <div class="jobs-list center">
            <div class="card card_2">
              <img src="https://peaku.co/img/company.svg" alt="Logo empresa" width="90" height="90" class="rounded">
              <div class="card-body">
                <a>Node.js Developer</a>
                <div class="card-info">
                  <div class="info-item">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g><path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path><path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path></g></svg>
                    <span>
                      Bankuish
                    </span>
                  </div>
                  <div class="info-item">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g><path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path><path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path></g></svg>
                    <span>
                      Remoto
                    </span>
                  </div>
                  <div class="info-item">
                    <svg  viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g ><path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path><path d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z"></path></g></svg>
                    <span>
                      $40K - 70K USD
                    </span>
                  </div>
                  <div class="info-item">
                    <svg data-v-1c70d678="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi"><g data-v-1c70d678=""><path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"></path></g></svg>
                    <span>
                      1 Vacante
                    </span>
                  </div>
                  <div class="info-item">
                    <svg data-v-1c70d678="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-calendar3 b-icon bi"><g data-v-1c70d678=""><path d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"></path><path d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"></path></g></svg>                    <span>
                      2 days ago
                    </span>
                  </div>
                </div>
                <div class="tags">
                  <div>
                    <button>api restful</button>
                    <button>nodesjs (express)</button>
                    <button>nosql</button>
                  </div>
                  <div>
                    <button>plan carrera</button>
                    <button>vesting</button>
                    <button>trabajo remoto</button>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="jobs-list center">
            <div class="card card_2">
              <img src="https://s3-us-west-2.amazonaws.com/peakuresumes/company_logos/2078/PeakU_Inc._logo.png?AWSAccessKeyId=AKIAIVHM6DISVPRGW5OQ&amp;Signature=O6qS7%2BDDuNZECbweFsefwzAJG9w%3D&amp;Expires=1658182685" alt="Logo empresa" width="90" height="90" class="rounded">
              <div class="card-body">
                <a>Desarrollador Fullstack</a>
                <div class="card-info">
                  <div class="info-item">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g><path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path><path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path></g></svg>
                    <span>
                      Confidencial
                    </span>
                  </div>
                  <div class="info-item">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g><path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"></path><path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path></g></svg>
                    <span>
                      Remoto
                    </span>
                  </div>
                  <div class="info-item">
                    <svg  viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><g ><path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path><path d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z"></path></g></svg>
                    <span>
                      Confidencial
                    </span>
                  </div>
                  <div class="info-item">
                    <svg data-v-1c70d678="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-people b-icon bi"><g data-v-1c70d678=""><path d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"></path></g></svg>
                    <span>
                      1 Vacante
                    </span>
                  </div>
                  <div class="info-item">
                    <svg data-v-1c70d678="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-calendar3 b-icon bi"><g data-v-1c70d678=""><path d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z"></path><path d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"></path></g></svg>                    <span>
                      3 days ago
                    </span>
                  </div>
                </div>
                <div class="tags">
                  <div>
                    <button>angular 2</button>
                    <button>.net</button>
                    <button>aws</button>
                  </div>
                  <div>
                    <button>team building</button>
                    <button>curso de ingles</button>
                    <button>trabajo remoto</button>
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>
      </section>
    </div>
</template>

<script>
export default{
    name: 'home-view'
}
</script>
<style scoped>
.card_2{
  padding-top: 50px;
}
.card-body a{
  position: absolute;
  left: 0;
  top: -1rem;
  left: 5em;
}
.input2{
    margin: auto;
    width: 80%;
}
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap');
.jobs{
    margin-top: 5rem!important;
    margin: 3rem -20em;
    width: 96%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: absolute;
}
.center{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.search {

  width: 100%;
  height: 137px;
  background: linear-gradient(90deg, #59a8ea,#1262a7);
}

.input-group{
  display: flex;
  flex-direction: row;
  width: 1110px;
  height: 49px;
  background: #fff;
  border-radius: 6px;
}
.search-icon{
  margin-top: 12px;
}
.search-icon span{
  padding: 0 16px;
  font-size: 26px;
  color: #495057;
}
.input-group input {
  width: 100%;
  box-shadow: none;
  border: #fff;
  outline: #fff;
  font-family: Roboto, sans-serif;
  font-size: 20px;
  font-weight: 400;
  color: #495057;
  border-radius: 6px;

}
.input-group input:focus {
  box-shadow: none;
  border: none;
}
.filters{
  width: 1110px;
  display: flex;
  flex-direction: row;
  align-items: start;
  margin-top: 12px;
  text-align: center;
}
.filters button {
  display: flex;
  align-items: center;
  background-color: transparent;
  border: 1px solid transparent;
  color: #f8f9fa;
  border-color: #f8f9fa;
  border-radius: 20px;
  padding: 6px 20px;
  margin-right: 6px;
}
.filters button:hover {
  color: #212529;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}
.filters svg {
  padding-top: 3px;
  padding-left: 6px;
}

.jobs-list{
  width: 100%;
  font-family: 'Montserrat', sans-serif;
  font-size: 20px;
}
.card{
  width: 1110px;
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-top: 9px;
  margin-bottom: 9px;
  border: 1px solid #dee2e6;
}
.card:hover {
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.2)
}
.card img {
  margin-top: -36px;
  margin-left: 9px;
  margin-right: 16px;
}
.card-body{
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: start;
}
.card-body a {
  color: #343a40;
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 26px;
  margin-top: 30px;
  margin-bottom: 20px;
  text-decoration: none;
}
span {
  font-family: 'Montserrat', 'Roboto', sans-serif;
  letter-spacing: -1px;
}
.card-info{
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-top: -9px;
  margin-bottom: 9px;
}
.info-item{
  display: flex;
  align-items: center;
  margin-right: 66px;
  font-family: "Montserrat", "Roboto", sans-serif;
  font-size: 20px;
  font-weight: 400;
}
.info-item svg {
  margin-right: 6px;
}
.tags{
  width: 90%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-top: 20px;
  margin-bottom: 30px;
}
.tags button {
  border: 1px solid grey;
  border-radius: 10px;
  font-size: 12px;
  color: grey;
  text-transform: uppercase;
  margin-right: 3px;
  margin-bottom: 3px;
  padding: 2px 9px;
  cursor: pointer;
}
</style>