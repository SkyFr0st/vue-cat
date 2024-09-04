<template lang="">
<link rel="stylesheet" href="https://unpkg.com/boxicons@latest/css/boxicons.min.css">
    <div>
        <section class="contact" id="contact">
        <div class="social">
            <a href="#"><i class='bx bxl-facebook'></i></a>
            <a href="#"><i class='bx bxl-instagram'></i></a>
            <a href="#"><i class='bx bxl-youtube'></i></a>
        </div>
        <div class="links">
            <a href="#">Privacy Policy</a>
            <a href="#">Term of Use</a>
            <a href="#">Our Company</a>
        </div>
        <div class="design">
       <p>&#169;Design By Arnus Sillapasorn</p>
       </div>
    </section>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .contact{
    margin-top: 25px;
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #914F1E;
}
.social a{
    font-size: 27px;
    
    margin: 0.5rem;
}
.social a .bx{
    margin-top:10px;
    padding: 5px;
    color: #fff;
    background: #000000;
    border-radius: 50%;
}
.social a .bx:hover{
    background: #c75504;
}
.links{
    margin: 1rem 0 1rem;
}
.links a{
    font-size: 1rem;
    font-weight: 500;
    color: #fff;
    padding: 1rem;
}
.design{
    color: #fff;
}
.links a:hover{
    color: #c75504;
}
.contact p{
    text-align: center;
}
</style>