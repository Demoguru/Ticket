pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
               //bat "rmdir  /s /q TicketBookingServiceJunitTesting"
                bat "git clone https://github.com/shikhaminhas/demo_ticketproject.git"
                bat "mvn clean package"
            }
       // }
        //stage('install') {
           // steps {
                //bat "mvn install -f TicketBookingServiceJunitTesting"
            }
        }
        //stage('test') {
            //steps {
                //bat "mvn test -f TicketBookingServiceJunitTesting"
            //}
       // }
        //stage('package') {
           //steps {
                //bat "mvn package -f TicketBookingServiceJunitTesting"
           // }
       // }
   // }
}
