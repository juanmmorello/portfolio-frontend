<template>
  <div>
    <div class="container">
      <Navbar />
      <div class="row">
        <div class="col">
          <div class="card jmm-card" style="margin-top: 25px;">
            <div class="card-body">
              <h5 class="card-title">Skills</h5>
              <h6 class="card-subtitle mb-2 text-muted">
                Backend proficiencies
              </h6>
              <p class="card-text">
                I'm proficient with Java, developing both monolithic and
                microservices with Spring Framework and all the family of Spring
                projects.
                <br />Also I have experience with PHP and C#.NET. Moreover, I
                have knowledge on Linux environments (CentOS and Ubuntu),
                Docker, MySQL, PostgreSQL, SQL Server, Oracle, Apache and NginX.
                <br />I'm currently learning NodeJS to build backend
                applications and have a broader understanding on modern tools,
                and know which tool is right for the job.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <div class="card jmm-card">
            <div class="card-body">
              <h5 class="card-title">Skills</h5>
              <h6 class="card-subtitle mb-2 text-muted">
                Frontend proficiencies
              </h6>
              <p class="card-text">
                I'm used to develop great frontend experiences using HTML, CSS,
                vanilla JavaScript, and web applications using VueJS
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.jmm-header {
  margin: 45px 0px;
}
.jmm-mainTitle {
  color: rgb(212, 212, 212);
}
.jmm-subTitle {
  color: rgb(179, 179, 179);
}

.jmm-marginHelper {
  margin-bottom: 40px;
}
.jmm-card {
  background-color: rgba(204, 204, 204, 0.884);
  margin-bottom: 50px;
}
</style>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "about",
  components: {
    Navbar
  }
};
</script>
