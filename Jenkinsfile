node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Checkout code from repository
   checkout scm

   // Get the maven tool.
   // ** NOTE: This 'M3' maven tool must be configured
   // **       in the global configuration.

   // Mark the code build 'stage'....
   stage 'Build'
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/f4c6525c-1065-49d6-abdd-e6e86f3f617c@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/eefd06f5c4d7474b8161796f96f48fe7/184376c3-dda3-4fbe-9514-16ae5b6877ae', color: '800000'
   // Run the maven build
}

