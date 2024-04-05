<template>
<div id="container">
    <div class="social">
        <div>
            <a href="https://www.linkedin.com/in/divano-rizqi-anandra-5b5131300/" target="_blank">
        <img src="../../assets/social/Linkedin.svg" alt="linkedin" />
        </a>
        </div>
        
        <span>Divano Rizqi Anandra</span>
    </div>

    <div class="social">
        <div>
        <a href="https://github.com/DivanoRizqiAnandra" target="_blank">
        <img src="../../assets/social/github.png" />
        </a>
        </div>
        <span>DivanoRizqiAnandra</span> 
    </div>

    <div class="social">
        <div>
        <a href="mailto:divanorizqi@gmail.com" target="_blank">
        <img src="../../assets/social/Mail.svg"/>
        </a>
        </div>
        <span>divanorizqi@gmail.com</span> 
    </div>
</div>
</template>

<script>


export default ({
    setup() {
        
    },
    name: 'Social',
    data () {
        return {
            
        }
    }
})

</script>


<style scoped>


#container{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    margin-top: 50px;
}

.social{ 
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-bottom: 20px;
    padding: 20px;
}

img{
    width: 50px;
    height: 50px;
    margin: 10px;
}

</style>
