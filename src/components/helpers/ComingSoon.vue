<template>
    <div class="modalCntr">
        <div class="modalBody">
            <div class="csName tac">JODHPUR HANDICRAFTS</div>
            <picture class="tac"><img alt="under construction site" src="./../../assets/img/underContsruction.svg" ></picture>
            <div class="tac csHead">We are revamping our website, Apologies for inconvenience.</div>
            <div class="tac csSubHead">Please feel free to get in touch with us at <a href="mailto:beparam18@gmail.com">beparam18@gmail.com</a> or <a href="tel:+919667859741">+91 9667859741</a></div>
        </div>
    </div>
</template>

<script>
</script>

<style lang="scss" scoped>
.modalCntr {
    display: grid;
    place-items: center;
    width:100%;
    height:100vh;
    .csName{font-size:20px;padding:1rem;}
    .modalBody{
        width: 80%;
        display: flex;
        flex-direction: column;
        img{
            width:60%;
            margin:0 auto;
        }
        .csHead{
            padding:1rem;
            font-size:20px;
        }
        .csSubHead{
            font-size:18px;
            a{color:#6C63FF;}
        }
    }
   
}
</style>
