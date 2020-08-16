<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Assignment Solution for Module 2</title>
    
</head>
<style >
* {
    box-sizing: border-box;
    font-family: Helvetica;
}

body {
    background-color: #d6d6d6;
}

h1 {
    text-align: center;
    color: black;
}

section {
    border: 1px solid black;
    background-color: #b5c4d2;
    margin: 10px;
}

section>h2 {
    float: right;
    border-bottom: 1px solid black;
    border-left: 1px solid black;
    margin: 0;
    width: 230px;
    text-align: center;
    font-style: Times;
    font-size: 24px;
    font-weight: bold;
    height: 45px;
    padding-top: 10px;
}

section.lebesgue>h2 {
    background-color: #76b8db;
}

section.fubini>h2 {
    background-color: #4f7acd;
}

section.luzin>h2 {
    color: #e2e2e2;
    background-color: #10328a;
}

section>p {
    padding: 40px 15px 15px 15px;
}

.row {
    width: 100%;
}


/* Desktop view options */

@media (min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
        float: left;
    }
    .col-lg-1 {
        width: 8.33%;
    }
    .col-lg-2 {
        width: 16.66%;
    }
    .col-lg-3 {
        width: 25%;
    }
    .col-lg-4 {
        width: 33.33%;
    }
    .col-lg-5 {
        width: 41.66%;
    }
    .col-lg-6 {
        width: 50%;
    }
    .col-lg-7 {
        width: 58.33%;
    }
    .col-lg-8 {
        width: 66.66%;
    }
    .col-lg-9 {
        width: 74.99%;
    }
    .col-lg-10 {
        width: 83.33%;
    }
    .col-lg-11 {
        width: 91.66%;
    }
    .col-lg-12 {
        width: 100%;
    }
}


/* Tablet view options */

@media (min-width: 768px) and (max-width: 991px) {
    .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
        float: left;
    }
    .col-md-1 {
        width: 8.33%;
    }
    .col-md-2 {
        width: 16.66%;
    }
    .col-md-3 {
        width: 25%;
    }
    .col-md-4 {
        width: 33.33%;
    }
    .col-md-5 {
        width: 41.66%;
    }
    .col-md-6 {
        width: 50%;
    }
    .col-md-7 {
        width: 58.33%;
    }
    .col-md-8 {
        width: 66.66%;
    }
    .col-md-9 {
        width: 74.99%;
    }
    .col-md-10 {
        width: 83.33%;
    }
    .col-md-11 {
        width: 91.66%;
    }
    .col-md-12 {
        width: 100%;
    }
}


/* Mobile view options */

@media (max-width: 767px) {
    .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
        float: left;
    }
    .col-sm-1 {
        width: 8.33%;
    }
    .col-sm-2 {
        width: 16.66%;
    }
    .col-sm-3 {
        width: 25%;
    }
    .col-sm-4 {
        width: 33.33%;
    }
    .col-sm-5 {
        width: 41.66%;
    }
    .col-sm-6 {
        width: 50%;
    }
    .col-sm-7 {
        width: 58.33%;
    }
    .col-sm-8 {
        width: 66.66%;
    }
    .col-sm-9 {
        width: 74.99%;
    }
    .col-sm-10 {
        width: 83.33%;
    }
    .col-sm-11 {
        width: 91.66%;
    }
    .col-sm-12 {
        width: 100%;
    }
}
</style>
<body>
    <h1>Notable Mathematicians</h1>
    <div class="row">
        <div class="col-lg-4 col-md-6 col-sm-12">
            <section class="lebesgue">
                <h2>Henri Lebesgue</h2>
                <p>
                    Henri Lebesgue was born on 28 June 1875 in Beauvais, Oise. Lebesgue's father was a typesetter and his mother was a school teacher. His parents assembled at home a library that the young Henri was able to use. His father died of tuberculosis when Lebesgue
                    was still very young and his mother had to support him by herself. As he showed a remarkable talent for mathematics in primary school, one of his instructors arranged for community support to continue his education at the Collège de
                    Beauvais and then at Lycée Saint-Louis and Lycée Louis-le-Grand in Paris.
                </p>
            </section>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-12">
            <section class="fubini">
                <h2>Guido Fubini</h2>
                <p>
                    Born in Venice, he was steered towards mathematics at an early age by his teachers and his father, who was himself a teacher of mathematics. In 1896 he entered the Scuola Normale Superiore di Pisa, where he studied under the notable mathematicians Ulisse
                    Dini and Luigi Bianchi. He gained some early fame when his 1900 doctoral thesis, entitled Clifford's parallelism in elliptic spaces, was discussed in a widely read work on differential geometry published by Bianchi in 1902.
                </p>
            </section>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
            <section class="luzin">
                <h2>Nikolai Luzin</h2>
                <p>
                    Nikolai Nikolaevich Luzin (also spelled Lusin;   9 December 1883 – 28 January 1950) was a Soviet/Russian mathematician known for his work in descriptive set theory and aspects of mathematical analysis with strong connections to point-set topology. He was
                    the eponym of Luzitania, a loose group of young Moscow mathematicians of the first half of the 1920s. They adopted his set-theoretic orientation, and went on to apply it in other areas of mathematics.
                </p>
            </section>
        </div>
    </div>
</body>

</html>
