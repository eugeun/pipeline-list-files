@Library('pipeline-library') _

node {
    stage("Show Files") {
        checkout scm
        def xml_files = findFiles(glob: '**/*.xml')
        for (xml_file in xml_files) {
            echo "${xml_file}"
        }
    }
}
