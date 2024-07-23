<template>
  <div class="landing">
      <div class="container" id="backlayer">
          <div class="row md-d-block justify-content-center align-items-center">
              <div id="left-div" class="col-4">
                  <img class="profile" src="@/assets/b&w.jpg"/>
              </div>
              <div id="right-div" class="col-4">
                  <h1>About S'phathimandla</h1>
                  <p>
                      I possess a diverse skill set as both an aspiring web developer and in Geographic Information Systems (GIS). Completed a rigorous six-month web development bootcamp, mastering modern technologies to design and develop user-friendly and interactive web applications. Additionally, I have two years of hands-on experience in GIS, with expertise in the full data life cycle. Proficient in database management. Fluent in English, IsiZulu, and IsiXhosa, I have strong communication and interpersonal skills, supported by proficiency in MS Office (Excel, PowerPoint, Word, Outlook, Visio). Ready to leverage this unique combination of skills to drive innovation in any project or team.
                  </p>
                  <div>
                      <a class="animated-btn" target="blank" href="https://drive.google.com/file/d/1hKaEkU3c-TFMwkhCraXWhCCGDJY2-jF-/view?usp=sharing" download>Download CV
                      </a>
                </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'LandingComp'
}
</script>

<style>
.landing {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: white;
  /* border: solid 6px #990011; */
  border: solid 6px #408EC6;
}

#backlayer {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 90vh;
  background: #408EC6;
  z-index: 1;
}

@media screen and (max-width: 768px) {
  .landing {
      height: fit-content;
      background: #990011;
      padding-top: 28px;
      padding-bottom: 28px;
  }

  #backlayer {
      height: fit-content;
      background: whitesmoke;
      z-index: 1;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
  }

  #left-div,
  #right-div {
      display: block;
      width: 100%;
      text-align: center;
  }

  .profile {
      width: 100%;
      height: auto;
  }
}

#right-div {
  background: white;
}

#left-div {
  background: #FCF6F5;
}

.profile {
  max-width: 100%;
  height: auto;
}

p, h1{
  font-family:'Times New Roman', Times, serif

}
</style>
