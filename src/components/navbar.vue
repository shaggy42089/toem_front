<template>
    <nav class="navbar navbar-expand-lg d-block p-0">
        <div class="flex-row-between ps-4 pe-5">
            <span>
                <a class="link fs-2 fw-semibold" href="">TOEM</a>
            </span>
            <ul class="flex-row-between d-flex p-0 m-0">
                <li><a class="link" href="">Add source</a></li>
                <li><a class="link" href="">Add script</a></li>
                <li><a class="link" href="">Contact</a></li>
            </ul>
        </div>
    </nav>
</template>

<style scoped>
    .flex-row-between {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
    }

    nav div {
        max-width: 100%;
        padding: 10px 10px;
        background-color: #0984e3;
        position:sticky;
        border-radius: 0 0 5px 5px;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        box-shadow: 0 2px 4px 0 rgba(0,0,0,.1);
        color: #dfe6e9;
    }

    ul {
        margin-right: 10%;
    }

    ul li {
        text-decoration: none;
        display: inline-block;
    }

    ul li:not(:last-child) {
        margin-right: 10px;
    }
    
    .link {
        text-decoration: none;
        color: #dfe6e9;
        padding: 5px;
        border-radius: 5px;
    }

    ul li a:hover {
        color: white;
        background-color: #74b9ff;
    }


</style>