<h1 align="center">Welcome to Esquenta Porquinho Documentation 👋</h1>

<div align="center">
    <img src=".github\images\documentation.png" alt="This is an image of a pig under a book with `docs` in front of it">
</div> 

***

> The ideia of this project is contrubiting with IoT technology for Animal Welfare, specially in pig farms. The research that this project is part of aims to study the best development of beef pork when the Animal Welfare concepts are applied since they born.

> The image below explain in summary what is the propose of this project and how it will be built.

<div align="center">
    <img src=".github\images\description.jpg" alt="This is an image explain the propose and the methodology of the project">
</div> 

> Besides that, this project is also part of another reasearch. This another research aims to study the collect of data from IoT devices and to build a pattern for develeopmente using this devices. So, is very important too the technical side of this project and doesn't just the animal welfare part. 

> The image below explain in summary how it works the technical communication, the relationship of the logical and fisical structutes and the show the principal components and technologies used.

<div align="center">
    <img src=".github\images\communication.png" alt="This is an image explain how the project communication works">
</div>

## How the heating system definitely works?

According to Ferreira (2005) and Pandorfi et al. (2005) the ideal temperatures for piglets according to the weeks of birth:

<table align=center>
    <tr>
        <td>Age</td>
        <td colspan='2'>Temperature (°C)</td>
    </tr>
    <tr>
        <td>&nbsp</td>
        <td>Min</td>
        <td>Max</td>
    </tr>
    <tr>
        <td>0</td>
        <td>30</td>
        <td>32</td>
    </tr>
    <tr>
        <td>1</td>
        <td>28</td>
        <td>30</td>
    </tr>
    <tr>
        <td>2</td>
        <td>26</td>
        <td>28</td>
    </tr>
    <tr>
        <td>3</td>
        <td>24</td>
        <td>26</td>
    </tr>
    <tr>
        <td>4</td>
        <td>22</td>
        <td>24</td>
    </tr>
</table>

Following the literature, this information is kept in a database. The ESP makes a request to the server indicating the box number, the server calculates the age of the piglets in that box and sends it to ESP. With given parameters the ESP reads the environmental sensors and if the temperature is below ideal, turns on the heating system.

This process is repeated every minute, with readings being maintained in the database. When the system heats the room to the ideal temperature, the ESP verify and performs the shutdown.

***

## :link: Useful links
- [Back-End Repository](https://github.com/Esquenta-Porquinho/back-end)
- [Front-End Repository](https://github.com/Esquenta-Porquinho/front-end)
***

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Esquenta-Porquinho/documentation/issues). 
***

## Show your support ⭐️

Give a ⭐️ if this project helped you!
***

