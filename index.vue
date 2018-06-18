<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
    <meta charset="utf-8">
    <title>Vue.js - Hello</title>
    <script src="https://cdn.jsdelivr.net/npm/vue@2.5.16/dist/vue.js"></script>
</head>

<BODY background="704532.jpg"></BODY>

<body>
    <h3 align="center">
        <font color="black">
            <div id="vue-app">
                <h1>{{ histore}} </h1>
                <IMG SRC="sssssssssss.PNG" width="200">
                <h2>{{ name }} </h2>
                <h2>{{ nickname }} </h2>
                <h2>{{ age }} </h2>
                <h2>{{ birdth }} </h2>
                <h2>{{ address }} </h2>
                <h2>{{ school }}</h2>
                <h2>เพลงที่ชอบ :
                    <a v-bind:href="music">click link...</a>
                </h2>
        </font>
    </h3>
    </div>
    <script src="app.js" charset="utf-8"></script>
</body>

</html>