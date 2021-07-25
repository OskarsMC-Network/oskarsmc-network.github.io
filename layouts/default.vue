<template>
  <div class="main">
      <b-navbar class='navbar-custom' toggleable="lg" type="dark" variant="dark">
        <b-navbar-brand>
          <img src="https://avatars.githubusercontent.com/u/81993477"  alt="" height="32px" style="border-radius: 5px"/>
          <b-dropdown split split-to="/" variant="outline-primary" text="OskarsMC Software" class="m-2">
            <b-dropdown-item href="https://oskarsmc.com/">OskarsMC</b-dropdown-item>
            <b-dropdown-item href="https://plugins.oskarsmc.com/">OskarsMC Plugins</b-dropdown-item>
          </b-dropdown>
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>

          </b-navbar-nav>
          <b-navbar-nav class="ml-auto">
            <b-dropdown split-to='/' right variant='outline-info' text='Socials' class='m-2'>
              <b-dropdown-item href='https://github.com/OskarsMC-Network' target='_blank'>GitHub</b-dropdown-item>
              <b-dropdown-item href='https://twitter.com/oskarsmcnetwork/' target='_blank'>Twitter</b-dropdown-item>
              <b-dropdown-item href='https://discord.gg/KfmcRzv6Gh' target='_blank'>Discord</b-dropdown-item>
            </b-dropdown>
          </b-navbar-nav>
        </b-collapse>
        </b-navbar>
    <Nuxt />
    <div class="footer">
      <h4>&copy; OskarsMC 2021 - 2021</h4>
    </div>
  </div>
</template>

<style>
body {
  overflow: overlay;
}

::-webkit-scrollbar {
  width: 5px;
}

::-webkit-scrollbar-track {
  background-color: transparent;
}
 
::-webkit-scrollbar-thumb {
  background: rgba(255,149,149,1);
  border-radius: 5px 0 0 5px;
}

::-webkit-scrollbar-thumb:hover {
  background: rgba(255,81,81,1);
  width: 10px;
}

.main {
  padding: 0;
  margin: 0;
}

.showcase-2 {
  padding-left: 10vw;
  padding-right: 10vw;
  padding-top: 3vh;
  background-color: rgb(230, 230, 230);
  display: flex;
  min-height: 20vh;
  padding-bottom: 10vh;
  text-align: left;
}

.showcase-2 h1 {
  font-size: 5vh;
  font-family: 'Ubuntu', sans-serif;
  flex: 2;
}

.showcase-2 div {
  padding-top: 3vh;
  font-size: 2vh;
  font-family: 'Poppins', Arial, Helvetica, sans-serif;
  font-weight: 100;
  flex: 2;
}

.showcase-2 h6 {
  color: gray;
}

.footer {
  border-top: solid gray 1px;
  font-family: 'Ubuntu Mono', Arial, Helvetica, sans-serif;
  text-align: center;
  padding-top: 1vh;
}

.footer h4 {
  font-size: 1.6vh;
  padding: 0;
}
</style>