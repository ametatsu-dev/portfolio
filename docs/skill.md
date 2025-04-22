---
title: スキルセット
icon: material/star
---

|    5    |    4    |    3    |    2     |    1     |
| :-----: | :-----: | :-----: | :------: | :------: |
| 5年以上 | 2年以上 | 1年以上 | 半年以上 | 半年未満 |

<div class="grid cards" markdown>

- LP/Webサイト

    ```mermaid
    ---
    config:
        theme: dark
        themeVariables:
            cScale0: "#0000FF"
    ---
    %%{init: {
    "radar": {
        "width": 250,
        "height": 250,
        "marginTop": 50,
        "marginBottom": 50,
        "marginLeft": 50,
        "marginRight": 50
    }
    }}%%
    radar-beta
        axis wordpress["Wordpress"]
        axis php["PHP"]
        axis html["HTML"]
        axis javascript["JavaScript"]
        axis typescript["TypeScript"]
        axis css["CSS"]
        axis design["Design"]
        curve _m["Me"]{4, 5, 5, 4, 5, 5, 1}

    max 5
    min 0
    showLegend false
    graticule polygon
    ```


- バックエンド

    ```mermaid
    ---
    config:
        theme: dark
        themeVariables:
            cScale0: "#FF0000"
    ---
    %%{init: {
    "radar": {
        "width": 250,
        "height": 250,
        "marginTop": 50,
        "marginBottom": 50,
        "marginLeft": 50,
        "marginRight": 50
    }
    }}%%
    radar-beta
    axis php["PHP"]
    axis python["Python"]
    axis kotlin["Kotlin"]
    axis typescript["TypeScript"]
    axis rust["Rust"]
    %% ---------------------------------
    axis cakePHP["CakePHP"]
    axis laravel["Laravel"]
    axis spring["Spring Boot"]
    axis fastAPI["FastAPI"]
    %% ---------------------------------
    curve _m["Me"]{5, 4, 5, 5, 1, 4, 4, 5, 4}

    max 5
    min 0
    showLegend false
    graticule polygon
    ```

- フロントエンド

    ```mermaid
    ---
    config:
        theme: dark
        themeVariables:
            cScale0: "#00FF00"
    ---
    %%{init: {
    "radar": {
        "width": 250,
        "height": 250,
        "marginTop": 50,
        "marginBottom": 50,
        "marginLeft": 50,
        "marginRight": 50
    }
    }}%%
    radar-beta
    axis typescript["TypeScript"]
    axis javascript["JavaScript"]
    axis html["HTML"]
    axis css["CSS"]
    axis jquery["jQuery"]
    axis vue["Vue.js"]
    axis react["React.js"]
    axis vite["Vite"]
    curve _m["Me"]{5, 4, 5, 5, 4, 5, 3, 2}

    max 5
    min 0
    showLegend false
    graticule polygon
    ```

- インフラ

    ```mermaid
    ---
    config:
        theme: dark
        themeVariables:
            cScale0: "#FF00FF"
    ---
    %%{init: {
    "radar": {
        "width": 250,
        "height": 250,
        "marginTop": 50,
        "marginBottom": 50,
        "marginLeft": 50,
        "marginRight": 50
    }
    }}%%
    radar-beta
    axis aws["AWS"]
    axis azure["Azure"]
    axis gcp["GCP"]
    curve a["Alice"]{5, 4, 0}

    max 5
    min 0
    showLegend false
    graticule polygon
    ```

</div>
