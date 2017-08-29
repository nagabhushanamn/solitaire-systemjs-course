


node{

    // checkout from SCM
    stage 'checkout SCM'
    git 'https://github.com/nagabhushanamn/solitaire-systemjs-course'

    // install dependencies
    stage 'get dependencies'
    sh 'npm install'

    // rum all unit tests
    stage 'Unit test'
    sh 'npm run test-single-run -- --browsers PhantomJS'


}


