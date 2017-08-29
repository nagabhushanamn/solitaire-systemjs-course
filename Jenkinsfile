


node{
    
    stage 'checkout SCM'
    checkout([$class: 'GitSCM',
              branches: [[name: '*/master']], 
              doGenerateSubmoduleConfigurations: false, 
              extensions: [], 
              submoduleCfg: [], 
              userRemoteConfigs: [[url: 'https://github.com/nagabhushanamn/solitaire-systemjs-course']]])

}





