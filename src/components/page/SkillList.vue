<template>
    <h1>Software Development</h1>
    <div class="bg-pattern">
    <div class="skill">
      <div>
        <Skill Skillname="C" />
        <Cone Textid="c" />
      </div>
      <div>
        <Skill Skillname="C++" />
        <Cone Textid="cpp" />
      </div>

      <div>
        <Skill Skillname="Python" />
        <Cone Textid="python" />
      </div>


 
      <div>
        <Skill Skillname="Visual Studio Code" />
        <Cone Textid="vs" />
      </div>

    </div>
  </div>
    <h1>Front End Web</h1>
    <div class="bg-pattern">
    <div class="skill">
      <div>
        <Skill Skillname="HTML" />
        <Cone Textid="html" />
      </div>
      <div>
        <Skill Skillname="CSS" />
        <Cone Textid="css" />
      </div>
      <div>
        <Skill Skillname="Javascript" />
        <Cone Textid="js" />
        </div>

    </div>
  </div>
    <h1>Back end Web</h1>
    <div class="bg-pattern">
    <div class="skill">
      <div>
        <Skill Skillname="Javascript" />
        <Cone Textid="js" />
      </div>

      <div>
        <Skill Skillname="MySQL" />
        <Cone Textid="mysql" />
      </div>

    </div>
  </div>

    <h1>ML | IA | BI</h1>
    <div class="bg-pattern">
    <div class="skill">
      <div>
        <Skill Skillname="Python" />
        <Cone Textid="python" />
      </div>
    </div>
    </div>
  </template>
  
  <script>
  import Skill from '../object/Skill.vue';
  import Cone from '../object/Cone.vue';
  
  export default ({
      name : "SkillList",
      components: { Skill, Cone, Skill }
  })
  </script>
  
  <style scoped>
  .skill {
    display: flex;
    flex-wrap: wrap;
  }
  
  .Skill,
  .Cone {
    box-sizing: border-box;
    padding: 10px;
    opacity: 1;
  }
  



  h1 {
    margin : 0;
    background: linear-gradient(
      90deg,
      rgba(2, 0, 36, 1) 0%,
      rgba(185, 56, 53, 1) 0%,
      rgba(190, 117, 41, 1) 32%,
      rgba(225, 198, 95, 1) 66%,
      rgba(214, 239, 50, 1) 100%,
      rgba(0, 212, 255, 1) 100%
    );
  }


#software > * {
  opacity : 1;
}

  </style>
  