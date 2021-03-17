<template>

    <div class="modalCntr">
        <div class="modalBody">
            <div class="csName ac">JODHPUR HANDICRAFTS</div>
            <div class="img ac"><img src="./../../assets/img/underContsruction.svg" ></div>
            <div class="ac csHead">We are revamping our website, Apologies for inconvenience.</div>
            <div class="ac csSubHead">Please feel free to get in touch with us at <a href="mailto:beparam18@gmail.com">beparam18@gmail.com</a> or <a href="tel:+919667859741">+91 9667859741</a></div>
           
        </div>
    </div>
</template>

<script>
</script>

<style lang="scss">
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
       .img{
           img{
               width:60%;
               margin:0 auto;
               }
        }
       
        .csHead{
            padding:1rem;
            font-size:20px;
            font-weight: bold;
        }
        .csSubHead{
            font-size:18px;
            font-weight: bold;
        }
    }
   
}
</style>
