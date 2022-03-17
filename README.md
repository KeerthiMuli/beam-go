## Install Go and Verify Version
https://go.dev/doc/install

# Steps performed in PowerShell
## To obtain the Apache Beam Go SDK
 - On Executing the command "go get -u github.com/apache/beam/sdks/v2/go/pkg/beam" gives an error " go.mod file not found in current directory or any parent directory". 
 - Using the command "go mod init github.com/KeerthiMuli/beam-go," create a new go.mod file. Execute "go get -u github.com/apache/beam/sdks/v2/go/pkg/beam" after creating a new go.mod file..
## Installing wordcount example:
The command "go install github.com/apache/beam/sdks/v2/go/examples/wordcount" is used to install the wordcount file. But the command did not install the wordcount file. As a result, a file wordcount was created manually and copied the code from the wordcount from apcahe beam go sdk.
## Running the wordcount
wordcount --input sample.txt --output KeerthiMuli_counts

