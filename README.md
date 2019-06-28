# jmeter


# Use
docker run --rm -v $(pwd):/jmeter -t jbauson/jmeter -n -t YourJMX.jmx  -l $(date +%s).log -e -o ./$(date +%s)
