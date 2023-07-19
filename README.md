# PyData Prague

- [Meetup](https://www.meetup.com/PyData-Prague/) - Find and register to our meetups here!
- [Twitter](https://www.twitter.com/PyDataPrague/) - We post here...
- [LinkedIn](https://www.linkedin.com/company/pydata-prague/) - ...and here...
- [Facebook](https://www.facebook.com/PyDataPrague) - ...and here!

PyData Prague is a community of data scientists, engineers, analysts, and various other developers in the area of scientific computing and data analysis. The term [PyData](https://pydata.org/) refers to an educational program of [NumFOCUS](https://numfocus.org/), an american non-profit helping open source software in terms of governance, financial support, and operations.

The PyData network hosts meetups in hundreds of cities around the world and several conferences each year. The Prague chapter started in 2018 with the aim of spreading the word of open source scientific computing in the Czech Republic. And while the chapter is based in Prague, we operate and collaborate countrywide.

## Code of Conduct

We adhere to PyData's code of conduct, here's its short version:

> Be kind to others. Do not insult or put down others. Behave professionally. Remember that harassment and sexist, racist, or exclusionary jokes and language are not appropriate for PyData.
>
> All communication should be appropriate for a professional audience including people of many different backgrounds. Sexual language and imagery is not appropriate.
>
> PyData is dedicated to providing a harassment-free event experience for everyone, regardless of gender, sexual orientation, gender identity, and expression, disability, physical appearance, body size, race, or religion. We do not tolerate harassment of participants in any form.
>
> Thank you for helping make this a welcoming, friendly community for all.

You can find more information at [pydata.org/code-of-conduct/](https://pydata.org/code-of-conduct/)

We have hosted several meetups, you can check them out on our [Meetup page](https://www.meetup.com/PyData-Prague). We try and host speakers from various backgrounds, so that our attendees get to find out about all sorts of things possible with the NumFOCUS toolkit (and beyond!).

## Upcoming Meetups

There are no meetups planned for the nearest future... BUT join us at [PyCon CZ](https://cz.pycon.org/2023/) for a track full of data-centered talks and much much more!

## Past Meetups

### [PyData Prague #14 - Voice upon a Time](https://www.meetup.com/pydata-prague/events/293042146/) (3.5.2023 at Heureka)

#### Karel Boháček -  Sign language recognition: Enabling communication for the hearing-impaired through machine learning

In this talk, our project on sign language recognition will be presented. The aim of the project is to create a prototype app that can facilitate communication between hearing-impaired individuals and those who do not know sign language. The challenges faced by hearing-impaired individuals in communicating with the general population will be discussed, and how technology can help bridge this gap will be explained.

A Python code relying on Mediapipe library will be introduced, and its use in extracting key features from sign language gestures, such as hand and finger positions and movements, will be explained. The machine learning techniques used to recognize and classify these gestures will be delved into. The data preprocessing steps, model selection, and training process will be covered, as well as the evaluation metrics used to measure the accuracy of the model. Finally, the prototype will be showcased, and its operation in real-time will be demonstrated. The limitations of our current approach and potential future developments in the field will also be discussed.

#### Franz Kiraly - A unified interface for machine learning with time series - an introduction

Sktime is a widely used scikit-learn compatible library for learning with time series. sktime is easily extensible by anyone, and interoperable with the pydata/numfocus stack.

This short talk gives an introduction to sktime, the time series learning tasks it addresses, and a summary of usage and interfaces. It further introduces common feature extraction, pipelines and composition building blocks, and explains reduction patterns in sktime – using an estimator or object for one learning task to solve another, e.g., a tabular regressor for forecasting.

This is a basic introduction and an overview talk, no prior knowledge is required.

### [PyData Prague #13 - In Good We Rust](https://www.meetup.com/pydata-prague/events/290041316/) (13.12.2022 at Deepnote)

#### Ondřej Vostál - Async Python modules in Rust

I'll demonstrate how to write a Python module in Rust. What's more, the module will communicate both ways between Python and Rust using asyncio and tokio. After the talk, you'll be able to write an app that asynchronously processes data in Rust without holding the GIL. The main advantage of this approach as opposed to microservices is less boilerplate and saving the IPC overhead.

#### Jan Soubousta - How we built a Python SDK for our (open) APIs

During this session, we will present how we built and open-sourced a Python SDK for our analytics APIs covered by OpenAPI specification. We will share best practices applied on Python projects (data classes, services, tests, documentation, Github actions, pip, ...). In the end, we will conduct a live demo - Github APIs -> PostgreSQL -> dbt -> GoodData -> Deepnote(GoodData Python SDK).

### [PyData Prague #12 - Minutes to a Degree](https://www.meetup.com/pydata-prague/events/288395992/) (18. 10. 2022 at LMC) 

#### Ondřej Bojar - Machine Translation Usable in Practice, Let's Move to Minuting

During the last eight years of deep neural networks rewriting the landscape of machine translation (MT), we got to the stage where MT is clearly usable and progress hard to measure for language pairs covered well with data. Let us now apply similar technologies to the task of automatic creation of minutes from project meetings ("minuting"). With a similar devotion, we should make automatic minutes usable in a couple of years. And perhaps machine understanding will be necessary at last; to my surprise, it was not needed for MT.

#### Martin Fleischmann - A Gentle Introduction to Spatial Data in the Pandas Ecosystem

"Everything is related to everything else, but near things are more related than distant things”
That is the first law of geography. But how do we apply it to data science? How do we ensure that our analysis has a spatial dimension and that it can be mapped? How can we combine data based on their location? Are there any spatial patterns? These are the questions you will be able to answer after a gentle introduction to spatial data science in the pandas ecosystem. We will start with a brief explanation of the key concepts like geometries and projections to introduce GeoPandas, a package that brings geo to pandas. Then we’ll check how the ecosystem supporting GeoPandas looks like and what it offers, followed by a short excursion to the realm of spatial analytics using the packages from the PySAL (Python Spatial Analysis Library) project. We will be able to expand traditional exploratory data analysis with spatial using the esda package, interpolate data between different spatial units using the tobler package or analyse the structure of cities using momepy. Finally, when the data begin to look too large to work with, we switch to distributed dask-geopandas and wrap up our journey with spatial operations powered by Dask somewhere in the cloud.

### [PyData Prague #11 - Hovering over Capulets](https://www.meetup.com/pydata-prague/events/286566742/) (27. 6. 2022 at Ataccama)

#### Radek Ježek - Using drone imagery to detect vegetation around power lines ([video](https://www.youtube.com/watch?v=zKjYUnT7DRk))

When was the last time you encountered a power outage? You would be a bit concerned if you knew how much of today's critical infrastructure relies on the uninterrupted supply of electricity. How can drones help? This talk explains how we used drone images to automatically detect one of the most common causes of power outages - when trees come dangerously close to the wires.

The presentation will cover the complete workflow:

- Capturing images using automated drone missions.
- Building a 3D model of the terrain.
- Using computer vision and neural networks for detecting wires in the images.
- Building a 3D representation of the wires with epipolar geometry.
- Visualizing the vegetation encroachment.

#### Matěj Račinský - Julia in Python's den ([video](https://youtu.be/U5zt6OZVxrs))

Julia is a rather new programming language, designed for modern scientific computing. This talk will compare Julia to Python, discuss its current state and production-readiness, emphasise its strengths and weaknesses, describe the interoperability with Python, and speculate whether it is now a good time to rewrite all your Python projects in Julia - all that with some important takeaways from more than a year of running Julia in production at Avast.

### [PyData Prague #10 - Pandemic Lite](https://www.meetup.com/PyData-Prague/events/285562340/) (10. 5. 2022 at Creative Dock)

#### Jeremy Tuloup - JupyterLite: Jupyter ❤️ WebAssembly ❤️ Python ([slides](https://github.com/jtpio/pydata-prague-meetup-2022), [video](https://youtu.be/mB806GtibR4))

JupyterLite is a JupyterLab distribution that runs entirely in the web browser, backed by in-browser language kernels. This presentation will be a functional talk to present JupyterLite with concrete examples and live demos.

#### Roman Neruda, Petra Vidnerová - Tested on agents - how we designed an agent-based epidemiological model ([video](https://youtu.be/aIxrvlL47io))

Epidemiological modeling helps us to understand the dynamics of disease spread and the effects of various protective measures. Agent-based models provide simulation tools for detailed modeling of individual human behavior. We will present a general network agent model that has been used to study epidemic scenarios in various environments, including a typical Czech county, or a school.

### [PyData Prague #9 - Reinforcement Yearning](https://www.meetup.com/PyData-Prague/events/279339785/) (13. 7. 2021 at Holešovická Šachta)

No talks.

### [PyData Prague #8 - Collaborative Dimensions](https://www.meetup.com/PyData-Prague/events/273506477/) (5. 10. 2020, virtual)

#### Jan Matas - Making data science notebook collaborative ([video](https://www.youtube.com/watch?v=GQr1uMK74F4))

Jupyter notebook is now one of the most popular tools for data scientists, even though it is fairly difficult to work with it in a team setting. In this talk, we will first explore how notebooks work under the hood, then we will discuss how we can build collaboration features to enable real-time editing (like google docs) and finally we will address some security challenges inherent to having collaborative data science tools in the cloud.

#### Ondřej Grover - Xarray, more than Pandas in multiple dimensions ([video](https://www.youtube.com/watch?v=ww4EYv20Ucw), [slides](https://github.com/smartass101/xarray-pydata-prague-2020))

The Xarray library has in recent years become one of the de-facto standards for working with multi-dimensional datasets in Python. While calling it "a generalization of Pandas into multiple dimensions" gives a reasonable first impression, there is much more to it than that. For instance, the transparent and well structured API offers a concise handle on the depths of NumPy and Dask broadcasting magic. The API and helper functions also enable the construction of convenient and versatile wrappers of e.g. Scipy routines which then become applicable in any domain where data can be represented by Xarray containers. The talk will showcase the basic Pandas-like usage as well as some of the aforementioned advanced features.

### [PyData Prague #7 - Call for Community](https://www.meetup.com/PyData-Prague/events/272546041/) (25. 8. 2020 at Klub Avu)

No talks.

### [PyData Prague #6 - Extended Automation](https://www.meetup.com/PyData-Prague/events/267957841/) (3. 2. 2020 at CreativeDock)

#### Adam Hanka - Automation in InsurTech and Banking ([video](https://www.youtube.com/watch?v=pWQM-BCd_T8))

Automation and artificial intelligence can bring improvements in customer experience, shorten application time and simplify the underwriting process, reduce costs and replace some tedious and repetitive human labor such as damage inspection or claim processing. How does it work in the world of finance, especially insurance and banking, both examples of the most traditional industries, posing strong resistance towards changes?

Possible future development in the industry will be demonstrated on two recent data science and machine learning projects:
* Recognition and evaluation of car damages.
* Scoring process based on structured information from social media.

#### Jan Pipek - A practical guide to designing implants for pandas ([slides](https://janpipek.github.io/talks/pydata-prague_2020/#/))

The pandas library offers three approaches to user customization – class inheritance, series/data frame accessors, and extension arrays/dtypes. The talk introduces all of them shortly with real-world examples and code, while focusing on a complete implementation of physical-unit-aware data column example.

### [PyData Prague #5 - Dashing Automobile](https://www.meetup.com/PyData-Prague/events/266462703/) (27. 11. 2019 at Microsoft)

#### Andrej Svitek - Data Science in Automotive industry ([video](https://www.youtube.com/watch?v=pGAZpvad0PU))

The Automotive industry is one of the most important drivers (pun intended) of the Czech economy. With more than 1,4 million cars produced per year, 800 companies involved and 160 000 direct employees, Automotive is considered the largest industry in the Czech Republic accounting for more than 9 % of GDP.

With constant flood of buzzwords (IIoT, Industry 4.0, Digital factory 2.0, Autonomous Driving just to name a few), the aim of this talk is to present a more realistic and data-driven perspective of the industry as well as look at the advantages and challenges of Data Science projects within this environment.

#### Dom Weldon - Dash: Interactive Data Visualization Web Apps with no Javascript ([video](https://www.youtube.com/watch?v=dewrzMPPLDU), [slides](https://docs.google.com/presentation/d/1hHTRy6_5D59jmJ_dQQJcFdSxp8_sF8owOTz8n4ltYno/edit#slide=id.g6bad58c9c8_0_95))

Your data science project may need to produce interactive tools and visualizations to allow end-users to explore data and results. Dash, a project by the team that makes Plotly, solves some of these problems by allowing data scientists to build rich and interactive websites in pure Python, with minimal knowledge of HTML and absolutely no Javascript.

This talk will give an overview of Dash, how it works and what it can be used for, before outlining some of the common problems that emerge when data scientists are let loose to produce web applications, and web developers have to work with the pydata ecosystem.

### [PyData Prague #4 - Mapping Science](https://www.meetup.com/PyData-Prague/events/264776737/) (30. 9. 2019 at (A)void Floating Gallery)

#### Diar Masri - Data Science at LMC ([video](https://youtu.be/ztfHcGDf5rs), [slides](talks/diar_masri-2019_30_09.pdf))

Searching for job is a struggle that LMC is trying to simplify. Therefore, I would like to introduce a practical overview of how data science is applied at LMC to achieve such a goal. We do so by applying data science to better understand our users experience and abilities using techniques of Natural Language Processing (NLP). Moreover, we examine current preferences of our users using Recommender System in order to recommend them the most relevant job options and shorten the path to their next career.

#### Vojtěch Filipec - Curious about a new place? Explore many of them via OpenStreetMaps API ([video](https://www.youtube.com/watch?v=7RxQIMIUJWg), [slides and code](https://github.com/vojtech-filipec/PyConCZ-OSM-API))

Knowledge of the neighborhoods may identify deficient services to a marketing company, it also enables you to address your spouse's inquiry about points of interest on a day-trip. To acquire such knowledge, you need a rich source of data with decent API. OpenStreetMaps offer both. This talk explains how to access the data points in OSM and how to query their labels and content using two Python libraries (overpass and overpy) as well as the underlying OSM query language.


### [PyData Prague #3 - Mouse Experience](https://www.meetup.com/PyData-Prague/events/262289857/) (24. 6. 2019 at Microsoft)

#### Karla Fejfarová - My Data Look Like a Mouse ([video](https://www.youtube.com/watch?v=bl0z5jHmFuc), [slides](http://crysa.fzu.cz/karla/slides/2019_pydata.html))

This talk will give you a short tour of the Czech Centre for Phenogenomics in the BIOCEV centre in Vestec and a brief overview of current research in mouse-based functional genomics. Karla will also present various types of data we generate during the research and will show you how Python helps us to overcome some of the everyday challenges we face. Karla Fejfar­ová is a biostatistician at the Czech Centre of Phenogenomics.

#### Tomáš Muchka - What the Heck Does UX Mean? ([video](https://www.youtube.com/watch?v=K4mocwsew8k))

They work in all kinds of companies from startups to corporates. They could be sitting right next to you; the UX designers. But what is their actual job and how could you help each other? Let's find out with Tomáš Muchka, a senior UX designer at GoodData.


### [PyData Prague #2 - Optimized Elasticity](https://www.meetup.com/PyData-Prague/events/257775220/) (23. 1. 2019 at FIT CTU)

#### Honza Král - The how and why of Elasticsearch ([video](https://www.youtube.com/watch?v=55YJxJbeznQ))

Elasticsearch is an open source distributed datastore, we will see what makes it tick, how to use it from Python and try to draw some conclusions as to where it might fit in in your organization. Honza Král is a principal consulting architect from Elastic and a long-term core committer to Django.

#### Jakub Urban - Optimizing numerical calculations in Python ([video](https://www.youtube.com/watch?v=I_BRzn4zMnQ))

Jakub Urban, a senior Pythonista from Quantlane with rich experience in scientific computing and modelling, will show various possibilities for making your (mostly) numerical calculations in Python fast. He will cover optimization and parallelization using Numpy, Numba, Cython or Dask. You will learn that Python can be as fast as Fortran with a very little effort. In case it cannot, you will see how to seamlessly turn Fortran/C/C++ into a Python module.

### [PyData Prague #1 - Open Source and Open Communities](https://www.meetup.com/PyData-Prague/events/254559250/) (18. 10. 2018 at Avast)

#### Ian Ozsvald - NumFOCUS and PyData + Delivering Data Science Projects ([video](https://www.youtube.com/watch?v=6wckJlowTAg))

Ian Ozsvald, a London-based data scientist with 15+ years of experience, he co-founded PyData London, one of the largest PyData communities in the world. Ian will introduce PyData, NumFOCUS and the community behind these initiatives. He'll then talk about successfully delivering a data science project.

#### Štěpán Roučka - Symbolic Computing with SymPy ([video](https://www.youtube.com/watch?v=tsOzJ-Co938))

Štěpán Roučka, a contributor to the SymPy project, a computer algebra system widely used within academia and industry, both as a standalone tool and as part of other scientific packages. Štepán will give a brief overview of SymPy's functionality and will show you a few examples, which may motivate you to add SymPy to your data science toolbox.
