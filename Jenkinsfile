node {
stage('cmd') {
RET = sh (
script: 'hostname',
returnStdout: true
).trim()
echo "hostname: ${RET}"
}
}