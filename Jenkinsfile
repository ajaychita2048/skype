node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'fe464498-42a9-49e5-a3c5-88b55b0f324b') {

        def customImage = docker.build("7989461575/ajaytest")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
