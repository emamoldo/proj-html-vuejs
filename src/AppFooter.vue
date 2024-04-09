<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <!-- Footer Section -->
    <div class="footer">
        <div class="footer_text">
            <strong>Hey! Join to our Community</strong>
            <p>Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus. Curabitur feugiat volputate parus
                ipsum
                dolores ficilis uns etra.</p>
            <button class="get_sign" type="button">SIGN UP ></button>
        </div>
    </div>

    <!-- Newsletter Section -->
    <div class="newsletter">
        <p>Subscribe to uor Newsletter</p>
        <div class="newsletter_utilities">
            <input type="text" placeholder="Insert your email*">
            <button type="button">SEND</button>
        </div>
    </div>

    <!-- About Section -->
    <div class="about">
        <div class="container">
            <div class="about_section">
                <strong>AVADA TECH FORUM</strong>
                <p>Sed semper, nisl id feugiat eleifend, erat est digssin felis, quis auctor elit enim nec ante. Cras et
                    nibh
                    risus. Pellentesque non mi sit amet mi intermentum.</p>
            </div>

            <div class="about_section">
                <strong>POPULAR TOPICS</strong>
                <p><i class="fa-solid fa-angle-right"></i> Nam a dolor volutpat massa auctor semper </p>
                <p><i class="fa-solid fa-angle-right"></i> Sed eusmod nusc urna fermentum arcu dapibus fringilla. </p>
                <p><i class="fa-solid fa-angle-right"></i> Cras lacinia tellus id mauris finibus iacus molestie </p>
                <p><i class="fa-solid fa-angle-right"></i> Curabitur a scelerisque ligula</p>
            </div>

            <div class="about_section">
                <strong>RECENT TOPICS</strong>
                <p><i class="fa-solid fa-angle-right"></i> Cras lacinia tellus id mauris finibus iacus molestie </p>
                <p><i class="fa-solid fa-angle-right"></i> Proin at ligula sagittis vestibulum nusu vitae </p>
                <p><i class="fa-solid fa-angle-right"></i> Sed nec metus at est tincidont elementum </p>
                <p><i class="fa-solid fa-angle-right"></i> Nulla egestas nulla eu nulla suscipit molestie</p>
            </div>

            <div class="about_section">
                <strong>LATEST REPLIES</strong>
                <p><i class="fa-solid fa-angle-right"></i> Cras lacinia tellus id mauris finibus iacus molestie </p>
                <p><i class="fa-solid fa-angle-right"></i> Cras lacinia tellus id mauris finibus iacus molestie </p>
                <p><i class="fa-solid fa-angle-right"></i> Nulla egestas nulla eu nulla suscipit molestie </p>
                <p><i class="fa-solid fa-angle-right"></i> Mauris ac nibh quis eros sagittis lacinia a et dui</p>
            </div>
        </div>
    </div>
    <br>
    <hr>

    <!-- Copyright Section -->
    <div class="copy">
        <p><i class="fa-regular fa-copyright"></i> Copyright 2012 - 2020 | Avada Theme by <strong>Theme Fusion</strong>
            |
            All Rights Reserved | Powered by <strong>WordPress</strong></p>
        <div class="icons">
            <i class="facebook fa-brands fa-facebook-f"></i>
            <i class="twitter fa-brands fa-twitter"></i>
            <i class="instagram fa-brands fa-instagram"></i>
            <i class="youtube fa-brands fa-youtube"></i>
        </div>
    </div>
</template>


<style>
/* Footer Section */
.footer {
    background-image: url("../src/assets/img/join_now_cta_bg.jpg");
    background-size: 100%;
    height: 550px;

    .footer_text {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top: 10rem;
        gap: 2rem;

        strong {
            color: var(--bool-white);
            font-size: 35px;
            width: 250px;
            text-align: center;
        }

        p {
            width: 550px;
            text-align: center;
        }
    }
}

/* Newsletter Section */
.newsletter {
    background-color: var(--bool-text-primary);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 1rem;
    height: 200px;

    p {
        color: var(--bool-black);
        font-size: 20px;
    }

    .newsletter_utilities {
        display: flex;
        gap: 1rem;

        input {
            height: 25px;
            width: 400px;
        }

        button {
            width: 150px;
            padding: 0.5rem;
            background-color: var(--bool-black);
            color: var(--bool-white);
            border: none;
        }

    }


}

/* About Section */
.about {
    .container {
        margin-top: 5rem;
        margin-left: 24rem;
        display: flex;
        justify-content: space-between;
        width: 1100px;

        .about_section {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            width: 250px;
            padding-bottom: 2rem;

            p {
                color: black;
                padding: 0.5rem 0;
                border-bottom: 1px solid var(--bool-darker);
            }
        }
    }
}

/* Copyright Section */
.copy {
    margin-top: 2rem;
    margin-left: 15rem;
    margin-right: 15rem;
    display: flex;
    justify-content: space-between;
    margin-bottom: 2rem;

    .icons {
        display: flex;
        gap: 1rem;

        .facebook,
        .twitter,
        .instagram,
        .youtube {
            height: 30px;
            width: 30px;
            display: flex;
            border-radius: 50%;
            justify-content: center;
            align-items: center;
            color: var(--bool-white);
        }

        .facebook {
            background-color: var(--bool-facebook);
        }

        .twitter {
            background-color: var(--bool-twitter);
        }

        .instagram {
            background-color: var(--bool-instagram);
        }

        .youtube {
            background-color: var(--bool-youtube);
        }
    }

    p {
        color: black;
    }
}
</style>
