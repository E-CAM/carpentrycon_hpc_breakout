## The Carpentries and HPC

### What's been done?

- Birds-of-a-Feather session at SC17, [report](https://hpc-uk.github.io/sc17-hpccarpentry-bof/pdf/sc17-hpccarpentry-bof-report.pdf)  |
- Two novice lessons are "in the wild" |
  - [HPC-in-a-day](https://psteinb.github.io/hpc-in-a-day/)
  - [HPC intro](https://hpc-carpentry.github.io/hpc-intro/)
  

Note:

Give some context first.

Report from SC17 at https://hpc-uk.github.io/sc17-hpccarpentry-bof/pdf/sc17-hpccarpentry-bof-report.pdf

---

## Keeping track of your opinions

- We will use Socrative to gather your opinions and help drive the discussion 

<div>
    <iframe src="https://b.socrative.com/teacher/#import-quiz/34463134" frameborder="0" ></iframe>
</div>

Note:

- Highlight the outcomes through a Socrative quiz 
- Use the quiz to see how much people agree

---

## Learner Profile



---

## Prerequisites



---

## Topics



---

## Portability



---

## Template Features

- Code Presenting |
- Repo Source, Static Blocks, GIST |
- Custom CSS Styling |
- Slideshow Background Image |
- Slide-specific Background Images |
- Custom Logo, TOC, and Footnotes |

Note:
Keep yourself on track using lists within your speaker notes:

- Key insight.
- Supporting use case.
- Time to delve deeper.

---?code=src/go/server.go&lang=golang&title=Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

Note:
Best to keep it simple. Try highlighting just one key message per slide.

---

@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

Note:
Perhaps it's time for an insightful anecdote to keep your
audience engaged?

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

Note:

Reinforce key points to drive home your message.

---

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Image](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Slide-specific Background Images](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting) [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents) [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

Note:

Let your audience know where they can find additional
help.

And where they can find your presentaton slides,
online @ [GitPitch.com](https://gitpitch.com) :)

---

### Questions?

<br>

Note:

Encourage questions, it's a great opportunity to
learn from your audience.

---?image=assets/image/gitpitch-audience.jpg&opacity=100

@title[Download this Template!]

### <span class="white">Get your presentation started!</span>
### [Download this template @fa[external-link gp-download]](https://gitpitch.com/template/download/white)

Note:

Now it's your turn. The fastest way from idea to presentation
is to download a GitPitch presentation template. Visit the
Template Gallery [here](https://gitpitch.com/templates.html).

