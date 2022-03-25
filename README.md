<div id="top"></div>


<!-- ABOUT THE PROJECT -->
## About The Project

 
  **Right**,

I started this because I found my self reusing the same pieces of code to genereate a JWT and wanted to come up with a solution that could be used across multiple projects.

Currently this is only set up to work with simple Login and Register functions but would like to expand this to cover anything

feel free to contribute!

<sub><sub><sub>plz contribute</sub></sub></sub>


<p align="right">(<a href="#top">back to top</a>)</p>



### Built With


* [Go](https://go.dev/)
* [Go Fiber](https://gofiber.io/)
* [Docker](https://www.docker.com/) (optional)


<p align="right">(<a href="#top">back to top</a>)</p>


### Getting Started


1. Clone the repo
   ```sh
   git clone https://github.com/giuseppe-g-gelardi/go_token_gen.git
   ```
2. Install dependencies 
   ```sh
   go mod tidy
   ```
3. Create a .env file
   ```sh
   touch .env
   ```
4. Enter your JWT Secret Key in `.env`, you can find an example in .env.example
   ```js
   JWT="ENTER YOUR SECRET_KEY"
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Example

Send a User ID to this server
```sh
    const response = await axios.post('http://localhost:8080/token', {
      id: user._id
    })
```
and it will respond with a JWT


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



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Giuseppe Gelardi - [LinkedIn](https://www.linkedin.com/in/giuseppe-gelardi/)

Project Link: [https://github.com/giuseppe-g-gelardi/go_token_gen](https://github.com/giuseppe-g-gelardi/go_token_gen)

<p align="right">(<a href="#top">back to top</a>)</p>



