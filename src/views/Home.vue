<template>
  <div>
    <div class="container">
      <Navbar />
      <div class="row">
        <div class="col jmm-header">
          <h1 class="text-center jmm-mainTitle">Juan M. Morello</h1>
          <h2 class="text-center jmm-subTitle">Fullstack software developer</h2>
        </div>
      </div>
      <h3 class="text-center jmm-mainTitle jmm-marginHelper">
        Projects I've worked on
      </h3>
      <div class="row">
        <div class="col-6">
          <div class="card jmm-card">
            <div class="card-body">
              <h5 class="card-title">Banco Sáenz</h5>
              <h6 class="card-subtitle mb-2 text-muted">
                Fullstack software development with cloud architecture
              </h6>
              <p class="card-text">
                I was part of a team in which we developed the necessary
                infrastructure for the bank to grant credits and other products
                in an automated and online way.
                <br />The project was developed in Spring Boot, with a
                PostgreSQL database, and the various frontends were developed in
                VueJS. We deployed our solutions in a Docker Swarm environment
              </p>
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="card jmm-card">
            <div class="card-body">
              <h5 class="card-title">MisExpensasWeb.com</h5>
              <h6 class="card-subtitle mb-2 text-muted">
                Fullstack software development
              </h6>
              <p class="card-text">
                I was part of a team in which we developed a project that was
                born in a hackathon.
                <br />It is developed using Spring Boot, with a MySQL database,
                and the frontend is developed in HTML, CSS and JQuery. We
                deployed our solutions to an Apache Tomcat web container
              </p>
              <a href="https://misexpensasweb.com" class="card-link"
                >Product link</a
              >
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="card jmm-card">
            <div class="card-body">
              <h5 class="card-title">TPJuegos.com</h5>
              <h6 class="card-subtitle mb-2 text-muted">
                Fullstack software development
              </h6>
              <p class="card-text">
                I developed the web architecture to be able to channel the flow
                of user registration to a web service, offering the possibility
                to manage the game accounts, perform transactions that maintain
                the operational costs of both the game server and the web
                server.
                <br />It was developed using PHP 7.2 with a MySQL database, and
                HTML, CSS and Jquery for the frontend
              </p>
              <a href="http://tpjuegos.com" class="card-link">Product link</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "home",
  components: {
    Navbar
  }
};
</script>

<style scoped>
.jmm-header {
  margin: 45px 0px;
}
.jmm-mainTitle {
  color: rgb(209, 209, 209);
}
.jmm-subTitle {
  color: rgb(184, 184, 184);
}

.jmm-marginHelper {
  margin-bottom: 40px;
}

.jmm-card {
  background-color: rgba(204, 204, 204, 0.884);
  margin-bottom: 50px;
}
</style>
