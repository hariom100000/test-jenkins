pipeline {
  agent any
  stages {
    stage('azure-login') {
      steps {
        sh '''AZURE_CLIENT_ID=\'70f1443e-39c2-4d41-bb25-fb53bf2f66d8\'
AZURE_CLIENT_SECRET=\'16I8Q~mczScDfgTmyjbfi0pasuOPyHvuu~1X_aE9\'
AZURE_TENANT_ID=\'e89b9cb6-ceb6-41ac-8dcc-950ebbc47dae\'

az login --service-principal \\
            --username "$AZURE_CLIENT_ID" \\
            --password "$AZURE_CLIENT_SECRET" \\
            --tenant "$AZURE_TENANT_ID"'''
      }
    }

  }
}