node {
    stage("Show Files") {
        def files = findFiles glob: '**/*.xml'
        for(int i; i < files.size(); i++) {
            sh "echo ${i} && cat ${files[i]}"
        }
    }
}
