---
title: "Quickstart"
description: "Quickstart to test and start working with Kaoto, the low code and no code integration orchestration tool."
draft: false
---

## Using a standalone executable

Go to [https://github.com/KaotoIO/kaoto-ui/releases/latest](https://github.com/KaotoIO/kaoto-ui/releases/latest) and download the appropiate file (see following sections) from the **Assets** section at the bottom of the release information.

### Using JAR file

As a pre-requisite, [you must have Java 17+](https://adoptium.net) already installed in your computer.

Then, run the jar file as you would run it normally:

```bash
java -jar kaoto-$version-runner.jar
```

You can now access Kaoto on [http://localhost:8081](http://localhost:8081)

Learn more about how to use Kaoto on the [User Guide](/docs/user-guide)

### Using native executable

If you downloaded one of the native executables valid for your architecture and operative system, you just have to run the downloaded file as you would run any other application file in your operative system.

Note that as it is a native build, you should have the exact same environment as the one in which the executable was built. All our executables are built using the latest versions of github machines.

You can now access Kaoto on [http://localhost:8081](http://localhost:8081)

Learn more about how to use Kaoto on the [User Guide](/docs/user-guide)


## Using Docker

The only pre-requisite is to have [docker installed](https://docs.docker.com/get-docker/).

```bash
docker run --rm  -p 8081:8081  --name kaoto kaotoio/standalone:latest
```

You can now access Kaoto on [http://localhost:8081](http://localhost:8081)

Learn more about how to use Kaoto on the [User Guide](/docs/user-guide)

Always stop the containers when finishing using Kaoto, so you don't have containers dangling:

```bash
docker stop kaoto
```

