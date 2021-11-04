# How-to-Intern
How to Intern

Airline pilot in Asia 🌏 in COVID 😢 and into crypto 😊 check out the emoji's... 

Bitcoin

Journey

How to get started

(

Role Description:

As an Intern in Validator Relations you will:
Develop a short term goal, and be held accountable to it’s completion. Successful, or unsuccessful.
Plan, and execute a public course on Node setup (twitter spaces, discord voice, or other open forums)
Assist the Public Relations Team
Assist the Validator Relations Team
Work 10-15 flexible hours per week
Write weekly reviews of your progress, and learning

You will find it easier to do your job if you have the following qualities. 
Needless to say, none of these qualities supersede your intellectual and professional curiosity:

Proficient in written English, and comfortable with technical language
Comfortable with simultaneously managing multiple contexts and communication streams
Familiarity with DevOps terminology and practices
Familiarity with running software Cosmos-SDK, Tendermint
Have some experience setting up and running a Terra node

https://www.youtube.com/watch?v=2lKAvltKX6w


![2021-11-04 (7)](https://user-images.githubusercontent.com/93710516/140307137-dd569b3d-81ce-4b28-9d9e-94bc5b172a69.png)

<div style="page-break-after: always;"></div>

Next

# How to -> Intern Interview
## _From a Boeing 747 pilot to a wanna be Crypto Intern_


A brief story of how I went from flying a B747-800F to writing this article.

- Flying
- The Crypto Rabbit Hole
- Interning Wanna Be

## Flying

- Learnt to fly in Cessna 152, Cessna 172, and Piper Seminole PA-44
- After earning my Commercial Pilot Licence I became a Flight Instructor
- Moved from Instructing to flying a Boeing 727 in various roles
- Moved to Hong Kong and started flying for Cathay Pacific
- I currently fly a Boeing 747 freighter, and previously flew Airbus A330, A340 and Boeing 777 aircraft.

Flying has been something that I wanted to do as a young child.  I am blessed to hae been able to acheive that dream.

As [Leonardo Da Vinci] was quoted, and found on the [Pilot Mall Blog][df2]

> “Once you have tasted flight, you will forever walk the earth with your eyes turned skyward, for there you have been, and there you will always long to return.”


## Markdown - I'm just going to leave this in...

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.
- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and......  OK thats enough of that


As part of the discovery proccess into trying to formulate a responese to the interview task that I was given, I have had to digest many new terms, definations, languages, and concepts.


I am unabashedly copying the landing page from [Dillinger][df2] 

## The Crypto Rabbit Hole



Chinese New Year 2020 is when I first realized that my aviation career might be derailed.
More specificially January 27th.  My wife handed me face masks and insisted that I wear them walking though the airport terminals. 
[See photo][df3] - Not sure how to insert a photo inline from GitHub into the document. [Syntax Guide for later][df4]

Very quickly Hong Kong people stopped travelling due to remembering SARS, and Cathay and Dragonair started parking aircraft.
Needing to turn my mild OCD 
arkdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the 

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [Leonardo Da Vinci]: <https://en.wikipedia.org/wiki/Leonardo_da_Vinci>
   [df1]: <https://www.pilotmall.com/blogs/news/30-best-aviation-quotes-of-all-time>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [df2]: <https://dillinger.io/>
   [df3]: <https://github.com/cjerv/files/blob/main/EA160132-AA76-486E-AE83-E7767308735E%202.JPG>
   [df4]: <https://daringfireball.net/projects/markdown/syntax>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>

