# README #

## What is this repository for? ##

The purpose of this repository is to maintain control over versions of JSON Lint. This maintains uniformity when
enforcing coding standards and formatting rules. This allows for easier upgrades and prevents newer versions from
breaking the pipeline.

---

## Configuration information ##

You can use the following command to lint all JSON files.

```shell
find . -name "*.json" -type f | xargs jsonlint
```

See links below for more information about JSON Lint and Alpine Linux.

---

## Useful links ##
  
* **Project links:**
  
  * **Project Docker pull address:**  docker pull monkeyknuckles/json

  * **Project Docker landing page:**  <https://hub.docker.com/r/monkeyknuckles/jsonlint-docker>
  * **Project clone address:**        <https://github.com/NinjaMonkeyGames/jsonlint-docker.git>
  * **Project landing page:**         <https://github.com/NinjaMonkeyGames/jsonlint-docker>
  * **Project wiki page:**            <https://github.com/NinjaMonkeyGames/jsonlint-docker/wiki>

* **3rd Party links:**

  * **Alpine source pull address:**   docker pull alpine:3.20.0

  * **Website:**          <https://jsonlint.com>
  * **GitHub JSONLint:**  <https://github.com/joereynolds/jsonlint>
  * **VSC Plugin:**       <https://marketplace.visualstudio.com/items?itemName=wekex.JsonLint>

---

## Includes ##

* Alpine Linux              v3.20.0
* Node                      v20.13.1
* NPM                       v10.8.0
* JSON Lint                 v1.6.3

---

## Files ##

| File Or Folder Name:                  | Files | Description Of File Or Folder Contents                               |
|---------------------------------------|-------|----------------------------------------------------------------------|
| > .git                                |   29  | Contains git configuration files.                                    |
| > .github > workflows > pipeline.yml  |   1   | Lints all JSON files in docker.                                      |
| dockerfile                            |   1   | Information on how to build docker.                                  |
| README.md                             |   1   | Contains information about the project.                              |
| LICENSE                               |   1   | Repository license agreement.                                        |
| avatar.png                            |   1   | Personal avatar for (Daniel Mallet) internal company use.            |
| logo.png                              |   1   | Company logo.                                                        |

---

## Version history ##

This project uses a sequential versioning system.

| Version No:    | Description Of Update                                                                               |
|----------------|-----------------------------------------------------------------------------------------------------|
| 0.0.0.0        | Base files included.                                                                                |
| 0.0.0.1        | Updated lint code.                                                                                  |

---

## Contact information ##

Author: Daniel Mallett (Monkey Knuckles)

![Ninja Monkey Games](logo.png "Logo")
![Monkey Knuckles](avatar.png "Avatar")

If you have any problems with the repository or have any suggestions please contact us at <info@ninjamonkeygames.com>.

You may also contact us via our [website](https://ninjamonkeygames.com).

Any bugs should be raised as an [issue](https://github.com/NinjaMonkeyGames/jsonlint-docker/issues) on GitHub.

---

## Copyright ##

*Ninja Monkey Games Copyright © 2024 All rights reserved.*
