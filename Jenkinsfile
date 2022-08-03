pipeline {
    agent any
             stages {
                  stage ('copy-index') {
                    steps {
                    sh 'cp -r index.html  /var/www/html'
}

}

stage ('qa-index') {
                    steps {
                    sh 'cp -r qa.html  /var/www/html'
}

}
stage ('dev-index') {
                    steps {
                    sh 'cp -r dev.html  /var/www/html'
}

}

}
}
