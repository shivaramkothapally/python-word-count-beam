# python-word-count-beam
# commands for creating actiavating virtual enviornment
mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount ` -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner
# commands  for getting output
python -m apache_beam.examples.wordcount --input C:\Users\S541906\Documents\44517\python-word-count-beam\sample.txt --output C:/Users/S541906/Documents/44517/python-word-count-beam/counts
