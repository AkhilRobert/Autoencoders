---
title: " "
order: "-100"
---

<style>
    :root {
        --size: 25px;
    }

    .container-wasfasdf {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 40px;
    }
    
    .card {
        background: rgb(50 50 50/var(--tw-bg-opacity));
        border-radius: 10px;
        padding: 40px;
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 100%;
        max-width: 600px;
    }

    .profile {
        height: calc(var(--size) * 5);
        width: calc(var(--size) * 5);
        border-radius: 50%;
    }

    .card-main {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 20px;
    }

    .card-main > div {
        text-align: center;
    }

    .card__name {
        margin-bottom: 0px !important;
        font-size: 20px;
        color: white;
    }

    .card__name-title {
        margin-bottom: 0;
        font-size: 15px;
    }

    .sidebar-right {
        display: none;
    }

    img {
        height: var(--size);
        width: var(--size);
        cursor: pointer;
    }
</style>

:::content-center

<h1>Our Team</h1>

<div class="container-wasfasdf">
    <div class="card">
        <div class="card-main">
            <img class="profile" src="/images/avatars/akhilrobert.png" />
            <div>
                <p class="card__name">Akhil Robert</p>
                <p class="card__name-title">student</p>
            </div>
        </div>
        <a href="https://github.com/AkhilRobert">
            <img src="/images/github-mark/github-mark-white.png" />
        </a>
    </div>
    <div class="card">
        <div class="card-main">
            <img class="profile" src="/images/avatars/barathi.png" />
            <div>
                <p class="card__name">Barathi</p>
                <p class="card__name-title">student</p>
            </div>
        </div>
        <a href="#">
            <img src="/images/github-mark/github-mark-white.png" />
        </a>
    </div>
    <div class="card">
        <div class="card-main">
            <img class="profile" src="/images/avatars/pavithra.png" />
            <div>
                <p class="card__name">Pavithra</p>
                <p class="card__name-title">student</p>
            </div>
        </div>
        <a href="#">
            <img src="/images/github-mark/github-mark-white.png" />
        </a>
    </div>
</div>

:::

:::content-center

<h1 style="margin-top:50px;">Guides</h1>

<div class="container-wasfasdf">
    <div class="card">
        <div class="card-main">
            <img class="profile" src="/images/avatars/deivamani.png" />
            <div>
                <p class="card__name">Deivamani</p>
                <p class="card__name-title">Professor</p>
            </div>
        </div>
        <a href="https://github.com/DeivamaniM">
            <img src="/images/github-mark/github-mark-white.png" />
        </a>
    </div>
    <div class="card">
        <div class="card-main">
            <img class="profile" src="/images/avatars/muthumani.png" />
            <div>
                <p class="card__name">Muthumani</p>
                <p class="card__name-title">Industry Expert</p>
            </div>
        </div>
        <a href="https://github.com/DeivamaniM">
            <img src="/images/github-mark/github-mark-white.png" />
        </a>
    </div>
</div>
:::
