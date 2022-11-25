<template>
    <div class="footer-background">
        <div class="links-container">
            <div class="button">
                <a href="#!">SIGN-UP NOW!</a>
            </div>
            <div class="socials">
                <ul>
                    <li class="follow">follow us</li>
                    <li>
                        <img src="@/img/footer-facebook.png" alt="">
                    </li>
                    <li>
                        <img src="@/img/footer-twitter.png" alt="">
                    </li>
                    <li>
                        <img src="@/img/footer-youtube.png" alt="">
                    </li>
                    <li>
                        <img src="@/img/footer-pinterest.png" alt="">
                    </li>
                    <li>
                        <img src="@/img/footer-periscope.png" alt="">
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
name: 'FooterLinks',
}
</script>

<style>
.footer-background {
    background-color: #303030;
    height: 110px;
    padding: 0 5rem;
}

.links-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

a {
    color: white;
    background-color: #303030;
    border: 2px solid #0282F9;
    padding: .5rem 1.5rem;
    text-decoration: none;
}

.follow {
    text-transform: uppercase;
    color: #0282F9;
}

.socials ul {
    list-style-type: none;
    display: flex;
    align-items: center;
    gap: 1rem;
}
</style>