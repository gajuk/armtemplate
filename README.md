# armtemplate
armtemplate for keyvault

Deploy an ARM template for azure keyvault using powershell. Define access policies to set and retrieve secrets. 
Lastly, inject the attached key-value pair into it.


splitsamples {

    psreventHubName = "timeseries-eh-psr"
    psrconsumerGrpName = "cntnr-2.0.0"
    psreventHubnamespace ="dataq-ts-eh-psr"
    psrSASName = "ListenPolicy"
    psrSASKey = ""

    storageAccountName = "dataqtssa"
    storageAccountKey = ""
    storageContainerName = "dataqjava"

    rawSamplesEventHubName = "timeseries-eh-rawsample"
    rawSamplesEventHubnamespace = "dataq-ts-eh-rawsamples"
    rawSamplesSASName = "SendPolicy"
    rawSamplesSASKey = ""
    
    psrStatusEventHubName = "timeseries-eh-psrstatus"
    psrStatusEventHubnamespace = "dataq-ts-eh-status"
    psrStatusSASName = "SendPolicy"
    psrStatusSASKey = ""
}
