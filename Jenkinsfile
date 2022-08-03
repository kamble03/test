pipeline {
    agent any
             stages {
                  stage ('copy-index') {
                    steps {
                     'cp -r index.html  /var/www/html'
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
stage ('install apche') {
                    steps {
                    'sudo yum install httpd -y'
}

}
stage ('start-apche') {
                    steps {
                    'service httpd start'
}

}
}
}
