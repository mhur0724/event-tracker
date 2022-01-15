# Natural Event Tracker
<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">

  <p align="center">
 A React based Natural Event Tracker (inspired by TraversyMedia) that calls the Google Maps and NASA events tracker API to generate a map that shows the location and general information of any specified event (wildfire, sea and lake ice, volcano, or storm).
    <br />
    <br />
    <a href="https://mhur0724.github.io/event-tracker">View Demo</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<p align="center">
<img width="670" alt="event-tracker" src="https://user-images.githubusercontent.com/86213479/149592399-7c94ea90-c4d7-426a-a6ca-ec0a6d5eb2f1.png">
</p>

I started to learn React and this is a project I made in order to practice and solidy my React skills. You can filter from a list of events that you'd like to see. Currently the NASA API is only returning 4 types of events (wildefire, severe storms, earthquakes, and sea and lake ice) which is why those are the only options to filter from. 

While the base of this project is guided by [TraversyMedia's tutorial video](https://www.youtube.com/watch?v=ontX4zfVqK8&list=PLillGF-RfqbY3c2r0htQyVbDJJoBFE6Rb&index=33&ab_channel=TraversyMedia), I've added extra functionality by allowing the user to filter the type of events they'd like to see.

You may need to zoom out or move the map around to find your event. For example the "Sea and Lake Ice" events are located near the bottom of the map as that's where they would mostly form.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [React](https://reactjs.org/)
* CSS
* [Google Map API](https://developers.google.com/maps/documentation/javascript/overview)
* [NASA Event Tracker API](https://eonet.gsfc.nasa.gov/docs/v2.1)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/mhur0724/event-tracker.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## How to Use

Clicking the event in the filter menu will toggle the event marker for each type of event. 

<div align="center">
<h3>Volcano's Off</h3>
<img width="724" alt="natural-events-unclicked" src="https://user-images.githubusercontent.com/86213479/149593655-e591b6c2-0bf7-4a42-9545-6ba258822cb3.png">
 </div>
 
<div align="center">
<h3>Volcano's On</h3>
<img width="724" alt="natural-events-clicked" src="https://user-images.githubusercontent.com/86213479/149593732-5fd4772e-6f74-4333-9a74-efdc0996e28c.png">
 </div>

<div align="center">
<h3>Open Location Info Box</h3>
<img width="724" alt="location-info-box" src="https://user-images.githubusercontent.com/86213479/149594021-24de03a1-e8de-4fd6-934f-77a4bbb5706b.png">
</div>
<p>*The red box that is surrounding the event marker will not be there, I added that to the image to highlight that clicking on the marker will bring up the event location info</p*>


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Matthew Hur - [LinkedIn](https://www.linkedin.com/in/matthewhur/) - mhur0724@gmail.com

Portfolio Link: [https://mhur0724.github.io/portfolio/](https://mhur0724.github.io/portfolio/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Project Idea Inspired by [TraversyMedia](https://www.youtube.com/watch?v=ontX4zfVqK8&list=PLillGF-RfqbY3c2r0htQyVbDJJoBFE6Rb&index=33&ab_channel=TraversyMedia)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
