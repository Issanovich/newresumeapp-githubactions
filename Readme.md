Express Logo
Fast, unopinionated, minimalist web framework for Node.js.

This project has a Code of Conduct.

Table of contents
Installation
Features
Docs & Community
Quick Start
Running Tests
Philosophy
Examples
Contributing to Express
TC (Technical Committee)
Triagers
License
NPM Version NPM Install Size NPM Downloads OpenSSF Scorecard Badge

import express from 'express'

const app = express()

app.get('/', (req, res) => {
  res.send('Hello World')
})

app.listen(3000)
Installation
This is a Node.js module available through the npm registry.

Before installing, download and install Node.js. Node.js 18 or higher is required.

If this is a brand new project, make sure to create a package.json first with the npm init command.

Installation is done using the npm install command:

npm install express
Follow our installing guide for more information.

Features
Robust routing
Focus on high performance
Super-high test coverage
HTTP helpers (redirection, caching, etc)
View system supporting 14+ template engines
Content negotiation
Executable for generating applications quickly
Docs & Community
Website and Documentation - [website repo]
GitHub Organization for Official Middleware & Modules
Github Discussions for discussion on the development and usage of Express
PROTIP Be sure to read the migration guide to v5

Quick Start
The quickest way to get started with express is to utilize the executable express(1) to generate an application as shown below:

Install the executable. The executable's major version will match Express's:

npm install -g express-generator@4
Create the app:

express /tmp/foo && cd /tmp/foo
Install dependencies:

npm install
Start the server:

npm start
View the website at: http://localhost:3000

Philosophy
The Express philosophy is to provide small, robust tooling for HTTP servers, making it a great solution for single page applications, websites, hybrids, or public HTTP APIs.

Express does not force you to use any specific ORM or template engine. With support for over 14 template engines via @ladjs/consolidate, you can quickly craft your perfect framework.

Examples
To view the examples, clone the Express repository:

git clone https://github.com/expressjs/express.git --depth 1 && cd express
Then install the dependencies:

npm install
Then run whichever example you want:

node examples/content-negotiation
Contributing
Linux Build Test Coverage

The Express.js project welcomes all constructive contributions. Contributions take many forms, from code for bug fixes and enhancements, to additions and fixes to documentation, additional tests, triaging incoming pull requests and issues, and more!

See the Contributing Guide for more technical details on contributing.

Security Issues
If you discover a security vulnerability in Express, please see Security Policies and Procedures.

Running Tests
To run the test suite, first install the dependencies:

npm install
Then run npm test:

npm test
People
The original author of Express is TJ Holowaychuk

List of all contributors

TC (Technical Committee)
UlisesGascon - Ulises Gascón (he/him)
jonchurch - Jon Church
wesleytodd - Wes Todd
LinusU - Linus Unnebäck
blakeembrey - Blake Embrey
sheplu - Jean Burellier
crandmck - Rand McKinney
ctcpip - Chris de Almeida
TC emeriti members
Triagers
aravindvnair99 - Aravind Nair
bjohansebas - Sebastian Beltran
carpasse - Carlos Serrano
CBID2 - Christine Belzie
enyoghasim - David Enyoghasim
UlisesGascon - Ulises Gascón (he/him)
mertcanaltin - Mert Can Altin
0ss - Salah
import-brain - Eric Cheng (he/him)
3imed-jaberi - Imed Jaberi
dakshkhetan - Daksh Khetan (he/him)
lucasraziel - Lucas Soares Do Rego
IamLizu - S M Mahmudul Hasan (he/him)
Sushmeet - Sushmeet Sunger
Triagers emeriti members
License
MIT