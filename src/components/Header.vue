<template>
    <div class="header-container">
        <div class="header-name">
            <h1>Maximiliano Castrucci</h1>
            <h3>Full Stack software Engineer</h3>
        </div>
        <img src="@/assets/mcastrucci_cv_profile_picture.png">
    </div>
</template>

<style scoped>
    .header-container {
        display: flex;
        flex-direction: row;
        align-content: center;
        font-size: 20px;
        height: 200px;
        background-color: #574b90;
        width: 100%;
        text-align: center;    
        color: white;
        font-weight: 400;
        letter-spacing: 4px;
    }

    .header-name {
        flex-grow: 2;
    }

    .header-container img{
        height: 200px;
        border-top-left-radius: 20px;
    }

</style>