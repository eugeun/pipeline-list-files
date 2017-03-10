@Library('pipeline-library') _

node {
    stage("Show Files") {
        checkout scm
        List<File> xml_files_list = new File(".").listFiles("*.xml").findAll()
        for (xml_file in xml_files_list) {
            echo xml_file
        }
    }
}
